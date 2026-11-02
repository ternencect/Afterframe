# 代表性示例与验证记录

只保留一组完整的“诊断 → 编辑 → 复核”试跑，覆盖三类不同结果。查看[原图与全部六张候选](closed-loop/COMPARISON.md)，包括未采用的结果，没有只挑成功图。

| 案例 | 代表的决策 | 最终选择 |
| --- | --- | --- |
| 人物插画 | 右袖排线减轻，但全图纸纹漂移，局部收益不足以抵消保护失败 | 两组均保留原图 |
| 像素机器人 | 右鞋软边与光晕改善，但鞋口及轮廓包含推断性重建 | 两组均采用 v1，不能视作生产精灵验证 |
| 展览海报 | 标题拼写和底部信息对比度改善，额外排版变化属于取舍 | 两组均采用 v1，未验证真实手机显示规格 |

## 保留的证据

- [三张合成原图及来源说明](evaluation/README.md)
- [运行协议](closed-loop/PROTOCOL.md)、[当时的 Skill 快照](closed-loop/skill-snapshot.md)及[版本变化](closed-loop/skill-change.json)
- [With 的需求与原诊断](closed-loop/with/cases.json)、[调用与提示词](closed-loop/with/run.json)、[逐项复核](closed-loop/with/report.md)
- [Without 的需求与原诊断](closed-loop/without/cases.json)、[调用与提示词](closed-loop/without/run.json)、[逐项复核](closed-loop/without/report.md)
- [独立匿名目视复核](closed-loop/independent-review.md)、[揭盲映射](closed-loop/blind-map.json)及[原图校验值](closed-loop/checksums-before.json)

原始 JSON 保留运行时路径和工具输出信息，外部临时路径只是历史记录，不是可下载的仓库资源。换机器核查时，将包含 `Afterframe/` 的历史仓库路径映射到当前仓库根目录；原图校验值仍适用。仓库图片可通过上述 Markdown 对照访问。

## 验证范围与精简说明

这是三张已使用过的合成样例上的流程试跑，使用历史 Skill 快照和受限的生成式工具；不能证明当前版本的整体有效性，也没有验证参考画法迁移或真实创作者满意度。选择原图不代表问题已经修复。

此前第一轮诊断和第二轮固定任务重复实验已移出仓库，完整材料在维护者本地归档。第二轮曾记录诊断指标持平、局部编辑出现有限收益信号；精简不改变这一有限结论，也不将剩余案例包装为普遍效果证明。当前仓库仅支持直接复核本次保留的闭环试跑。
