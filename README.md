# TWINS — Sons Of The Forest 服务器生态

项目主页：<https://Twins-SOTF.github.io/>

一套面向 SotF 专用服务器的双端数据链路方案：

- **C 端探针**（[SotfClientProbe](https://github.com/Twins-SOTF/SotfClientProbe)）：客户端采集插件（BepInEx / C# / .NET6），提供 HUD 统计、KD 排行榜上报、屏幕接管、禁止物资清单检测
- **S 端 DS 插件**：服务器端校验与规则执行
- **Center 中台**：中心服务（端口 11008）统一收口双端上报，对接数据库完成存储与排行计算
- **SteamID 交叉验证**：以 Steam 身份为锚点，客户端与服务端双重核对，防止数据伪造

## 相关仓库

- [SotfClientProbe](https://github.com/Twins-SOTF/SotfClientProbe) — C 端数据采集插件源码
