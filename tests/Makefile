SIM ?= icarus
TOPLEVEL_LANG ?= verilog
VERILOG_SOURCES += $(PWD)/../hdl/xor.v
or:
	$(MAKE) sim MODULE=xor_test TOPLEVEL=xor
include $(shell cocotb-config --makefiles)/Makefile.sim
