# Changelog

## [Unreleased]

### Changed
- 总纲：反向挑战补实测形态（层是稳定器）；需求层模板必写项增「假设与风险」
- 《从动态过程到静态结构》：形式化兼有发现功能，字段化是显性化的发生点
- 《数据契约为何自建》：过程侧验收两形态（主观判断的有边界出口、门槛须经历真实拒绝）
- 《从写代码到设计处理步骤》：显性化最小单元是字段；门槛须经历拒绝
- 《本地数据目录》：元数据模型获最小实证雏形
- 总纲目录改回缩写 intro，其余保留全拼

## [0.1.2] - 2026-11-05

### Changed
- 目录名改用全拼：`intro/` → `introduction/`、`spec/` → `specification/`、`impl/` → `implementation/`，导读、论文索引与各篇参考文献同步
- 总纲：增补「规模 vs 确定性」分歧定位与外部场景外推示例（4.5 节）
- 《从写代码到设计处理步骤》：增补智能体行为通例的外部例证
- 《从动态过程到静态结构》：4.2 节增补范畴论描述的最小示意
- 《数据契约为何自建》：增补流转方向差异（3.4 节），结尾去重
- 《本地数据目录》：按设计思路重述为本地数据索引（类比云端 Data Catalog 对不同数据源建索引）

## [0.1.1] - 2026-11-05

### Added
- 新增系列导读（index.md）与论文索引化 README
- 《本地数据目录：面向智能体处理的数据入口》提案成稿（impl/catalog.md，基于同名草稿，标注待答问题）
- 《从写代码到设计处理步骤：AI 时代的数据工程角色》成稿（spec/blueprint.md，基于同名口述草稿重梳逻辑）
- 《数据契约为何自建：现有方案的边界》成稿（spec/contract.md，基于同名口述草稿重梳逻辑）
- 《从动态过程到静态结构：数据意图的形式化与工具选型》成稿（intent/index.md，基于同名口述草稿重梳逻辑）
- 《蓝图》草稿迁入（spec/blueprint.md，来自 quanttide-data 的 data/context/eassy）
- 《数据契约》草稿迁入（spec/contract.md，来自 quanttide-data 的 data/context/eassy）
- 《意图》草稿迁入（intent/index.md，来自 quanttide-data 的 data/context/eassy）
- 《数据目录》草稿迁入（impl/catalog.md，来自 quanttide-data 的 data/context/eassy）

### Removed
- 《数据合同》移出（intro/contract.md → quanttide-data 的 data/history）
- 《制衣厂数据清洗》移出（processing/cleaning.md → quanttide-tech 的 data/brochure/qtdata/how.md）

## [0.1.0] - 2026-04-28

### Added
- 添加《数据合同》文章（intro/contract.md）
- 添加《制衣厂数据清洗》文章（processing/cleaning.md）

### Infrastructure
- 初始化仓库，添加 README

[Unreleased]: https://github.com/quanttide/quanttide-essay-of-data-engineering/compare/v0.1.1...HEAD
[0.1.1]: https://github.com/quanttide/quanttide-essay-of-data-engineering/compare/v0.1.0...v0.1.1
[0.1.0]: https://github.com/quanttide/quanttide-essay-of-data-engineering/commits/v0.1.0
