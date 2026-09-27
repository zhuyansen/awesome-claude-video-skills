# Awesome Claude Video Skills

[English](README.md)

让 **Claude Code、Codex 等编程 agent 做视频**的开源 skill 和工具包:HyperFrames、Remotion、动效、剪辑、讲解、数字人。共 169 个仓库,每个都由 [Agent Skills Hub](https://agentskillshub.top?utm_source=github&utm_medium=awesome-list) 读过 README 并做了安全评级。

带类型筛选的在线页面:**[https://agentskillshub.top/best/opus-5-5-video/](https://agentskillshub.top/best/opus-5-5-video/?utm_source=github&utm_medium=awesome-list)** · 每 8 小时刷新

## 目录

- [用 Claude Opus 5.5 做出来的](#made-with-opus-55)
- [🧱 框架与通用工具包](#type-general) (29)
- [📣 产品宣传与演示](#type-promo) (26)
- [🎓 讲解科普](#type-explainer) (32)
- [✂️ 剪辑与后期](#type-editing) (35)
- [📱 短视频与口播](#type-shorts) (19)
- [🧑‍💼 数字人](#type-avatar) (4)
- [📖 故事与动画](#type-story) (12)
- [🎞 动效与 Logo](#type-motion) (10)
- [🎵 音乐视频](#type-music) (2)

## 什么样的仓库能上榜

1. 它做视频、剪视频或做动效。3D 网页、提示词合集不算。
2. 它是给 agent 用的:skill、插件、MCP 服务器,或为 agent 写的工具包。
3. 它有 README。没有 README 就没法评级。
4. 50 星及以上只看是否切题;50 星以下还要过 README 质量线(展示成品、一条命令上手、说清产出、文档完整),并且至少 5 星——点名 Claude Opus 5.5 的除外。

这些问题由决策模型逐个读 README 回答,不是人工挑选。卡在线上的仓库可能判到任一边,归错了请提 issue。

<a id="made-with-opus-55"></a>
## 用 Claude Opus 5.5 做出来的

README 写明用这个模型做的项目。

| 仓库 | 星数 | 做什么 | 安全评级 |
|---|---:|---|---|
| [JohnHeibel/PDoomVideo](https://github.com/JohnHeibel/PDoomVideo) | 1.1k | Claude Opus 5.5 音乐视频《I'm Upping My P(doom)》的源代码 | [*待评级*](https://agentskillshub.top/skill/JohnHeibel/PDoomVideo/?utm_source=github&utm_medium=awesome-list) |
| [JohnHeibel/ClaudeAnimationBase](https://github.com/JohnHeibel/ClaudeAnimationBase) | 414 | 用 Claude 制作手绘卡通动画的入门套件：p5.js + p5.brush、Clawd 角色、31 种表演情绪和给模型的指南 | [*待评级*](https://agentskillshub.top/skill/JohnHeibel/ClaudeAnimationBase/?utm_source=github&utm_medium=awesome-list) |
| [lemomo-ai/lemo-opuscar](https://github.com/lemomo-ai/lemo-opuscar) | 174 | Opus 5.5 x 39 种影片风格：风格提示词 + 纯代码样片 + 导演与技术指南 | [SAFE](https://agentskillshub.top/skill/lemomo-ai/lemo-opuscar/?utm_source=github&utm_medium=awesome-list) |
| [ledbetterljoshua/functional-emotions-video](https://github.com/ledbetterljoshua/functional-emotions-video) | 45 | Claude Opus 5.5 制作的《Functional Emotions》手绘风音乐视频：自研 GPU 笔触渲染器、7 个并行章节 agent | [*待评级*](https://agentskillshub.top/skill/ledbetterljoshua/functional-emotions-video/?utm_source=github&utm_medium=awesome-list) |

<a id="type-general"></a>
## 🧱 框架与通用工具包

[在在线页面打开这一类,按星数排序 →](https://agentskillshub.top/best/opus-5-5-video/?utm_source=github&utm_medium=awesome-list#type-general)

| 仓库 | 星数 | 做什么 | 安全评级 |
|---|---:|---|---|
| [calesthio/OpenMontage](https://github.com/calesthio/OpenMontage) | 61.4k | 开源的 agent 视频制作系统：12 条制作流水线、100+ 工具、700+ skill 与知识文件 | [SAFE](https://agentskillshub.top/skill/calesthio/OpenMontage/?utm_source=github&utm_medium=awesome-list) |
| [heygen-com/hyperframes](https://github.com/heygen-com/hyperframes) | 53.4k | 写 HTML，渲染成视频，为 agent 而建 | [SAFE](https://agentskillshub.top/skill/heygen-com/hyperframes/?utm_source=github&utm_medium=awesome-list) |
| [hypit-ai/hypit](https://github.com/hypit-ai/hypit) | 16.4k | 用 AI agent 复刻爆款视频的完整流程：换脸、换文案、换 B-roll，一条命令产出 100 个变体 | *待评级* |
| [remotion-dev/skills](https://github.com/remotion-dev/skills) | 4.7k | Agent Skills 合集 | [SAFE](https://agentskillshub.top/skill/remotion-dev/skills/?utm_source=github&utm_medium=awesome-list) |
| [NarratorAI-Studio/narrator-ai-cli-skill](https://github.com/NarratorAI-Studio/narrator-ai-cli-skill) | 2.7k | AI 解说大师 Agent skill，封装 narrator-ai-cli 供 Claude、Codex 等工具调用 | [SAFE](https://agentskillshub.top/skill/NarratorAI-Studio/narrator-ai-cli-skill/?utm_source=github&utm_medium=awesome-list) |
| [digitalsamba/claude-code-video-toolkit](https://github.com/digitalsamba/claude-code-video-toolkit) | 2.1k | 面向 Claude Code 的 AI 原生视频制作工具包 | [SAFE](https://agentskillshub.top/skill/digitalsamba/claude-code-video-toolkit/?utm_source=github&utm_medium=awesome-list) |
| [vibe-motion/skills](https://github.com/vibe-motion/skills) | 1.3k | vibe motion 的 agent skills | [SAFE](https://agentskillshub.top/skill/vibe-motion/skills/?utm_source=github&utm_medium=awesome-list) |
| [bangtutorial/bang-motion](https://github.com/bangtutorial/bang-motion) | 524 | 浏览器动态图形 agent skill：片头、宣传片、动态排版和五种讲解风格，输出单个 index.html | [SAFE](https://agentskillshub.top/skill/bangtutorial/bang-motion/?utm_source=github&utm_medium=awesome-list) |
| [iart-ai/motion-skills](https://github.com/iart-ai/motion-skills) | 516 | 50 个开源 skill，教 AI 编程 agent 做动态图形、动画和视频，分 14 个安装包 | [SAFE](https://agentskillshub.top/skill/iart-ai/motion-skills/?utm_source=github&utm_medium=awesome-list) |
| [kangarooking/director-skills](https://github.com/kangarooking/director-skills) | 147 | 导演 Skill：面向 AI 视频创作的开源 Agent Skills | [SAFE](https://agentskillshub.top/skill/kangarooking/director-skills/?utm_source=github&utm_medium=awesome-list) |
| [video-db/skills](https://github.com/video-db/skills) | 121 | 给 agent 用的服务端视频工作流：导入、理解、搜索、剪辑、流式播放 | [SAFE](https://agentskillshub.top/skill/video-db/skills/?utm_source=github&utm_medium=awesome-list) |
| [jhartquist/claude-remotion-kickstart](https://github.com/jhartquist/claude-remotion-kickstart) | 120 | 用 Claude Code 和 Remotion 以编程方式制作视频 | [*待评级*](https://agentskillshub.top/skill/jhartquist/claude-remotion-kickstart/?utm_source=github&utm_medium=awesome-list) |
| [Johnson-Jia/video-clipforge](https://github.com/Johnson-Jia/video-clipforge) | 39 | AI 短视频制作系统：给一个想法，完成写稿、配音、画面和成片，基于 Claude Code + HyperFrames | [SAFE](https://agentskillshub.top/skill/Johnson-Jia/video-clipforge/?utm_source=github&utm_medium=awesome-list) |
| [iart-ai/motion-design-skills](https://github.com/iart-ai/motion-design-skills) | 33 | 可安装的 Claude Code skills，涵盖动效设计基础、引擎和品牌元素，含 After Effects、Remotion 等 | *待评级* |
| [zhouyuechuan2025-ui/ai-self-media-video-packaging-skill](https://github.com/zhouyuechuan2025-ui/ai-self-media-video-packaging-skill) | 32 | 开放的 Agent Skill：用 Remotion（可选 HyperFrames）包装口播视频，含可安全 seek 的动效和线条插画 | *待评级* |
| [GordenSun/react-bits-video](https://github.com/GordenSun/react-bits-video) | 28 | 整合 react-bits、Remotion 和 HyperFrames 的视频生成 Skill | *待评级* |
| [bbylw/hyperframes-cn](https://github.com/bbylw/hyperframes-cn) | 28 | HyperFrames 开源框架：将 HTML、CSS、媒体与可定位动画转为确定性的 MP4 视频，可通过 CLI 或 skills 使用 | *待评级* |
| [smwbev/framewright](https://github.com/smwbev/framewright) | 21 | 完全用代码生成短视频的 agent skill + 模板：单个 HTML 文件，每一帧都是纯函数 | [SAFE](https://agentskillshub.top/skill/smwbev/framewright/?utm_source=github&utm_medium=awesome-list) |
| [doublesq97-ui/su-card-to-video](https://github.com/doublesq97-ui/su-card-to-video) | 18 | 基于 HyperFrames、GSAP 和 FFmpeg 的极简 HTML/CSS 卡片转视频入门 skill | *待评级* |
| [gloweaseco-leo/hyperdirector](https://github.com/gloweaseco-leo/hyperdirector) | 17 | 基于 HyperFrames 的结构化 AI 视频制作 Hermes Skill Pack：brief → 分镜 → HTML → lint/渲染 | *待评级* |
| [resemble-ai/remotion-resemble-skill](https://github.com/resemble-ai/remotion-resemble-skill) | 9 |  | *待评级* |
| [patraxo/ltx2-vidgen-skill](https://github.com/patraxo/ltx2-vidgen-skill) | 8 | 通过 Claude Code skill 在自己的 Modal GPU 上自托管 LTX-2.3：t2v、i2v、关键帧、v2v 和同步音频 | [*待评级*](https://agentskillshub.top/skill/patraxo/ltx2-vidgen-skill/?utm_source=github&utm_medium=awesome-list) |
| [molkex/mcp-flow-google](https://github.com/molkex/mcp-flow-google) | 7 | Google Flow 的 MCP 服务器：在 Claude Code、Cursor 等客户端里用 Veo 生成视频、Nano Banana 生成图片 | [SAFE](https://agentskillshub.top/skill/molkex/mcp-flow-google/?utm_source=github&utm_medium=awesome-list) |
| [vibe-motion/remotion-starter](https://github.com/vibe-motion/remotion-starter) | 7 | 用 Claude Code 指挥 Remotion 出视频的工作台脚手架：三层架构 + hooks 守规矩 + skills 编排流程，陈与小金维护 | [*待评级*](https://agentskillshub.top/skill/vibe-motion/remotion-starter/?utm_source=github&utm_medium=awesome-list) |
| [VasiniDevi/motion-skills](https://github.com/VasiniDevi/motion-skills) | 6 | 给 AI agent 用的编程式动效设计 skills：用 Python 做动态图形、动态排版、数据可视化和幻灯片 | *待评级* |
| [chenyuxiaojin/cyxj-remotion-starter](https://github.com/chenyuxiaojin/cyxj-remotion-starter) | 6 | 用 Claude Code 指挥 Remotion 出视频的工作台脚手架：三层架构 + hooks 守规矩 + skills 编排流程，作者陈与小金 | [SAFE](https://agentskillshub.top/skill/chenyuxiaojin/cyxj-remotion-starter/?utm_source=github&utm_medium=awesome-list) |
| [davidcervinka/vibe-editing](https://github.com/davidcervinka/vibe-editing) | 6 | 视频版的 vibe coding：通过和 Claude Code 对话完成发布片、活动回顾片和 Reels 的剪辑、配乐与交付 | *待评级* |
| [iart-ai/data-animation-skills](https://github.com/iart-ai/data-animation-skills) | 6 | Claude Code 的数据视频/动态信息图 skills：把 CSV 变成动态图表，每一帧数字都准确 | *待评级* |
| [magichourhq/skills](https://github.com/magichourhq/skills) | 6 | 面向 Codex、Claude Code 等 agent 的 AI 媒体生成 skills，覆盖图片、视频和音频工作流 | [SAFE](https://agentskillshub.top/skill/magichourhq/skills/?utm_source=github&utm_medium=awesome-list) |

<a id="type-promo"></a>
## 📣 产品宣传与演示

[在在线页面打开这一类,按星数排序 →](https://agentskillshub.top/best/opus-5-5-video/?utm_source=github&utm_medium=awesome-list#type-promo)

| 仓库 | 星数 | 做什么 | 安全评级 |
|---|---:|---|---|
| [Vincentwei1021/video-shotcraft](https://github.com/Vincentwei1021/video-shotcraft) | 9.7k | 用 Remotion 做电影感产品视频的 skill：152 张镜头配方卡、209 个动效预览和一套模板 | [SAFE](https://agentskillshub.top/skill/Vincentwei1021/video-shotcraft/?utm_source=github&utm_medium=awesome-list) |
| [geekjourneyx/hyperframes-motion-director](https://github.com/geekjourneyx/hyperframes-motion-director) | 447 | 中文优先的 HyperFrames 动效视频制作 Agent Skill，素材可来自文章、产品、网站和 README | [SAFE](https://agentskillshub.top/skill/geekjourneyx/hyperframes-motion-director/?utm_source=github&utm_medium=awesome-list) |
| [op7418/guizang-product-video-skill](https://github.com/op7418/guizang-product-video-skill) | 441 | 归藏 product video skill：复用真实产品组件和设计语言，用代码制作软件更新宣传片，支持 Claude Code 和 Codex | [SAFE](https://agentskillshub.top/skill/op7418/guizang-product-video-skill/?utm_source=github&utm_medium=awesome-list) |
| [tugrawork-creator/saas-motion-kit](https://github.com/tugrawork-creator/saas-motion-kit) | 128 | 用 HyperFrames + Claude Code 为软件产品做宣传和动效视频：调性矩阵、多样性审查、24 种转场、100 个分镜主题 | [SAFE](https://agentskillshub.top/skill/tugrawork-creator/saas-motion-kit/?utm_source=github&utm_medium=awesome-list) |
| [leosssvip-dot/remotion-ad-video-skill](https://github.com/leosssvip-dot/remotion-ad-video-skill) | 108 | 让 AI 编程 agent 根据 URL 创建 Remotion 广告视频项目，无需视频生成模型 | [*待评级*](https://agentskillshub.top/skill/leosssvip-dot/remotion-ad-video-skill/?utm_source=github&utm_medium=awesome-list) |
| [kangarooking/promo-creator-skills](https://github.com/kangarooking/promo-creator-skills) | 101 | 产品宣传视频创作 Skills：从产品判断、分镜、素材、HyperFrames 剪辑到 BGM 设计的完整 agent 工作流 | [*待评级*](https://agentskillshub.top/skill/kangarooking/promo-creator-skills/?utm_source=github&utm_medium=awesome-list) |
| [bestagentkits/motion-video-skill](https://github.com/bestagentkits/motion-video-skill) | 69 | 用 HyperFrames（HTML + GSAP）做卡点 1080p 动态图形视频的 agent skill，含 AI 配音、字幕、音效和配乐 | [*待评级*](https://agentskillshub.top/skill/bestagentkits/motion-video-skill/?utm_source=github&utm_medium=awesome-list) |
| [norahe0304-art/30x-video](https://github.com/norahe0304-art/30x-video) | 63 | 输入一个 URL，输出产品发布视频的 Claude Code skill（Remotion + React），内置 16 条审美准则，不用模板 | [SAFE](https://agentskillshub.top/skill/norahe0304-art/30x-video/?utm_source=github&utm_medium=awesome-list) |
| [trunghaiy/appshot](https://github.com/trunghaiy/appshot) | 43 | 用 TypeScript 配置生成 App Store 和 Google Play 预览视频与截图，基于 Remotion，附带 agent skills | [SAFE](https://agentskillshub.top/skill/trunghaiy/appshot/?utm_source=github&utm_medium=awesome-list) |
| [BayramAnnakov/remotion-video-director](https://github.com/BayramAnnakov/remotion-video-director) | 41 | 交互式 Claude Code skill，通过专家引导的讨论来制作 Remotion 视频 | [*待评级*](https://agentskillshub.top/skill/BayramAnnakov/remotion-video-director/?utm_source=github&utm_medium=awesome-list) |
| [kingselyjoe/video-shotcraft-dsh](https://github.com/kingselyjoe/video-shotcraft-dsh) | 35 | 面向 DeepSeek Harness 的电影感产品视频 Agent Skill，含 152 张镜头配方卡、Remotion 模板和音频资产 | *待评级* |
| [mattivilola/brag-codex](https://github.com/mattivilola/brag-codex) | 32 | latent-spaces/brag 的 Codex 兼容版，用于制作 HyperFrames 发布视频 | *待评级* |
| [gorkem-bwl/onboarding-video-generator](https://github.com/gorkem-bwl/onboarding-video-generator) | 31 | 用 Remotion 制作栏宽尺寸 Web 应用引导视频的 Claude Code skill | *待评级* |
| [Finderchangchang/promo-video-skill](https://github.com/Finderchangchang/promo-video-skill) | 29 | 让 DeepSeek 这类便宜模型也能用 Remotion 做竖版宣传片的 skill，覆盖软件、餐饮、电商、教育、美业、文旅，中英双语 | [*待评级*](https://agentskillshub.top/skill/Finderchangchang/promo-video-skill/?utm_source=github&utm_medium=awesome-list) |
| [new-xp/ultrademo](https://github.com/new-xp/ultrademo) | 29 | 为网站、SaaS 应用等自动生成演示视频的工具，通过 Claude Code skill 执行 | [*待评级*](https://agentskillshub.top/skill/new-xp/ultrademo/?utm_source=github&utm_medium=awesome-list) |
| [Arman-Luthra/aftr](https://github.com/Arman-Luthra/aftr) | 22 | After Effects 版的 Puppeteer：用 Claude Code 操作 AE 制作可用于生产的视频 | *待评级* |
| [AmazingAng/ccvideo](https://github.com/AmazingAng/ccvideo) | 20 | 基于真实界面采集制作 Claude 风格宣传视频的 Claude Code skill（Remotion） | [*待评级*](https://agentskillshub.top/skill/AmazingAng/ccvideo/?utm_source=github&utm_medium=awesome-list) |
| [derrickgong87/demo-video-creation-skill](https://github.com/derrickgong87/demo-video-creation-skill) | 19 | 可复用的 Codex skill：根据公司 URL、截图和产品流程制作 SaaS 与产品演示视频 | [*待评级*](https://agentskillshub.top/skill/derrickgong87/demo-video-creation-skill/?utm_source=github&utm_medium=awesome-list) |
| [dlazy-ai/ai-product-video](https://github.com/dlazy-ai/ai-product-video) | 14 | 把产品做成电影感宣传视频的 agent skill：152 张镜头配方卡、209 种风格变体、149 个音效、10 镜头模板 | [SAFE](https://agentskillshub.top/skill/dlazy-ai/ai-product-video/?utm_source=github&utm_medium=awesome-list) |
| [kiki-lgtm-dot/cinematic-product-promo-skill](https://github.com/kiki-lgtm-dot/cinematic-product-promo-skill) | 14 | Remotion 产品宣传片 Agent Skill：150+ 镜头配方、200+ 动效预览、2.5D 运镜、节奏剪辑与声音设计 | *待评级* |
| [smit-vanani/claude-promo-video](https://github.com/smit-vanani/claude-promo-video) | 13 | 用 Remotion 把网站 URL 做成卡点产品宣传视频，场景对齐音乐起音，渲染自检，输出横竖屏和缩略图 | [*待评级*](https://agentskillshub.top/skill/smit-vanani/claude-promo-video/?utm_source=github&utm_medium=awesome-list) |
| [memex-lab/product-launch-video-skill](https://github.com/memex-lab/product-launch-video-skill) | 12 | 用 Remotion 制作电影感产品发布视频的 AI agent skill | [*待评级*](https://agentskillshub.top/skill/memex-lab/product-launch-video-skill/?utm_source=github&utm_medium=awesome-list) |
| [iart-ai/ad-video-skills](https://github.com/iart-ai/ad-video-skills) | 8 | Claude Code 的广告视频 skills：把一个动态图形模板批量做成符合品牌、可 A/B 测试的广告素材、发布片和用户证言短片 | *待评级* |
| [ChenShuo2004/cs-shotcraft-skill](https://github.com/ChenShuo2004/cs-shotcraft-skill) | 5 | CS Skills 产品宣传片 skill：真实产品界面、镜头表运镜、152 张镜头配方卡与 Ink Press 模板，Remotion 出片 | *待评级* |
| [mrieck/demoday-claude-plugin](https://github.com/mrieck/demoday-claude-plugin) | 5 | 为项目制作演示视频的 Claude Code 插件：操作浏览器/CLI 录制，再用 Remotion 等合成带转场的视频 | *待评级* |
| [opus-pro/opus-video-studio](https://github.com/opus-pro/opus-video-studio) | 5 | 面向 Codex 和 Claude Code 的 Opus Video Tools，含 43 个开源视频模板和动效组件、画廊预览和演示 | *待评级* |

<a id="type-explainer"></a>
## 🎓 讲解科普

[在在线页面打开这一类,按星数排序 →](https://agentskillshub.top/best/opus-5-5-video/?utm_source=github&utm_medium=awesome-list#type-explainer)

| 仓库 | 星数 | 做什么 | 安全评级 |
|---|---:|---|---|
| [Alisa0808/vox-director](https://github.com/Alisa0808/vox-director) | 2.0k | 把一个选题做成 Vox 风格纸拼贴讲解或广告视频的 agent skill，基于 Atlas Cloud + ffmpeg 全流程自动化 | [SAFE](https://agentskillshub.top/skill/Alisa0808/vox-director/?utm_source=github&utm_medium=awesome-list) |
| [Vincentwei1021/video-talkcraft](https://github.com/Vincentwei1021/video-talkcraft) | 1.2k | 做配音驱动讲解视频的 agent skill：逐词配音同步、109 张动效配方卡、Remotion 渲染 | [SAFE](https://agentskillshub.top/skill/Vincentwei1021/video-talkcraft/?utm_source=github&utm_medium=awesome-list) |
| [adithya-s-k/manim_skill](https://github.com/adithya-s-k/manim_skill) | 1.1k | 用 Manim 制作 3Blue1Brown 风格动画的 agent skills | [SAFE](https://agentskillshub.top/skill/adithya-s-k/manim_skill/?utm_source=github&utm_medium=awesome-list) |
| [wshuyi/remotion-video-skill](https://github.com/wshuyi/remotion-video-skill) | 383 | 用 Remotion 框架以编程方式制作视频的 Claude Code Skill | [CAUTION](https://agentskillshub.top/skill/wshuyi/remotion-video-skill/?utm_source=github&utm_medium=awesome-list) |
| [shuyicc/MathLens](https://github.com/shuyicc/MathLens) | 360 | 数学题视频讲解 Agent Skill：粘贴一道题，自动完成分析、可视化讲解、配音脚本到 Manim 动画视频 | [SAFE](https://agentskillshub.top/skill/shuyicc/MathLens/?utm_source=github&utm_medium=awesome-list) |
| [hi-nikola/hand-drawn-explainer-video-nikola](https://github.com/hi-nikola/hand-drawn-explainer-video-nikola) | 346 | 中文手绘知识讲解视频 Codex Skill：逐笔故事、双语义岛、让怪诞小黑动起来与程序动画 | [SAFE](https://agentskillshub.top/skill/hi-nikola/hand-drawn-explainer-video-nikola/?utm_source=github&utm_medium=awesome-list) |
| [Anil-matcha/vox-ai-motion-graphics-generator](https://github.com/Anil-matcha/vox-ai-motion-graphics-generator) | 223 | 把任意选题做成 Vox 风格纸拼贴讲解视频的 agent skill，脚本、关键帧、动画、配音、配乐和字幕全自动 | [SAFE](https://agentskillshub.top/skill/Anil-matcha/vox-ai-motion-graphics-generator/?utm_source=github&utm_medium=awesome-list) |
| [runesleo/claude-video-kit](https://github.com/runesleo/claude-video-kit) | 120 | Agent Skill + Remotion 流水线：brief/脚本 → 审核回执 → 带旁白的 9:16 讲解视频 | [SAFE](https://agentskillshub.top/skill/runesleo/claude-video-kit/?utm_source=github&utm_medium=awesome-list) |
| [sunxiayi/make-blender-education-video-skill](https://github.com/sunxiayi/make-blender-education-video-skill) | 45 | 用 Blender 制作经事实核查的电影感教学视频的 Codex 和 Claude Code skill | [*待评级*](https://agentskillshub.top/skill/sunxiayi/make-blender-education-video-skill/?utm_source=github&utm_medium=awesome-list) |
| [znyupup/knowledge-explainer-skill](https://github.com/znyupup/knowledge-explainer-skill) | 45 | 把一份 markdown 文稿自动生成讲解动画视频，基于 Remotion + AI Agent | *待评级* |
| [Anil-matcha/zack-d-films-ai-video-generator](https://github.com/Anil-matcha/zack-d-films-ai-video-generator) | 37 | 把选题做成 Zack D Films 风格 3D 动画短片的 agent skill，脚本、角色、关键帧、配音和字幕全自动 | [*待评级*](https://agentskillshub.top/skill/Anil-matcha/zack-d-films-ai-video-generator/?utm_source=github&utm_medium=awesome-list) |
| [santmun/video-vox](https://github.com/santmun/video-vox) | 32 | 用 Claude Code + Remotion 就任意主题制作 Vox 风格竖屏动画短视频（卡通 + 配音 + 音乐 + 音效） | *待评级* |
| [Mr-funny/hbg-douyin-code-explainer-video](https://github.com/Mr-funny/hbg-douyin-code-explainer-video) | 31 | HBG Codex skill：中文 9:16 HyperFrames 讲解视频，含对话 TTS、Whisper 同步、BGM 和成片视觉 QA | [SAFE](https://agentskillshub.top/skill/Mr-funny/hbg-douyin-code-explainer-video/?utm_source=github&utm_medium=awesome-list) |
| [vibe-motion/remotion-code-motion-explainer](https://github.com/vibe-motion/remotion-code-motion-explainer) | 31 | 制作连贯、可编辑的 Remotion 讲解视频的 AI Agent skill，作者 Bingo | [SAFE](https://agentskillshub.top/skill/vibe-motion/remotion-code-motion-explainer/?utm_source=github&utm_medium=awesome-list) |
| [iart-ai/explainer-video-skills](https://github.com/iart-ai/explainer-video-skills) | 26 | Claude Code 的讲解视频 skills：编写脚本、分镜并渲染带旁白的讲解视频、年度回顾和动态图解 | *待评级* |
| [Phantomlau3674/voxstylehub-steven](https://github.com/Phantomlau3674/voxstylehub-steven) | 24 | 独立的 Codex skill：制作 Vox 风格的编辑式拼贴知识视频，用 Remotion 确定性合成，可选生成式动效 | [*待评级*](https://agentskillshub.top/skill/Phantomlau3674/voxstylehub-steven/?utm_source=github&utm_medium=awesome-list) |
| [Mng-dev-ai/explainer-video](https://github.com/Mng-dev-ai/explainer-video) | 19 | 把任意主题做成带旁白动画讲解视频的 AI skill，本地运行、免费，支持 Claude Code / Codex / Cursor | [*待评级*](https://agentskillshub.top/skill/Mng-dev-ai/explainer-video/?utm_source=github&utm_medium=awesome-list) |
| [holy-templar/vox-animated-ad-mcp](https://github.com/holy-templar/vox-animated-ad-mcp) | 19 | 给 AI agent 用的 Vox 风格纸拼贴动画视频 skill，在对话中输入一句话即可生成讲解或广告视频 | [*待评级*](https://agentskillshub.top/skill/holy-templar/vox-animated-ad-mcp/?utm_source=github&utm_medium=awesome-list) |
| [aijiduonadegou/Paper-Cut](https://github.com/aijiduonadegou/Paper-Cut) | 16 | 无需视频模型的拼贴动画 skill：图像模型定稿、原图拆层与 HyperFrames 代码动画，做纸拼贴科普视频 | *待评级* |
| [chenyuxiaojin/cyxj-hyperframes](https://github.com/chenyuxiaojin/cyxj-hyperframes) | 16 | 开源的 HTML + GSAP 视频项目与可复用工具包，用于制作 Claude Code 教程视频，基于 HeyGen HyperFrames | *待评级* |
| [cclank/lanshu-html2video-skill](https://github.com/cclank/lanshu-html2video-skill) | 14 | 用 Codex 和 Remotion 把网页文章做成 1080p 视频 | *待评级* |
| [kakaxi12/vox-director-codex](https://github.com/kakaxi12/vox-director-codex) | 11 | 用 ImageGen、HyperFrames 和 MiniMax 旁白制作 Vox 风格编辑式纸拼贴视频的 Codex skill | *待评级* |
| [ssrajadh/paperview](https://github.com/ssrajadh/paperview) | 9 | 把论文、代码库等做成讲解视频，本地渲染 + TTS，Claude Code 插件 | *待评级* |
| [pjecuacion/script-to-video-skill](https://github.com/pjecuacion/script-to-video-skill) | 7 | 面向 HyperFrames 工作流的公开版脚本转视频 skill，路径已脱敏，示例不含密钥 | *待评级* |
| [ahmdd4vd/MotionCraft](https://github.com/ahmdd4vd/MotionCraft) | 6 | 让 AI agent 用 Remotion 制作简洁动态图形视频的 Agent Skill，一条命令安装 | [SAFE](https://agentskillshub.top/skill/ahmdd4vd/MotionCraft/?utm_source=github&utm_medium=awesome-list) |
| [jinjin1/scenewright](https://github.com/jinjin1/scenewright) | 6 | Claude Code 原生流水线：把源文本做成带旁白、Remotion 渲染的 YouTube 讲解视频，本地韩语 TTS | *待评级* |
| [sukai213/bilibili-ai-video](https://github.com/sukai213/bilibili-ai-video) | 6 | AI 科技测评视频制作与 B 站自动发布 Codex Skill：原创文案、Qwen3-TTS 配音、ffmpeg 剪辑、投稿 API 发布 | *待评级* |
| [BusyBee3333/animated-explainer-skills](https://github.com/BusyBee3333/animated-explainer-skills) | 5 | 把动画讲解视频做成单个 HTML 文件的 Claude Code skills：GSAP 编排模式、重叠检查器、ElevenLabs 配音 | *待评级* |
| [centraltowerlabs/diagram-tour](https://github.com/centraltowerlabs/diagram-tour) | 5 | 为代码库（或其他复杂系统）生成讲解导览视频的 Claude Skill | *待评级* |
| [coding-ax/docvideoer](https://github.com/coding-ax/docvideoer) | 5 | 文档转视频 skills：把文档 URL、网页文章、Markdown 或文本转成带中文旁白的 Remotion 讲解视频 | *待评级* |
| [cymcymcymcym/notes-to-video](https://github.com/cymcymcymcym/notes-to-video) | 5 | 把笔记做成 3Blue1Brown 风格的动画讲解视频，Claude Code skill + Manim + TTS + ffmpeg | [*待评级*](https://agentskillshub.top/skill/cymcymcymcym/notes-to-video/?utm_source=github&utm_medium=awesome-list) |
| [git-story-film](https://github.com/EverMind-AI/Raven/tree/HEAD/skills/git-story-film) | 所在仓库 EverMind-AI/Raven: 4.1k | 把一个仓库的 Git 历史拍成两分钟左右的手绘动画短片：故事、角色、分镜、浏览器预览，最后渲染 4K/60fps MP4 | [SAFE](https://agentskillshub.top/skill/EverMind-AI/Raven/?utm_source=github&utm_medium=awesome-list) |

<a id="type-editing"></a>
## ✂️ 剪辑与后期

[在在线页面打开这一类,按星数排序 →](https://agentskillshub.top/best/opus-5-5-video/?utm_source=github&utm_medium=awesome-list#type-editing)

| 仓库 | 星数 | 做什么 | 安全评级 |
|---|---:|---|---|
| [FireRedTeam/FireRed-OpenStoryline](https://github.com/FireRedTeam/FireRed-OpenStoryline) | 3.4k | AI 视频剪辑 agent：用自然语言交互、LLM 规划和工具编排做导演式剪辑，支持可复用的 Style Skills | [SAFE](https://agentskillshub.top/skill/FireRedTeam/FireRed-OpenStoryline/?utm_source=github&utm_medium=awesome-list) |
| [Agentchengfeng/chengfeng-videocut-skills](https://github.com/Agentchengfeng/chengfeng-videocut-skills) | 3.0k | 用 Claude Code Skills 做的视频剪辑 agent | [SAFE](https://agentskillshub.top/skill/Agentchengfeng/chengfeng-videocut-skills/?utm_source=github&utm_medium=awesome-list) |
| [0xsline/OpenChatCut](https://github.com/0xsline/OpenChatCut) | 2.0k | 开源、本地优先的对话式 AI 视频编辑器，带专业多轨时间线、Agent Skills、MCP 集成和 Remotion 渲染 | [SAFE](https://agentskillshub.top/skill/0xsline/OpenChatCut/?utm_source=github&utm_medium=awesome-list) |
| [cartesiancs/cartcut](https://github.com/cartesiancs/cartcut) | 756 | 给 AI agent 用的视频编辑器，相信开源可以胜过商业工具 | [SAFE](https://agentskillshub.top/skill/cartesiancs/cartcut/?utm_source=github&utm_medium=awesome-list) |
| [hetpatel-11/Adobe_Premiere_Pro_MCP](https://github.com/hetpatel-11/Adobe_Premiere_Pro_MCP) | 610 | Adobe Premiere Pro MCP：通过 MCP 为 Codex、Claude 等客户端提供 AI 驱动的视频剪辑工具 | [SAFE](https://agentskillshub.top/skill/hetpatel-11/Adobe_Premiere_Pro_MCP/?utm_source=github&utm_medium=awesome-list) |
| [zenstory-ai/video-recap-skills](https://github.com/zenstory-ai/video-recap-skills) | 533 | 用 Claude Code skills 把视频做成中文解说成片，可选一键导出可编辑剪映草稿 | [SAFE](https://agentskillshub.top/skill/zenstory-ai/video-recap-skills/?utm_source=github&utm_medium=awesome-list) |
| [hassancs91/claude-youtube-editor](https://github.com/hassancs91/claude-youtube-editor) | 314 | 录好口播，其余交给 Claude Code：剪辑、画面、配音、音效、封面和 YouTube 上传 | [SAFE](https://agentskillshub.top/skill/hassancs91/claude-youtube-editor/?utm_source=github&utm_medium=awesome-list) |
| [leancoderkavy/premiere-pro-mcp](https://github.com/leancoderkavy/premiere-pro-mcp) | 292 | 独立、本地优先的 Adobe Premiere Pro MCP 服务器，通过本地 CEP 桥接连接 Claude、Codex 或 Cursor | [SAFE](https://agentskillshub.top/skill/leancoderkavy/premiere-pro-mcp/?utm_source=github&utm_medium=awesome-list) |
| [AgriciDaniel/claude-shorts](https://github.com/AgriciDaniel/claude-shorts) | 217 | 交互式长视频转短视频的 Claude Code skill：Remotion 渲染动态字幕、AI 片段评分、光标跟踪和音频感知的边界吸附 | [SAFE](https://agentskillshub.top/skill/AgriciDaniel/claude-shorts/?utm_source=github&utm_medium=awesome-list) |
| [erduo1998-cell/erduo-broll-loop-engineering](https://github.com/erduo1998-cell/erduo-broll-loop-engineering) | 203 | SRT 驱动的双后端 B-roll Agent Skill：自动路由 HyperFrames / Remotion，集成 152 张镜头卡 | [SAFE](https://agentskillshub.top/skill/erduo1998-cell/erduo-broll-loop-engineering/?utm_source=github&utm_medium=awesome-list) |
| [Cassette-Editor/oh-my-cassette](https://github.com/Cassette-Editor/oh-my-cassette) | 154 | 你的随身 AI 剪辑搭档：面向 Claude Code、Codex、Hermes 和 OpenCode 的 AI 视频剪辑插件与 MCP 服务器 | [SAFE](https://agentskillshub.top/skill/Cassette-Editor/oh-my-cassette/?utm_source=github&utm_medium=awesome-list) |
| [znyupup/ai-video-editing-skill](https://github.com/znyupup/ai-video-editing-skill) | 135 | 自动剪辑 vlog 的 AI Agent Skill：输入原始素材，输出成片，基于 ffmpeg + Whisper + Vision API | [SAFE](https://agentskillshub.top/skill/znyupup/ai-video-editing-skill/?utm_source=github&utm_medium=awesome-list) |
| [naive-kun/naive-video-skill](https://github.com/naive-kun/naive-video-skill) | 130 | 把口播视频做成带字幕和动效成片的 Codex skill | [SAFE](https://agentskillshub.top/skill/naive-kun/naive-video-skill/?utm_source=github&utm_medium=awesome-list) |
| [Monet-AI-Editor/Monet](https://github.com/Monet-AI-Editor/Monet) | 116 | 用 Claude Code 或 Codex 剪辑视频、设计图片 | [SAFE](https://agentskillshub.top/skill/Monet-AI-Editor/Monet/?utm_source=github&utm_medium=awesome-list) |
| [blixvip/easyedit](https://github.com/blixvip/easyedit) | 109 | 输入电影名，得到带字幕台词的卡点粉丝混剪；本地优先，无需 API key，配合 Claude Code / Codex 使用 | [SAFE](https://agentskillshub.top/skill/blixvip/easyedit/?utm_source=github&utm_medium=awesome-list) |
| [ayushozha/AdobePremiereProMCP](https://github.com/ayushozha/AdobePremiereProMCP) | 106 | Adobe Premiere Pro 的 MCP 服务器：1,027 个工具，覆盖时间线剪辑、调色、混音、特效和导出 | [SAFE](https://agentskillshub.top/skill/ayushozha/AdobePremiereProMCP/?utm_source=github&utm_medium=awesome-list) |
| [louisedesadeleer/cut-video](https://github.com/louisedesadeleer/cut-video) | 101 | Claude Code skill：精简长录制内容，去掉静音、语气词和空白，保留笑声和喜剧停顿，在 Apple Silicon 上运行快 | [SAFE](https://agentskillshub.top/skill/louisedesadeleer/cut-video/?utm_source=github&utm_medium=awesome-list) |
| [AKMessi/vex](https://github.com/AKMessi/vex) | 85 | 视频剪辑版的 Claude Code | [*待评级*](https://agentskillshub.top/skill/AKMessi/vex/?utm_source=github&utm_medium=awesome-list) |
| [JUNKDOGE-JOE/after-effects-mcp](https://github.com/JUNKDOGE-JOE/after-effects-mcp) | 75 | agent 驱动的 After Effects 自动化：MCP 服务器 + CEP 插件，提供 30 个 ae.* 工具 | [SAFE](https://agentskillshub.top/skill/JUNKDOGE-JOE/after-effects-mcp/?utm_source=github&utm_medium=awesome-list) |
| [kurbaitaev/ghost-editor](https://github.com/kurbaitaev/ghost-editor) | 61 | 口播 Reels 的 AI 视频剪辑 skill，基于 HyperFrames：7 种风格、避开人脸的字幕、动效场景，可逆向还原参考剪辑 | [*待评级*](https://agentskillshub.top/skill/kurbaitaev/ghost-editor/?utm_source=github&utm_medium=awesome-list) |
| [hahadu4520/vlog-cut](https://github.com/hahadu4520/vlog-cut) | 49 | 给 Claude Code 用的「按文案剪辑」流水线 | *待评级* |
| [ops120/video-recap-skills-plus](https://github.com/ops120/video-recap-skills-plus) | 39 | 用 Claude Code skill 把任何视频剪辑成中文解说视频，支持剪映导出 | [*待评级*](https://agentskillshub.top/skill/ops120/video-recap-skills-plus/?utm_source=github&utm_medium=awesome-list) |
| [Kappaemme-git/codex-video-short-maker-skill](https://github.com/Kappaemme-git/codex-video-short-maker-skill) | 35 |  | *待评级* |
| [darrenli6/JJKoubo](https://github.com/darrenli6/JJKoubo) | 32 | JJ 口播：本地优先的视频剪辑 Skills 合集，面向口播、访谈、知识分享等以讲话为主的视频 | [SAFE](https://agentskillshub.top/skill/darrenli6/JJKoubo/?utm_source=github&utm_medium=awesome-list) |
| [krusemediallc/video-editor-agent](https://github.com/krusemediallc/video-editor-agent) | 17 | 端到端剪辑短视频的 Claude Code skill 包：克隆参考 Reel 风格、动态图形、音效设计、逐帧 QA | [SAFE](https://agentskillshub.top/skill/krusemediallc/video-editor-agent/?utm_source=github&utm_medium=awesome-list) |
| [manthanpatelll/leadgenman-video-skills](https://github.com/manthanpatelll/leadgenman-video-skills) | 17 | 六个 Claude Code skill 组成的自动化视频内容流水线，含 SRT、YouTube 描述、Reel 叠加层等 | *待评级* |
| [jincheng2026/jc-remotion-skills](https://github.com/jincheng2026/jc-remotion-skills) | 14 | Remotion 口播视频 AI 成片工作流（Codex / Claude Code）：粗剪 + SRT 进，带 MG 包装、音效、母带的成片出 | [SAFE](https://agentskillshub.top/skill/jincheng2026/jc-remotion-skills/?utm_source=github&utm_medium=awesome-list) |
| [cocolayuan/videoclip-AI-skill](https://github.com/cocolayuan/videoclip-AI-skill) | 13 | 基于 Claude Skill 的视频全自动剪辑工具包 | [SAFE](https://agentskillshub.top/skill/cocolayuan/videoclip-AI-skill/?utm_source=github&utm_medium=awesome-list) |
| [PoetCoderJun/MotionTalk](https://github.com/PoetCoderJun/MotionTalk) | 12 | 用一个 Agent Skill 把剪好的口播视频做成动态图形视频 | [SAFE](https://agentskillshub.top/skill/PoetCoderJun/MotionTalk/?utm_source=github&utm_medium=awesome-list) |
| [ZiadAbdelkarim/beat-synced-edit](https://github.com/ZiadAbdelkarim/beat-synced-edit) | 10 | 自动卡点剪辑：输入歌曲和原始素材，分析节拍、能量和场景后剪出成片，附带 Claude Code skill | [SAFE](https://agentskillshub.top/skill/ZiadAbdelkarim/beat-synced-edit/?utm_source=github&utm_medium=awesome-list) |
| [misbahsy/tiktok-ig-shorts](https://github.com/misbahsy/tiktok-ig-shorts) | 10 | 用 HyperFrames 配合 Claude 和 Codex 生成 TikTok 和 Instagram 短视频 | *待评级* |
| [qingyunAGI/qingyun-cine-skill](https://github.com/qingyunAGI/qingyun-cine-skill) | 10 | 先规划后剪辑的电影感视频剪辑 Codex skill，适用于预告片、卡点剪辑、宣传片和精彩集锦 | *待评级* |
| [Fagan1024/smart-video-editor](https://github.com/Fagan1024/smart-video-editor) | 7 | 会看画面的 AI 自动剪辑 Skill：先用视觉模型看懂素材再决定剪哪几秒 | *待评级* |
| [hahadu4520/newcut-video-clipping-skill](https://github.com/hahadu4520/newcut-video-clipping-skill) | 6 | 开源 Codex skill：按语义剪辑中文视频，含开头钩子、字幕、清理和 FFmpeg 渲染 | *待评级* |
| [jackjls/jtxvideo-skill](https://github.com/jackjls/jtxvideo-skill) | 5 | Codex + HyperFrames 口播视频制作 Skill：按 SRT、结构、分镜、设计、渲染的审核流程生成 AI 金融短视频 | [*待评级*](https://agentskillshub.top/skill/jackjls/jtxvideo-skill/?utm_source=github&utm_medium=awesome-list) |

<a id="type-shorts"></a>
## 📱 短视频与口播

[在在线页面打开这一类,按星数排序 →](https://agentskillshub.top/best/opus-5-5-video/?utm_source=github&utm_medium=awesome-list#type-shorts)

| 仓库 | 星数 | 做什么 | 安全评级 |
|---|---:|---|---|
| [Yuuhann1999/codex-storyboard](https://github.com/Yuuhann1999/codex-storyboard) | 344 | 本地多项目 Codex 视频分镜工作台，支持图片/视频生成任务、HyperFrames 与 Remotion 自动回填 | [SAFE](https://agentskillshub.top/skill/Yuuhann1999/codex-storyboard/?utm_source=github&utm_medium=awesome-list) |
| [hassancs91/claude-faceless-shorts-creator](https://github.com/hassancs91/claude-faceless-shorts-creator) | 267 | Claude Code 驱动的不露脸 YouTube Shorts 工厂：Remotion 画面、ElevenLabs 配音与逐词字幕 | [SAFE](https://agentskillshub.top/skill/hassancs91/claude-faceless-shorts-creator/?utm_source=github&utm_medium=awesome-list) |
| [jaxxchen003/book-video-factory](https://github.com/jaxxchen003/book-video-factory) | 105 | 可移植的 Codex skill，用于可审计、注重版权的中文书评短视频工作流 | [SAFE](https://agentskillshub.top/skill/jaxxchen003/book-video-factory/?utm_source=github&utm_medium=awesome-list) |
| [Maartenlouis/remotion-ads](https://github.com/Maartenlouis/remotion-ads) | 59 | 用 Remotion 制作 Instagram Reels 和轮播广告的 Claude Code skill | [SAFE](https://agentskillshub.top/skill/Maartenlouis/remotion-ads/?utm_source=github&utm_medium=awesome-list) |
| [pyang5166/gbro-collage-info](https://github.com/pyang5166/gbro-collage-info) | 51 | 半调纸拼贴风信息动画 Agent Skill：根据旁白脚本生成，基于 HyperFrames，不用图像模型 | [*待评级*](https://agentskillshub.top/skill/pyang5166/gbro-collage-info/?utm_source=github&utm_medium=awesome-list) |
| [liangdabiao/story-handdrawn-video](https://github.com/liangdabiao/story-handdrawn-video) | 48 | 把中文/英文故事文本变成 9:16 竖屏手绘蜡笔风短视频的 Remotion 视频 Skill | *待评级* |
| [yuwenbin121/book-video-production-skill](https://github.com/yuwenbin121/book-video-production-skill) | 17 | 制作基于事实的竖屏图书视频的 Codex skill | [*待评级*](https://agentskillshub.top/skill/yuwenbin121/book-video-production-skill/?utm_source=github&utm_medium=awesome-list) |
| [intelligent-iterations/ii-content-engine](https://github.com/intelligent-iterations/ii-content-engine) | 14 | 面向 Claude Code 和 Codex 的内容生成与自动发布引擎，用 Grok 为 TikTok、Instagram、X 生成视频 | *待评级* |
| [iart-ai/tiktok-video-skills](https://github.com/iart-ai/tiktok-video-skills) | 11 | Claude Code 的短视频 skills，用于制作 Reels、TikTok 和 YouTube Shorts | *待评级* |
| [adriiita/vertical-video-editing-skill](https://github.com/adriiita/vertical-video-editing-skill) | 10 | Claude skill：用 HyperFrames 把脚本和口播素材做成 9:16 竖屏短视频，含剪辑、运镜、动态图形和音效 | *待评级* |
| [Samin12/samin-reel-engine-plugin](https://github.com/Samin12/samin-reel-engine-plugin) | 8 | 模块化 Codex 插件，制作有来源依据的 Reels：调研、脚本、真实 B-roll、快速剪辑、质量审查和赠品活动交接 | *待评级* |
| [riffkit/skill](https://github.com/riffkit/skill) | 7 | Riffkit 官方 skill：在 AI agent 或浏览器里，把爆款 TikTok 的套路改编成自己的短视频 | [SAFE](https://agentskillshub.top/skill/riffkit/skill/?utm_source=github&utm_medium=awesome-list) |
| [zoglmk/codex-video-pipeline](https://github.com/zoglmk/codex-video-pipeline) | 6 | 从选题、脚本和素材到成片、封面与发布包的 AI 视频生产流水线 Skill | *待评级* |
| [icytear-svg/podcast-to-video](https://github.com/icytear-svg/podcast-to-video) | 5 | 把播客单集做成适配各平台的带字幕视频的 Codex skill | [SAFE](https://agentskillshub.top/skill/icytear-svg/podcast-to-video/?utm_source=github&utm_medium=awesome-list) |
| [inematds/skill-video-plan-editor](https://github.com/inematds/skill-video-plan-editor) | 5 | 把主题或链接转成专业视频剪辑方案（不绑定渲染器）的 skill，可选用 FFmpeg/Auto-Editor/HyperFrames 渲染 | *待评级* |
| [liangdabiao/wechat-article-remotion](https://github.com/liangdabiao/wechat-article-remotion) | 5 | 动画 skill：把任意微信公众号文章转成 Studio 风格的 Remotion 视频，暖白画布、镜像透视格子、章节进度，保留原文配图 | *待评级* |
| [marketcalls/story-telling](https://github.com/marketcalls/story-telling) | 5 | 把一段内容做成带旁白的故事视频：Sarvam AI 配音、FLUX 2 插画、Remotion 渲染，附带 Claude Code skills | [*待评级*](https://agentskillshub.top/skill/marketcalls/story-telling/?utm_source=github&utm_medium=awesome-list) |
| [ninestonelee/youtube-shorts-factory](https://github.com/ninestonelee/youtube-shorts-factory) | 5 | Claude Code skill：YouTube 参考视频分析 → 对标 → 30% 以上改编 → AI Shorts 制作工作流 | *待评级* |
| [wendymardigian-prog/Editor-IA-Pro](https://github.com/wendymardigian-prog/Editor-IA-Pro) | 5 | 基于 Remotion 和 Claude Code 构建的 AI 视频编辑器 | *待评级* |

<a id="type-avatar"></a>
## 🧑‍💼 数字人

[在在线页面打开这一类,按星数排序 →](https://agentskillshub.top/best/opus-5-5-video/?utm_source=github&utm_medium=awesome-list#type-avatar)

| 仓库 | 星数 | 做什么 | 安全评级 |
|---|---:|---|---|
| [heygen-com/skills](https://github.com/heygen-com/skills) | 454 | HeyGen AI agent skills：通过 v3 Video Agent 流水线创建数字人并制作视频 | [SAFE](https://agentskillshub.top/skill/heygen-com/skills/?utm_source=github&utm_medium=awesome-list) |
| [Upload-Post/avatar-mix](https://github.com/Upload-Post/avatar-mix) | 130 | 用 HeyGen 数字人、HyperFrames 动态背景、音乐、音效和 Hormozi 风格字幕生成横竖屏视频并发布到社交平台的 skill | [*待评级*](https://agentskillshub.top/skill/Upload-Post/avatar-mix/?utm_source=github&utm_medium=awesome-list) |
| [AgriciDaniel/lipnardo](https://github.com/AgriciDaniel/lipnardo) | 22 | Claude Code 的 HeyGen 数字人视频生成 skill：批量、模板、翻译、照片数字人、TTS，仅用 Python 标准库 | [*待评级*](https://agentskillshub.top/skill/AgriciDaniel/lipnardo/?utm_source=github&utm_medium=awesome-list) |
| [zlong6943-commits/football-prediction-avatar-video](https://github.com/zlong6943-commits/football-prediction-avatar-video) | 9 | Codex skill：制作经核实的中文足球预测数字人视频，含官方 logo、字幕、动态图形和审批关卡 | [SAFE](https://agentskillshub.top/skill/zlong6943-commits/football-prediction-avatar-video/?utm_source=github&utm_medium=awesome-list) |

<a id="type-story"></a>
## 📖 故事与动画

[在在线页面打开这一类,按星数排序 →](https://agentskillshub.top/best/opus-5-5-video/?utm_source=github&utm_medium=awesome-list#type-story)

| 仓库 | 星数 | 做什么 | 安全评级 |
|---|---:|---|---|
| [gnipbao/story-to-handdrawn-video](https://github.com/gnipbao/story-to-handdrawn-video) | 2.1k | Agent skill：把中文故事文案或有序图片转成手绘日记漫画风动画（无声 MP4 画面轨） | [SAFE](https://agentskillshub.top/skill/gnipbao/story-to-handdrawn-video/?utm_source=github&utm_medium=awesome-list) |
| [JohnHeibel/ClaudeAnimationBase](https://github.com/JohnHeibel/ClaudeAnimationBase) | 414 | 用 Claude 制作手绘卡通动画的入门套件：p5.js + p5.brush、Clawd 角色、31 种表演情绪和给模型的指南 | [*待评级*](https://agentskillshub.top/skill/JohnHeibel/ClaudeAnimationBase/?utm_source=github&utm_medium=awesome-list) |
| [aaronyi97/image-story-video-wizard](https://github.com/aaronyi97/image-story-video-wizard) | 351 | 带确认关卡的 Codex 和 WorkBuddy skill，用于音频先行的图片故事视频制作 | [SAFE](https://agentskillshub.top/skill/aaronyi97/image-story-video-wizard/?utm_source=github&utm_medium=awesome-list) |
| [liyue-aigc/xianxia-cinematic-video-director](https://github.com/liyue-aigc/xianxia-cinematic-video-director) | 268 | 用于东方仙侠题材分镜、运镜和视频连贯性的 Codex Skill | [SAFE](https://agentskillshub.top/skill/liyue-aigc/xianxia-cinematic-video-director/?utm_source=github&utm_medium=awesome-list) |
| [LetMeHappyCode/auto-video-agent](https://github.com/LetMeHappyCode/auto-video-agent) | 216 | 基于 Agent / Skill / Workflow 编排，流水线化生成「分镜插画提示词 → AI 生图 → 拼接成片」的成套视频 | [SAFE](https://agentskillshub.top/skill/LetMeHappyCode/auto-video-agent/?utm_source=github&utm_medium=awesome-list) |
| [lemomo-ai/lemo-opuscar](https://github.com/lemomo-ai/lemo-opuscar) | 174 | Opus 5.5 x 39 种影片风格：风格提示词 + 纯代码样片 + 导演与技术指南 | [SAFE](https://agentskillshub.top/skill/lemomo-ai/lemo-opuscar/?utm_source=github&utm_medium=awesome-list) |
| [Mr-funny/hbg-life-simulation](https://github.com/Mr-funny/hbg-life-simulation) | 140 | HBG Agent Skill：制作中文人生模拟叙事视频，含统一漫画 IP、多段人生快速开场、Edge TTS、同步字幕和成片 QA | [SAFE](https://agentskillshub.top/skill/Mr-funny/hbg-life-simulation/?utm_source=github&utm_medium=awesome-list) |
| [liangdabiao/story-handdrawn-remotion](https://github.com/liangdabiao/story-handdrawn-remotion) | 35 | 视频 Skill：把中文/英文故事文本变成手绘日记漫画风竖屏视频，每句按文字、黑白画稿、彩色插画三阶段揭示 | *待评级* |
| [AsadMoulviDev/reel-video](https://github.com/AsadMoulviDev/reel-video) | 28 | 用 Claude Code、Codex、Cursor 和 Grok Build 制作 AI 视频，除已付费的套餐外无额外生成费用 | *待评级* |
| [AllenAI2014/remotion-guofeng-starter](https://github.com/AllenAI2014/remotion-guofeng-starter) | 25 | 国风纸片动画：Remotion 风格资产库 + 制作流程 Skill，给 AI 一首诗或成语即可出片，全程代码渲染 | *待评级* |
| [taylorzhou16/video-gen](https://github.com/taylorzhou16/video-gen) | 9 | 面向 Claude Code 的 AI 视频剪辑 Skill | [SAFE](https://agentskillshub.top/skill/taylorzhou16/video-gen/?utm_source=github&utm_medium=awesome-list) |
| [tuzhechen2005/opus-video-skills](https://github.com/tuzhechen2005/opus-video-skills) | 6 | 用 Claude Opus 5.5 以代码制作视频的 skill 合集，每种风格一个 skill，如手绘动画、动态排版短片 | [*待评级*](https://agentskillshub.top/skill/tuzhechen2005/opus-video-skills/?utm_source=github&utm_medium=awesome-list) |

<a id="type-motion"></a>
## 🎞 动效与 Logo

[在在线页面打开这一类,按星数排序 →](https://agentskillshub.top/best/opus-5-5-video/?utm_source=github&utm_medium=awesome-list#type-motion)

| 仓库 | 星数 | 做什么 | 安全评级 |
|---|---:|---|---|
| [diffusionstudio/lottie](https://github.com/diffusionstudio/lottie) | 5.5k | 用 Claude Code 或 Codex 生成可用于生产的 Lottie 动画 | [SAFE](https://agentskillshub.top/skill/diffusionstudio/lottie/?utm_source=github&utm_medium=awesome-list) |
| [nolangz/pixel2motion](https://github.com/nolangz/pixel2motion) | 2.3k | AI logo 动画 skill：把位图 logo 转成 SVG 动画、HTML 动画演示、GIF/视频预览和动效 QA 证据 | [SAFE](https://agentskillshub.top/skill/nolangz/pixel2motion/?utm_source=github&utm_medium=awesome-list) |
| [pyang5166/gbro-collage-broll](https://github.com/pyang5166/gbro-collage-broll) | 1.3k | 半调纸拼贴 B-roll 生成 skill：三闸门审批，Gemini Omni Flash 首尾帧组装动画 | [SAFE](https://agentskillshub.top/skill/pyang5166/gbro-collage-broll/?utm_source=github&utm_medium=awesome-list) |
| [MegaTroll222/VOX-COLLAGE-BROLL](https://github.com/MegaTroll222/VOX-COLLAGE-BROLL) | 211 | 把一句口播变成纸拼贴讲解视频的 Claude Code skill，gbro-collage-broll 的英文改编版 | [*待评级*](https://agentskillshub.top/skill/MegaTroll222/VOX-COLLAGE-BROLL/?utm_source=github&utm_medium=awesome-list) |
| [Liamrjohnston/remotion-motion-graphics-skill](https://github.com/Liamrjohnston/remotion-motion-graphics-skill) | 72 | 用于 AI 视频工作流的 Remotion 动态图形 skills，可用于生产 | [*待评级*](https://agentskillshub.top/skill/Liamrjohnston/remotion-motion-graphics-skill/?utm_source=github&utm_medium=awesome-list) |
| [AgriciDaniel/claude-gif](https://github.com/AgriciDaniel/claude-gif) | 28 | Claude Code 的 GIF 制作 skill，6 条生成流水线，含 Remotion、Veo 3.1、FFmpeg、图片序列等 | *待评级* |
| [toufuim/personal-ip-brand-intro-skill](https://github.com/toufuim/personal-ip-brand-intro-skill) | 20 | 开源 Codex Skill：用文字、原创插图或用户图片制作个人 IP 品牌开场，支持上传音乐对拍与无音乐自主节拍 | [*待评级*](https://agentskillshub.top/skill/toufuim/personal-ip-brand-intro-skill/?utm_source=github&utm_medium=awesome-list) |
| [fernandokaraka/remotion-motion-graphics-skill](https://github.com/fernandokaraka/remotion-motion-graphics-skill) | 11 | Claude Code skill：用 Remotion 做动态图形视频，含标题卡、字幕条和带 alpha 通道的叠加层 | *待评级* |
| [zhenwusw/orca-motion-skill](https://github.com/zhenwusw/orca-motion-skill) | 7 | 制作场景内动态图形的 agent skill，由抽象的、设计 token 驱动的形状构成，与 orca-transition-skill 配套 | *待评级* |
| [acelera-agency/html-animation](https://github.com/acelera-agency/html-animation) | 6 | 用代码做动态图形的 agent skill：以单个 HTML 文件制作动画 logo、动态排版和品牌视频并导出 MP4 | *待评级* |

<a id="type-music"></a>
## 🎵 音乐视频

[在在线页面打开这一类,按星数排序 →](https://agentskillshub.top/best/opus-5-5-video/?utm_source=github&utm_medium=awesome-list#type-music)

| 仓库 | 星数 | 做什么 | 安全评级 |
|---|---:|---|---|
| [JohnHeibel/PDoomVideo](https://github.com/JohnHeibel/PDoomVideo) | 1.1k | Claude Opus 5.5 音乐视频《I'm Upping My P(doom)》的源代码 | [*待评级*](https://agentskillshub.top/skill/JohnHeibel/PDoomVideo/?utm_source=github&utm_medium=awesome-list) |
| [ledbetterljoshua/functional-emotions-video](https://github.com/ledbetterljoshua/functional-emotions-video) | 45 | Claude Opus 5.5 制作的《Functional Emotions》手绘风音乐视频：自研 GPU 笔触渲染器、7 个并行章节 agent | [*待评级*](https://agentskillshub.top/skill/ledbetterljoshua/functional-emotions-video/?utm_source=github&utm_medium=awesome-list) |

**安全评级**是 Agent Skills Hub 对仓库 README 和安装步骤的评级。*待评级*表示目录还没评到它。

## 相关合集

- [opusvideo/awesome-claude-video](https://github.com/opusvideo/awesome-claude-video) —— 大家用 Opus 5.5 做出来的视频,附原帖。它收作品,本列表收工具。
- [TripoGrowthLab/awesome-opus-5-5-prompts](https://github.com/TripoGrowthLab/awesome-opus-5-5-prompts) —— Opus 5.5 做 3D 场景、游戏和模拟的提示词。

## 推荐仓库

提一个 issue 附上 GitHub 链接。它会走和每个条目一样的评审;决定上不上榜的是上面的规则,不是星数。

---

机器可读版本:[`data/skills.json`](data/skills.json)。生成于 2026-09-27。
