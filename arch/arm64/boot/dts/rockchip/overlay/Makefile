# SPDX-License-Identifier: GPL-2.0
dtbo-$(CONFIG_ARCH_ROCKCHIP) += \
	rk3568-opp-2.2ghz.dtbo \
	rk3568-h6xk-disable-pcie2x1.dtbo \
	rk3568-h69k-disable-sata.dtbo \
	rk3568-h69k-disable-usb3.dtbo \
	rk3568-disable-gmac0.dtbo \
	rk3568-disable-gmac1.dtbo \
	rk3588-disable-gmac0.dtbo \
	rk3588-disable-gmac1.dtbo \
	rk3588-full-cpufreq.dtbo \
	rk3588-i2c0-m1.dtbo \
	rk3588-i2c1-m0.dtbo \
	rk3588-i2c2-m4.dtbo \
	rk3588-i2c3-m1.dtbo \
	rk3588-i2c4-m3.dtbo \
	rk3588-i2c6-m3.dtbo \
	rk3588-i2c7-m3.dtbo \
	rk3588-i2c8-m2.dtbo \
	rk3588-i2c8-m4.dtbo \
	rk3588-pwm0-m2.dtbo \
	rk3588-pwm11-m1.dtbo \
	rk3588-pwm12-m0.dtbo \
	rk3588-pwm13-m0.dtbo \
	rk3588-pwm13-m2.dtbo \
	rk3588-pwm14-m0.dtbo \
	rk3588-pwm14-m1.dtbo \
	rk3588-pwm14-m2.dtbo \
	rk3588-pwm15-m0.dtbo \
	rk3588-pwm15-m1.dtbo \
	rk3588-pwm15-m3.dtbo \
	rk3588-pwm1-m2.dtbo \
	rk3588-pwm2-m1.dtbo \
	rk3588-pwm3-m1.dtbo \
	rk3588-pwm3-m3.dtbo \
	rk3588-pwm5-m2.dtbo \
	rk3588-pwm6-m2.dtbo \
	rk3588-pwm7-m3.dtbo \
	rk3588-pwm8-m0.dtbo \
	rk3588-sdio-uhs.dtbo \
	rk3588-sdhci-hs400.dtbo \
	rk3588-spi0-m2-cs0-spidev.dtbo \
	rk3588-spi0-m2-cs1-spidev.dtbo \
	rk3588-spi1-m1-cs0-spidev.dtbo \
	rk3588-spi1-m1-cs1-spidev.dtbo \
	rk3588-spi4-m2-cs0-spidev.dtbo \
	rk3588-uart2-m0.dtbo \
	rk3588-uart2-m2.dtbo \
	rk3588-uart3-m1.dtbo \
	rk3588-uart4-m2.dtbo \
	rk3588-uart6-m1.dtbo \
	rk3588-uart7-m1-ctsn-rtsn.dtbo \
	rk3588-uart7-m1.dtbo \
	rk3588-uart7-m2.dtbo \
	rk3588-uart8-m0.dtbo \
	rockchip-i2c7.dtbo \
	rockchip-i2c8.dtbo \
	rockchip-pcie-gen2.dtbo \
	rockchip-rk3328-opp-1.4ghz.dtbo \
	rockchip-rk3328-opp-1.5ghz.dtbo \
	rockchip-rk3399-opp-2ghz.dtbo \
	rockchip-spi-jedec-nor.dtbo \
	rockchip-spi-spidev.dtbo \
	rockchip-uart4.dtbo \
	rockchip-dwc3-0-host.dtbo \
	rockchip-w1-gpio.dtbo \
	rockchip-rk3318-box-led-conf1.dtbo \
	rockchip-rk3318-box-led-conf2.dtbo \
	rockchip-rk3318-box-led-conf3.dtbo \
	rockchip-rk3318-box-led-conf4.dtbo \
	rockchip-rk3318-box-emmc-ddr.dtbo \
	rockchip-rk3318-box-wlan-ap6334.dtbo \
	rockchip-rk3318-box-wlan-ext.dtbo \
	rockchip-rk3318-box-wlan-ap6330.dtbo \
	rockchip-rk3318-box-cpu-hs.dtbo \
	rockchip-rk3318-box-emmc-hs200.dtbo \
        rk3308-bs.dtbo rk3308-bs@1.3ghz.dtbo \
        rk3308-sdio@10mhz.dtbo rk3308-sdio@4mhz.dtbo \
        rk3308-emmc.dtbo
        

scr-$(CONFIG_ARCH_ROCKCHIP) += \
       rockchip-fixup.scr

dtbotxt-$(CONFIG_ARCH_ROCKCHIP) += \
       README.rockchip-overlays

targets += $(dtbo-y) $(scr-y) $(dtbotxt-y)

always         := $(dtbo-y) $(scr-y) $(dtbotxt-y)
clean-files    := *.dtbo *.scr

