# ak2077-skills

一个用于分享和开源 Codex 技能（Skills）的个人技能库。

## 仓库结构

```text
ak2077-skills/
├── skills/
│   └── <skill-name>/
│       ├── SKILL.md              # 必需：触发描述与执行说明
│       ├── agents/
│       │   └── openai.yaml       # 推荐：技能列表与快捷入口的 UI 元数据
│       ├── scripts/              # 可选：可重复执行的脚本
│       ├── references/           # 可选：按需加载的参考资料
│       └── assets/               # 可选：模板、图片、字体等输出资源
├── .gitattributes
├── .gitignore
├── LICENSE
└── README.md
```

每个技能都放在 `skills/<skill-name>/` 下。除 `SKILL.md` 和推荐的
`agents/openai.yaml` 外，仅在确有需要时创建可选资源目录。

## 添加技能

1. 使用小写字母、数字和连字符命名技能目录，例如 `daily-report-writer`。
2. 创建 `skills/<skill-name>/SKILL.md`，文件名必须保持大写。
3. `SKILL.md` 的 YAML frontmatter 只包含 `name` 和 `description`：

   ```yaml
   ---
   name: daily-report-writer
   description: Describe what the skill does and the situations that should trigger it.
   ---
   ```

4. 在正文中使用祈使句写清工作流，并保持简洁；详细资料放到 `references/`。
5. 按需添加 `scripts/`、`references/` 或 `assets/`，不要创建空目录。
6. 提交前检查目录名与 `name` 一致，并验证示例脚本可以实际运行。

## 安装单个技能

将目标技能目录复制到 Codex 技能目录：

```powershell
Copy-Item -Recurse .\skills\<skill-name> "$env:USERPROFILE\.codex\skills\<skill-name>"
```

也可以直接从本仓库选择需要的技能进行安装；各技能的依赖与使用方式以其
`SKILL.md` 为准。

## 设计原则

- 只保留执行任务所需的信息，避免重复和冗余文档。
- 使用渐进式披露：触发信息放在 frontmatter，核心流程放在 `SKILL.md`，细节按需放入资源目录。
- 对易出错或需要稳定复用的流程优先提供脚本，并在发布前实际测试。
- 不在单个技能目录内添加 `README.md`、安装指南、变更日志等辅助文档。

## License

[MIT](LICENSE)
