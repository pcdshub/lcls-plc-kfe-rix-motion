IOC_TOP = /reg/g/pcds/epics/ioc/common/ads-ioc/R0.2.1
IOC_INSTANCE_PATH := $(shell pwd)

# Set PRODUCTION_IOC to 1 to move from a testing to a production IOC:
PRODUCTION_IOC := 0

PROJECT_NAME = plc-rix-motion
PROJECT_PATH := ../../plc-rix-motion/plc-rix-motion.tsproj
PLC = rix_motion

PYTMC_OPTS :=
PREFIX = PLC:RIX:MOTION

include $(IOC_TOP)/iocBoot/templates/Makefile.base
