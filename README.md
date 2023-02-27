# C-Media
public (kext-only) version of my port of Clemens' (ALSA) C-Media oxygen card family supporting (i may miss a few):

- ASUS Xonar Essence ST, STX, STX II (with daughterboard)
- ASUS Xonar DG, D1, DX, D2, D2X, DS, DSX
- ASUS Xonar HDAV1.3 DELUXE (with daughterboard)
- Asus Xonar HDAV SLIM
- TempoTec Fantasia
- TempoTec Serenade
- AuzenTech Meridian
- AuzenTech Meridian 2G
- HT-Omega Claro
- HT-Omega Claro Halo

right now i am running this exact driver on my Mac Pro (10.14.6) with a Xonar Essence STX II card without issues.

to adjust the headphone impedance settings, you will need to use HALLAB because the existing volume/controls are limited.

there are no channel-specific controls because i did not see any need for them.

other cards will probably need some slight tweaks (D1,DX,HDAV Slim, etc) and a few more volume/mixer controls, but really at this point i have proved what i wanted to prove.

that this can be done. and i did it 

i am hugely grateful for [@pmj](https://github.com/pmj) (phil dennis jordan aka God) for helping me find firm footing as i really started this project.

i have to thank Siguza from the macosxbook forum for his help in porting certain linux calls.

and of course my dawg [@onereddogmedia](https://github.com/onereddogmedia) for his incredibly useful insight, which iced the driver and made it rock stable (after it gets past initialisation).

last but not least, the man of the hour (or past five years), the legend Clemens Ladisch ([@cladisch](https://github.com/cladisch)) who wrote the ALSA driver for this family of cards, and answered all of my questions.

![Image of driver detection](https://raw.githubusercontent.com/i3roly/C-Media/master/info.png)

![Image of driver detection](https://raw.githubusercontent.com/i3roly/C-Media/master/STHPfunctionality.gif)

![Image of driver detection](https://raw.githubusercontent.com/i3roly/C-Media/master/spdif_analog_run.gif)
