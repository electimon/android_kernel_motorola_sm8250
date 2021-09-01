ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
        dtbo-y += \
                nio/nigga.dtbo
endif

always		:= $(dtb-y) $(dtbo-y)
subdir-y	:= $(dts-dirs)
clean-files    := *.dtb *.dtbo
