#
# Makefile for the QCOM spcific video device drivers
# based on V4L2.
#

obj-$(CONFIG_MSM_VIDC_V4L2)     += vidc/
obj-y += broadcast/
obj-$(CONFIG_DVB_MPQ) += dvb/

ifeq ($(CONFIG_SEC_J5_PROJECT),y)
obj-$(CONFIG_MSMB_CAMERA) += camera_v2_j5/
else ifeq ($(CONFIG_SEC_J5N_PROJECT),y)
obj-$(CONFIG_MSMB_CAMERA) += camera_v2_j5/
else ifeq ($(CONFIG_SEC_J5X_PROJECT),y)
obj-$(CONFIG_MSMB_CAMERA) += camera_v2_j5/
else ifeq ($(CONFIG_SEC_GTEL_PROJECT),y)
obj-$(CONFIG_MSMB_CAMERA) += camera_v2_gte/
else ifeq ($(CONFIG_SEC_GTES_PROJECT),y)
obj-$(CONFIG_MSMB_CAMERA) += camera_v2_gte/
else
obj-$(CONFIG_MSMB_CAMERA) += camera_v2/
endif

obj-$(CONFIG_MSM_VPU) += vpu/
