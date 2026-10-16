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

### 学习许可与权利保留

- 本项目允许个人、学校和研究者进行非商业性的学习、研究和引用。
- 未经著作权人书面许可，不得将项目内容用于商业开发、产品制造、商业服务、商业宣传、投标交付、毕业设计成品交付或再授权。
- 不得删除作者、来源、版本历史和第三方许可证声明，不得将本项目或其衍生成果宣称为与作者无关的原创项目。
- 软件源码适用 [PolyForm Noncommercial 1.0.0](https://polyformproject.org/licenses/noncommercial/1.0.0/)；机械模型、PCB、原理图、图片、文档、Unity 工程和其他非软件资料适用 [CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/)。
- SE、SW、STEP/STP 及其他三维模型仅允许个人或学校进行非商业学习、评审和研究；未经著作权人书面许可，不得用于加工、打样、制造、销售、量产、投标、产品交付、商业宣传、改作或再授权。
- 第三方组件、模板、元件库、外购件模型和工具仍受其原始许可证约束；本声明不扩大作者对第三方内容的权利。

商业使用、产品化、公司内部长期使用、转让或排他性授权需另行取得著作权人的书面许可。