# thermalmonitordDisabler
[中文](https://github.com/rponeawa/thermalmonitordDisabler/blob/main/README_CN.md)

**由于在 bilibili、QQ 等平台上，部分人为了获得早已明确写出解决方案的关于该工具的问题的帮助，干扰了我的正常生活，对我未按照其要求修改工具或增添功能进行无理的人身攻击，该项目永久停更。**

**Due to some individuals on platforms like Bilibili and QQ interfering with my normal life in order to gain assistance with questions about this tool that already have clearly stated solutions, and due to their unreasonable personal attacks on me for not modifying or adding features to this tool as they requested, I have decided to permanently stop updating the project.**

A tool used to disable thermalmonitord to prevent throttling and screen dimming when iOS devices overheat. You can also disable OTA and UsageTrackingAgent with this.

Works on all versions below iOS 18.1 beta 4, thermal throttling may be unable to be completely disabled on A15+ devices.

<img src="/images/overview.png" style="height:300px;">

## Running the Program
Download the latest version from [releases](https://github.com/rponeawa/thermalmonitordDisabler/releases/latest) based on your system, and run thermalmonitordDisabler or thermalmonitordDisabler.exe.

To execute the code, follow these steps:

Requirements:
- pymobiledevice3
- Python 3.8 or newer

Note: It is highly recommended to use a virtual environment:
```
python3 -m venv .env # only needed once
# macOS/Linux:  source .env/bin/activate
# Windows:      ".env/Scripts/activate.bat"
pip3 install -r requirements.txt # only needed once
python3 gui_app.py
```
Note: It may be either `python`/`pip` or `python3`/`pip3` depending on your path.

Run `python3 cli_app.py` for CLI version.

**Find My should be turned off to use this tool.**

**iPhone battery will be displayed as an unknown part/unverified in Settings after disabling thermalmonitord.**

## Credits
- Modified from [leminlimez](https://github.com/leminlimez)/[Nugget](https://github.com/leminlimez/Nugget)
- [JJTech](https://github.com/JJTech0130) for Sparserestore/[TrollRestore](https://github.com/JJTech0130/TrollRestore)
- [pymobiledevice3](https://github.com/doronz88/pymobiledevice3)
