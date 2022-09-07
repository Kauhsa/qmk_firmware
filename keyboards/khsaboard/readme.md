# Hello to new owner!

Some notes:

-   Connect Micro USB to the _left_ half. I don't remember whether the keyboard is wired in such a way that connecting USB to the _right_ half is supported at all. Worst case, fries the MCU.
-   _DO NOT_ connect/disconnect TRRS cable while USB is connected. Fries the MCU.
-   Flashing - put keyboard to flash mode by holding the BOOTSEL button on MCU and _then_ connecting the USB to your computer. Command `qmk flash -kb khsaboard -km default` works (if you use this branch).
-   IIRC, you don't need to flash the right half again if you just change keymap.
-   Default keymap is probably some nonsense that you want to replace altogether.
