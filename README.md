# service-monitor

# 需求分析&场景描述
服务器上的应用偶尔会出现卡死，或者cpu占用100%，造成用户体验极差？

有时候连远程服务器都连接不上，真的是很头痛。

或者在回家的路上，突然用户说特别卡，不能提前预知服务器的运行状态。不能及时的发现问题并追踪。

目前一种解决方案就是停止应用重启，最坏的就是重启服务器。

于是乎，为了解决以上头痛问题，对应用状态和服务器运行状态进行监听，及早及时的发现问题并修复问题，也就可以提前预知服务器的状态趋势。

# 功能要点
监听应用服务运行状态, 同时监听cpu及服务占用情况以及相关应用的堆栈信息，设置阈值，超过可以发送邮件。为了及时记录服务器异常，方便追踪查找问题。
# 开发语言
python
# 相关三方依赖

# 其他
