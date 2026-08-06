# Hackpad

hi this my hackpad reposty, i oringaly started making this hackpad on blueprint but blueprint has ended so i moved over to forge to finsch 
i designed the macropad for hardware monitoring and functioning as a soundboard. It features an integrated display, a rotary encoder for volume control, and 4 programmable buttons for macros (like passwords) and shortcuts (like `Ctrl+C`). While the screen currently displays a static photo, the software for hardware monitoring and volume control is fully functional.

## Why Did I Make This?
I built this macropad because I wanted to learn how to design my own PCBs and write custom firmware. This project served as an excellent introduction to creating my first PCB. Additionally, I built it to improve my personal workflow, making it easier to adjust settings and monitor my system while doing homework or 3D modeling.




## How to Assemble
To recreate my Hackpad, you will need a soldering iron, access to a 3D printer, a computer for flashing the firmware, and basic soldering skills.

1. **Order the PCB:** Upload the Gerber files (`macro pad_drl.zip`) found in the `gerbers` folder of my repository to a manufacturer like JLCPCB ([JLCPCB Link](https://shorturl.at/ydwEK)). Order this first, as shipping takes a logng if you want it cheap time!
2. **Order Parts:** While waiting for the PCB, order the remaining components from the Bill of Materials (BOM) via AliExpress.
3. **3D Print the Case:** Download the 3D model from the `cadmodel` folder in the repository and print it yourself, or use a site like JLC3DP ([JLC3DP Link](https://jlc3dp.com/3d-printing-quote?from=button)).
4. **Soldering:** Once all parts arrive, solder the components onto the PCB following the reference photos.
5. **flashing the firmware** use the guide below this bultlist to flash the firmware
6. **Assembly:** Drop the finished PCB into the 3D-printed case. You can use glue for extra security. after that you can put on the top part of the case and schrew it on 

## refence pictures for soldering
<img width="1724" height="938" alt="image" src="https://github.com/user-attachments/assets/04a45da7-f430-4142-9e4a-e12406900282" />
<img width="1724" height="938" alt="image" src="https://github.com/user-attachments/assets/973dba4a-bca7-4c6e-bf2c-5c3535d9df99" />
after you are don with soldering with soldering it should look like this (this is a render) 
if youres looks just like this one you can put the keycaps on and move on with the next part of making my hackpad  



## How to Flash youre hackpad
This project uses an RP2040 microcontroller. ( a xiamiseeed)

1. to flash the firmware i recomend you Follow this guide how to flash microcontroler for keyboards : [sl1nk.com/z8o8f68](https://sl1nk.com/z8o8f68).
2. Once the firmware is successfully flashed, you can put the pcb in the case and place the top on the case and secure it with generic screws (or the ones listed in the BOM).

## Bill of Materials (BOM)
Here are all the parts and prices required for this build:

| Item | Price | Link |
| :--- | :--- | :--- |
| Keycaps (Green) | €2.45 | [AliExpress Link](https://l1nk.dev/9ejw5r6) |
| Rotary Encoder | €1.46 | [AliExpress Link](https://nl.aliexpress.com/item/1005009040530746.html) |
| 128x32 Screen | €2.02 | [AliExpress Link](https://a.aliexpress.com/_EJ4NFM8) |
| Switches (20pc) | €3.18 | [AliExpress Link](https://nl.aliexpress.com/item/1005011838889689.html) |
| Seeed RP2040 | €10.94 | [AliExpress Link](https://a.aliexpress.com/_EQkfTBi) |
| Screws | €3.93 | [AliExpress Link](https://nl.aliexpress.com/item/1005008724193768.html) |
| PCB | €3.65 | N/A |
| Filament | Free (I pay) | N/A |
| **Total AliExpress** | **€23.98** | |
| **Total Complete** | **€27.63** | |

## Some known Issues (wil get fixed)
* The screen currently only displays a static photo, this because i have not build yet so i cant debug it and writ software for it

## pictures of the hackpad, schemtic, pcb and etc
<img width="1087" height="765" alt="image" src="https://github.com/user-attachments/assets/5b38e566-780a-4d95-bc80-86efb456a5aa" />
<img width="953" height="722" alt="image" src="https://github.com/user-attachments/assets/63d06758-fc59-4dbb-899e-4b716b773767" />
<img width="1688" height="906" alt="image" src="https://github.com/user-attachments/assets/a76c55c1-07ce-4306-8192-1f9a89df3340" />
<img width="1322" height="805" alt="image" src="https://github.com/user-attachments/assets/b3376ccc-643e-46c7-ba38-3270b7413afb" />
<img width="1225" height="915" alt="image" src="https://github.com/user-attachments/assets/0cd2037a-315b-4bd3-ba42-b141b81cde8d" />
<img width="1444" height="757" alt="image" src="https://github.com/user-attachments/assets/32005165-104e-4ba9-bd32-0e87eec072a8" />




## Credits
* Huge thanks to Hack Club and forge for the suport, guides and help from the comunti 
