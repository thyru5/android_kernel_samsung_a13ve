ccflags-y += -I$(src)			# needed for trace events

obj-y					+= ion/

obj-$(CONFIG_ASHMEM)			+= ashmem.o
obj-$(CONFIG_DEBUG_KINFO)		+= debug_kinfo.o
obj-$(CONFIG_ANDROID_VSOC)		+= vsoc.o
obj-$(CONFIG_ANDROID_INTF_ALARM_DEV)	+= alarm-dev.o

obj-$(CONFIG_SAMSUNG_LMKD_DEBUG)		+= lmkd_debug.o