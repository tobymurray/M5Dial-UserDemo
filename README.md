Diff from original repo:
- Build with ESP-IDF v5.4.1
- Remove vendored LovyanGFX, add as submodule and update to 1.2.0
- Remove vendored lvgl, add as submodule and update to 8.4.0
- Comment out `fillSmoothRoundRectInDifference` block

# M5Dial-UserDemo

M5Dial user demo for hardware evaluation.

### Tool Chains

[ESP-IDF v5.4.1](https://docs.espressif.com/projects/esp-idf/en/v5.4.1/esp32s3/index.html)

### Build

```bash
git clone https://github.com/m5stack/M5Dial-UserDemo.git
cd M5Dial-UserDemo
idf.py build
```
