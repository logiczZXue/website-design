# WirelessDataset-Demo

## 项目简介

这个仓库是**WirelessAgent**项目的数据集演示仓库，展示了用于无线通信智能问答的WCHW数据集。

## 仓库内容

- **数据集样本**: WCHW无线通信问答数据集（测试集和验证集）
- **WirelessAgent介绍**: 基于大语言模型的无线网络智能代理
- **性能结果**: Agent在数据集上的表现评估

## 数据集说明

### WCHW数据集
- `wchw_test.jsonl`: 测试集，包含401道无线通信专业题目
- `wchw_validate.jsonl`: 验证集，包含89道无线通信专业题目

### 数据格式
每条数据包含以下字段：
- `question`: 题目内容
- `answer`: 标准答案  
- `cot`: 详细解题思路（Chain of Thought）
- `id`: 唯一标识符

### 题目类型
涵盖无线通信各个领域：
- 数字信号处理（PCM、量化、采样）
- 调制解调技术（AM、FM、PSK、FSK、QAM）
- 信道编码与纠错
- 天线与电波传播
- 信噪比与频谱效率计算
- 多址接入技术
- 移动通信系统

## WirelessAgent简介

WirelessAgent是利用大语言模型（LLMs）为无线网络创建的智能AI代理框架，具有以下特点：

- **智能推理**: 通过先进推理能力处理复杂无线网络任务
- **多模态处理**: 支持多种数据类型的综合分析
- **自主决策**: 实现网络的自动化管理和优化
- **高性能**: 相比传统方法实现44.4%更高的带宽利用率

## 在线演示

🌐 **可视化网站**: [即将上线]

## 相关论文

- **WirelessAgent: Large Language Model Agents for Intelligent Wireless Networks**
  - 发表于: China Communications 2025
  - arXiv: [2409.07964](https://arxiv.org/abs/2409.07964)

## 项目团队

本项目由Jingwen Tong教授团队开发，致力于将大语言模型技术应用于无线网络智能管理。

---


*最近一次更新: 2024年12月*
