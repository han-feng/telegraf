# Telegraf [![Circle CI](https://circleci.com/gh/han-feng/telegraf.svg?style=svg)](https://circleci.com/gh/han-feng/telegraf)

Telegraf 的个性化定制版，用于学习研究。

1. 调整 CircleCI 构建脚本，减少编译输出的包类型（[CircleCI 配置](.circleci/config.yml)）
2. 增加 mips64el 架构支持（[构建配置](scripts/build.py)）
3. 缩减了插件数量，仅包含常用插件；（[inputs](plugins/inputs/all/all.go)，[outputs](plugins/outputs/all/all.go)，测试代码调整）

参见：[Telegraf 官方仓库](https://github.com/influxdata/telegraf/blob/master/README.md)
