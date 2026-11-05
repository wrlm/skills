# AI Skills Collection

可复用的中文优先 AI Agent Skills，集中维护和发布。

## 已收录

| Skill | 用途 |
| --- | --- |
| [proposal-advisor](skills/proposal-advisor/) | 职工代表大会提案选题、调研辅导、起草优化、质量预审、研讨发言 |

## 安装

将 `skills/<skill-name>` 对应目录复制到所用 Agent 工具支持的 Skills 目录，确保其中的 `SKILL.md` 位于 Skill 目录根部。各工具具体加载方式可能不同。

支持兼容的 skills 安装器时，可尝试：

```bash
npx skills add wrlm/skills --skill proposal-advisor
```

请以所用工具的现行安装文档为准。

## 贡献

欢迎 Issue / Pull Request；新增 Skill 应具备明确用途、完整 `SKILL.md` 和必要测试案例。请勿提交企业内部文件、个人敏感资料、受版权保护的培训材料或凭空生成的事实。

## 声明

各 Skill 为 AI 辅助工具，不替代法律、业务或组织的正式审核。各单位使用前应自行补充本地制度、审查范围与保密要求。

## License

MIT，见 [LICENSE](LICENSE)。
