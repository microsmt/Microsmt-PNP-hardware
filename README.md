# Microsmt-PNP-hardwware
# Introduction
  We are building hardware suitable for OPENPNP. All its functions are only for OPENPNP.
# No.1  PNP Mainboard
 1:About the pnp  mainboard The schematic diagram of microsmt pnpboard is modified from the open source document of smoothieboard, mainly as follows:

 2: The network module and temperature measurement module are deleted because they are meaningless to the PNP machine.

 3: The A5984 driver chip is replaced by the easier and cheaper TMC2209 driver module, so the electronic potentiometer MCP4451 is useless. When you need to change the drive current, you need to use a screwdriver to turn the mechanical potentiometer on the TMC2209 module.

4: 3pcs freewheeling diodes is connected in parallel to the drive mos of the vacuum pump and relay. avoid the reverse current of the motor damage the mos.

5: Some chips have been replaced with brands with the same parameters but easier to buy.

6：We do not have a separate software version. It is recommended to obtain the firmware dedicated to OPENPNP from the following link. It is contributed by makr.
                  https://makr.zone/smoothieware-new-firmware-for-pnp/500/
                  
#  Notice
  The  sch  and  pcb  document   only  open with  AD.

#  Thank  
 
