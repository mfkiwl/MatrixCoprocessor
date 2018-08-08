# Co-processor for Matrix calculations in embedded systems.

Architecture of co-processor developed as a part of my Bachelor thesis. Made using VHDL, Quartus Prime 17.1 and Modelsim. Tested and programmed on FPGA (Cyclone V GX 5CGXFC5C6F27C7N).
It uses Schur's complement,  modified Fadeev algorythm and systolic architecture to realize basic matrix operations (+, -, *, inversion) and their combinations in constant count of cycles.

## Prototype

Prototype is implemented using FPGA and VHDL and operates with 4x4 matrices in 12,5MHz frequency. With some modifications this should be easily improveable.

## Built With

* [Quartus Prime(17.1)](https://www.altera.com/products/design-software/fpga-design/quartus-prime/overview.html) - Synthesis and overall design compilation and programming to FPGA board
* Modelsim - Altera - Simulation tool
* [Cyclone V GX Starter Kit](https://www.intel.com/content/www/us/en/programmable/solutions/partners/partner-profile/terasic-inc-/board/cyclone-v-gx-starter-kit.html) - board used.
* [FPGA board control panel](http://www.terasic.com.tw/cgi-bin/page/archive.pl?Language=English&CategoryNo=165&No=830&PartNo=4) - Used for testing purposes (reading from and writing to SRAM that is embedded in board)
## Authors

* **Olafs Aploks** - *Initial work*, **Jānis Šate** - *Supervisor*

