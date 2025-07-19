# SPDX-License-Identifier: GPL-2.0-only
# Copyright (C) 2018-2020 Oplus. All rights reserved.

GCOV_PROFILE := y
LINUXINCLUDE += -I$(srctree)/

ccflags-y += -DMALI_UNIT_TEST=0
ccflags-y += -DMALI_GPU_LKG=1

obj-$(CONFIG_OPLUS_FEATURE_GEAS) += oplus_bsp_geas.o
oplus_bsp_geas-y := \
	geas.o \
	geas_sysctrl.o
