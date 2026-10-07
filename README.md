# 芒格决策分析 Skill

一个可复用的 Codex / Agent Skill，用多元思维模型帮助分析商业机会、产品选择和一般决策。

它会明确区分事实、假设、概率判断与行动建议，并重点检查反向风险、机会成本、能力圈、激励机制、心理偏误、复利、安全边际和退出条件。

## 安装

将本仓库克隆或下载到你的 Skill 目录，例如：

```powershell
git clone https://github.com/huangziyi498-sudo/munger-decision-skill.git "$env:USERPROFILE\.codex\skills\munger-decision-analysis"
```

重启或重新加载 Codex 后即可使用。

## 使用示例

```text
用芒格决策分析，帮我判断这个商业机会是否值得投入。
```

```text
比较方案 A、方案 B 和暂时不行动，重点分析机会成本、安全边际与退出条件。
```

```text
我已经投入半年了。请区分沉没成本和继续投入的真实依据，并告诉我什么证据会改变结论。
```

## 设计原则

- 只使用真正影响结论的模型，不机械罗列概念。
- 对关键结论进行跨模型验证。
- 优先提出低成本、可逆、能减少不确定性的行动。
- 不伪造精确概率、市场事实或名人原话。

## 许可证

[MIT](LICENSE)
