# multivariate-ridge-with-thresholding

> ⚠️ 本仓库代码位于 `reference_code/`，是 2020 年前后读博期间的历史实现，仅作参考与溯源，不代表当前可用状态；新的开发请另建目录（如 `src/`），不要直接改这里的文件。

## 这个项目研究什么

这个项目研究如何把带 p 值阈值化的岭回归扩展到多变量精细定位，并结合遗传相关与效应量相关提高 SNP 优先级划分。目标是在多性状信息之间借力，同时控制噪声位点。

## 方法/数据

使用 R、Python 和 Jupyter 实现岭回归、阈值化、lasso/glasso 及图模型，结合模拟数据与 GWAS ATLAS、GIANT、PGC 等公开 GWAS 汇总统计开展评估。

## 当前状态

已有多版模拟和分析脚本；尚缺一键复现入口，真实数据分析与结果整理仍未完成。

## 代码地图

- `reference_code/fine-mapping-simulation/`：精细定位、回归与模拟流程。
- `reference_code/fine-mapping-simulation/simulationv4/`：后续版本的模拟实验。
- `reference_code/fine-mapping-simulation/gene-graph-conv-/`：图模型与图卷积相关探索。
