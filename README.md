# T1 报关单智能生成助手 · 测试与解析结果

本仓库只包含 **测试报告、测试数据与测试结果**，不包含任何业务源码。

## 目录

| 路径 | 内容 |
| --- | --- |
| `index.html` | 测试报告主页（截图已内嵌，可直接打开） |
| `results/parse_run.json` | 本次真实解析运行结果（业务编号 / Trace / 5 阶段 20 步 / 33 栏位状态） |
| `results/agent_decisions.json` | 每份文件解析后 Agent 判断要整合哪些栏位（含原文依据、页号、采用规则） |
| `results/sample_fields.json` | 报关单样板（报关单样例.pdf）的栏位与取值 |
| `results/format_tests.json` | PDF / PPT / 邮件 的解析测试结果 |
| `evidence/*.png` | 真实上传全流程截图 |
| `data/报关单素材/` | 样板与第 1 组四份单证（合同 / 发票 / 提单 / 箱单） |
| `data/报关单素材/1..100` 抽样 | 素材库分组样本 |
| `data/format_samples/` | PPTX 与 EML 解析样本 |
| `data/T1_100_sample_matched_answers/` | 100 份标准答案 JSON |

## 复现

打开 `index.html` 即可查看全部测试过程与结果；数据文件可直接用于比对。
