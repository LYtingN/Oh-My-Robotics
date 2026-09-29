# Papers

> Status: `to-read` · `reading` · `read` · `dropped`

## Delta-0 (Δ₀): A New Chapter in Humanoid Intelligence

- **Status**: `to-read`
- **Added**: 2026-09-29
- **Topic**: Humanoid Loco-Manipulation
- **Authors**: Delta Intelligence Team
- **Year**: 2026 (September 2026)
- **Type / source**: Company research article; Delta Intelligence Blog
- **Original URL**: 2026-09 · https://deltai.com/en/blog/delta-0
- **Paper URL**: No public paper identified
- **Identifier**: No DOI or arXiv ID identified
- **Tags**: `humanoid-foundation-model` · `loco-manipulation` · `whole-body-control` · `world-action-model` · `human-motion-data` · `real-world-rl`
- **Notes**: Delta-0 combines a latent world-action model with a learned whole-body controller. The policy maps vision, language, and robot state to motion commands and 69-DoF joint targets, while a shared delta-action interface supports teleoperation, human corrections, and real-world RL post-training. The article also describes pretraining with more than 10,000 hours of paired egocentric human observations and whole-body motion.
- **Verification**: Title, institutional authorship, publication month, architecture, data description, and evaluation protocol were checked against the official article. No standalone paper, DOI, arXiv record, code release, or peer-review record was identified. Performance results are self-reported by Delta Intelligence.

## OM-1: Frontier Robot Intelligence, Learned Firsthand from Humans

- **Status**: `to-read`
- **Added**: 2026-09-29
- **Topic**: Humanoid Loco-Manipulation
- **Authors**: Reward AI Team
- **Year**: 2026 (September 2026)
- **Type / source**: Company research article; Reward AI Blog
- **Original URL**: 2026-09 · https://www.rewardai.com/blog/OM-1/
- **Paper URL**: No public paper identified
- **Identifier**: No DOI or arXiv ID identified
- **Tags**: `generalist-policy` · `cross-embodiment` · `human-demonstration` · `multimodal-policy` · `contact-rich-manipulation` · `reinforcement-learning-control`
- **Notes**: OM-1 is the policy component of Reward AI's Omnibody stack. It learns directly from robot-free human demonstrations captured with the wearable Omnibody Hand and consumes images, tactile signals, proximity measurements, and hand-pose trajectories. A simulation-trained control layer executes manipulation and navigation commands across embodiments ranging from industrial arms to humanoids.
- **Verification**: Title, institutional authorship, publication month, model inputs, training setup, and control description were checked against the official article. No standalone paper, DOI, arXiv record, code release, or peer-review record was identified. Claims such as learning a new task from less than 30 minutes of data are self-reported by Reward AI.

## Generate, Track, Improve: Perceptive Multi-Skill Humanoid Locomotion with RL-Fine-Tuned Motion Generators

- **Status**: `to-read`
- **Added**: 2026-09-29
- **Topic**: Humanoid Loco-Manipulation
- **Authors**: Zachary Olkin; William D. Compton; Aaron D. Ames
- **Year**: 2026
- **Type / source**: arXiv preprint; Robotics (`cs.RO`)
- **Version**: v1, 2026-09-25
- **Project URL**: 2026-09-25 · https://zolkin1.github.io/generate-track-improve/
- **Paper URL**: 2026-09-25 · https://arxiv.org/abs/2609.31577
- **Identifier**: arXiv:2609.31577; DOI: [10.48550/arXiv.2609.31577](https://doi.org/10.48550/arXiv.2609.31577)
- **Tags**: `humanoid-robot` · `perceptive-locomotion` · `multi-skill` · `flow-matching` · `motion-generation` · `reinforcement-learning` · `depth-perception`
- **Notes**: The paper presents a two-layer architecture in which a perceptive flow-matching motion generator plans whole-body trajectories from raw depth images and a control-guided RL tracking policy executes them. An off-policy fine-tuning loop uses structured search and advantage-weighted regression to improve terrain consistency and skill composition on a Unitree G1.
- **Verification**: Bibliographic metadata, abstract-level method description, project link, platform, and reported results were checked against arXiv. This is a preprint; the full paper has not yet been read.

## STRIDER: Stepping-Enabled Multi-Gait Hierarchical 3D Loco-Manipulation Framework for Humanoid Robots

- **Status**: `to-read`
- **Added**: 2026-09-29
- **Topic**: Humanoid Loco-Manipulation
- **Authors**: Yuanzhuo Li; Wen Zhao; Zhe Yong; Xiang Meng; Gang Han; Hengle Ren; Xiaoyang Zheng; Zhen Wang; Yijie Guo
- **Year**: 2026
- **Type / source**: arXiv preprint; Robotics (`cs.RO`); submitted to ICRA 2027
- **Version**: v1, 2026-09-20
- **Paper URL**: 2026-09-20 · https://arxiv.org/abs/2609.23483
- **Identifier**: arXiv:2609.23483; DOI: [10.48550/arXiv.2609.23483](https://doi.org/10.48550/arXiv.2609.23483)
- **Tags**: `humanoid-robot` · `loco-manipulation` · `hierarchical-control` · `stepping` · `multi-gait` · `reinforcement-learning` · `sim-to-real`
- **Notes**: STRIDER combines terrain-aware 3D stepping, adversarial-motion-prior walking, and Cartesian upper-body control. Its Latent Distillation PPO formulation integrates on-policy RL, DAgger-style action reconstruction, and latent alignment to distill a stepping expert into a hierarchical controller deployed on the TianGong Omni humanoid.
- **Verification**: Bibliographic metadata, submission information, abstract-level method description, and platform details were checked against arXiv. This is a preprint submitted to ICRA 2027; the full paper has not yet been read.

## WholeBodyWAM: Generalizing Pre-trained World-Action Priors to Humanoid Loco-Manipulation via WBC-Grounded Coordination

- **Status**: `to-read`
- **Added**: 2026-09-29
- **Topic**: Humanoid Loco-Manipulation
- **Authors**: Zhuo Li; Yiming Yao; Jim Tan; Mengjie Jing; Zhipeng Dong; Fei Chen
- **Year**: 2026
- **Type / source**: arXiv preprint; Robotics (`cs.RO`)
- **Version**: v1, 2026-09-15
- **Project URL**: 2026-09-15 · https://wholebodywam.github.io/
- **Paper URL**: 2026-09-15 · https://arxiv.org/abs/2609.16644
- **Identifier**: arXiv:2609.16644; DOI: [10.48550/arXiv.2609.16644](https://doi.org/10.48550/arXiv.2609.16644)
- **Tags**: `humanoid-robot` · `loco-manipulation` · `world-action-model` · `whole-body-control` · `visual-dynamics` · `generalization`
- **Notes**: WholeBodyWAM extends pre-trained world-action priors from arm-centric manipulation to humanoid loco-manipulation. It jointly predicts future visual dynamics, manipulation actions, and whole-body control intents, while grounding the semantics of heterogeneous whole-body controllers and coordinating their behavior.
- **Verification**: Bibliographic metadata, abstract-level method description, project link, and reported results were checked against arXiv. This is a preprint; the full paper has not yet been read.

## Perceptive Behavior Foundation Model: Adapting Human Motion Priors to Robot-Centric Terrain

- **Status**: `to-read`
- **Added**: 2026-09-29
- **Topic**: Humanoid Loco-Manipulation
- **Authors**: Zifan Wang; Yizhao Li; Teli Ma; Qiang Zhang; Yudong Fan; Hao Xu; Shuo Yang; Junwei Liang
- **Year**: 2026
- **Type / source**: CoRL 2026; RSS 2026 WCBM Workshop; arXiv preprint; Robotics (`cs.RO`)
- **Version**: v2, 2026-06-15 (v1 submitted 2026-06-06)
- **Project URL**: 2026-06-06 · https://acodedog.github.io/perceptive-bfm/
- **Paper URL**: 2026-06-06 · https://arxiv.org/abs/2606.08059
- **Repository URL**: 2026-06-06 · https://github.com/Mondo-Robotics/PMT
- **Identifier**: arXiv:2606.08059; DOI: [10.48550/arXiv.2606.08059](https://doi.org/10.48550/arXiv.2606.08059)
- **Tags**: `humanoid-robot` · `perceptive-locomotion` · `behavior-foundation-model` · `human-motion-prior` · `terrain-adaptation` · `reinforcement-learning` · `whole-body-control`
- **Notes**: Perceptive BFM grounds raw human-motion references in robot-centric terrain perception. Its terrain-conformal reference synthesis pipeline generates terrain-compatible supervision offline; a PPO-trained teacher is then distilled into an identity-gated Transformer student that adapts contacts, posture, clearance, and timing while preserving the original motion command interface. The released implementation targets the Unitree G1.
- **Verification**: Title, authors, submission history, venue information, arXiv identifier, project page, and public code repository were cross-checked against arXiv and the official project resources. The paper is listed as CoRL 2026 on the project page; the full paper has not yet been read.

## LadderMan: Learning Humanoid Perceptive Ladder Climbing

- **Status**: `to-read`
- **Added**: 2026-08-28
- **Topic**: Humanoid Loco-Manipulation
- **Authors**: Siheng Zhao; Yuanhang Zhang; Ziqi Lu; Pieter Abbeel; Rocky Duan; Koushil Sreenath; Yue Wang; C. Karen Liu; Guanya Shi
- **Year**: 2026
- **Type / source**: arXiv preprint; Robotics (`cs.RO`), Artificial Intelligence (`cs.AI`), Computer Vision and Pattern Recognition (`cs.CV`), Machine Learning (`cs.LG`)
- **Version**: v1, 2026-06-04
- **Project URL**: 2026-06-04 · https://ladderman-robot.github.io/
- **Paper URL**: 2026-06-04 · https://arxiv.org/abs/2606.05873
- **Repository URL**: 2026-06-04 · https://github.com/amazon-far/LadderMan
- **Identifier**: arXiv:2606.05873; DOI: [10.48550/arXiv.2606.05873](https://doi.org/10.48550/arXiv.2606.05873)
- **Tags**: `humanoid-robot` · `ladder-climbing` · `visuomotor-policy` · `imitation-learning` · `reinforcement-learning` · `sim-to-real` · `whole-body-control`
- **Notes**: LadderMan unifies perceptive ladder climbing and on-ladder manipulation. It learns multiple climbing experts from a single reference motion through hybrid motion tracking, distills them into a depth-based policy with imitation and reinforcement learning, and uses vision foundation models to reduce the sim-to-real perception gap.
- **Verification**: Bibliographic metadata was cross-checked against arXiv and the project page. This is a preprint; the full paper has not yet been read.

## Dyna-2: A 1-Million-Hour Scaling Law for World-Action Models

- **Status**: `to-read`
- **Added**: 2026-09-04
- **Topic**: Video-Action World Models
- **Authors**: Dyna Robotics
- **Year**: 2026 (August 2026)
- **Type / source**: Company research article / technical report; Dyna Robotics
- **Original URL**: 2026-08 · https://www.dyna.co/dyna-2
- **Paper URL**: No standalone PDF or arXiv version identified
- **Identifier**: No DOI or arXiv ID identified
- **Tags**: `robot-learning` · `robotic-manipulation` · `world-action-model` · `human-video` · `scaling-laws` · `cross-embodiment-transfer` · `video-diffusion` · `flow-matching`
- **Notes**: Dyna-2 is presented as a world-action model with a video-diffusion backbone pretrained on more than one million hours of first-person human manipulation video. The article studies data scaling from 1,000 to 1,000,000 hours, human-to-robot cross-embodiment transfer, and the contribution of video-prediction objectives to generalization.
- **Verification**: Title, institutional authorship, publication month, suggested citation, architecture, and experiment scope were checked against the official article. No standalone paper, arXiv record, DOI, code release, or peer-review record was identified. Scaling and performance claims are self-reported by Dyna Robotics.

## Zero-WAM: In-Context World-Action Modeling from Human Videos for Open-Ended Task Generalization

- **Status**: `to-read`
- **Added**: 2026-08-28
- **Topic**: Video-Action World Models
- **Authors**: Jiaming Zhou; Qihang Zhang; Gangwei Xu; Cunxin Fan; Yujie Zhao; Ruilin Wang; Yiming Luo; Shuai Yang; Xing Zhu; Yujun Shen; Junwei Liang; Yinghao Xu
- **Year**: 2026
- **Type / source**: arXiv preprint; Robotics (`cs.RO`), Computer Vision and Pattern Recognition (`cs.CV`)
- **Version**: v2, 2026-08-27 (v1 submitted 2026-08-26)
- **Project URL**: 2026-08-26 · https://robbyant-research.github.io/Zero-WAM/
- **Paper URL**: 2026-08-26 · https://arxiv.org/abs/2608.26103
- **Repository URL**: 2026-08-26 · https://github.com/robbyant-research/Zero-WAM
- **Identifier**: arXiv:2608.26103; DOI: [10.48550/arXiv.2608.26103](https://doi.org/10.48550/arXiv.2608.26103)
- **Tags**: `robot-learning` · `robotic-manipulation` · `world-action-model` · `in-context-learning` · `human-video`
- **Notes**: Zero-WAM uses human demonstration videos as in-context task specifications and trains a causal video-action model for zero-shot generalization to unseen tasks. The paper also introduces the HumanGen data-generation pipeline and an in-context future-chunk prediction objective.
- **Verification**: Bibliographic metadata was cross-checked against arXiv and the project page. This is a preprint; the full paper has not yet been read.

## LingBot-VA: Causal World Modeling for Robot Control

- **Status**: `to-read`
- **Added**: 2026-09-01
- **Topic**: Video-Action World Models
- **Authors**: Lin Li; Qihang Zhang; Yiming Luo; Shuai Yang; Ruilin Wang; Fei Han; Mingrui Yu; Zelin Gao; Nan Xue; Xing Zhu; Yujun Shen; Yinghao Xu
- **Year**: 2026
- **Type / source**: RSS 2026; arXiv preprint; Computer Vision and Pattern Recognition (`cs.CV`), Robotics (`cs.RO`)
- **Version**: v2, 2026-03-22 (v1 submitted 2026-01-29)
- **Project URL**: 2026-01-29 · https://technology.robbyant.com/lingbot-va
- **Paper URL**: 2026-01-29 · https://arxiv.org/abs/2601.21998
- **Repository URL**: 2026-01-29 · https://github.com/Robbyant/lingbot-va
- **Models and datasets URL**: 2026-01-29 · https://huggingface.co/collections/robbyant/lingbot-va
- **Identifier**: arXiv:2601.21998; DOI: [10.48550/arXiv.2601.21998](https://doi.org/10.48550/arXiv.2601.21998)
- **Tags**: `robot-learning` · `robotic-manipulation` · `video-action-model` · `world-model` · `autoregressive-diffusion` · `mixture-of-transformers` · `long-horizon`
- **Notes**: LingBot-VA is an autoregressive video-action world model that jointly learns future-frame prediction and action execution in a unified interleaved sequence. Its design includes a shared visual-action latent space, a Mixture-of-Transformers architecture, closed-loop rollouts updated with real observations, and asynchronous action prediction and motor execution.
- **Verification**: Title, authors, versions, subject classifications, RSS 2026 status, project page, repository, and Hugging Face resources were cross-checked against arXiv and official Robbyant pages. The full paper has not yet been read.

## Introducing S1: In-Context Learning for Robotics

- **Status**: `to-read`
- **Added**: 2026-08-28
- **Topic**: In-Context Robot Learning
- **Authors**: Skild AI
- **Year**: 2026 (August 2026)
- **Type / source**: Company research article; Skild AI
- **Original URL**: 2026-08 · https://www.skild.ai/blogs/s1
- **Paper URL**: No public paper identified
- **Identifier**: No DOI or arXiv ID identified
- **Tags**: `robot-learning` · `robotic-manipulation` · `foundation-model` · `in-context-learning` · `video-demonstration` · `long-horizon`
- **Notes**: S1 is presented as a robot foundation model that uses a single video demonstration as context and performs seen or unseen tasks without fine-tuning or post-training. The article includes long-horizon demonstrations lasting up to roughly ten minutes.
- **Verification**: Title, institutional authorship, publication month, and suggested citation were checked against the official Skild AI article. No standalone paper, DOI, arXiv record, public method specification, or peer-review record was identified. Benchmark results are self-reported by Skild AI.

## Precise Manipulation with Efficient Online RL

- **Status**: `to-read`
- **Added**: 2026-09-02
- **Topic**: Online Reinforcement Learning
- **Authors**: Charles Xu; Jost Tobias Springenberg; Michael Equi; Ali Amin; Adnan Esmail; Sergey Levine; Liyiming Ke
- **Year**: 2026
- **Type / source**: Research paper and project article; Physical Intelligence
- **Project URL**: 2026-03-19 · https://www.pi.website/research/rlt
- **Paper URL**: 2026-03-19 · https://www.pi.website/download/rlt.pdf
- **Identifier**: No DOI or arXiv ID identified
- **Tags**: `robot-learning` · `robotic-manipulation` · `vision-language-action` · `online-reinforcement-learning` · `sample-efficient-rl` · `precision-manipulation` · `actor-critic`
- **Notes**: The work introduces RL tokens, compact state representations extracted from a pretrained vision-language-action model and consumed by a lightweight actor-critic that can be updated on the robot. The online policy edits VLA action chunks using off-policy reinforcement learning, reference-action regularization, and optional human intervention.
- **Verification**: Title, authors, publication date, paper PDF, and method overview were checked against the official Physical Intelligence research page. No arXiv record, DOI, public code, or independent peer-review record was identified. The full paper has not yet been read.

## LightNav-0: Eliciting VLM Spatial Intelligence for Generalist Embodied Navigation

- **Status**: `to-read`
- **Added**: 2026-09-01
- **Topic**: Generalist Navigation
- **Authors**: Light Origins Team
- **Year**: 2026
- **Type / source**: Technical report and open-source project; Light Origins
- **Project URL**: 2026-09-01 · https://www.lightorigins.com/en/blog/lightnav-0
- **Report URL**: 2026-09-01 · https://static.lightorigins.com/website/reports/lightnav-0-technical-report_02cfc2f.pdf
- **Repository URL**: 2026-09-01 · https://github.com/lightorigins/LightNav-0
- **Model URL**: 2026-09-01 · https://huggingface.co/LightOriginsHQ/LightNav-0
- **Identifier**: No DOI or arXiv ID identified
- **Tags**: `embodied-navigation` · `vision-language-model` · `vision-language-action` · `real2sim2real` · `zero-shot-generalization` · `cross-embodiment` · `reinforcement-learning`
- **Notes**: LightNav-0 is a generalist embodied-navigation model based on Qwen3-VL and aligned through embodied-reasoning mid-training, embodied supervised fine-tuning, and online reinforcement learning. Its Real2Sim2Real data engine converts internet scenes into navigation experience, while one model targets instruction following, open-vocabulary object navigation, and visual tracking across several robot embodiments.
- **Verification**: Title, institutional authorship, publication date, technical report, GitHub repository, and Hugging Face model were checked against official Light Origins resources. This is an institutional technical report rather than an arXiv or peer-reviewed paper; benchmark results are primarily reported by the publisher.

## Alec Helbling: Blogs and Visualizations

- **Status**: `to-read`
- **Added**: 2026-09-03
- **Topic**: Generative Modeling and Visualizations
- **Authors**: Alec Helbling
- **Year**: Continuously updated (the index currently covers 2025–2026)
- **Type / source**: Personal technical blog and interactive visualization index
- **Original URL**: Added 2026-09-03 · https://alechelbling.com/blog.html
- **Identifier**: No DOI or arXiv ID
- **Tags**: `machine-learning` · `generative-modeling` · `diffusion-models` · `rectified-flow` · `transformers` · `dimensionality-reduction` · `interactive-visualization`
- **Notes**: A continuously updated technical-resource index covering Rectified Flow, diffusion models, Isomap, KV caching, Stein variational gradient descent, conditional independence sampling, and vector fields. It serves as background material for generative modeling, sampling, and mathematical concepts used in robot learning.
- **Verification**: The page title, author, and current blog and visualization entries were checked against the rendered site. This is a personal resource index rather than a single paper or peer-reviewed source; individual subpages should be verified when read.
