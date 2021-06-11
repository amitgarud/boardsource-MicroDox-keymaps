# boardsource-MicroDox-keymaps

The /microdox/keymaps/manna-harbour_miryoku/ folder contains the implementation of the Miryoku layout for the BoardSource Microdox. For information on Miryoku layout, please visit https://github.com/manna-harbour/miryoku.

The /microdox/keymaps/custom-miryoku/ has some thumb keys swapped that I find convinient as a past user of the awesome Kinesys Advantage keyboard.

To use in QMK version of your choise, drop the keymap folders (manna-harbour_miryoku / custom-miryoku) in the keymaps directory in your QMK repo, and flash both halfs following instructions on the QMK docs. E.g. I've used a pro-micro for right half and a elite-c for the right half, so my commands were 'make boardsource/microdox:custom-miryoku:dfu-split-left' and 'make boardsource/microdox:custom-miryoku:avrdude-split-right'.

Sharing it as I didn't find a drop in implementation when I was looking for it couple of months ago, and I love it even though I am still on QWERTY.
Let me know if this helps you choose a better 36 key layout for QMK :slightly_smiling_face:
