_PLUGIN  = 1
ARCH     = arm
XARCH    = $(ARCH)
CPU     ?= cortex-a9
MEM     ?= 128M
#UBOOT   ?= v2015.07
LINUX   ?= v4.0
BUILDROOT?= 2016.05
KRN_ADDR?= 0x60003000
RDK_ADDR?= 0x60900000
DTB_ADDR?= 0x60500000
UCONFIG ?= vexpress_common.h
NETDEV  ?= lan9118
SERIAL  ?= ttyAMA0
#ROOTDEV ?= /dev/mmcblk0
#ROOTDEV ?= /dev/null
ROOTDEV ?= /dev/ram0
FSTYPE  ?= ext2
ORIIMG  ?= arch/$(ARCH)/boot/zImage
UORIIMG ?= arch/$(ARCH)/boot/uImage
ORIDTB  ?= arch/$(ARCH)/boot/dts/vexpress-v2p-ca9.dtb
CCPRE   ?= arm-linux-gnueabi-
#BIMAGE ?= $(PREBUILT_UBOOT)/$(XARCH)/$(BOARD)/$(UBOOT)/u-boot
KIMAGE  ?= $(TOP_DIR)/boards/$(BOARD)/kernel/$(XARCH)/$(LINUX)/zImage
DTB     ?= $(TOP_DIR)/boards/$(BOARD)/kernel/$(XARCH)/$(LINUX)/vexpress-v2p-ca9.dtb
ROOTFS  ?= $(PREBUILT_ROOT)/$(XARCH)/$(CPU)/rootfs.cpio.gz
#UROOTFS ?= $(PREBUILT_ROOT)/$(XARCH)/$(CPU)/rootfs.cpio.uboot
HROOTFS ?= $(PREBUILT_ROOT)/$(XARCH)/$(CPU)/rootfs.$(FSTYPE)
