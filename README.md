# AV Famicom audio rebalance mod
AV Famicom audio rebalance mod with onboard JIO chip

This mod with restore audio balance for AV famicom 

This mod as been possible with the help of @RGBeter in collaboration with @zaxour and other people I might be forgetting from the nes-help discord channel

***please take note of R5, it should be labeled R14. ***
corrected original schematic
edit .: need to edit original schematic to include 330pf cap close to acc.  pin output.

<img width="989" height="823" alt="Capture d’écran 2025-09-30 153217" src="https://github.com/user-attachments/assets/596ccf0a-a6f5-4e55-ade0-4215cfb32920" />

Audio rebalance mod using the onboard JIO and changing value of feedback resistor to 100k
demo:
https://youtu.be/wgp7kMOipns


with  200kohm bypass resistor and emitter follower bypass.
https://youtu.be/3buJMaxNMy4?si=RrFYKJSqxp3j4Q_5

![20251005_102746](https://github.com/user-attachments/assets/80d7fa41-af7f-43b0-8db3-0068e95631dc)
![20250930_141717](https://github.com/user-attachments/assets/3fd073a5-3826-4cd8-a2e6-b9875dedbee0)

<img width="1024" height="828" alt="Capture d’écran 2025-09-30 153411" src="https://github.com/user-attachments/assets/1f0d915d-1e1a-4a32-b037-563eba46cb34" />

with NESRGB cpu pin 1 and 2 processed from NESRGB audio amp. pin 17 of JIO lifted, pin 16n of JIO grounded. rest of console unmodded.
https://youtu.be/984OKWRvlqM?si=iO-1KLJwgtD5y-Pq



Basic documentation. more will follow.
for av famicom just swap R14 for a 200kohm resistor. bypass the emitter-follower, lift positive leg of C4 and bridge audio from pin 46 to it (or from positive lead of R8 to lifted positive lead of C4).
Original AV famicom audio path reversed engineered by me
<img width="989" height="823" alt="Capture d’écran 2025-09-30 153217" src="https://github.com/user-attachments/assets/b59b905a-caff-428d-b0f2-1c748323d421" />


@RGBeter from discord have been a great help suggesting me to use this schematic which is base of the original famicom 
![Screenshot_20250901_182014_Discord](https://github.com/user-attachments/assets/8ab7f5b0-f714-4ed8-a752-f6f4a288eae3)


<img width="1206" height="1029" alt="av_fami_audio_pre_mod3" src="https://github.com/user-attachments/assets/ad465ad6-02af-4c49-aa9e-daefc739e2d2" />

original audio path for famicom red and white
![tnAKiml](https://github.com/user-attachments/assets/c24acef5-7a1a-4cd0-bfbc-f87b37309d15)



@RGBeter suggest using an amp after pin 46 before send it to multiout output

also ouput for multiout could be changed to this, replace 1uF cap and 39uH FC for 330 ohm resistor a and 10uF cap
![Screenshot_20250901_160254_Discord](https://github.com/user-attachments/assets/c42a2936-389f-46e4-b9d4-4d47c8147217)


Picture from the from basic mod (don't mind the red and black wires they go nowhere)
![20250901_180043](https://github.com/user-attachments/assets/0b91dcae-13fb-492c-af7b-f610674f0296)


AV Famicom audio rebalance mod with an 74UCH04

this demo is with an 74UCH04. I've changed the 20k and 12k resistors for 10k and 5.6k. feedback resistor at 47k.
https://youtu.be/IyiM1r6P4y0


zaxour recommend 5.1k and 9.4k to properly restore audio at the same level as the og famicom.

![20250904_144728](https://github.com/user-attachments/assets/d7377174-a13d-4c0c-8dda-cf29d857ab76)


audio path underside. 
There is a trace that goes into the innner layers I wasn't able to trace it completely. 
![av_famicom_pcb_audio_path-1](https://github.com/user-attachments/assets/70eeeb51-472e-41f7-9327-d76ecced332f)



<img width="421" height="114" alt="image" src="https://github.com/user-attachments/assets/c6a2cd9b-0cfc-4059-9306-6b16b4fad8d1" />
<img width="459" height="94" alt="image" src="https://github.com/user-attachments/assets/1abac8e8-65ff-401c-a98e-a2b99227bfb0" />

AV Famicom audio rebalance mod with an 74UCH04, audio taken from pin 1 and 2 directly
https://youtu.be/Jiav9FQyHyg
![Screenshot_20251005_134155_Discord](https://github.com/user-attachments/assets/e6583043-a8d5-4204-bc1c-fc6a560e8923)



