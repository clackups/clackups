# Clackups Keyboard Projects

## Mirrored keyboards for one-handed input

These keyboard layouts implement the idea suggested in the
[publication of Edgar
Matias](https://www.billbuxton.com/matias93.html), also [endorsed in
XKCD
blog](https://blog.xkcd.com/2007/08/14/mirrorboard-a-one-handed-keyboard-layout-for-the-lazy/).

The layouts optimize the work for a one-handed user: Space+letter
produces a letter from the opposite side of the keyboard, mirrored
along the TGB-YHN axis. They also add a few more combinations for
easier accessibility (such as issuing a Ctrl-Alt-Del with one hand).

The current design offers a standard QWERTY keyboard, optimized for one-handed input: it does not need
any physical work to assemble (you only need to load a new QMK firmware), and it works for one-handed 
input by both left and right hands. It also works for bilateral hand amputees.

* **YMDK YD60MQ**, a low-cost, wired, full-profile mechanical keyboard  [Description in
  Ukrainian](https://github.com/clackups/qmk_userspace/blob/main/YMDK_YD60MQ_one-handed_layout_Ukrainian.pdf),
  [keymap.c comments in
  English](https://github.com/clackups/qmk_userspace/blob/main/keyboards/ymdk/yd60mq/keymaps/claclups_mirrored/keymap.c).


* **NuPhy Air60 V2**, a neat low-profile 3-mode keyboard (wired, Bluetooth, and 2.4Ghz dongle),
    about 2-3 times more expensive than the YD60MQ, and it supports
    both Mac and Windows layouts. [Description in
    English](https://github.com/clackups/qmk_firmware/tree/onehanded_nuphy_air60_v2/keyboards/nuphy/air60_v2/ansi/keymaps/clackups_mirrored).

Outdated designs:

* **[CSTC40 planck keyboard (before November
    2024)](https://github.com/clackups/qmk_userspace/blob/main/ONE_HANDED_CSTC40.md)**,
    redesigned for the left or right hand. It requires a physical work
    on attaching the keycaps and a bit of handwriting. KPrepublic
    started selling a different model of the keyboard under the same
    name in November 2024, so this firmware would not work on it.

## Other projects

* Reverse-engineered X.Tips X3S (aka X3). The keyboard is sold as "X3 Wired Corne Keyboard" on Aliexpress, and
it declares itself as "X.Tips X3S" in USB. See more details [in the project
folder](https://github.com/clackups/qmk_userspace/tree/main/keyboards/clackups/xtips_x3s).


* [Wrist controlled gamepad for a disabled user](https://github.com/clackups/wrist_gamepad).



## Copyright and license

This work is published and distributed under the [GNU GPL](LICENSE)
terms and conditions.

clackups@gmail.com

Fediverse: [@clackups@social.noleron.com](https://social.noleron.com/@clackups)
