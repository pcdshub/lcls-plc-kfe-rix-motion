IOC_TOP = /reg/g/pcds/epics/ioc/common/ads-ioc/R0.2.3
IOC_INSTANCE_PATH := $(shell pwd)

# Set PRODUCTION_IOC to 1 to move from a testing to a production IOC:
PRODUCTION_IOC := 1

PROJECT_NAME = plc-fee-rix-motion
PROJECT_PATH := ../../plc-fee-rix-motion/plc-fee-rix-motion.tsproj
PLC = fee_rix_motion

PYTMC_OPTS :=
PREFIX = PLC:FEE:RIX:MOTION

include $(IOC_TOP)/iocBoot/templates/Makefile.base
