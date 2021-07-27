ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)

dtbo-$(CONFIG_ARCH_MSM8953) += msm8953-mtp-overlay-hw-R00-sku-00.dtbo \
			       msm8953-mtp-overlay-hw-R01-sku-00.dtbo \
			       msm8953-mtp-overlay-hw-R02-sku-00.dtbo

msm8953-mtp-overlay-hw-R00-sku-00.dtbo-base := sdm450-pmi632-hw-R00-sku-00.dtb
msm8953-mtp-overlay-hw-R01-sku-00.dtbo-base := sdm450-pmi632-hw-R01-sku-00.dtb
msm8953-mtp-overlay-hw-R02-sku-00.dtbo-base := sdm450-pmi632-hw-R02-sku-00.dtb

else
dtb-$(CONFIG_ARCH_MSM8953) += msm8953-cdp.dtb \
	msm8953-mtp.dtb \
	msm8953-ext-codec-mtp.dtb \
	msm8953-qrd-sku3.dtb \
	msm8953-rcm.dtb \
	apq8053-rcm.dtb \
	msm8953-ext-codec-rcm.dtb \
	apq8053-cdp.dtb \
	apq8053-ipc.dtb \
	msm8953-ipc.dtb \
	apq8053-mtp.dtb \
	apq8053-ext-audio-mtp.dtb \
	apq8053-ext-codec-rcm.dtb \
	msm8953-cdp-1200p.dtb \
	msm8953-iot-mtp.dtb \
	apq8053-iot-mtp.dtb \
	apq8053-lite-dragon-v1.0.dtb \
	apq8053-lite-dragon-v2.0.dtb \
	apq8053-lite-dragon-v2.1.dtb \
	apq8053-lite-dragon-v2.2.dtb \
	apq8053-lite-dragon-v2.2.1.dtb \
	apq8053-lite-dragon-v2.3.dtb \
	apq8053-lite-dragon-v2.4.dtb \
	apq8053-lat-concam-dev.dtb \
	apq8053-lat-concam-proto.dtb \
	msm8953-pmi8940-cdp.dtb \
	msm8953-pmi8940-mtp.dtb \
	msm8953-pmi8937-cdp.dtb \
	msm8953-pmi8937-mtp.dtb \
	msm8953-pmi8940-ext-codec-mtp.dtb \
	msm8953-pmi8937-ext-codec-mtp.dtb \
	msm8953-pmi632-cdp-s2.dtb \
	msm8953-no-pmi.dtb


dtb-$(CONFIG_ARCH_SDM450) += sdm450-rcm.dtb \
	sdm450-cdp.dtb \
	sdm450-mtp.dtb \
	sda450-cdp.dtb \
	sda450-mtp.dtb \
	sdm450-qrd.dtb \
	sdm450-pmi8940-mtp.dtb \
	sdm450-pmi8937-mtp.dtb \
	sdm450-iot-mtp.dtb \
	sdm450-qrd-sku4.dtb \
	sdm450-pmi632-cdp-s2.dtb \
	sdm450-pmi632-mtp-s3.dtb \
	sda450-pmi632-cdp-s2.dtb \
	sda450-pmi632-mtp-s3.dtb \
	sdm450-no-pmi.dtb	



endif

always		:= $(dtb-y)
subdir-y	:= $(dts-dirs)
clean-files	:= *.dtb
