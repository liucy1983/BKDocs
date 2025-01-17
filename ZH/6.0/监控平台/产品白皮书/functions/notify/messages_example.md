# 通知内容说明

监控有四类消息通知渠道样式，每一种又有 3 种汇总的信息格式。 

## 功能一览

* 通知渠道：短信，电话，邮件，IM 文本(微信，企业微信)
* 消息格式：单事件告警，同策略多事件告警，不同策略多事件告警
* 通知类型：异常通知，恢复通知，无数据通知

## 功能说明

### 邮件&同策略多事件告警

* 邮件信息最多，带对比图，带事件详情链接
* 同策略多事件：只有目标不一样，将在告警目标提供 IP/服务实例列表
![-w2020](media/15911009385709.jpg)

### 短信&单事件告警

短信最简洁，不带链接，不带图
![-w2020](media/15911011080145.jpg)

### 微信/企业微信&汇总告警

当同一时间达到了汇总收敛的阈值会进行跨策略的告警合并，提示汇总条数，并给出一个代表信息。详情点击进入可以看到更具体的。邮件就会带有事件的列表。并且微信带有移动端 H5 的入口，具体查看[移动端](h5_app.md)

![-w2020](media/15911013706265.jpg)

### 无数据告警

无数据告警都是预警级别
![-w2020](media/15911562374591.jpg)

### 已恢复通知

![-w2020](media/15911563921839.jpg)

### 电话

因为电话本身就会有限流和收敛，所以电话起到的是提醒。

```bash
当前{{业务}} {{策略名}}发生{{等级}}告警
```
