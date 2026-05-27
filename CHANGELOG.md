# Changelog

All notable changes to Fate · 天命鑑定.

## [Unreleased]

### Added
- 城市搜索自动补全（输入城市名即时匹配，342 城）
- webapp-testing E2E 测试框架（Playwright + test_cases.json）
- testing-strategies / code-refactoring 通用 skill

### Changed
- 格局兜底逻辑：月支本气不透干时不直接取格
- 大运 L4 层加入病药修正（助长原病扣分+药到加分）
- 城市选择器从 <select> 改为 <input> 自动补全

### Fixed
- 自动补全首次加载无法匹配城市
- 3 处乾造文案中性别指代混用
- index.html 预加载提示缺失

## [3.7.0] - 2026-05-24

### Added
- KNOWN_CASES 扩展至 5 个校准案例
- 飞书桥接 bridge.py（DeepSeek TUI ⇄ 飞书群聊）
- SSL 证书部署到 clouddaqing.com

### Changed
- 城市库从 37 省会扩充至 342 地级市

### Fixed
- 枭印夺食/比劫夺财/天干合绊检测
- 格局简介文案部分描述性别人称错误

## [3.6.0] - 2026-05-17

### Added
- 格局简介 31 篇散文故事（汪曾祺式风格）
- 乾造/坤造双版文案
- README 致敬中华文化章节

### Changed
- 大运评分升级（L1 身强身弱感知，L3 制化检测）
- 格局判定优化（阳干从格阈值、化气格验证）

### Fixed
- 标签栏样式、中文引号字符冲突
