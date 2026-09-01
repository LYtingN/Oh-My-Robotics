# Papers

> 状态：`to-read` · `reading` · `read` · `dropped`

## Zero-WAM: In-Context World-Action Modeling from Human Videos for Open-Ended Task Generalization

- **状态**：`to-read`
- **加入日期**：2026-08-28
- **分类**：Generalist Robot Learning and Task Generalization
- **子分类**：In-Context Learning and Video-Conditioned Policies
- **作者**：Jiaming Zhou；Qihang Zhang；Gangwei Xu；Cunxin Fan；Yujie Zhao；Ruilin Wang；Yiming Luo；Shuai Yang；Xing Zhu；Yujun Shen；Junwei Liang；Yinghao Xu
- **年份**：2026
- **类型/来源**：arXiv 预印本；Robotics (`cs.RO`)，Computer Vision and Pattern Recognition (`cs.CV`)
- **版本**：v2，2026-08-27（v1 提交于 2026-08-26）
- **原始 URL**：https://robbyant-research.github.io/Zero-WAM/
- **论文 URL**：2026-08-26 · https://arxiv.org/abs/2608.26103
- **标识符**：arXiv:2608.26103；DOI: [10.48550/arXiv.2608.26103](https://doi.org/10.48550/arXiv.2608.26103)
- **标签**：`robot-learning`、`robotic-manipulation`、`world-action-model`、`in-context-learning`、`human-video`
- **备注**：以人类示范视频作为上下文任务说明，训练因果视频—动作模型，使机器人在未见任务上进行零样本跨任务泛化；论文同时提出 HumanGen 数据生成流程和 in-context future chunk prediction（IFP）目标。
- **核验状态**：书目信息已通过 arXiv 与项目页交叉核验；尚未下载或阅读论文全文。

## Introducing S1: In-Context Learning for Robotics

- **状态**：`to-read`
- **加入日期**：2026-08-28
- **分类**：Generalist Robot Learning and Task Generalization
- **子分类**：In-Context Learning and Video-Conditioned Policies
- **作者**：Skild AI（机构作者）
- **年份**：2026（2026 年 8 月）
- **类型/来源**：公司技术文章 / 产品研究博客；Skild AI
- **原始 URL**：2026-08 · https://www.skild.ai/blogs/s1
- **论文 URL**：无公开论文版本
- **标识符**：无 DOI 或 arXiv 编号
- **标签**：`robot-learning`、`robotic-manipulation`、`foundation-model`、`in-context-learning`、`video-demonstration`、`long-horizon`
- **备注**：介绍机器人基础模型 S1：使用单个视频示范作为上下文，在不微调或后训练的情况下执行已见及未见任务，并展示最长约 10 分钟的长时程操作。文章报告在 100K 小时训练规模的内部未见任务基准上，视频上下文策略的成功率为 66%，语言提示策略为 9%。
- **核验状态**：标题、机构作者、日期和建议引用格式已通过 Skild AI 原始页面核验；截至 2026-08-28 未找到对应的正式论文、公开方法细节或 DOI/arXiv 记录。实验结果来自公司内部基准，属作者自报且未经公开同行评审，阅读时需保留此限制。

## LadderMan: Learning Humanoid Perceptive Ladder Climbing

- **状态**：`to-read`
- **加入日期**：2026-08-28
- **分类**：Humanoid Locomotion and Whole-Body Control
- **子分类**：Perceptive Locomotion and Loco-Manipulation
- **作者**：Siheng Zhao；Yuanhang Zhang；Ziqi Lu；Pieter Abbeel；Rocky Duan；Koushil Sreenath；Yue Wang；C. Karen Liu；Guanya Shi
- **年份**：2026
- **类型/来源**：arXiv 预印本；Robotics (`cs.RO`)，Artificial Intelligence (`cs.AI`)，Computer Vision and Pattern Recognition (`cs.CV`)，Machine Learning (`cs.LG`)
- **版本**：v1，2026-06-04
- **原始 URL**：https://ladderman-robot.github.io/
- **论文 URL**：2026-06-04 · https://arxiv.org/abs/2606.05873
- **标识符**：arXiv:2606.05873；DOI: [10.48550/arXiv.2606.05873](https://doi.org/10.48550/arXiv.2606.05873)
- **标签**：`humanoid-robot`、`ladder-climbing`、`visuomotor-policy`、`imitation-learning`、`reinforcement-learning`、`sim-to-real`、`whole-body-control`
- **备注**：提出面向人形机器人感知式爬梯与梯上操作的统一系统。方法先通过混合运动跟踪从单一参考动作学习多个爬梯专家，再以模仿学习和强化学习蒸馏为基于深度视觉的统一策略；同时利用视觉基础模型缩小深度感知的 sim-to-real 差距，并训练独立操作策略支持梯上遥操作任务。
- **核验状态**：书目信息已通过 arXiv 与项目页交叉核验；目前为预印本，尚未下载或阅读论文全文。

## LightNav-0: Eliciting VLM Spatial Intelligence for Generalist Embodied Navigation

- **状态**：`to-read`
- **加入日期**：2026-09-01
- **分类**：Generalist Robot Learning and Task Generalization
- **子分类**：Generalist Embodied Navigation
- **作者**：Light Origins Team（机构作者）
- **年份**：2026（2026-09-01）
- **类型/来源**：技术报告与开源项目；Light Origins
- **原始 URL**：https://www.lightorigins.com/blog/lightnav-0
- **报告 URL**：2026-09-01 · https://static.lightorigins.com/website/reports/lightnav-0-technical-report_02cfc2f.pdf
- **代码 URL**：https://github.com/lightorigins/LightNav-0
- **模型 URL**：https://huggingface.co/LightOriginsHQ/LightNav-0
- **标识符**：无 DOI 或 arXiv 编号
- **标签**：`embodied-navigation`、`vision-language-model`、`vision-language-action`、`real2sim2real`、`zero-shot-generalization`、`cross-embodiment`、`reinforcement-learning`
- **备注**：提出通用具身导航模型 LightNav-0，以 Qwen3-VL 为基础，通过具身推理中期训练、具身监督微调和在线强化学习三个阶段进行对齐。其 Real2Sim2Real 数据引擎将 2,000+ 互联网真实场景转化为 4,000+ 小时导航经验；同一模型面向指令跟随、开放词汇目标导航和视觉跟踪，并展示向人形、四足、轮式与空中机器人零样本迁移。
- **核验状态**：标题、机构作者、发布日期、技术报告、GitHub 代码仓库和 Hugging Face 模型链接已通过 Light Origins 原始页面及官方仓库核验。当前为机构技术报告而非 arXiv 或正式同行评审论文；基准结果主要由发布方报告，阅读时需保留此限制。

## LingBot-VA: Causal World Modeling for Robot Control

- **状态**：`to-read`
- **加入日期**：2026-09-01
- **分类**：Generalist Robot Learning and Task Generalization
- **子分类**：Video-Action World Models
- **作者**：Lin Li；Qihang Zhang；Yiming Luo；Shuai Yang；Ruilin Wang；Fei Han；Mingrui Yu；Zelin Gao；Nan Xue；Xing Zhu；Yujun Shen；Yinghao Xu
- **年份**：2026
- **类型/来源**：RSS 2026；arXiv 预印本；Computer Vision and Pattern Recognition (`cs.CV`)，Robotics (`cs.RO`)
- **版本**：v2，2026-03-22（v1 提交于 2026-01-29）
- **原始 URL**：https://github.com/Robbyant/lingbot-va
- **论文 URL**：2026-01-29 · https://arxiv.org/abs/2601.21998
- **项目 URL**：https://technology.robbyant.com/lingbot-va
- **代码 URL**：https://github.com/Robbyant/lingbot-va
- **模型与数据 URL**：https://huggingface.co/collections/robbyant/lingbot-va
- **标识符**：arXiv:2601.21998；DOI: [10.48550/arXiv.2601.21998](https://doi.org/10.48550/arXiv.2601.21998)
- **标签**：`robot-learning`、`robotic-manipulation`、`video-action-model`、`world-model`、`autoregressive-diffusion`、`mixture-of-transformers`、`long-horizon`
- **备注**：提出自回归 video-action world model LingBot-VA，在统一的交错序列中联合学习未来帧预测与动作执行。其设计包括共享视觉—动作隐空间、Mixture-of-Transformers、基于真实观测更新的闭环 rollout，以及并行动作预测与电机执行的异步推理，面向长时程操作、数据高效后训练及对新配置的泛化。
- **核验状态**：标题、作者、版本、学科分类、arXiv 标识符、RSS 2026 信息、项目页、代码仓库及 Hugging Face 资源已通过 arXiv 和 Robbyant 官方页面交叉核验；尚未下载或阅读论文全文。
