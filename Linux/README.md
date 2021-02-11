### Directory Guide for Linux

1. **xkbsymbols_jpcolemak**
    - symlink as `jpcolemak` to `/usr/share/X11/xkb/symbols`

2. **xkbrulesevdev_jpcolemak.xml**
    - copy layout declaration `jpcolemak` from file contents
    - add to `/usr/share/X11/xkb/rules/evdev.xml`

3. **ibuscomponent_jpcolemak.xml**
    - copy IBus engine `xkb:jpcolemak::ja` from file contents
    - add to `/usr/share/ibus/component/simple.xml`

### Post-installation

1. Test new layout by running `setxkbmap jpcolemak`
2. Clear xkb cache by running `sudo dpkg-reconfigure xkb-data`
2. Restart `ibus-daemon`
3. Add `Japanese (Colemak)` to IBus input methods
4. Cheers! 🈶️🍻️
