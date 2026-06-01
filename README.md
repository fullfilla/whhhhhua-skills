# whhhhhua-skills

`whhhhhua-skills` 是一个个人 skill 仓库，用来集中存放可复用的 Codex / Claude 风格技能包。

后续如果继续新增 skill，建议每个 skill 都放在仓库根目录下的独立文件夹里，并保持统一结构，例如：

```text
skill-name/
├── SKILL.md
├── README.md
└── examples/
```

## Skill 列表

目前仓库中已有的 skill：

| Skill | 说明 | 路径 |
| --- | --- | --- |
| `thesis-academic-revision-skill` | 维普AIGC-面向中文本科论文的学术写作修订 skill，重点处理断句、标点、形容词/副词滥用，并辅助压缩空泛学术腔。 | [thesis-academic-revision-skill](./thesis-academic-revision-skill/) |
| `patent-drafting-skill` | 面向中国发明专利撰写的 skill，用于根据技术交底、权利要求草案、检索结果、公式和用户模板生成或修订专利文本。 | [patent-drafting-skill](./patent-drafting-skill/) |
| `patent-review-skill` | 面向中国发明专利审核的 skill，用于检查权利要求支持、步骤衔接、公式正确性、现有技术风险和 AI 味表达。 | [patent-review-skill](./patent-review-skill/) |

## 使用方式

如果你想单独查看某个 skill，直接进入对应目录，优先看：

1. `README.md`
2. `SKILL.md`
3. `examples/`

