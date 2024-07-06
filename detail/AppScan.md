## AppScan <https://github.com/TongchengOpenSource/AppScan>
<!--auto_detail_badge_begin_0b490ffb61b26b45de3ea5d7dd8a582e-->
![Language](https://img.shields.io/badge/Language-Python-blue)
![Author](https://img.shields.io/badge/Author-TongchengOpenSource-orange)
![GitHub stars](https://img.shields.io/github/stars/TongchengOpenSource/AppScan.svg?style=flat&logo=github)
![Version](https://img.shields.io/badge/Version-V2.1.5-red)
![Time](https://img.shields.io/badge/Join-20231025-green)
<!--auto_detail_badge_end_fef74f2d7ea73fcc43ff78e05b1e7451-->

<h1 align="center">
  <a href="https://github.com/tongcheng-security-team/Appscan"><img src="https://github.com/TongchengOpenSource/AppScan/raw/main/doc/image/AppScan.png" width="30%"  alt="AppScan"></a>
</h1>

---

<h4 align="center">安全隐私卫士（AppScan）一款免费的企业级自动化隐私检测工具。</h4>

## 背景
&emsp;&emsp;随着移动互联网的高速发展, 各公司对保护用户的个人隐私安
全意识也在愈发重视. 但是在实际业务场景中受限于代码开发
质量或因产品设计不谨慎等原因, APP 难免会引入一些违规收集
的合规问题, 因此各公司也在加大人力进行合规风险检测, 不过
随着业务不断发展、功能的频繁迭代更新, 导致人工检测成本
突增并且很多功能无法检测覆盖, 基于以上背景, 我们开发了
AppScan 这款隐私合规检测工具, 它是一款基于动态分析, 可以
精准定位 APP 的违规风险点的自动化隐私检测工具, 能够大大
提高了合规检测的效率, 帮助使用者便捷、高效、全面的完成
合规检测, 保障业务合规运行.

&emsp;&emsp;AppScan作为一款免费工具，可以帮助大家便捷、高效、全面的完成合规检测，但是由于AppScan还是一个刚孵化的产品，在自动化等方面还没有很完善，我们希望可以吸取大家在使用过程中发现的问题以及优化的建议，帮助AppScan一起成长。

## AppScan优点
+ 全面性: &ensp;从信息收集、权限申请及数据传输等多个维度，实现对APP个人信息合规的全面检测。
+ 规范性: &ensp;全面覆盖《App违法违规收集使用个人信息行为认定方法》、国家标准GB/T35273《信息安全技术 个人信息安全规范》、《中华人民共和国网络安全法》等主流安全检测标准。
+ 高效性: &ensp;可帮助APP开发公司及开发者快速对APP进行日常合规检测，深度挖掘隐私合规风险点、快速处理大批量App，替代人工翻查代码，降低时间与人力成本，显著提升检测效率。
+ 易用性: &ensp;无需环境搭配、开箱即用。

## 安装指南
⬇️[下载地址](https://github.com/tongcheng-security-team/AppScan/releases)

## 支持的环境
- windows: 10及以上
- macOs: 11.0及以上
- android: 8.x及以上
- app: 64位/未加固(有时候引入的第三方sdk也会自带一些反检测功能)

## 模拟器
根据 https://github.com/TongchengOpenSource/AppScan/discussions/29 的投票结果, 我们对MuMu和雷神进行了适配工作
目前模拟器支持未完全上线, 用户可在 release 中下载pre版本进行测试
目前支持的模拟器
- 雷神模拟器9(需要在 设置-其他设置 中开启root权限, 设置ADB调试为'开启本地连接')

目前暂不支持的模拟器
- MuMu模拟器12(未找到ADB开关, 导致ADB无法识别到设备)

## 使用文档
> 使用者查看此文档即可

🏠[使用文档](https://github.com/TongchengOpenSource/AppScan/wiki)

## 开发文档
> 开发者需要额外查看文档
### 架构
👽[架构说明](https://github.com/TongchengOpenSource/AppScan/blob/main/doc/architecture.md)

### 开发文档
👽[开发文档](https://github.com/TongchengOpenSource/AppScan/blob/main/doc/dev.md)

### build指南
👽[build指南](https://github.com/TongchengOpenSource/AppScan/blob/main/doc/build.md)

### api文档
👽[api文档](https://github.com/TongchengOpenSource/AppScan/blob/main/doc/api.md)

## 系统展示
* 连接展示

![!连接展示](https://github.com/TongchengOpenSource/AppScan/raw/main/doc/image/connect.png)

* 结果展示

![!结果展示](https://github.com/TongchengOpenSource/AppScan/raw/main/doc/image/dashboard.png)

<!--auto_detail_active_begin_e1c6fb434b6f0baf6912c7a1934f772b-->
## 项目相关


## 最近更新

#### [v2.1.5] - 2024-05-26

**新功能**  
- 修复AndroidID误报  
- SDK名单新增quickGame匹配  

**优化**  
- 丰富安卓ID触发场景  
- 丰富获取安装app信息触发场景  

**修复**  
- 打标信息缺失

#### [v2.1.2] - 2023-11-25

**新功能**  
- 支持雷电模拟器9  
- 更新frida到16.1.4  
- 更新adb到RC14.0.5  

**优化**  
- 迁移更新源到githubRelease  
- '关于我们'菜单优化  
- 增加错误日志记录堆栈信息  

**修复**  
- 修复打标页面描述错误与错位  
- 修复android13兼容问题  
- 修复打标文案错乱问题  
- 修复app信息缺失导致的panic问题

<!--auto_detail_active_end_f9cf7911015e9913b7e691a7a5878527-->
