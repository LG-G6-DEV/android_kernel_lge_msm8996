ccflags-y += -Iinclude/drm -I$(src)/../ -I$(src)/../dsi-staging/
ccflags-y += -Idrivers/gpu/drm/msm/sde

lge_display_common-objs := lge_dsi_panel.o
lge_display_common-objs += lge_panel_reg.o
lge_display_common-objs += lge_ddic_ops.o
lge_display_common-objs += lge_ddic_ops_sw43408.o
lge_display_common-objs += lge_ddic_ops_sw43408a.o
lge_display_common-objs += notifier/lge_panel_notifier.o
obj-$(CONFIG_LGE_DISPLAY_COMMON) += lge_display_common.o
