#  RISC-V Reference SoC Tapeout Program VSD

<div align="center">

![RISC-V](https://img.shields.io/badge/RISC--V-SoC%20Tapeout-blue?style=for-the-badge&logo=riscv)
![VSD](https://img.shields.io/badge/VSD-Program-orange?style=for-the-badge)
![Participants](https://img.shields.io/badge/Participants-3500+-success?style=for-the-badge)
![India](https://img.shields.io/badge/Made%20in-India-saffron?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjQiIGhlaWdodD0iMjQiIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPHJlY3Qgd2lkdGg9IjI0IiBoZWlnaHQ9IjgiIGZpbGw9IiNGRjk5MzMiLz4KPHJlY3QgeT0iOCIgd2lkdGg9IjI0IiBoZWlnaHQ9IjgiIGZpbGw9IiNGRkZGRkYiLz4KPHJlY3QgeT0iMTYiIHdpZHRoPSIyNCIgaGVpZ2h0PSI4IiBmaWxsPSIjMTM4ODA4Ii8+Cjwvc3ZnPgo=)

</div>
Based on the Indrocution Program of the course here are some key takeaways.

### Chip Design Flow
<div align="center">
	
| Flow |
| :---: |
| GCC application |
| ⬇️ |
| Specs model (chip modelling) |
| ⬇️ |
| RTL architect |
| ⬇️ |
| SoC design (Processor,Peripherals) |
| ⬇️ |
| SoC integration |
| ⬇️ |
| Tapeout(RTL2GDS-GDSII-DRC/LVS-factory-chips) |

</div>
<details>
	<summary>Week 0 - Tools Installation </summary>
	
# Week 0 - Tools Installation
## Yosys
```
$ git clone https://github.com/YosysHQ/yosys.git
$ cd yosys 
$ sudo apt install make (If make is not installed please install it) 
$ sudo apt-get install build-essential clang bison flex \
    libreadline-dev gawk tcl-dev libffi-dev git \
    graphviz xdot pkg-config python3 libboost-system-dev \
    libboost-python-dev libboost-filesystem-dev zlib1g-dev
$ make 
$ sudo make install
```
<img width="600" alt="yosys" src="https://github.com/mvbc-22/RISC-V_tapeout_program/blob/main/images/yosys.png">

## Iverilog
```
$ sudo apt-get install iverilog
```
<img width="600" alt="iverilog" src="https://github.com/mvbc-22/RISC-V_tapeout_program/blob/main/images/iverilog.png">

## GTKWave
```
$ sudo apt update
$ sudo apt install gtkwave
```

<img width="1000" alt="gtkwave" src="https://github.com/mvbc-22/RISC-V_tapeout_program/blob/main/images/gtkwave.png">

