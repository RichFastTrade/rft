# RichFastTrade

## 简介

RichFastTrade 是一个基于 Golang 的量化交易系统，旨在提供快速、高效、灵活的交易策略和分析工具。它集成了多种交易策略和分析工具，包括图表分析、缠论、K线预处理、交易策略和决策等。

## 微服务组件

RichFastTrade 由以下微服务组成：

- [x] [timer](https://github.com/RichFastTrade/timer) - 任务调度服务，负责定时创建任务并分发到任务队列，供其他微服务执行。
- [x] [datahub](https://github.com/RichFastTrade/datahub) - 行情数据服务，负责同步K线，提供交易所实时数据和K线数据
- [x] [analyzer](https://github.com/RichFastTrade/analyzer) - 交易分析服务，负责图表分析、缠论、K线预处理等功能
- [x] [notifier](https://github.com/RichFastTrade/notifier) - 预警通知服务，负责通知分发，包括邮件、短信、微信等
- [ ] [drawer](https://github.com/RichFastTrade/drawer) - 图表绘制服务，负责绘制各种图表
- [x] [rft_shared](https://github.com/RichFastTrade/rft_shared) - 公共服务组件，包括共享的数据结构、工具函数等

## Docker 镜像
[harbor](https://harbor.richfast.trade)

## 开发指南

[这里可以放整体开发规范和指引]