obj-$(CONFIG_MTK_VIBRATOR) := vibrator_drv.o
obj-y += $(subst ",,$(CONFIG_MTK_PLATFORM))/

obj-$(CONFIG_THUNDERQUAKE_ENGINE_GPL) += thunderquake_engine.o 

ccflags-y += -I$(srctree)/drivers/misc/mediatek/vibrator/$(MTK_PLATFORM)
