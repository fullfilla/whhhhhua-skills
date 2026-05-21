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
| `thesis-academic-revision-skill` | 面向中文本科论文的学术写作修订 skill，重点处理断句、标点、形容词/副词滥用，并辅助压缩空泛学术腔。 | [thesis-academic-revision-skill](./thesis-academic-revision-skill/) |

## 使用方式

如果你想单独查看某个 skill，直接进入对应目录，优先看：

1. `README.md`
2. `SKILL.md`
3. `examples/`

## 后续维护建议

后面继续往这个仓库里加 skill 时，建议同步维护这份列表：

- 增加一个新目录
- 在根 `README.md` 的表格里补一行
- 每个 skill 自己保留独立的 `README.md` 和示例文件
