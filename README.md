# Noel's zmk-config, modified from eiga

### Table of contents
- [Dongle Flashing](#dongle-flashing)
- [ZMK Keymap Editor](#zmk-keymap-editor)
- [Shops and Useful links](#shops-and-other-useful-links)

## TOTEM

- [TOTEM](https://github.com/eigatech/zmk-config/tree/totem)
- [TOTEM Dongle](https://github.com/eigatech/zmk-config/tree/totem-dongle)
- [TOTEM Prospector](https://github.com/eigatech/zmk-config/tree/totem-prospector)

## Dongle Flashing

Dongle configs use Seeed Xiao Ble microcontrollers housed in a nifty 3D printed [case](https://www.printables.com/model/522586-seeed-xiao-ble-case).

1. Turn all controllers off
2. Flash the dongle controller with the **appropriate** `settings_reset` file.
3. Flash the dongle controller with the `dongle` file.
4. Flash the first half with the the `settings_reset` file.
5. Flash the first half with the `left` or `right` files.
6. Repeat steps 4 and 5 for the other half.

> [!WARNING]  
> When using both Nice!Nano and Seeed XIAO microcontrollers, make sure you are flashing them with the correct files!

## ZMK Keymap Editor

Nick Coutsos' [Keymap Editor](https://nickcoutsos.github.io/keymap-editor/) is a user-friendly, browser-based WYSIWYG app designed to make editing your keymap file easier. It supports conditional layers, behaviors, combo and macro editing, rotary encoders, and more.

## Shops and other useful links

Kits, Prebuilts, Parts:
- [kbd.news](https://kbd.news/vendors) - mechanical keyboard vendors list
- [42keebs.eu](http://42keebs.eu/) - diy kits, including Corne, switches and other parts
- [keeb.supply](https://keeb.supply/) - diy kits and prebuilts, including TOTEM, tools and other parts
- [splitkb.com](https://splitkb.com/) - diy kits, including Corne, switches, tools and other parts
- [bastardkb.com](https://bastardkb.com/) - diy kits and prebuilts, including Charybdis (wired only w/ qmk)
- [typeractive.xyz](https://typeractive.xyz/) - diy kits and prebuilts, including Corne w/ nice!views, switches, tools and other parts

Documentation and guides:
- [ZMK Firmware Documentation](https://zmk.dev/docs)
- [Eren's Wireless Charybdis Mini Guide](https://github.com/erenatas/charybdis-wireless-3x6)
