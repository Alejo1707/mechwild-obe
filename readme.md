# MechWild OrangeBoyErgo

<p align="center">

![Wireless OrangeBoyErgo](https://i.imgur.com/NIReAQp.jpeg)

</p>

Original firmware taken from MechWild's GitHub repository. Its "bbpad" branch was the most recent one being updated for the OBE: https://github.com/MechWild/zmk/tree/bbpad/app/boards/shields/obe.

**FEATURES**
- Knob.
- Split backspace.
- Arrow keys (split right shift).

**QUALITY OF LIFE**
- Disabled underglow.
- 1 minute idle.
- 10 minutes sleep.
- Improved connection stability (CONFIG_BT_CTLR_TX_PWR_PLUS_8).

**SPECIFICS**
- MechWild combos left: lock layer (not programmed), reset, bootloader.
- Windows and Mac layers along with some for each OS.
- Mac layer has swapped LCTRL with LGUI.
- Mirrored left side numpad.
- Layers: Windows (0), Mac (1), Windows Mods (2), Mac Mods(3), Windows Numpad (4), Mac Numpad (5).
- BlueTooth profile selectors on arrow keys on mod layers.
- BlueTooth clear key on pipe on mod layers.
- Profiles: Up (BT 0), Left (BT 1), Down (BT 2), Right (BT 3).

**PILLBUG PINOUT**<br />
R0: 29<br />
R1: 28<br />
R2: 27<br />
R3: 26<br />
R4: 25<br />
R5: 38<br />
R6: 39<br />

C0: 21<br />
C1: 19<br />
C2: 18<br />
C3: 17<br />
C4: 16<br />
C5: 15<br />
C6: 14<br />
C7: 13<br />
C8: 12<br />
C9: 11<br />

PillBug (BlackPill drop-in replacement) schematic for the OBE

<p align="center">
        
![BlackPill Pinout for the OBE](https://i.imgur.com/MNj33Vg.png)

</p>
