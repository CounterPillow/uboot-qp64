#
# (C) Copyright 2006
# Wolfgang Denk, DENX Software Engineering, wd@denx.de.
#
# (C) Copyright 2003
# Pavel Bartusek, Sysgo Real-Time Solutions AG, pba@sysgo.de
#
#
# SPDX-License-Identifier:	GPL-2.0+
#

obj-y := ext4fs.o ext4_common.o dev.o
obj-$(CONFIG_EXT4_WRITE) += ext4_write.o ext4_journal.o crc16.o
obj-$(CONFIG_CMD_EXT4_SPARSE_WRITE) += ext4_sparse.o
