# SPDX-License-Identifier: GPL-2.0-only

ccflags-y += -I$(srctree)/techpack/sec-camera/include/uapi
ccflags-y += -I$(srctree)/techpack/sec-camera/drivers/cam_utils
ccflags-y += -I$(srctree)/techpack/sec-camera/drivers/cam_cpas/include
ccflags-y += -I$(srctree)/techpack/sec-camera/drivers/cam_sensor_module/cam_sensor_io
ccflags-y += -I$(srctree)/techpack/sec-camera/drivers/cam_sensor_module/cam_sensor_utils
ccflags-y += -I$(srctree)/techpack/sec-camera/drivers/cam_sensor_module/cam_cci
ccflags-y += -I$(srctree)/techpack/sec-camera/drivers/cam_req_mgr
ccflags-y += -I$(srctree)/techpack/sec-camera/drivers/cam_smmu/
ccflags-y += -I$(srctree)/techpack/sec-camera/drivers/cam_core
ccflags-y += -Idrivers/misc/

obj-$(CONFIG_SPECTRA_CAMERA) += cam_csiphy_soc.o cam_csiphy_dev.o cam_csiphy_core.o
