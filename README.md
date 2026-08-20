# Traditional Divination Research Workflow

A reusable Codex skill for analyzing traditional Chinese divination questions as cultural, historical, and comparative research.

It is designed for questions such as loss-location analysis, supplied hexagram or chart interpretation, comparison of traditional methods, and reality-check updates. It explicitly separates:

- traditional-source reasoning;
- modern probabilistic reasoning;
- verified facts and unresolved uncertainty.

The skill does not claim supernatural certainty and must not be used as the sole basis for medical, legal, financial, safety-critical, or irreversible decisions.

## Installation

Copy this repository into your Codex skills directory:

```text
~/.codex/skills/traditional-divination-research-workflow/
```

The resulting structure should include:

```text
traditional-divination-research-workflow/
├── SKILL.md
└── agents/
    └── openai.yaml
```

Start a new Codex turn and invoke:

```text
$traditional-divination-research-workflow Analyze this loss-location question...
```

## Core safeguards

- Preserve raw casting inputs and never fabricate missing data.
- Cite traditional sources when available and label unverified conventions.
- Keep symbolic interpretation separate from ordinary-world evidence.
- Register hypotheses before reality checks to reduce hindsight bias.
- Use low-risk, reversible checks and explicit stopping rules.
- Never accuse a person based on divination.

## 中文说明

这是一个用于 Codex 的可复用 skill，面向传统中国术数问题的文化、历史与比较研究，例如寻物位置分析、用户提供的卦象或课式解读、不同传统方法比较，以及实地查找后的证据更新。

它强制区分三类内容：

- 传统文献与术数规则推理；
- 现代概率和现实常识推理；
- 已验证事实与尚未解决的不确定性。

本 skill 不宣称超自然确定性，不应作为医疗、法律、金融、安全或不可逆决定的唯一依据，也不得仅凭术数推演指控他人。

安装后可这样调用：

```text
$traditional-divination-research-workflow 请按文化研究方法分析这个寻物问题……
```

See [SKILL.md](SKILL.md) for the complete workflow.

## License

MIT
