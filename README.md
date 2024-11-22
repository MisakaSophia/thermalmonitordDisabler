# thermalmonitordDisabler
A tool used to disable thermalmonitord to prevent throttling and screen dimming when iOS devices overheat. You can also disable OTA and UsageTrackingAgent with this.

Works on all versions from iOS 15.7 (possibly) to iOS 18.2 Beta 2. Thermal throttling may be unable to be completely disabled on A15+ devices.

<img src="/images/overview.png" style="height:300px;">

## Running the Program
Download the latest version from [releases](https://github.com/rponeawa/thermalmonitordDisabler/releases/latest) based on your system, and run thermalmonitordDisabler.app or thermalmonitordDisabler.exe.

To execute the code, follow these steps:

Requirements:
- pymobiledevice3
- Python 3.8 or newer

Note: It is highly recommended to use a virtual environment:
```
python3 -m venv .env # only needed once
# macOS/Linux:  source .env/bin/activate
# Windows:      ".env/Scripts/activate.bat"
pip3 install -r requirements.txt --ignore-requires-python # only needed once
python3 gui_app.py
```
Note: It may be either `python`/`pip` or `python3`/`pip3` depending on your path.
You need to have `usbmux` service running to run this on Linux.

**Find My should be turned off to use this tool.**

**iPhone battery will be displayed as an unknown part/unverified in Settings after disabling thermalmonitord.**

## Credits
- Modified from [leminlimez](https://github.com/leminlimez)/[Nugget](https://github.com/leminlimez/Nugget)
- [JJTech](https://github.com/JJTech0130) for Sparserestore/[TrollRestore](https://github.com/JJTech0130/TrollRestore)
- [pymobiledevice3](https://github.com/doronz88/pymobiledevice3)
