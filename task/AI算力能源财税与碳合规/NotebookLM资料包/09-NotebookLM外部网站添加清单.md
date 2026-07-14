# NotebookLM 外部网站添加清单

本文件中的网址建议通过 NotebookLM 的“网站”来源单独添加。只上传本文件不会让 NotebookLM 自动读取链接背后的完整网页。

## 第一轮添加

### 全国一体化算力网实施意见

用途：核对统一度量、计费、交易、结算，跨区域调度，算电融合，绿电比例和碳汇互认等政策表述。

https://www.gov.cn/zhengce/zhengceku/202401/content_6924596.htm

### 2026年政府工作报告

用途：核对“超大规模智算集群、算电协同等新基建工程”的正式表述。

https://www.gov.cn/gongbao/2026/issue_12646/202603/content_7064134.html

### ISO/IEC 21031:2024

用途：确认Software Carbon Intensity标准状态、功能单位和软件碳强度方法。

https://www.iso.org/standard/86612.html

### Software Carbon Intensity公开规范

用途：阅读SCI的边界、功能单位、运行排放和硬件隐含排放计算过程。

https://sci.greensoftware.foundation/

### AI Energy Score

用途：学习固定任务、硬件、批处理和配置条件下的AI推理能耗比较方法。

https://huggingface.github.io/AIEnergyScore/

## 第二轮添加

### 国家数据局高质量数据集相关文件

用途：理解数据集词元交易和数据价值体系。注意：该文件不等于算力token能耗定价政策。

https://www.nda.gov.cn/sjj/zwgk/tzgg/0608/20260608172117399715004_pc.html

### IEA《Energy and AI》

用途：理解全球数据中心电力需求情景、电网接入和能源供应约束。

https://www.iea.org/reports/energy-and-ai

### Carbon Aware SDK

用途：了解如何调用地区与时间碳强度数据，构建碳感知应用和调度原型。

https://carbon-aware-sdk.greensoftware.foundation/docs/overview

### CodeCarbon

用途：了解本地程序CPU、GPU和RAM能耗及碳排跟踪工具。

https://codecarbon.io/

## 添加后的检查

网站导入完成后，向 NotebookLM 提问：

```text
请列出你实际读取到的所有网站来源，并分别引用一段只有该网页才包含的具体内容。如果网页只读取到标题、摘要、登录页或导航页，请明确标记“正文未成功读取”，不要假装已经读取全文。
```

