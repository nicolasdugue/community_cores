################################################################################
# Automatically-generated file. Do not edit!
################################################################################

-include ../makefile.init

RM := rm -rf

# All of the sources participating in the build are defined here
-include sources.mk
-include src/subdir.mk
-include subdir.mk
-include objects.mk

ifneq ($(MAKECMDGOALS),clean)
ifneq ($(strip $(C++_DEPS)),)
-include $(C++_DEPS)
endif
ifneq ($(strip $(C_DEPS)),)
-include $(C_DEPS)
endif
ifneq ($(strip $(CC_DEPS)),)
-include $(CC_DEPS)
endif
ifneq ($(strip $(CPP_DEPS)),)
-include $(CPP_DEPS)
endif
ifneq ($(strip $(CXX_DEPS)),)
-include $(CXX_DEPS)
endif
ifneq ($(strip $(C_UPPER_DEPS)),)
-include $(C_UPPER_DEPS)
endif
endif

-include ../makefile.defs

# Add inputs and outputs from these tool invocations to the build variables 

# All Target
all: CoeurCommunaute 
#CoeurCommunaute-Old 
#Triangles 

# Tool invocations
CoeurCommunaute: $(OBJS) $(USER_OBJS)
	@echo 'Building target: $@'
	@echo 'Invoking: Cross G++ Linker'
	g++  -o "CoeurCommunaute" $(OBJS) $(USER_OBJS) $(LIBS)
	@echo 'Finished building target: $@'
	@echo ' '

#CoeurCommunaute-Old: $(OBJS_O) $(USER_OBJS)
#	@echo 'Building target: $@'
#	@echo 'Invoking: Cross G++ Linker'
#	g++  -o "CoeurCommunaute-Old" $(OBJS_O) $(USER_OBJS) $(LIBS)
#	@echo 'Finished building target: $@'
#	@echo ' '

#Triangles: $(OBJS_T) $(USER_OBJS)
#	@echo 'Building target: $@'
#	@echo 'Invoking: Cross G++ Linker'
#	g++  -o "Triangles" $(OBJS_T) $(USER_OBJS) $(LIBS)
#	@echo 'Finished building target: $@'
#	@echo ' '

# Other Targets
clean:
	-$(RM) $(C++_DEPS)$(OBJS)$(OBJS_T)$(OBJS_O)$(C_DEPS)$(CC_DEPS)$(CPP_DEPS)$(EXECUTABLES)$(CXX_DEPS)$(C_UPPER_DEPS) CoeurCommunaute-Old  CoeurCommunaute
	-@echo ' '

.PHONY: all clean dependents
.SECONDARY:

-include ../makefile.targets
