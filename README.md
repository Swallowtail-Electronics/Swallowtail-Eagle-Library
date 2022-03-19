# Swallowtail Electronics Eagle Libraries
----------------

Here it is! The Swallowtail Electronics standard EAGLE library for EAGLE V6.0 and greater (tested up to V9.6.2). Download the library [here](https://github.com/Swallowtail-Electronics/Swallowtail-Eagle-Library/zipball/master).

If this library is of use to you please consider our products at the [Swallowtail Electronics Storefront](https://swallowtailelectronics.com).

Note that we cannot guarantee every component in this library is perfectly to spec. Use these files at your own risk. *We cannot be held responsible for faulty PCBs. Always check your parts against a 1:1 printout.*

## How to Install
----------------
1. Enter the `Control Panel` window in EAGLE.
2. Go to `Options>Directories` menu. Edit the `Libraries` line to something like:

For Windows
> \$EAGLEDIR\\lbr;\$HOME\\external_lbrs

For OS X
> \$EAGLEDIR/lbr:$HOME/external_lbrs
3. Save your changes.
4. EAGLE should prompt you to create the `external_lbrs` if it does not exist. Place this in the location you would like and select `Yes`.
5. Find and open the `external_lbrs` directory. Unzip the .lbr files from this repo into that folder.
6. Restart EAGLE. The library should now appear.

## Library Descriptions
----------------
Parts have been grouped into common catagories. All Swallowtail Libraries are indicated with the prefix SW.
- *Aesthetics* - Logos and notes.
- *BatteryChargers* - Mix of battery chargers for various chemisties.
- *BuckBoost* - Buck/Boost style power supply ICs.
- *Communications* - Digital and RF communications ICs.
- *Connectors* - Mix of though-hole and SMD connectors.
- *Conversion* - Various ADC/DAC ICs.
- *Crystals* - Crystal Oscillators, TXCOs, RTCs.
- *Diodes* - Rectifiers, Zeners, TVS, Schottky.
- *Display* - LCDs, Seven-Segments and OLEDs.
- *Frames* - Design Frames for printable schematics.
- *Fuses* - Circuit protection via varistors, PTCCs.
- *Input* - Buttons, Switches, Rotary Encoders.
- *LDO* - Low Dropout or Linear Regulators.
- *Logic* - 4XXX and 74XX series logic ICs
- *MfgTest* - Manufacturing Fiducials, Jumpers, and Test Points.
- *Microcontrollers* - ATmegas, ATtinys, PICs, STM32s, etc.
- *MOSFET* - Field Effect Transistors of all types.
- *Motor* - Motor drivers, H-bridges of all types.
- *OpAmp* - Operational Amplifiers from the fast to classics.
- *Passives* - Resistors, Capacitors, and Inductors.
- *Sensors* - Accelerometers, gyros, compasses, magnetometers, light sensors, temp sensors, transducers of all types.
- *Supply* - Conviently marked and aesthetically pleasing supply markers.

## Spotted an Error?
----------------
If you discover a bug with an existing component, please submit an issue or pull request. Please call out the specific part number and library in your request.