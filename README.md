# appimage-test
appimage test
mksquashfs AppDir AppImage.squashfs -all-root
./appimagetool-x86_64.AppImage AppDir
