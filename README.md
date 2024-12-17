# Introduction
The H961-U v6.1 is a battery management system (BMS) and power bank module. It has features like :
* Over charge protection
* Over Discharge protection
* Short circuit protection
which ensures that the lithium ion batteries (18650 cells) remain at a safe and operable state.
It has two USB A ports for charging two devices at a rate of 5V & 2.4A on the quick charge port and 5V and 2A on the standard port.
The board has 3 input ports for charging the batteries, which include a type C port, lightning port and a micro usb port.
It has a built-in 7 segment display to indicate the charge of the battery and a few other LEDs to show whether the device is charging or not.

The goal of this project is to incorporate the power bank module with some recycled 18650 lithium ion cells to make a simple power bank.
The casing fo the power bank is made of PLA plastic. I will be using a FDM 3D printer to create the case.

## Materials required:
* H961-U v6.1
* 3 (Nos.)18650 cells which are compatible with the module
* 3D printed case, lid and button (stl files are in this doc)
* Soldering iron, solder and flux
* 24 gauge wire
* Double Sided Tape (to hold down the batteries)
* FeviBond (to glue the lid to the case)

## NOTE:
It is important to handle lithium cells with care. They can catch on fire or explode if they are not properly handled. To take proper care of the cells,
read the datasheet for your specific cell to understand its parameters  over-voltage, over-current, over-discharge operating temperature, charge cycles etc.
Ensure that the cells operate at the conditions specified by the manufacturer. If the parameters of the cells do not match that of the power-bank module, do not use it.
Avoid dropping the cells or storing them in environments which might compromise the safety of the cells. Refer to the datasheet for proper storage and use.
Do not expose the cells to cold or hot environments. Excessive heat can cause the battery to explode. Follow all specifications provided by the manufacturer for safe use.

When you are choosing the cells for the bank configuration, ensure that they are from the same batch, i.e. the cells should have similar/equal voltages or should have gone
through similar/equal number of charge cycles. For brand new cells this shouldn't be a problem as long as all 3 cells are of the same model and have same specifications.
If you are reusing cells form an old device (such as a laptop), ensure that the cells have similar/equal voltage and charge cycles. 

Regardless of the state of the cell, whether brand new or used, charge the cells using an external charger to full capacity and note down how the voltage drops over a 
span of day. Based on these observations, choose or reject the cells. If there is a drastic difference between the cells, do not use them. 
After connecting the cells to the power bank module, avoid using metallic tools to pry, push or pull the battery, the board or the wires as it might short the connections 
on the board or between the cells. The battery should be connected in a bank configuration only when you're ready to place it into the case.
Do not place the bare PCB or the cells near/on any conducting surfaces.

## SETUP

In my configuration, I will be wiring the 3 cells in parallel so 3P configuration. The cells have been extracted from a laptop battery. So they should have gone through similar
amount of wear. It is still recommended to charge all the cells, individually to full capacity and then to measure how much the voltage drops over few hours to see if the cells
are comparable. It is also recommended not to directly solder the wires to the lithium ion cell, as the battery is sensitive to temperature and this can also cause the cell
to explode if the cells remain at a higher temperature. However, soldering quickly, without continously heating the cell can help us to solder the wires without
excessively heating the cells.

After connecting the cells in a parallel configuration, connect the positive terminal of the battery to BAT+ on the power bank module and negative terminal of
the battery to BAT- of the module. These connections should be made before placing the battery and the board in the housing, as it is easier to solder without the risk
of melting the case.

The case is designed to hold the board using friction. Insert the button into the case. Slide the board into the case, such that the usb ports are in their slots.
Push down on the board after the usb ports are allgined with the case. This will hold down the board. No additional support is needed to hold it down as the tapered walls of
the case should hold the board firmly. Apply the double sided tape to the battery and then stick it to the case. Apply glue to the outer edge of the case and press down the lid
to attach the lid.
  

  
  
  
