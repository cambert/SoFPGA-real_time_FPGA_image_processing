all:run compile

compile:
	iverilog -o hello hello.v

run: compile
	vvp hello

