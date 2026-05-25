# 母婴产品销售分析（Power BI）

## 项目背景
基于淘宝母婴订单数据（约1.2万条），分析品类销售情况、监控月度波动、评估品牌集中度

## 工具
- Power BI / Power Query：数据清洗与建模
- DAX：度量值开发

## 数据清洗（Power Query）
- 过滤空值和异常值（销售额≤0的订单）
- 合并品牌表和订单表
- 转换日期字段格式

## 核心指标
- 总成交量
- 月度环比
- 品牌集中度（CR3/CR5）

## 看板页面与核心结论

| 分析页面 | 核心发现 | 业务建议 |
|----------|----------|----------|
| 销量分析 | 孕妇装19.47%，哺乳文胸17.38%，家居服14.72%，TOP3合计超50% | 运营资源优先向TOP3品类倾斜 |
| 趋势分析 | 2020年3月环比+109%，2021年1月环比-26% | 复盘异常月份的活动/供应链 |
| 同环比分析 | 2020年下半年增长，Q4达峰值后回落 | Q4大促策略可复制 |
| 品牌集中度 | CR3贡献58%销售额 | 关注腰部品牌培养 |
| 价格带分析 | 100-200元价格带贡献45%销售额 | 选品聚焦此区间 |

## 截图
👉 [查看详细分析报告](./DETAILED-ANALYSIS.md)
![销量分析](https://github.com/user-attachments/assets/a60ec65e-af37-496f-b238-6990a713bd26)

![趋势分析](https://github.com/user-attachments/assets/16ada184-6f5d-4348-bb43-ab9a47c02c19)

![同环比](https://github.com/user-attachments/assets/70a33471-14d0-4417-ad34-fbd0dd19cc0f)

![品牌集中度](https://github.com/user-attachments/assets/46a0d63a-bbce-4d85-ba8e-48a9b86a3a97)

![价格带](https://github.com/user-attachments/assets/68cab72c-0b34-4995-bb19-519426db9305)
