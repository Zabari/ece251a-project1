################################################################################
# Automatically-generated file. Do not edit!
################################################################################

# Keil tools exit code 1 is warnings only, so don't treat as an error in make
RC := test $$? -lt 2

-include ../makefile.init

RM := rm -rf

# All of the sources participating in the build are defined here
-include sources.mk
-include src/subdir.mk
-include lib/efm8bb3/peripheralDrivers/src/subdir.mk
-include lib/efm8bb3/bsp/efm8_memory_lcd/src/source/subdir.mk
-include lib/bsp/efm8_memory_lcd/src/subdir.mk
-include subdir.mk
-include objects.mk

-include ../makefile.defs

# Add inputs and outputs from these tool invocations to the build variables 

# All Target
all: EFM8BB3_PowerModes_2.omf

# Tool invocations
EFM8BB3_PowerModes_2.omf: echo_path $(OBJS)
	@echo 'Building target: $@'
	@echo 'Invoking: Keil 8051 Linker'
	wine "/home/daniel/Downloads/SimplicityStudio_v4/developer/toolchains/keil_8051/9.53/BIN/LX51" "@EFM8BB3_PowerModes_2.lnp" || $(RC)
	@echo 'Finished building target: $@'

# Change from all upper case to the expected case
	@-mv "EFM8BB3_POWERMODES_2.OMF.CRBUILD" "$@"

# Generate hex file: EFM8BB3_PowerModes_2.hex
	@wine "/home/daniel/Downloads/SimplicityStudio_v4/developer/toolchains/keil_8051/9.53/BIN/Ohx51" "EFM8BB3_PowerModes_2.omf" "HEXFILE (EFM8BB3_PowerModes_2.hex)" "H386" 2>&1 >/dev/null

# Other Targets
clean:
	-$(RM) $(EXECUTABLES)$(OBJS) EFM8BB3_PowerModes_2.omf
	-@echo ' '

.PHONY: all clean dependents
.SECONDARY:

-include ../makefile.targets
# echo the path
echo_path:
	@echo PATH=$$PATH
	@echo ' '

