# 座舱 PRD 写作 Skills

给智能座舱产品经理使用的中文 PRD 写作工具包。先把用户问题、方案理由和交互规则写清，再调整表达，减少空话、模板腔和翻译腔。

日常写座舱 PRD，优先使用 **cockpit-prd-writing**。

| Skill | 用途 | 在线阅读 |
| --- | --- | --- |
| cockpit-prd-writing | 撰写、修订和评审座舱 PRD，按立项、方案评审或研发交付调整深度 | [打开 SKILL.md](skills/cockpit-prd-writing/SKILL.md) |
| humanizer-zh | 保留事实、数字和限定条件，调整中文表达 | [打开 SKILL.md](skills/humanizer-zh/SKILL.md) |
| find-skills | 查找其他适合任务的社区 skill | [打开 SKILL.md](skills/find-skills/SKILL.md) |

## 下载与使用

[下载完整 skill 包](https://github.com/hadan8977/cockpit-prd-skills/raw/refs/heads/main/downloads/cockpit-prd-skills.zip)

解压后有三个独立的 skill 文件夹。将需要的文件夹完整放入所用 agent 的技能目录，保留其中的 `SKILL.md`、`references` 和其他随附文件；安装位置及加载方式以该 agent 的说明为准。

如果暂时不安装，也可以将上表中的 SKILL.md 链接交给能够读取 GitHub 文件的 agent，要求它阅读该文件及任务所需的关联参考文件，然后处理你的材料。

支持 `$技能名` 调用的 agent 可以使用：

> 用 $cockpit-prd-writing 修订这份 PRD。面向产品方案评审，中文自然、论证充分，保留已确认的产品决策，另附实质修改说明。

仅调整文字时可以使用：

> 用 $humanizer-zh 润色这段 PRD。保持正式程度，保留数字、否定、适用条件和产品决策；发现逻辑问题单独指出。

如需匹配个人文风，可同时提供几段你认可的文档文字。

## 座舱专用 skill 包含什么

- [结构与座舱检查](skills/cockpit-prd-writing/references/structure-and-cockpit.md)：文档深度、车辆状态、多乘员对象、触发时机、授权、接管、恢复及流程图一致性。
- [中文改写示例](skills/cockpit-prd-writing/references/chinese-examples.md)：展示怎样将抽象表述改成具体规则，同时保留原有含义。
- [行为检查案例](skills/cockpit-prd-writing/references/evaluation-cases.md)：检查润色是否改变时限、对象、否定、授权和任务范围。
- [来源与取舍](skills/cockpit-prd-writing/references/sources.md)：记录公开参考及适配理由。

例如，文档里写“3 秒内生成建议”，润色后仍须保留计时起点和生成事件，不能变成“及时响应”。只写文档时，不应修改 Demo；用户明确指定以 Demo 为准时，才按这一依据处理冲突。

本工具包不包含具体项目的 PRD、Demo 源码或车型能力定义。实际产品规则仍需以项目材料和已确认决策为准。

## 来源与许可

`cockpit-prd-writing` 为本项目整理的座舱写作 skill；公开方法的采用范围见其来源说明。

以下两项保留了上游内容与许可文件：

- `find-skills`：[Vercel Labs 原仓库](https://github.com/vercel-labs/skills)，收录版本 `1682051d48c34f5eb135e6475c1a965dce05e820`；[许可](skills/find-skills/LICENSE)。
- `humanizer-zh`：[syw2039 原仓库](https://github.com/syw2039/humanizer-zh)，收录版本 `72d73f9c8132817e21f66369de6925a659f9a6a6`；[许可](skills/humanizer-zh/LICENSE)及[来源声明](skills/humanizer-zh/NOTICE)。

收录日期：2026-09-08。已检查 skill 格式、本地引用及下载包完整性。写作效果需要结合实际 PRD 和个人文风继续校准。
