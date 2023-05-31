SIM ?= icarus
TOPLEVEL_LANG ?= verilog
VERILOG_SOURCES += $(PWD)/../hdl/exor.v
VERILOG_SOURCES += $(PWD)/../wrappers/exor_test.v

TOPLEVEL = xor_test
MODULE = xor_test

include $(shell cocotb-config --makefiles)/Makefile.sim
