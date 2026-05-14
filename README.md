## 仓库内容

- `maxwell.aedt`：ANSYS Maxwell 工程文件，用于电磁场建模与仿真。
- `simulation.slx`：MATLAB/Simulink 模型文件，用于系统级动态仿真。
- `实验报告.docx`：项目说明文档或实验报告。

## 项目说明

本项目包含：

- ANSYS Maxwell 电磁场建模与性能仿真
- MATLAB/Simulink 系统动态仿真与功能验证
- 项目实验报告与设计说明

## 仿真与 Maxwell 建模介绍

- 本项目使用 ANSYS Maxwell 进行电磁场建模，通过 Maxwell 的几何建模、网格划分、材料定义和求解设置分析电磁场分布与系统性能。
- `maxwell.aedt` 文件包含 Maxwell 模型结构、几何参数、材料属性、边界条件和求解设置，用于评估磁通分布、电磁力、损耗以及电流波形。
- 仿真过程包括模型搭建、网格优化、求解运行和结果后处理，支持查看磁感应强度、磁通密度、损耗分析和电磁兼容性评估等关键指标。
- 该 Maxwell 建模结果可用于验证设计方案、优化结构参数，并与 `simulation.slx` 中的系统级仿真结果进行联动分析。

## 使用方法

1. 使用 ANSYS Electronics Desktop 打开 `maxwell.aedt` 进行 Maxwell 电磁场仿真分析。
2. 使用 MATLAB/Simulink 打开 `simulation.slx` 查看模型结构并运行系统仿真。
3. 使用 Word 或兼容软件打开 `实验报告.docx`，阅读项目设计说明与实验结论。

## 注意事项

- 请确保本地已安装 ANSYS Electronics Desktop（包含 Maxwell）和 MATLAB/Simulink。
