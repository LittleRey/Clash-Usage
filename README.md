# Clash-Usage
#### Clash 下载

**ClashX 和 ClashX Pro**

工具开发者 [@yicheng](https://github.com/yichengchen/clashX) 表示后续会考虑支持自定义 GeoIP 库，目前需要使用手动替换的方式来使用项目中提供的数据库。

配置方式：点击状态栏的 ClashX 图标，选择「配置」> 「选择打开本地配置文件夹」，用本项目提供的 `Country.mmdb` 数据库替换弹出窗口中的同名文件 > 重新启动工具

⚠️ 请勿使用 「配置」> 「实验性功能」> 「更新 IP 数据库」这一功能，否则 IP 数据库会被还原回 MaxMind 的数据库。

**Clash for Windows**

工具开发者 [Fndroid](https://github.com/Fndroid/clash_for_windows_pkg) 暂未在工具提供内提供可以自定义 GeoIP 数据库的方式，目前需要使用手动替换的方式来使用项目中提供的数据库。

配置方式：打开软件控制面板 > General 选项卡 > 点击 Home Directory 区域下方的 「Open Directory」 > 用本项目提供的 `Country.mmdb` 数据库替换弹出窗口中的同名文件 > 重新启动工具

**OpenClash for OpenWRT**

工具开发者 [@vernesong](https://github.com/vernesong/OpenClash) 已经积极跟进，在 `v0.40.17` 版本中已经添加了自定义 GEOIP 和自定义大陆 IP 段的功能，并将本项目提供的数据库作为选项提供，非常友好。

配置方式：打开 OpenClash 配置页面 > 全局设置 > GEOIP 数据库订阅 >  下拉菜单中选择本项目 > 保存并应用。另外可以根据个人偏好，设定数据库更新时间间隔（本项目每 3 天更新一次）。

**Clash for Android**

工具开发者 [@Kr328](https://github.com/Kr328/ClashForAndroid) 明确表示不会支持自定义 GeoIP 数据库功能，态度非常坚决。给出的原因是「没有有效的校验手段」和「应用不针对中国大陆用户设计」，具体原因可以查看:

* [Kr328/ClashForAndroid#749](https://github.com/Kr328/ClashForAndroid/issues/749) 
* [Kr328/ClashForAndroid#411 (comment)](https://github.com/Kr328/ClashForAndroid/issues/411#issuecomment-640780469)
