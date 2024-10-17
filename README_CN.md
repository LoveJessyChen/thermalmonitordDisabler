# 温控禁用工具
**由于在 bilibili、QQ 等平台上，部分人为了获得早已明确写出解决方案的关于该工具的问题的帮助，干扰了我的正常生活，对我未按照其要求修改工具或增添功能进行无理的人身攻击，该项目永久停更。**

用于禁用 thermalmonitord，以防止 iOS 设备过热时的降频和屏幕变暗。你也可以使用它来禁用系统更新和 UsageTrackingAgent（系统日志）。

适用于 iOS 18.1 beta 4 以下的所有版本，但禁用温控可能在 A15 及以上设备上无法完全生效。

<img src="/images/overview_cn.png" style="height:300px;">

## 运行程序
根据您的系统，从 [Releases](https://github.com/rponeawa/thermalmonitordDisabler/releases/latest) 下载最新版，并运行 thermalmonitordDisabler 或 thermalmonitordDisabler.exe。

执行代码的步骤如下：

需求：
- pymobiledevice3
- Python 3.8 或更高版本

注意：强烈建议使用虚拟环境：
```
python3 -m venv .env # 只需执行一次
# macOS/Linux:  source .env/bin/activate
# Windows:      ".env/Scripts/activate.bat"
pip3 install -r requirements.txt # 只需执行一次
python3 gui_app.py
```
注意：根据您的路径，可能是 `python`/`pip` 或 `python3`/`pip3`。

对于命令行版，运行 `python3 cli_app.py`

**要使用此工具，必须关闭“查找我的 iPhone”。**

**禁用 thermalmonitord 后，iPhone 电池将在设置中显示为未知部件/未验证。**

## 致谢
- 修改自 [leminlimez](https://github.com/leminlimez)/[Nugget](https://github.com/leminlimez/Nugget)
- 感谢 [JJTech](https://github.com/JJTech0130) 提供的 Sparserestore/[TrollRestore](https://github.com/JJTech0130/TrollRestore)
- 感谢 [pymobiledevice3](https://github.com/doronz88/pymobiledevice3)
