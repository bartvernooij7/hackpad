# Hackpad

Hi, this is my Hackpad repository. I originally started making this Hackpad on Blueprint, but Blueprint has ended, so I moved over to Forge to finish.
I designed the macropad for hardware monitoring and functioning as a soundboard. It features an integrated display, a rotary encoder for volume control, and 4 programmable buttons for macros (like passwords) and shortcuts (like `Ctrl+C`). While the screen currently displays a static photo, the software for hardware monitoring and volume control is fully functional.

## what is the purpose of this project 
for my and for other people how to build your own macropad. but why build your own macropad if you can buy one in the store? 
because it is fun to do, and this one is fully customized to my needs and you can customize it to your needs 
## Why Did I Make This?
I built this macropad because I wanted to learn how to design my own PCBs and write custom firmware. This project served as an excellent introduction to creating my first PCB. Additionally, I built it to improve my personal workflow, making it easier to adjust settings and monitor my system while doing homework or 3D modeling.

## How to Assemble
To recreate my Hackpad, you will need a soldering iron, access to a 3D printer, a computer for flashing the firmware, and basic soldering skills.

1. **Order the PCB:** Upload the Gerber files (`macro pad_drl.zip`) found in the `gerbers` folder of my repository to a manufacturer like JLCPCB ([JLCPCB Link](https://shorturl.at/ydwEK)). Order this first, as shipping takes a long time if you want it cheap!
2. **Order Parts:** While waiting for the PCB, order the remaining components from the Bill of Materials (BOM) via AliExpress.
3. **3D Print the Case:** Download the 3D model from the `cadmodel` folder in the repository and print it yourself, or use a site like JLC3DP ([JLC3DP Link](https://jlc3dp.com/3d-printing-quote?from=button)).
4. **Soldering:** Once all parts arrive, solder the components onto the PCB following the reference photos.
5. **Flashing the firmware:** Use the guide below this bullet list to flash the firmware.
6. **Assembly:** Drop the finished PCB into the 3D-printed case. You can use glue for extra security. After that, you can put on the top part of the case and screw it on. 

## Reference pictures for soldering
<img width="1724" height="938" alt="image" src="https://github.com/user-attachments/assets/04a45da7-f430-4142-9e4a-e12406900282" />
<img width="1724" height="938" alt="image" src="https://github.com/user-attachments/assets/973dba4a-bca7-4c6e-bf2c-5c3535d9df99" />
After you are done with soldering, it should look like this (this is a render). 
If yours looks just like this one, you can put the keycaps on and move on with the next part of making my Hackpad.  

## How to Flash your Hackpad
This project uses an RP2040 microcontroller (a XIAO Seeed).

1. To flash the firmware, I recommend you follow this guide on how to flash microcontrollers for keyboards: [sl1nk.com/z8o8f68](https://sl1nk.com/z8o8f68).
2. Once the firmware is successfully flashed, you can put the PCB in the case, place the top on the case, and secure it with generic screws (or the ones listed in the BOM).

## Bill of Materials (BOM)
Here are all the parts and prices required for this build:

| Item | Price | Link |
| :--- | :--- | :--- |
| Keycaps (Green) | €2.45/$2.86 | [AliExpress Link](https://l1nk.dev/9ejw5r6) |
| Rotary Encoder | €1.52/$1.70 | [AliExpress Link](https://nl.aliexpress.com/item/1005009040530746.html) |
| 128x32 Screen | €1.60/$2.36 | [AliExpress Link](https://nl.aliexpress.com/item/1005013116684555.html?spm=a2g0o.cart.0.0.882661d7mZEAk9&mp=1&pdp_npi=6%40dis%21EUR%21EUR+9.41%21EUR+1.60%21%21EUR+1.60%21%21%21%40210381f017886929285718695e0f68%2112000060258627094%21ct%21NL%214712872211%21%211%210%21&gatewayAdapt=glo2nld) |
| Switches (20pc) | €3.18/$3.71 | [AliExpress Link](https://nl.aliexpress.com/item/1005011838889689.html) |
| Seeed RP2040 | €10.94/$12.77 | [AliExpress Link](https://a.aliexpress.com/_EQkfTBi) |
| Screws | €3.96/$4.59 | [AliExpress Link](https://nl.aliexpress.com/item/1005008724193768.html) |
| PCB | €8.52/$4.26 | N/A |
| Filament | Free (I pay) | N/A |
| **Total AliExpress** | **€23.98/$27.98** | |
| **Total Complete** | **€32.61/$32.25** | |

## Some known Issues (will get fixed)
* The screen currently only displays a static photo; this is because I have not built it yet, so I can't debug it and write software for it.

## Pictures of the Hackpad, schematic, PCB, etc.
<img width="1087" height="765" alt="image" src="https://github.com/user-attachments/assets/5b38e566-780a-4d95-bc80-86efb456a5aa" />
<img width="953" height="722" alt="image" src="https://github.com/user-attachments/assets/63d06758-fc59-4dbb-899e-4b716b773767" />
<img width="1688" height="906" alt="image" src="https://github.com/user-attachments/assets/a76c55c1-07ce-4306-8192-1f9a89df3340" />
<img width="1322" height="805" alt="image" src="https://github.com/user-attachments/assets/b3376ccc-643e-46c7-ba38-3270b7413afb" />
<img width="1225" height="915" alt="image" src="https://github.com/user-attachments/assets/0cd2037a-315b-4bd3-ba42-b141b81cde8d" />
<img width="1444" height="757" alt="image" src="https://github.com/user-attachments/assets/32005165-104e-4ba9-bd32-0e87eec072a8" />

## Credits
* Huge thanks to Hack Club and Forge for the support, guides, and help from the community.
