# zdma-mk2
FPGA card looks like an capture card, but hides inside pcileech-fpga researching tool.

![screenshot](https://github.com/dom0ng/zdma-mk2/blob/main/4k60pro.jpg)

# Backstory :

https://github.com/dom0ng/pcileech-multimedia-hd

https://www.unknowncheats.me/forum/anti-cheat-bypass/623718-pcileech-multimedia.html

Variant of multimedia firmware exist since probably 2018 because skill issue.

MK2 use a specific chipset (SmartVOD) but it's indeed a Xilinx based chipset / partnership.
They do share 1:1 configuration space except SmartVOD will have a extended DSN cap (that are nulled) at 0x100.

![screenshot](https://github.com/dom0ng/zdma-mk2/blob/main/ithazdma.png)


This project got abused everywhere and was a top threat back days.
It will outdate any detection mechanism that are based on xilinx artifact (Hello Bastian), since the whole original and legal device will have all of them.


# Anti-cheats : 

EAC (on Intel) can differenciate and validate this device aswell since ~May 2025.
They are cool enough to not have pressed any ban button yet since the original and legal card can have faulty firmware behavior.
The original is allowed when the clone is blocked.
+Rep

Consider this project ( at least the public version ) as fully outdated.

__VGK can make difference and validate it easily since January 2022.__
Real device is indeed blocked here aswell since this time.

![screenshot](https://github.com/dom0ng/zdma-mk2/blob/main/riotontop.PNG)

China AC also seems to know how to validate this specific clone, it will be __unsafe there or very risky to use since October 2024.__
Real device are still allowed. -> This is very interesting, are they checking for some odd capture card behavior (that card don't handle ?) or any pcileech specific behavior :)) :)) :)) We are not talking about config space heuristics anymore, good job there.
Or gummy bear on steroid hehehe ? :)

__Faceit block totally this capture card, but safely blocked like the original device since 2023.__
Real device is indeed blocked here aswell.


__Faceit implemented is_xilinx detection/prevention mechanism on 2022, but they forgot x4 lane device until end 2023.__ <--- if you know you know

Note: This why __M2 screamer was so important back days__ allowing x4 lane, bypassing this anti-fun software company by default, and it wasn't produced anymore back days. 
Today some china manufacturer have relaunched a batch of similar device and you can get x4 lane with interesting project like ZDMA or GBOX (check out : https://lightningz.net/)

Spoofing a x4 lane on a x1 lane FPGA board is eventually possible, but the upper port will still be negociated at x1, making this kind of setup totally useless (useless = detectable, upper port at x1 negociated but lower port at x4 ? :D) and are eventually caught by drvscan-like tools.

This is obviously __outdated information__ now but always good to know :-)

This project was created to test current top Anti-Cheats against FPGA approach with minimal effort / knowledge with maximal success.

For the vast majority of the lifespan of this project, __it was considered as "whitelisted".__
Aka Triggering every is_xilinx detection based mechanism but didn't caused specific ban or issue.
It got abused at fairly some impressive level.

This threat is mostly patched on major company.

It just showcase again that detecting rogue FPGA device can be very very challenging without involving false positive case.

# Driver :
https://help.elgato.com/hc/fr/articles/360027961152-Pilotes-Windows-pour-les-produits-Elgato-Gaming

# Improvement :
https://github.com/dom0ng/sc0710

You can eventually mimic more closely how the device behavior with the driver, theyre a open sourced reversed Linux version.

# Download :

ZDMA : https://github.com/dom0ng/zdma-mk2/blob/main/pcileech_tbx4_100t_top.bin

GBOX : https://github.com/dom0ng/zdma-mk2/blob/main/pcileech_gbox_top.bin

M2 Screamer : 

Consider this project as outdated.

# Credit :

aleks

niesow_

ko1n

rain

serbo

river

kateno

whole german scene

asdf

juho

every credits here are legit player, credited for moral support.

# Buy :

https://www.amazon.com/Elgato-Internal-Capture-ultra-low-latency/dp/B07VWXCXM7/ref=sr_1_1?sr=8-1
