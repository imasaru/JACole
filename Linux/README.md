### Directory Guide

1. **xkbsymbols_jp-colemak**
    - rename to `jp-colemak`
    - symlink to `/usr/share/X11/xkb/symbols`

2. **xkbkeycodes_jpcolemak.xml**
    - rename to `jpcolemak.xml`
    - symlink to `/usr/share/X11/xkb/keycodes`

3. **ibuscomponent_jpcolemak.xml**
    - copy IBus engine `xkb:jp-colemak::ja` from file contents
    - save in `/usr/share/ibus/component/simple.xml`
