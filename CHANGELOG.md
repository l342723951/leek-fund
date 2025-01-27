# ChangeLog

## [1.2.7]

- fix: 资金流向 img 重复添加 bug

## [1.2.6]

- 更换插件 LOGO，:heart: Design By @JayHuangTnT
- fix: 折叠基金 panel 时，股票数据不刷新 bug
- chore: 资金流向流出数据绿色显示

## [1.2.5]

- feat: 股市资金流向（北向资金、南向资金）
- fix: 定时配置修改后需要重启

## [1.2.4]

- fix: 状态栏数据不能刷新

## [1.2.3]

- feat: 基金右键菜单，查看持仓信息和历史净值列表

## [1.2.2]

- fix: sz 股票类型遗漏 :heart: PR by @httpcheck

## [1.2.0]

- feat: 支持股票模糊搜索添加
- fix: 股票支持前缀 `usr_` 美股 :heart: PR by @SubinY
- fix: 美股详情里实时趋势图定时 `20s` 刷新一次

## [1.1.10]

- feat: 基金 GUI 新增支持模糊匹配搜索 :heart: PR by @zomixi
- chore: 修改涨跌图标样式，提升体验

## [1.1.9]

- feat: 排序按钮新增第三个模式：不排序（升序/降序、不排序）
- fix: 基金详情页面实时走势图没有定时刷新（定时 20s 轮询）

## [1.1.8]

:bangbang: 插件由原来的 “韭菜基金” 改名为 **韭菜盒子**

- fix: 股票错误代码需要手动改配置文件问题 :heart: PR by @httpcheck
- feat: 点击基金也可以直接查看到实时走势图
- chore: 新增操作手册 :heart: PR by @Somin

## [1.1.7]

- feat: 新增基金实时走势图

## [1.1.6]

- feat: 新增基金历史走势图

## [1.1.5]

- fix: 修复 ubuntu 系统插件初始化 bug

## [1.1.4]

- chore: 加入错误日记提示，用于问题排查
- feat: 美化股票 K 线图样式

## [1.1.3]

- feat: 新增基金排行榜

## [1.1.2]

- fix: 闭市时插件启动 status bar 无法初始化问题

## [1.1.1]

- feat: 支持手动刷新数据
- feat: 股票悬浮显示今日详情 tooltip

## [1.1.0]

- feat: 支持升序/降序排序
- feat: 支持股票新增和删除 GUI 操作（基金也支持）

## [1.0.0]

**:triangular_flag_on_post:重大改变，代码 100% 重构**

- refactor: 重构代码，typescript 开发
- feat: 替换股票数据为新浪 api
- fix: 修复港股和美股数据无法获取问题

## [0.2.1]

- fix: 闭市后不再请求数据，数据定时请求时间固定在 9 点到 15 点

## [0.2.0]

- feat: 支持 GUI 操作新增&删除基金 :heart: PR by @zomixi

## [0.1.10]

- fix: 兼容到 VSCode `1.29.0` 版本
- chore: 配置说明修改

## [0.1.9]

- feat: 股票支持 K 线走势图

## [0.1.8]

- fix: 错误的基金编码处理
- feat: 支持基金历史数据查看&股票走势图查看

## [0.1.6]

- fix: 替换实时基金接口

## [0.1.5]

- 新增 A 股指数

## [0.1.4]

- 新增菜单面板查看基金和上证指数

## [0.1.3]

- 修改体验细节

## [0.1.0]

- 实现基金涨跌实时查看
