# SPDX-License-Identifier: GPL-2.0
dtbo-$(CONFIG_ARCH_ROCKCHIP) += \
	radxa-cm3-io-sata1.dtbo \
	radxa-cm3-io-sata2.dtbo \
	cm3-sodimm-io-sata.dtbo \
	radxa-5inch-touchscreen-on-cm3-sodimm-io.dtbo \
	radxa-5inch-touchscreen-on-rock-3a.dtbo \
	radxa-5inch-touchscreen-on-rock-3b.dtbo \
	radxa-cm3-io-dual-cameras-gc2053.dtbo \
	radxa-cm3-io-hd101boe9365-display.dtbo \
	radxa-cm3-io-i2c0-hym8563.dtbo \
	radxa-cm3-io-radxa-10p1inch-display.dtbo \
	radxa-cm3-io-sharp-lq133t1jw01-without-hdmi.dtbo \
	radxa-cm3-io-headphone.dtbo \
	radxa-cm3-io-pcie2x1.dtbo \
	radxa-cm3-sodimm-io-raspberrypi-7inch-touchscreen.dtbo \
	radxa-cm3-raspcm4io-pcie2x1.dtbo \
	rk3568-can1-m0.dtbo \
	rk3568-can1-m1.dtbo \
	rk3568-disable-gmac1.dtbo \
	rk3568-disable-npu.dtbo \
	rk3568-fiq-debugger-uart0.dtbo \
	rk3568-fiq-debugger-uart2m0.dtbo \
	rk3568-fiq-debugger-uart3m0.dtbo \
	rk3568-fiq-debugger-uart5m1.dtbo \
	rk3568-fiq-debugger-uart7m1.dtbo \
	rk3568-fiq-debugger-uart8m1.dtbo \
	rk3568-fiq-debugger-uart9m1.dtbo \
	rk3568-i2c2-m0.dtbo \
	rk3568-i2c3-m0.dtbo \
	rk3568-pwm12-m0.dtbo \
	rk3568-pwm12-m1.dtbo \
	rk3568-pwm13-m0.dtbo \
	rk3568-pwm13-m1.dtbo \
	rk3568-pwm14-m0.dtbo \
	rk3568-pwm14-m1.dtbo \
	rk3568-pwm15-m0.dtbo \
	rk3568-pwm15-m1.dtbo \
	rk3568-pwm0-m0.dtbo \
	rk3568-pwm0-m1.dtbo \
	rk3568-pwm1-m0.dtbo \
	rk3568-pwm1-m1.dtbo \
	rk3568-pwm2-m0.dtbo \
	rk3568-pwm2-m1.dtbo \
	rk3568-pwm8-m0-fan.dtbo \
	rk3568-pwm9-m0.dtbo \
	rock-3a-sata0.dtbo \
	rock-3a-sata1.dtbo \
	rock-3a-sata2.dtbo \
	rk3568-rock-3b-em05-modem.dtbo \
	rk3568-rock-3b-sata2.dtbo \
	rk3568-spi3-m0-cs0-spidev.dtbo \
	rk3568-spi3-m1-cs0-spidev.dtbo \
	rk3568-uart0.dtbo \
	rk3568-uart2-m0.dtbo \
	rk3568-uart3-m0.dtbo \
	rk3568-uart3-m1.dtbo \
	rk3568-uart5-m1.dtbo \
	rk3568-uart7-m1.dtbo \
	rk3568-uart8-m1.dtbo \
	rk3568-uart9-m1.dtbo \
	rk3568-w1-gpio.dtbo \
	rock-3a-raspberrypi-7inch-touchscreen.dtbo \
	rock-3ab-rpi-camera-v1p3-ov5647.dtbo \
	rock-3ab-rpi-camera-v2-imx219.dtbo \
	rock-3b-disable-hdmicec.dtbo \
	rock-3b-hdmi-and-sharp-lq133t1jw01-edp-lcd.dtbo \
	rock-3b-radxa-10p1inch-display.dtbo \
	rock-3c-ov5647.dtbo \
	rock-3c-radxa-5inch-touchscreen.dtbo \
	rock-3c-usb-otg.dtbo \
	rpi-ov5647-on-cm3-sodimm-io-csi0.dtbo \
	rpi-ov5647-on-cm3-sodimm-io-csi1.dtbo \
	audioinjector-isolated-soundcard.dtbo \
	rock-3c-raspberrypi-7inch-touchscreen.dtbo \
	rk3568-spi1-m1-cs0-spidev.dtbo \
	rk3568-spi0-m1-cs0-spidev.dtbo \
	radxa-cm3i-gmac1.dtbo \
	radxa-cm3-io-dual-cameras-gc2053-gc2093.dtbo

scr-$(CONFIG_ARCH_ROCKCHIP) += \
	rockchip-fixup.scr

dtbotxt-$(CONFIG_ARCH_ROCKCHIP) += \
	README.rockchip-overlays

targets += $(dtbo-y) $(scr-y) $(dtbotxt-y)

always			:= $(dtbo-y) $(scr-y) $(dtbotxt-y)
clean-files		:= *.dtbo *.scr

