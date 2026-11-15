# SPDX-License-Identifier: GPL-2.0
ccflags-y += -I$(src)			# needed for trace events

ifdef CONFIG_ASHMEM_C
obj-$(CONFIG_ASHMEM)		+= ashmem_c.o ashmem_exports.o
else
obj-$(CONFIG_ASHMEM)		+= ashmem.o ashmem_exports.o
endif
