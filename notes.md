## Mac 

- find folder taking most disk space
du -sh * | grep -E "\dG"

1.8G Documents
2.3G Downloads
34G Library
2.4G Music
28G Pictures
57G Public
18G Unix.sparsebundle
8.4G WorkDocs
194G brazil-pkg-cache

- mac osx won't wake from sleep 

sudo pmset standby 0
sudo pmset autopoweroff 0

ref: https://pdf.wondershare.com/macos-10-14/fix-mac-wont-wake-from-sleep-on-macos-10-14.html
