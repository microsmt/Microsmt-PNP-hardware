# Microsmt-pnpboard
# Introduction
  We are building a circuit board suitable for OPENPNP. All its functions are only for OPENPNP.

The schematic diagram of microsmt pnpboard is modified from the open source document of smoothieboard, mainly as follows:

1: The network module and temperature measurement module are deleted because they are meaningless to the PNP machine.

2: The A5984 driver chip is replaced by the easier and cheaper TMC2209 driver module, so the electronic potentiometer MCP4451 is useless. When you need to change the drive current, you need to use a screwdriver to turn the mechanical potentiometer on the TMC2209 module

3: Some chips have been replaced with brands with the same parameters but easier to buy.

4：We do not have a separate software version. It is recommended to obtain the firmware dedicated to OPENPNP from the following link. It is contributed by makr.
                  https://makr.zone/smoothieware-new-firmware-for-pnp/500/
#  Thank  
