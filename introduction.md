# devstats 介绍

## 关于 devstats

devstats 是一个使用 [HA](https://github.com/zalando/patroni) [Postgres](https://www.postgresql.org) 数据库和 [Grafana](https://grafana.com) 仪表盘来可视化 GitHub 存档的工具集。
所有的东西都是开源的，所以它可以被其他 [CNCF](https://www.cncf.io/) 和非 CNCF 开源项目使用。唯一的要求是，项目必须托管在一个公共的 GitHub 仓库上。
CNCF 的 [devstats](https://devstats.cncf.io/) 项目使用 [Equinix](https://www.equinix.com/) 裸机 [Kubernetes](https://kubernetes.io) 节点部署，并使用 [Helm](https://helm.sh/) 图部署。

## 在 TiDB 社区的应用

因为 devstats 支持其他项目使用，所以我们为 TiDB 社区部署了一套来帮助我们进行社区状况分析。（正在进行中）

## 关于本书

编写本书的目的：一方面是希望本书作为一本手册能够分析 devstats 的架构和记录它的部署流程，另外一方面也希望能够作为一个使用 devstats 的例子供其他社区参考。

