all:run compile

compile:
	iverilog -o dff_design dff.sv tb_dff.sv

run: compile
	vvp dff_design

