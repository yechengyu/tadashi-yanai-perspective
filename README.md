# 柳井正 · 服装经营思维顾问

以柳井正公开演讲、访谈及迅销经营记录为依据，帮助分析服装业务的客户价值、品质、交期、现场效率与组织协作。由女娲方法调研、提炼与验证，不是本人或迅销官方产品。

## 安装

[GitHub仓库](https://github.com/yechengyu/tadashi-yanai-perspective) · [下载ZIP](https://github.com/yechengyu/tadashi-yanai-perspective/archive/refs/heads/main.zip)

本仓库根目录包含 `SKILL.md`，无运行脚本、无密钥、无额外业务服务。

支持 skills CLI 的环境可执行：
```sh
npx skills add yechengyu/tadashi-yanai-perspective
```
该命令依赖目标环境有Node/npm，并由skills安装器选择兼容的AI工具；并非所有聊天工具都支持。安装器可能提示确认下载，请本人核对来源并操作。

手动方式：在GitHub的 Code → Download ZIP 下载，解压后若目录带 `-main` 后缀，先改名为 `tadashi-yanai-perspective`，再将整个文件夹放进所用AI工具支持的skills目录。Codex可用 `~/.codex/skills/tadashi-yanai-perspective/`，Claude Code可用 `~/.claude/skills/tadashi-yanai-perspective/`；其他工具按其正式说明，不把“上传一个文件”当成已安装技能。

安装后开启或刷新工具会话，调用 `$tadashi-yanai-perspective`，或者说“请用柳井正的经营视角分析这个问题”。若工具无法发现技能，仍可让AI读取 `SKILL.md` 体验方法，但须区分读取体验与技能安装。

## 课堂练习

同一个虚构问题分别用普通提问与本技能回答，比较它追问的事实、判断依据及下一步行动：

> 客户要求一批西服交期从20天缩短到15天，质量标准不变。业务想先承诺，生产担心返工。请先帮我梳理缺哪些事实，再比较可行办法。

然后换一件自己获准使用的真实问题，核对回答、指出错误、补规则，再测试。不要上传客户隐私或敏感业务数据。

## 结构

版本1.0.0。已做6道独立执行题与风格样例、双视角评审和结构检查；这些不等于真实经营效果或所有客户端兼容性已验证。详见验证记录。

- `SKILL.md`：触发条件、回答流程、核心模型、启发式及边界。
- `references/research/01-06*.md`：六个研究维度及出处与缺口。
- `references/evaluation.md`：真实独立测试和修正记录。

来源有日期和可靠性限制。研究者推断与人物原话分开；公司自述不等于独立效果验证。原始第三方文章未整体转载；研究摘要原创转述，来源版权归原权利人。

原创技能指令与研究归纳采用MIT许可，第三方资料不受该许可重新授权。

由 [女娲 · Skill造人术](https://github.com/alchaincyf/nuwa-skill) 方法生成；方法创建者：[花叔](https://x.com/AlchainHust)。本技能整理与维护：yechengyu。
