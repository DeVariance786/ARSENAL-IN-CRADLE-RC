# Arsenal in Cradle — 发布包

> 这里只放《Alice in Cradle》枪械模组 **Arsenal in Cradle** 的发布包（zip）。
> **源码不在本仓库**；本仓库只作为公开下载入口。

## 下载

到 [Releases](https://github.com/DeVariance786/ARSENAL-IN-CRADLE-RC/releases) 页面，按你的游戏版本选则压缩包：

| 你的游戏版本 | 用哪个包 |
|---|---|
| 0.29j2 | `ArsenalInCradle-<版本>-aic0.29j2.zip` |
| 0.30i | `ArsenalInCradle-<版本>-aic0.30i.zip` |

每个 zip 旁边有同名 `.sha256`，下载后可校验：

```
sha256sum -c ArsenalInCradle-<版本>-aic0.29j2.zip.sha256
```

## 安装

1. 解压到任意独立目录（不要直接解压进游戏目录）；
2. 运行包内 `launcher\AicLauncher.Gui.exe`，选择游戏目录与发布包，先看「安装计划」预览再执行；
   管理器会检查/安装 BepInEx 5.4.23.6（x64），安装前可一键备份存档；
3. 启动游戏，设置页能看到模组版本号即安装成功。

卸载同样在管理器里选择「卸载」并预览；建议先在游戏内「维护 → 卸载前清理」再卸载。

## 反馈问题

请附上三样东西，这可以有效提高我们的工作效率，并使得您更快收到反馈：

- 游戏版本与模组版本（设置页可见）；
- `BepInEx/LogOutput.log`（出错那次运行结束后的那一份）；
- 设置页导出的诊断报告（默认只写在本机，不会上传，无隐私风险）。

## 声明

- 非官方模组，与游戏作者无关。
- 发布包内含自制素材；不含、也不重分发游戏官方资源。
- 各版本的具体变更见对应 Release 的说明与包内 `CHANGELOG.md`。
