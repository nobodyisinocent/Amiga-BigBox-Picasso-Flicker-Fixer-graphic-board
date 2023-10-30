# Amiga BigBox Picasso Flicker Fixed graphic board V0.9

# Table of contents
1. [What's new here ?](#0)
2. [What that ?](#1)
3. [Some pictures](#2)
4. [Project files](#3)
5. [Interactive HTML BOM](#4)

# What's new here ? <a name="0"></a>
- 21/10/2023: Change footprint of jack connector to avoid mechanical conflict with Amiga case as showned in picture below.

![image](https://github.com/nobodyisinocent/Amiga-BigBox-Picasso-Flicker-Fixer-graphic-board/assets/80821708/cfd2dcb2-e4dd-43af-b72b-f824fb010bcb)

Footprint used: Jack_3.5mm_CUI_SJ1-3535NG

![image](https://github.com/nobodyisinocent/Amiga-BigBox-Picasso-Flicker-Fixer-graphic-board/assets/80821708/253f6a4d-b3f2-4f20-9715-ceb9226bdec1)


- 10/2023 : Project migrated under Kicad <del>6.0.2</del> 7.0.8,
- Interactive HTML BOM generated.

# What that ? <a name="1"></a>
This is a Picasso 4MB Flicker Fixed graphic board for Amiga 2000, 3000 &amp; 4000 initialy designed with Kicad 5.1.12 under Linux Mint.
Now, project is developped under Kicad 6.0.2 under Linux Mint 21.1.

This board is designed from the two following projects:
  - The GBA1000 4MB Picasso Board V3.3 from Georg Braun (No official Website anymore),
  - The MultiFix AGA from Matthias Heinrichs aka Matze on A1k.org. It's an ECS and AGA-combo scandoubler and flicker fixer.
  The link of his project is available here:  
  https://gitlab.com/MHeinrichs/multifix-aga
    
The Picasso graphic board is made of two PCBs. The main one includes the designs of the Picasso and of the Flicker Fixer. The second one is a little male slot connector PCB which must be connected into the video slot of the Amiga. It's used for the Flicked fixer. In an Amiga 4000, this little PCB is onto the same axis as the Zorro edge slot. In the Amiga 2000, it must be connected into the video slot which located between its PSU and its cover case. Two ribbon cables as used to connect this PCB to the Flicker Fixer part of the board. 

To be useful onto an Amiga 2000, you'll need an accelerator board with fast memory (64MB is perfect) 

I want to thanks a lot my friends Lolof and Seb132 ! ;-)

# Some pictures ? <a name="2"></a>
  
The PCB in raytraced view !
![Picasso_FF_V0 9-Board-3D](https://user-images.githubusercontent.com/80821708/192138232-0980a8f4-f7ab-41ed-835d-e44e98105e04.png)

PCB with silkscreen:
![Picasso_FF_V0 9-Board](https://user-images.githubusercontent.com/80821708/192138204-b8575fb5-7632-45b8-b50c-aa4279b76107.png)

Top layer:
![Picasso_FF_V0 9-Board-Front](https://user-images.githubusercontent.com/80821708/192138208-3882107a-19d0-4e16-9dbd-e4f735679f8a.png)

First inside layer:
![Picasso_FF_V0 9-Board-Inside1](https://user-images.githubusercontent.com/80821708/192138212-ad65cb16-fbc5-4c6e-8a14-595d25aa4300.png)

Second inside layer:
![Picasso_FF_V0 9-Board-Inside2](https://user-images.githubusercontent.com/80821708/192138219-f35df53d-d64d-4f8e-9ac6-da8bce98c020.png)

Back layer:
![Picasso_FF_V0 9-Board-Back](https://user-images.githubusercontent.com/80821708/192138207-c43ad853-ff0e-43da-a6f0-e8d194fdb732.png)
  
  
# Project files <a name="3"></a>
  
Sorry, no file available actually here.
The Kicad project is finalized. I'll perhaps launch a production for some PCB. After assembling, if the board run fine, I'll put here the gerber files. Please remember that this is a personnal projet, it's not for commercial purpose.

# Interactive HTML BOM <a name="4"></a>
For the assembling of the board, an interactive HTML BOM generated under Kicad will be available here!

![image](https://github.com/nobodyisinocent/Amiga-BigBox-Picasso-Flicker-Fixer-graphic-board/assets/80821708/9f5236b9-a6b9-4034-9ae6-0d34c69d1015)

