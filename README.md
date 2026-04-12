# Split Keyboard

## Building a custom wireless split mechanical keyboard from scratch.
## Why did I make this project?
  Sounded like a very fun project to make, also very cool to have your own custom keyboard (split one too). Also, I do not want to get carpal tunnel...
### PICTURES!!!
The easy part -

<img width="1904" height="1047" alt="1775320786451-4x2p1t" src="https://github.com/user-attachments/assets/c87b49f9-fe09-48dc-8f1e-37726bebfd35" />


The not-so-easy part - 

<img width="1915" height="1042" alt="1775912615627-d0wt4m" src="https://github.com/user-attachments/assets/be9c7628-58e8-4748-91be-615c5ea9f70d" />

## Assembly instructions - 
1. Heat-press the brass inserts into the case and glue the magnets into place.
2. Screw the stabilizers into the PCB and mount the sliding switch to the case.
3. Solder the diodes, Hall sensors, and header pins to the Seeeduino and PCB.
4. Connect the battery wires to the BAT pins and the sliding power switch.
5. Tuck the battery into its cavity and screw the PCB into the case.
6. Click switches into the plate, screw the plate to the case, and add keycaps.
7. Flash your ZMK firmware to the Seeeduino.
8. Repeat for the second half, pair them, and test your work.

## Bill of Materials (BOM)

| Name | Purpose | Quantity | Total Cost (USD) |
| :--- | :--- | :---: | :---: |
| **Seeed XIAO nRF52840** | Must be the nRF52840 version for Bluetooth | 2 | 32.00 |
| **LiPo Battery (3.7V)** | Look for "301230" or "401230" sizes (100–150mAh) | 2 | 6.00 |
| **Diodes (1N4148W)** | SOD-123 size (as per your KiCad layout) | 100 | 1.50 |
| **Budget Switches** | Outemu or Gateron Yellows | 45 | 12.00 |
| **Power Switches / Resistors** | MSK-12C02 switches and 0805 resistors | 1 | 2.00 |
| **Custom PCB (JLCPCB)** | $2 for boards + ~$8 global shipping | 1 | 10.00 |
| **TOTAL** |  |  | **63.50** |
