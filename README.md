# SoFPGA - real time FPGA image processing
**System on FPGA for real time FPGA image processing** - my personal approach for Image/Video processing on FPGA. The main motivation is to bring back my PhD project back to life while learning new stuff. I would like to cover the entire design cycle - software prototype, RTL simulation and FPGA development. 

*Motivation:*
- resurrect my project [Hardware architectures for infrared pedestrian detection systems](https://www.napier.ac.uk/research-and-innovation/research-search/outputs/hardware-architectures-for-infrared-pedestrian-detection-systems#downloads)
- brush up my RTL development skills
- learn new stuff

*Objectives:*
- use open source tools
   - [Icarus Verilog simulator](http://iverilog.icarus.com/)
   - [Verilator HDL simulator](https://www.veripool.org/wiki/verilator)
   - [cocotb](https://cocotb.readthedocs.io/en/latest/)
 - move out from my comfort zone
   - Python 3
   - Intel FPGA

*Goals:*
- create an open framework for FPGA image creation
- develop a platform which could be re-used for similar projects
- I want to see this again - real-time video capture into the FPGA, segmentation, classification and tracking on the output screen!


___



How to install [Icarus Verilog simulator](http://iverilog.icarus.com/)
----------------------------------------------------------------------

Follow [Installation_Guide](https://iverilog.fandom.com/wiki/Installation_Guide). If working in Centos 7, I would recommend the following path: 
- *Obtaining Source From git*
- *Compiling on Linux/Unix*
- [Getting Started tutorial](https://iverilog.fandom.com/wiki/Getting_Started)


How to install GTKWave
----------------------

- Download latest from http://gtkwave.sourceforge.net/ 
- `sudo yum localinstall gtkwave-3.3.61-1.el7.x86_64.rpm`
- If you have dependency issues with `libJudy` package - download from [here](https://centos.pkgs.org/7/epel-x86_64/Judy-1.0.5-8.el7.x86_64.rpm.html) and install:

   `sudo yum localinstall https://centos.pkgs.org/7/epel-x86_64/Judy-1.0.5-8.el7.x86_64.rpm.html`
- Run GTKWave as follows:
```
   cd examples/dff
   make
   gtkwave dump.vcd
```

Links
-----

[Quick github markup tutorial](https://github.com/adam-p/markdown-here/wiki/Markdown-Here-Cheatsheet)

[Github official markup docs](https://help.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax)
