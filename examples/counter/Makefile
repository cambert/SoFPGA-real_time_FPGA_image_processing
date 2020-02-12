all:run compile

compile:
	iverilog -o counter_design counter.sv tb_counter.sv

run: compile
	vvp counter_design

