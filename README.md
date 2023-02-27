# C-Media
public (kext-only) version of my port of ALSA's CMedia cards


right now i am running this exact driver on my Mac Pro (10.14.6) with a Xonar Essence STX II card without issues.

to adjust the headphone impedance settings, you will need to use HALLAB because the existing volume/controls are limited.

there are no channel-specific controls because i did not see any need for them.

other cards will probably need some slight tweaks (D1,DX,HDAV Slim, etc) and a few more volume/mixer controls, but really at this point i have proved what i wanted to prove.

that this can be done. and i did it 

i am hugely grateful for @pmj (phil dennis jordan aka God) for helping me find firm footing as i really started this project.

i have to thank Siguza from the macosxbook forum for his help in porting certain linux calls.

and of course my dawg @reddogmedia for his incredibly useful insight, which iced the driver and made it rock stable (after it gets past initialisation).

![Image of driver detection](https://raw.githubusercontent.com/i3roly/C-Media/master/info.png)

![Image of driver detection](https://raw.githubusercontent.com/i3roly/C-Media/master/STHPfunctionality.gif)

![Image of driver detection](https://raw.githubusercontent.com/i3roly/C-Media/master/spdif_analog_run.gif)
