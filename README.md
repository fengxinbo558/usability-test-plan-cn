# 可用性测试计划 Skill

为网站、App、小程序、后台系统、硬件或服务流程设计可直接执行的可用性测试任务、招募、主持、观察记录和停止方案。

## 适合处理

- 关键流程能否被目标用户独立完成
- 快速首轮测试或标准完整计划
- 样本覆盖、任务卡、主持提纲和观察表
- 高风险操作隔离、隐私控制和异常预案

本 Skill 不用于需求探索访谈、问卷推断、A/B 实验、市场规模估算或单纯界面审美评审。

## 使用

在 Codex 中直接调用：

```text
$usability-test-plan-cn 为这个关键流程制定一份可直接执行的可用性测试计划。
```

安装到个人 Skill 目录的一种方式：

```bash
git clone https://github.com/fengxinbo558/usability-test-plan-cn.git ~/.codex/skills/usability-test-plan-cn
```

若目标目录已经存在，请先自行检查，不要直接覆盖。

## 内容

- `SKILL.md`：主入口、模式选择、核心流程与安全边界
- `agents/openai.yaml`：中性中文 UI 元数据
- `references/planning-guide.md`：样本、任务与停止规则
- `references/execution-pack.md`：执行表单与记录模板
- `evals/`：触发与行为样例

## 验证与来源

本仓库版本已通过结构、安全、链接和隔离安装检查。来源和修改边界见 `UPSTREAM.md`，适用许可证原文见 `LICENSE.upstream`；这些文件属于法律与诚实溯源记录，不应删除。
