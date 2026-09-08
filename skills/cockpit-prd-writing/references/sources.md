# 来源与取舍

审阅日期：2026-09-08。以下链接用于方法来源追溯，不需要每次写 PRD 都重新打开。本 skill 的座舱检查和练习由本地任务归纳编写；它不是整车技术标准，也不宣称已通过大规模写作效果测试。

## 采用的公开参考

### Vercel Labs：find-skills

- [skills.sh 页面](https://skills.sh/vercel-labs/skills/find-skills)
- [审阅与安装版本](https://github.com/vercel-labs/skills/blob/1682051d48c34f5eb135e6475c1a965dce05e820/skills/find-skills/SKILL.md)
- 用途：查找和安装社区 skill。安装量和星标用于发现候选，不代表适合座舱写作；推荐前仍读真实指令、引用资源和依赖。

### Paweł Huryn：create-prd

- [审阅版本](https://github.com/phuryn/pm-skills/blob/18468a95b427e70e258b51389796367c6f684e7d/pm-execution/skills/create-prd/SKILL.md)
- 可参考之处：先明确问题、对象、价值、约束和验证，再组织方案；技术部分按相关性选用。
- 本地取舍：没有安装其独立 PRD skill。固定八章、每节关联战略、强制 OKR 格式，不适合作为每份中文座舱功能 PRD 的默认要求。这里采用按文档阶段选择结构的方式。

### syw2039：humanizer-zh

- [审阅与安装版本](https://github.com/syw2039/humanizer-zh/blob/72d73f9c8132817e21f66369de6925a659f9a6a6/SKILL.md)
- [中文表达参考](https://github.com/syw2039/humanizer-zh/blob/72d73f9c8132817e21f66369de6925a659f9a6a6/references/chinese-ai-patterns.md)
- 用途：在保留事实、限定条件和原有正式程度的前提下调整中文。它区分文体，也提醒不要把单个词语当成 AI 写作证据。
- 本地取舍：作为产品规则确定后的语言检查，不承担座舱能力判断，也不负责批准需求变更。上游的 MIT 许可和 NOTICE 随安装包保留。

## 比较后未直接安装的候选

- [Dean Peters：prd-development](https://github.com/deanpeters/Product-Manager-Skills/blob/main/skills/prd-development/SKILL.md)：适合较完整的需求梳理和工程交接，涉及其他组件 skill、工作坊协议和较长模板。此次需要日常中文 PRD 写作，因此没有引入整套流程。该链接为动态分支，后续评价应复核版本。
- [op7418：Humanizer-zh](https://github.com/op7418/Humanizer-zh/blob/main/SKILL.md)：有清理套话的参考价值，但所审阅版本还鼓励个人感受、题外话等表达。对需求规格直接使用这些规则可能损害准确性，故选择更强调事实保留与文体适配的版本。该链接同样为动态分支。

此次检索没有找到足够匹配“中文座舱产品经理 PRD”的现成一体化 skill；这不是断言生态中不存在此类工具。因此采用查找工具、通用中文润色和本地座舱写作三部分。

## 本地经验的适用范围

本地规则来自座舱主动建议 PRD 与 Demo 对齐任务，重点包括：以用户选定材料为准；区分生成、确认、执行与长期授权；检查手动接管、恢复及多乘员对象；对正文、图和 Demo 做一致性核对；解释实质修改。

“本项目以 Demo 为准”“某项能力移出首期”等历史决定不能推广到所有 PRD。这里保留判断方法，每次由新任务确定版本、范围和产品决策。未把历史凭据、个人目录、具体模型配置或整套对话写入 skill。
