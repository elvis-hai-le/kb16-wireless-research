# kb16-wireless-stock
Stock firmware of the DOIO KB16 wireless provided by manufacturer

According to DOIO, this is the source for the stock firmware, however, when trying to compile, there are issues with external variables not included with the firmware. ClownFish has done a modified/updated [version](https://github.com/clownfish-og/qmk_firmware/commit/ee38890f74c34a8b0aaf72232dc8c3288a4a89e3) which is able to compile if placeholders are used for the Bluetooth external variables.

I've posted some of my findings [here](https://github.com/thompson-vii/kb16_rev2_vial_fw/issues/12). Please don't hesitate to open issues to discuss here or join the [QMK discord](https://discord.com/invite/qmk) and mention bleps. I'll update this shortly to include a working up to date firmware for the KB16 wireless, and include instructions on flashing it.
