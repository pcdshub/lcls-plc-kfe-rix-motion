IOC_TOP = /reg/g/pcds/epics/ioc/common/ads-ioc/R0.3.1
IOC_INSTANCE_PATH := $(shell pwd)

# Set PRODUCTION_IOC to 1 to move from a testing to a production IOC:
PRODUCTION_IOC := 1

PROJECT_NAME = plc-kfe-rix-motion
PROJECT_PATH := ../../plc-kfe-rix-motion/plc-kfe-rix-motion.tsproj
PLC = kfe_rix_motion

PYTMC_OPTS :=
PREFIX = PLC:KFE:RIX:MOTION

include $(IOC_TOP)/iocBoot/templates/Makefile.base
