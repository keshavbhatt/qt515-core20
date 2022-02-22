
# Qt515-core20
Qt 5.15 runtime as content snap

This snap is to be consumed by various Qt apps that require Qt5.15 runtime. This snap will auto-connect and provide for an application published by [keshavnrj](https://snapcraft.io/search?q=keshavnrj). Other Developers who want to use this as their base can explicitly ask to auto-connect their app snap from store admin by writing a forum post in [snapcraft forums](https://forum.snapcraft.io/).

## Technical information about qt515-core20 content snap:

- Qt libraries are provided by beineri/opt-qt-5.15.2 PPA.
- There are few more packages which are used by consumer of this content snap like:
 - mpv, ffmpeg, socat, wget, xclip, python3
- The consumer snaps need to launch their apps using the provided [desktop-launch](https://github.com/keshavbhatt/qt515-core20/blob/main/snap_launcher/bin/desktop-launch) script or atleast use this in their command chain. One example consumer of this content snap is [whatsie](https://github.com/keshavbhatt/whatsie), read the snap/snapcraft.yaml file in whatsie's repo to see how to consume this snap as runtime.
- Current consumers of qt515-core20 content snap are listed and updated [here](https://gist.github.com/keshavbhatt/75f622373e2b57cd99ccd8f8a70d5b18)
- While committing this line to the readme, the daily active users count for this snap is ~60k as reported by the Snapcraft metrics dashboard.
