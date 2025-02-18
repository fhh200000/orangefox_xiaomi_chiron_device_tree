# orangefox_xiaomi_chiron_device_tree
Tree for building Orange Fox for Xiaomi MIX 2

## To compile

export ALLOW_MISSING_DEPENDENCIES=true

. build/envsetup.sh && lunch omni_chiron-eng

mka recoveryimage

## Device specifications

Basic   | Spec Sheet
-------:|:-------------------------
CPU     | Quad-core 2.45 GHz Kryo 280 & Quad-core 1.9 GHz Kryo 280
Chipset | Qualcomm MSM8998 Snapdragon 835
GPU     | Adreno 540
Memory  | 6 GB RAM
Shipped Android Version | 7.1.1
Storage | 64/128/256 GB (UFS Flash)
Battery | Non-removable Li-Po 3350 mAh (QC 3.0)
Display | 1080 x 2160 pixels, 5.99 inches (~403 ppi pixel density)
Camera  | 12 MP, f/2.0, phase detection autofocus, dual-LED (dual tone) flash

## Device picture

![Xiaomi Mi MIX 2](https://i8.mifile.cn/a1/pms_1505401464.03824312!560x560.jpg "Xiaomi Mi MIX 2 in black")
