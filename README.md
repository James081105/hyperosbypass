# 澎湃 OS BL 锁绕过工具

## 项目简介
本项目基于 Python 开发，旨在实现对澎湃 OS 设备的 Bootloader 锁（BL 锁）的绕过。借助该工具，用户能够尝试解锁受 BL 锁限制的澎湃 OS 设备。

## 注意事项
在使用本工具之前，请务必确认您设备的 Android 版本。仅 Android 版本早于 2024 - 07 的设备方可使用本工具进行 BL 锁绕过操作。您可以通过以下步骤查看设备的 Android 版本：
打开设备的“设置”应用 -> 点击“我的设备” -> 选择“全部参数与信息”，在其中查看“Android 版本”。

## 使用方法
### 步骤 1：开启开发者模式
- 打开设备的“设置”应用。
- 点击“我的设备”。
- 快速连续点击“OS 版本”五次，此时会弹出提示，表明已进入开发者模式。

### 步骤 2：开启 USB 相关调试功能
- 在“设置”中找到并打开“开发者模式”。
- 开启“USB 调试”、“USB 安装”以及“USB 调试（安全设置）”。

### 步骤 3：运行解锁工具
- 将设备通过 USB 数据线连接到电脑。
- 在电脑上运行 `hyperosbypass.exe` 文件。
- 根据工具的提示，输入需要解锁的选项，然后等待解锁过程完成。

### 步骤 4：处理解锁失败情况
若解锁过程失败，您可以尝试安装旧版本的“设置”应用，然后重新进行解锁操作。不同机型和版本的旧版“设置”应用可从以下链接下载：
1. [百度网盘链接](https://pan.baidu.com/s/1VUr6ST4-GQnedwImftcH7g?pwd=4sdp)，提取码：4sdp
2. [迅雷网盘链接](https://pan.xunlei.com/s/VOIA4qQKJrCMR9nPCNvcpSg_A1?pwd=g4cd#)，提取码：g4cd

## 风险提示
- 解锁 Bootloader 可能会使设备失去官方保修资格，请在操作前谨慎考虑。
- 不正确的操作可能会导致设备变砖或丢失数据，请务必备份好您的重要数据。

## 贡献
如果您发现任何问题或有改进建议，欢迎提交 Issue 或 Pull Request。

## 许可证
本项目遵循 [具体许可证名称] 许可证。请查看 `LICENSE` 文件以获取更多信息。

# HyperOS Bootloader Lock Bypass Tool

## Project Introduction
This project is developed based on Python and aims to bypass the Bootloader Lock (BL lock) of HyperOS devices. With this tool, users can attempt to unlock HyperOS devices restricted by the BL lock.

## Notes
Before using this tool, please make sure to confirm the Android version of your device. Only devices with an Android version earlier than July 2024 can use this tool to bypass the BL lock. You can check the Android version of your device through the following steps:
Open the "Settings" app on your device -> Tap "My Device" -> Select "All Parameters and Information", and check the "Android Version" there.

## Usage Instructions
### Step 1: Enable Developer Mode
- Open the "Settings" app on your device.
- Tap "My Device".
- Tap the "OS Version" five times in quick succession. A prompt will appear indicating that you have entered Developer Mode.

### Step 2: Enable USB Debugging Features
- Find and enable "Developer Mode" in the "Settings".
- Enable "USB Debugging", "USB Installation", and "USB Debugging (Security Settings)".

### Step 3: Run the Unlocking Tool
- Connect your device to the computer via a USB cable.
- Run the `hyperosbypass.exe` file on your computer.
- Follow the prompts of the tool, enter the option you need to unlock, and then wait for the unlocking process to complete.

### Step 4: Handle Unsuccessful Unlocking
If the unlocking process fails, you can try to install the old version of the "Settings" app and then perform the unlocking operation again. You can download the old versions of the "Settings" app for different models and versions from the following links:
1. [Baidu Netdisk Link](https://pan.baidu.com/s/1VUr6ST4-GQnedwImftcH7g?pwd=4sdp), Extraction Code: 4sdp
2. [Thunder Netdisk Link](https://pan.xunlei.com/s/VOIA4qQKJrCMR9nPCNvcpSg_A1?pwd=g4cd#), Extraction Code: g4cd

## Risk Warnings
- Unlocking the Bootloader may void the official warranty of your device. Please consider carefully before proceeding.
- Incorrect operations may cause your device to become unbootable or result in data loss. Please make sure to back up your important data.

## Contribution
If you find any issues or have suggestions for improvement, please feel free to submit an Issue or a Pull Request.

## License
This project is licensed under the [Specific License Name] license. Please refer to the `LICENSE` file for more information. 
