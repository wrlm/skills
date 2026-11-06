# AI Skills Collection

中文优先、可复用的 AI Agent Skills。每个 Skill 独立目录，可按需安装。

## 已收录

| Skill | 功能 |
| --- | --- |
| [worker-representative](skills/worker-representative/) | 职工代表履职助手：制度权责、听取诉求、沟通协商、投诉跟进、职代会发言与**提案全流程** |

原 `proposal-advisor` 提案辅导能力已整合到 `worker-representative`，无需安装两个 Skill。原目录不再单独维护。

## 安装

将 `skills/worker-representative` 文件夹复制到工具支持的 Skills 目录；每种工具的加载方式可能不同。

兼容的 Skills 安装工具可尝试：

```bash
npx skills add wrlm/skills --skill worker-representative
```

请以实际安装工具文档为准。

## 结构

```text
skills/
  worker-representative/
    SKILL.md
    README.md
    references/
      duty-guide.md
      communication-guide.md
      proposal-module.md
    assets/
      proposal-template.md
      speech-template.md
    evals/
      proposal-cases.jsonl
```

## 贡献与安全

欢迎 Issue、Pull Request。请勿上传个人敏感信息、企业内部文件、密钥或无权开源的讲座材料。AI 只提供辅助意见，不代替法定程序、正式审议、提案立案或专业法律意见。各单位须自行核实制度版本、适用法律、流程及保密要求。

## License

MIT，见 [LICENSE](LICENSE)。
