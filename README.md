08.03.2025 I have tested printing 2020 Extrusions 293mm looks very promising. :-) 🤩 This also use MGN12H 😊

28.02.2025 15:00 I have a new version this one doesn’t use any bearings or adjustments screws. Have less parts. I’m currently testing it. It use the spring from the Voron Extruder. I have not tested tool changes yet hopefully this doesn’t introduce a new problem.




~~![2024_v7_Hydra_Tool_Changer](https://github.com/user-attachments/assets/3ce1d50a-5780-406a-b5fd-529a8906fef1)~~

Release candidate 16.03.2025 This version use Exstruder spring at the center of the MGN9/12

~~Release candidate 24.12.2024 this version is deleted.~~

~~(Hydra Head MGN9H for now. MGN12 H & C is comminig (same Hydra Head offsets but alter the placement of the pulleys it is done I just need to test them))~~

Link: Hydra Tools SB

https://github.com/alfskaar/Hydra/blob/main/STLs/Toolheads/Hydra_Tool.stl

Link: Hydra Head MGN9H, 6mm Belt

https://github.com/alfskaar/Hydra/blob/main/STLs/Shuttle/MGN9H/Hydra_Head_MGN9H.stl

Link: Hydra Head MGN12H, 6mm Belt, you also need the new XY_joints_6mm_belt, as Hydra Head are the same offset for the belt for both MGN9 & MGN12

https://github.com/alfskaar/Hydra/blob/main/STLs/Shuttle/MGN12H/Hydra_Head_MGN12H.stl

************************************************************

<img width="966" alt="stealthburner_clip_section" src="https://github.com/user-attachments/assets/27685f81-cbdd-442c-8d07-2ad5dd7e1e85" />

<img width="430" alt="stealthburner_clip" src="https://github.com/user-attachments/assets/a95d224c-f796-4940-b4a8-0fa2e5c1d46d" />


Link:
https://github.com/alfskaar/Hydra/blob/main/STLs/Toolheads/Stealthburner/stealthburner_clip.stl

Or for additional holding down to bed.
https://github.com/alfskaar/Hydra/blob/main/STLs/Toolheads/Stealthburner/stealthburner_clip_ears.stl

************************************************************

<img width="434" alt="Dock_SB_clip_re_inforce_20mm" src="https://github.com/user-attachments/assets/41f54674-d6e1-41a4-a4b4-e0ecb289f828" />

Link: Dock
https://github.com/alfskaar/Hydra/tree/main/STLs/Toolheads/Stealthburner/Dock/RatRig_V-SLOT_2020

************************************************************

<img width="623" alt="Left_TBG_Lite_Stealthburner_01" src="https://github.com/user-attachments/assets/1b805e59-908c-46ac-9d32-e5042c4a9e99" />

Link:
https://github.com/alfskaar/Hydra/tree/main/STLs/Extruders/TBG_Lite_Left_Extruder

************************************************************

Umbilical using Cat 8 cable for 4 tools

https://github.com/alfskaar/Hydra/tree/main/STLs/Voron_2.4/Gantry/AB_Drive_Units_v_Umbilical

************************************************************



2024 04 26 Voron 2.4 Marlin Hydra tool changer
https://www.youtube.com/watch?v=dxacGMmqg3s

My added C code and config files are uploaded to this PR's
"platformio.ini, Configuration.h, Configuration_adv.h, pins_BTT_OCTOPUS_MAX_EZ.h, tool_change.cpp"
https://github.com/MarlinFirmware/Marlin/pull/26956


2024 v7 release candidate
************************************************************

Connecting...

Printer is now online.

Using tool 0.

g34

SENDING:G34

G34 Iteration: 1

1:2=0.005 3-2=0.008 3-1=0.003 4-3=0.010 4-2=0.017 4-1=0.012

Target accuracy achieved.

Did 1 of 5

Accuracy: 0.02

************************************************************
18.04.2024 kl 17:24:00



Singel tool tested and nothing found. Nice and tight and no play that affect the 3d print.
Parameters for Hydra toolchanger tested and tuned smooth as bacon in butter. :-) 🧈  10.04.2024

~~ ~~Just found my "MOSFET" isue. 23.03.2024 22:45:00 this take some time. ;-) it where pulling T1 (heater 1) to 0.70 volt and give it about 60 degrees Celsius. Fixed.~~ ~~


## Hydra Toolchanger

BOM, Date (DD.MM.YYYY) 07.03.2024
https://github.com/alfskaar/Hydra/commit/8cb29726a767612117fd642db2e9c7ac91441bed#commitcomment-139513031

#


Octopus-Max-EZ, 4 tools using Marlin

#

Pin, X3
<img width="135" alt="Pin_2024-03-07 at 18 50 05" src="https://github.com/alfskaar/Hydra/assets/31868161/6185ba89-0f6f-4dcc-b056-ccb20392aa4d">
<img width="483" alt="Pin_2024-03-07 at 18 49 54" src="https://github.com/alfskaar/Hydra/assets/31868161/eb194f39-679a-4cb4-9227-06a30563873d">
https://www.aliexpress.com/item/1005004255703769.html?spm=a2g0o.order_detail.order_detail_item.5.19acf19c9m2qwo

#

Bushing, X3 * (tools)
<img width="106" alt="Bushing 2024-03-07 at 19 06 34" src="https://github.com/alfskaar/Hydra/assets/31868161/7c34069d-42de-4e2f-86f9-eac2bfdfe223">
<img width="190" alt="Bushing 2024-03-07 at 19 06 13" src="https://github.com/alfskaar/Hydra/assets/31868161/8f7fdd81-2394-4efd-b3ed-29062f637ebc">

https://www.aliexpress.com/item/1005005335880614.html?spm=a2g0o.productlist.main.3.adeb7bcb60qlYa&algo_pvid=1eed7e33-0a1f-4754-a2ae-281e3dac1661&algo_exp_id=1eed7e33-0a1f-4754-a2ae-281e3dac1661-1&pdp_npi=4%40dis%21NOK%2118.67%2116.80%21%21%2112.70%2111.43%21%4021032dc617098345581521335ef1a8%2112000037875714932%21sea%21NO%214550078426%21&curPageLogUid=Y0uymCjm5xhP&utparam-url=scene%3Asearch%7Cquery_from%3A

#
V2 Shuttle
X2, 3x8x4 MR83zz bearings.
https://www.google.com/search?q=MR83zz
#
Will only be released if you ask for it. Please use v2 Shuttle BOM.


~~ ~~V1 Shuttle 
X2, 3x10x4 623 Bearings.
https://www.google.com/search?q=623+bearing~~ ~~
#
Magnets, X2

https://lecktor.com/en/v0-misc/390-round-n52-silver-magnets-6x3mm.html

OPTOTAP

X1 (Marlin)

X1 (RepRapFirmware) ? TBD

X1 ((Klipper) * (tools))

https://lecktor.com/en/voron-tap/1395-optotap-pcb-v21-5-24v.html
#


CNC friendly
immortal (as in Hydra one part (as in head) will stay the same ones you select MGN9H, MGN9C, MGN12H, MGN12C, 6mm, 9mm belts.
Combining  CNC and 3d printed parts best from both worlds.

Very modular.
Pin mod for the belt. I’m not giving up on this as working on the 3d printer is so nice.

I currently have about 15 🦷 holding the belt, so that can maybe be made smaller number of tooth's. Credits "Boop".

NO heat inserts.

NO glue

Can be 3d printed or CNC or both.

Magnet strength can be adjusted two different ways. They are secure and have no way of getting out.

Credit for the rest is all currently available toolchanger you can find. E3D, Prusa, tapchanger, Stealthchanger. and so on.

"Hydra, in Greek legend, the offspring of Typhon and Echidna (according to the early Greek poet Hesiod's Theogony), a gigantic water-snake-like monster with nine heads (the number varies), one of which was immortal."

Todo:
Pictures & Video ones I'm ready to release it to the public.


Add: Compatibility: BTT HERMIT CRAB V2.0 Current status: CAD: Both front & rear parts Done 16.03.2024, Next implementation. Done 20.03.2024, printed

Parts I need to order:

TYPE: HERMIT CRAB V2.0 - STANDARD VERSION

TYPE: HERMIT CRAB V2.0 - CAN VERSION

Order 16.02.2024 , received 27.02.2024

This will give you unlimited numbers of virtual (Manuel) tools.
Extruder,
Cutter,
Pen Plotter,
Laser Engraver,
Pick and place,
Other 

#
### Credits
https://github.com/VoronDesign/Voron-Stealthburner

https://github.com/VoronDesign/Voron-2

https://github.com/PrintersForAnts/Boop

https://github.com/viesturz/tapchanger

https://github.com/Stealthchanger/Toolchanger

https://github.com/bigtreetech/HermitCrab/tree/master/HermitCrab2

https://github.com/majarspeed/Misc-Voron/tree/main/StealthBurner%20Umbilical%20cover

https://github.com/Eytecz/LGX_Lite_Stealthburner_CW2_style_mount
