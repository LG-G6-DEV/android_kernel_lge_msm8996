#
## Makefile for the touchscreen drivers.
#
#
## Each configuration option enables a list of files.

# Touch Core Driver Common Header Code..!!
ccflags-y += -I$(srctree)/drivers/input/touchscreen/lge/

obj-$(CONFIG_LGE_TOUCH_LGSIC_SW49407)           += touch_sw49407.o
obj-$(CONFIG_LGE_TOUCH_LGSIC_SW49407)           += touch_sw49407_watch.o
obj-$(CONFIG_LGE_TOUCH_LGSIC_SW49407)           += touch_sw49407_prd.o
obj-$(CONFIG_LGE_TOUCH_LGSIC_SW49407)           += touch_sw49407_abt.o
#obj-$(CONFIG_LGE_TOUCH_LGSIC_SW49407)           += touch_sw49407_asc.o
obj-$(CONFIG_LGE_TOUCH_LGSIC_SW49407)           += touch_filter.o

obj-$(CONFIG_LGE_TOUCH_LGSIC_SW49407_LUCYE)           += touch_sw49407_lucye.o
obj-$(CONFIG_LGE_TOUCH_LGSIC_SW49407_LUCYE)           += touch_sw49407_watch_lucye.o
#obj-$(CONFIG_LGE_TOUCH_LGSIC_SW49407_LUCYE)           += touch_sw49407_prd_lucye.o
#obj-$(CONFIG_LGE_TOUCH_LGSIC_SW49407_LUCYE)           += touch_sw49407_abt_lucye.o
#obj-$(CONFIG_LGE_TOUCH_LGSIC_SW49407_LUCYE)           += touch_sw49407_asc_lucye.o
obj-$(CONFIG_LGE_TOUCH_LGSIC_SW49407_LUCYE)           += touch_filter.o