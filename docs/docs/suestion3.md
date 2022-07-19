### 游戏代码31-4302解决方案

国服的游戏目录下应该有的内容：
- YuanShen_Data [游戏数据文件夹]
- YuanShen.exe [游戏应用程序]
- config.ini [游戏配置文件]
- mhypbase.dll [未知]
- mhyprot2.Sys [未知]
- mhyprot3.Sys [未知]
- UnityPlayer.dll [未知]
- pkg_version [游戏检验文件，用于检验指定目录下的MD5值、文件大小，不可删除]

国际服的游戏目录下应该有的内容：
- GenshinImpact_Data [游戏数据文件夹]
- GenshinImpact.exe [游戏应用程序]
- config.ini [游戏配置文件]
- mhypbase.dll [未知]
- mhyprot2.Sys [未知]
- mhyprot3.Sys [未知]
- UnityPlayer.dll [未知]
- pkg_version [游戏检验文件，用于检验指定目录下的MD5值、文件大小，不可删除]

国服与国际服可忽略的文件夹或文件：
- ScreenShot [截图存放文件夹]
- Audio_语言名称_pkg_version [音频检验文件，用于检验指定目录下的MD5值、文件大小，可删除]
- *.bak [备份文件，可删除]

请检查游戏本体目录下是否拥有多余的文件夹或文件、应用程序等（注意，国服与国际服的文件夹、文件、应用程序应该不一致且不可以同时存在。除可忽略的文件外）

如果依旧出现31-4302，请检查pkg_version文件内是否包含正确的游戏路径，例如国服的pkg_version文件内出现了GenshinImpact_Data字样而非YuanShen_Data

如果依旧出现31-4302，请检查所有文件是否是最新的
