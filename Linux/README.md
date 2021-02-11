### Directory Guide for Linux

1. **xkbsymbols_jpcolemak**
    - rename to `jpcolemak`
    - symlink to `/usr/share/X11/xkb/symbols`

2. **xkbrulesevdev_jpcolemak.xml**
    - rename to `jpcolemak.xml`
    - copy layout `jpcolemak` from file contents
    - save in `/usr/share/X11/xkb/rules/evdev.xml`

3. **ibuscomponent_jpcolemak.xml**
    - copy IBus engine `xkb:jpcolemak::ja` from file contents
    - save in `/usr/share/ibus/component/simple.xml`
