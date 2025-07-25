# PlatformIO ESP32 Merge Bin

自动合并bin文件的脚本工具。

## Example

### 快速使用

```ini
[env:esp32-c3-devkitm-1]
...
extra_scripts = post:./merge_bin.py
```

### 自定义输出文件名或者输出目录

```ini
[env:esp32-c3-devkitm-1]
...
extra_scripts = post:./merge_bin.py
merge_bin_output_file = all_0x0.bin
merge_bin_output_dir = output
```

## Donate

If you think this project is helpful to you, you can donate to us to encourage the project to continue to develop and become more complete.

- PayPal

    [![Donate](https://www.paypalobjects.com/en_US/i/btn/btn_donate_SM.gif)](https://paypal.me/lbuque?country.x=C2&locale.x=zh_XC)
