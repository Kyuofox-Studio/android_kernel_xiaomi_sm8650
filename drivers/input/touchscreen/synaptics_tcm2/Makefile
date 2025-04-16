# SPDX-License-Identifier: GPL-2.0
obj-$(CONFIG_TOUCHSCREEN_SYNA_TCM2) += synaptics_tcm2.o
synaptics_tcm2-m := syna_tcm2.o
synaptics_tcm2-m += syna_tcm2_cdev.o
synaptics_tcm2-m += \
	tcm/synaptics_touchcom_core_v1.o \
	tcm/synaptics_touchcom_core_v2.o \
	tcm/synaptics_touchcom_func_base.o \
	tcm/synaptics_touchcom_func_touch.o
synaptics_tcm2-m += tcm/synaptics_touchcom_func_reflash.o
synaptics_tcm2-m += tcm/synaptics_touchcom_func_romboot.o
synaptics_tcm2-m += syna_tcm2_platform_spi.o
synaptics_tcm2-m += syna_tcm2_sysfs.o
synaptics_tcm2-m += syna_tcm2_testing.o
synaptics_tcm2-m += syna_xiaomi_driver.o
synaptics_tcm2-$(CONFIG_TOUCHSCREEN_TOUCHSCREEN_SYNA_TCM2_TRUSTED_TOUCH) += qts/qts_core.o
