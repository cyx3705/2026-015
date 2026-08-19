# 2026-015-Mastercam学习

> Mastercam 学习仓库，收录 UG NX 测试模型、面铣与动态铣削等 CAM 演示及 NC 程序，以及机床定义、后处理器与自定义刀具刀柄元文件

## 项目内容

1. **NX 模块**
`b-Module-NX` 存放 UG NX 零件模型，现有 `ug测试模型.prt` 与 `_model.prt`。
2. **CAM 模块**

- 面铣演示：`面铣演示.mcam`、`面铣演示2.mcam` 至 `面铣演示6.mcam`，以及后处理程序 `面铣演示3.NC`（材料 ALUMINUM MM - 2024，刀具 T1 / 10 平底刀）；
- 其他演示：`动态铣削演示.mcam`、`线框串联演示.mcam`、`cam建模学习.mcam`；
- 关联模型：`ug测试模型.mcam`、`T.mcam`。

3. **参考资料**

- `CNC_MACHINES/`：机床定义文件 380 个（`.mcam-control`、`.mcam-mmd`、`.mcam-rmd`、`.mcam-lmd`、`.mcam-wmd`、`.mcam-gmd`）；
- `Posts/`：后处理文件 69 个（`.pst`、`.psb`、`.set`）；
- `3XX(自治机床文件).mcam-mmd`：自治机床文件。

4. **Mastercam 元文件**

- `z-自定义刀具库.TOOLDB`：自定义刀具库；
- `z-自定义刀柄库.tooldb`：自定义刀柄库；
- `z-自定义机床文件.mcam-mmd`：自定义机床文件；
- `z-Mastercsm官方刀库.lnk`：官方刀库快捷方式。

## 保留内容
- 本模板项目介绍：此为最初的准备的项目模板
    每个分支项目都会由他去继承
- 作者：Pinavia - 2025
