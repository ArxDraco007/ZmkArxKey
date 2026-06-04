# ArxKey - A Custom Split Keyboard

## Building a custom wireless split mechanical keyboard from scratch.

## Why did I make this project?
  There are a lot of ill effects of using a non-ergonomic keyboard. Some basic effects happen, such as ulnar deviation (bending wrists outward), forearm pronation (palms facing down), and unnatural extension. It might also get very serious if you have Carpal Tunnel Syndrome (CTS): The median nerve in the wrist is compressed, often due to swollen tendons. It leads to numbness, tingling, and weakened grip strength. As the times change, you will require a keyboard as it becomes an integral part of your everyday life. It is best to have an ergonomic (furniture or equipment that makes it comfortable and effective for people who use it) keyboard, to make sure you enjoy your work.
You can also type very fast. It is also a very fun project to make, and it is also very cool to have your own custom keyboard (split one too).
### PICTURES!!!
The easy part -

<img width="1904" height="1047" alt="1775320786451-4x2p1t" src="https://github.com/user-attachments/assets/c87b49f9-fe09-48dc-8f1e-37726bebfd35" />


The not-so-easy part - 

<img width="1915" height="1042" alt="1775912615627-d0wt4m" src="https://github.com/user-attachments/assets/be9c7628-58e8-4748-91be-615c5ea9f70d" />

fusio' - 
<img width="1420" height="632" alt="left" src="https://github.com/user-attachments/assets/7711c0e2-655e-41af-9ecd-e7292ae6ff19" />


## Assembly instructions - 
1. Heat-press the brass inserts into the case and glue the magnets into place.
2. Screw the stabilizers into the PCB and mount the sliding switch to the case.
3. Solder the diodes, Hall sensors, and header pins to the Seeeduino and PCB.
4. Connect the battery wires to the BAT pins and the sliding power switch.
5. Tuck the battery into its cavity and screw the PCB into the case.
6. Click switches into the plate, screw the plate to the case, and add keycaps.
7. Flash your ZMK firmware to the Seeeduino.
8. Repeat for the second half, pair them, and test your work.
   
## How to use it?
1. Power on both halves, the keyboard will show as ArxSplit in the PC/Phone's Bluetooth settings.
2. The right and left layers are in the general QWERTY layout.
3. Plug the USB-C port into your PC or a charger. The XIAO powers on immediately and also charges the LiPo battery connected to the BAT/VBAT pads.
4. Flashing Firmware - Push the ZMK Files/ directory to a GitHub repo.
5. It will build two .uf2 files, my_keyboard_left and my_keyboard_right.
6. Double-tap the Reset button on the XIAO — it enters bootloader mode and mounts as a USB drive called XIAO-SENSE or NRF52BOOT. Drag and drop the .uf2 file onto that drive. It flashes automatically and reboots.

## Zine!

<img width="844" height="1294" alt="zine_page-0001" src="https://github.com/user-attachments/assets/45743b16-cf59-4109-8aca-d35d29783c61" />



| Name                           | Purpose                                          | Quantity | Total Cost (USD) | Link                                                                                                                                                                                         | Distributor |
| :----------------------------- | :----------------------------------------------- | :------: | :--------------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :---------- |
| **Hotswap Socket**             | Fittings for the Cherry MX                       |    50    |       6.00       | [https://stackskb.com/store/gateron-hotswap-sockets/](https://stackskb.com/store/gateron-hotswap-sockets/)                                                                                   | Stackskb    |
| **Seeed XIAO nRF52840**        | Must be the nRF52840 version for Bluetooth       |     2    |       32.00      | [https://makerbazar.in/products/seeed-studio-xiao-esp32s3-2-4ghz-wifi-ble-5-0](https://www.mouser.in/ProductDetail/Seeed-Studio/102010448?qs=Znm5pLBrcAJ5g%252BWAkitg4w%3D%3D&mgh=1&srsltid=AfmBOookTzqLpFXL5ZJK-A9C8BAJeETLAgGSwWRBi-OlQGBi2qX4YWWgBEQ)                                 | MakerBazar  |
| **LiPo Battery (3.7V)**        | Look for "301230" or "401230" sizes (100–150mAh) |     2    |       6.00       | [https://www.electropi.in/3.7v-300mah-lipo-battery-model-401230-india](https://www.electropi.in/3.7v-300mah-lipo-battery-model-401230-india)                                                 | Electropi   |
| **Diodes (1N4148W)**           | SOD-123 size (as per your KiCad layout)          |    100   |       1.50       | [https://robu.in/product/1n4148w-slkor-75v-1v-4ns-150ma-sod-123-switching-diodes-rohs](https://robu.in/product/1n4148w-slkor-75v-1v-4ns-150ma-sod-123-switching-diodes-rohs)                 | Robu        |
| **Cherry MX Switches**         | The keys                                         |    45    |       18.75      | [https://meckeys.com/shop/accessories/keyboard-accessories/key-switches/cherry-mx-rgb-switch/](https://meckeys.com/shop/accessories/keyboard-accessories/key-switches/cherry-mx-rgb-switch/) | Meckeys     |
| **Resistors** | 0805 resistors            |     1    |       2.00       | [https://robu.in/product/1k-ohm-1-4w-0805-surface-mount-chip-resistor-pack-of-10](https://robu.in/product/1k-ohm-1-4w-0805-surface-mount-chip-resistor-pack-of-10)                           | Robu        |
| **Custom PCB (JLCPCB)**        | $2 for boards + ~$8 global shipping              |     1    |       10.00      | [https://jlcpcb.com/](https://jlcpcb.com/)                                                                                                                                                   | JLCPCB      | 
| **TOTAL**                      |                                                  |          |     **76.25**    |                                                                                                                                                                                              |             |

