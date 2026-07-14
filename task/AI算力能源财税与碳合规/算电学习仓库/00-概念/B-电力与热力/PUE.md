---
type: concept
category: B-电力与热力
aliases: [Power Usage Effectiveness, 电能利用效率]
source_location: 原稿第124行
---

# PUE

## 定义

PUE是数据中心总能耗与IT设备能耗之比：

$$PUE=\frac{E_{facility}}{E_{IT}}$$

它反映供配电、冷却等设施为IT负载服务时产生的附加能耗。

## 边界与辨析

必须说明计量边界、测点和时间尺度。设计PUE、瞬时PUE、月度平均与全年平均不可直接混用。PUE不评价模型效率、电力来源或单位任务价值。

## 关系与应用

[[IT功率]]、[[热负荷]]、冷却方案、气象和负载率共同影响PUE。PUE用于把IT电量扩展为设施总电量，并进入碳排、成本和数据中心能效评价。

## 相关问题

Q3-Q5、Q37-Q48、Q78-Q89、Q116。

## 反例

PUE降低不保证总电量下降；PUE低也不表示所用电力低碳，更不表示AI模型高效。
