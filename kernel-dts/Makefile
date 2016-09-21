old-dtb := $(dtb-y)
dtb-y :=
makefile-path := platform/t210/fpga/kernel-dts

dtb-$(CONFIG_ARCH_TEGRA_21x_SOC) += tegra210-grenada.dtb

ifneq ($(dtb-y),)
dtb-y := $(addprefix $(makefile-path)/,$(dtb-y))
endif

dtb-y += $(old-dtb)
