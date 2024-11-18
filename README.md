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

* **[CSTC40 planck
    keyboard](https://github.com/clackups/qmk_userspace/blob/main/ONE_HANDED_CSTC40.md)**,
    redesigned for the left or right hand. It requires a physical work
    on attaching the keycaps and a bit of handwriting.

* **YMDK YD60MQ**, optimized for one-handed input: it does not need
  any physical work to assemble, and it works for one-handed input by
  both left and right hands. [Description in
  Ukrainian](https://github.com/clackups/qmk_userspace/blob/main/YMDK_YD60MQ_one-handed_layout_Ukrainian.pdf),
  [keymap.c comments in
  English](keyboards/ymdk/yd60mq/keymaps/claclups_mirrored/keymap.c).


* **NuPhy Air60 V2**, optiized for one-handed input: it's a neat
    low-profile 3-mode keyboard (wired, Bluetooth, and 2.4Ghz dongle),
    about 2-3 times more expensive than the YD60MQ, and it supports
    both Mac and Windows layouts. [Description in
    English](https://github.com/clackups/qmk_firmware/tree/onehanded_nuphy_air60_v2/keyboards/nuphy/air60_v2/ansi/keymaps/clackups_mirrored).


## Other projects

* Reverse-engineered X.Tips X3S (aka X3). The keyboard is sold as "X3 Wired Corne Keyboard" on Aliexpress, and
it declares itself as "X.Tips X3S" in USB. See more details [in the project
folder](https://github.com/clackups/qmk_userspace/tree/main/keyboards/clackups/xtips_x3s).




## Copyright and license

This work is published and distributed under the [GNU GPL](LICENSE)
terms and conditions.

clackups@gmail.com

Fediverse: [@clackups@social.noleron.com](https://social.noleron.com/@clackups)
