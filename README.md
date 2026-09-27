# Awesome Claude Video Skills

[中文](README.zh-CN.md)

Open-source skills and toolkits that let **Claude Code, Codex and other coding agents make video**: HyperFrames, Remotion, motion graphics, editing, explainers, avatars. 178 repos, each one read and security-graded by [Agent Skills Hub](https://agentskillshub.top?utm_source=github&utm_medium=awesome-list).

Live page with filters: **[https://agentskillshub.top/best/opus-5-5-video/](https://agentskillshub.top/best/opus-5-5-video/?utm_source=github&utm_medium=awesome-list)** · refreshed every 8 hours

## Contents

- [Made with Claude Opus 5.5](#made-with-opus-55)
- [🧱 Frameworks & toolkits](#type-general) (29)
- [📣 Promo & demos](#type-promo) (26)
- [🎓 Explainers](#type-explainer) (32)
- [✂️ Editing](#type-editing) (35)
- [📱 Shorts & social](#type-shorts) (19)
- [🧑‍💼 Avatars](#type-avatar) (4)
- [📖 Stories & animation](#type-story) (12)
- [🎞 Motion graphics](#type-motion) (10)
- [📝 Scripts & learning](#type-craft) (9)
- [🎵 Music videos](#type-music) (2)

## How a repo gets on the list

1. It makes or edits video or motion graphics. A 3D web page or a prompt collection does not count. The few entries under *Scripts & learning* come before the video (screenwriting, shot analysis) and are listed by the maintainer's choice.
2. An agent operates it: a skill, a plugin, an MCP server, or a toolkit written for the agent.
3. It has a README. Without one it cannot be graded.
4. At 50 stars or more it is listed on topic alone. Under 50 it must also clear a README quality bar (shows the result, one-command start, a concrete outcome, complete docs), and have 5 stars unless it names Claude Opus 5.5.

The questions are answered by a decision model reading each README, not by hand. A repo near a cut-off can land on either side; open an issue if one is misfiled.

<a id="made-with-opus-55"></a>
## Made with Claude Opus 5.5

Projects whose README says they were built with the model.

| Repo | Stars | What it does | Security |
|---|---:|---|---|
| [JohnHeibel/PDoomVideo](https://github.com/JohnHeibel/PDoomVideo) | 1.1k | Source code for the Claude Opus 5.5 music video for I'm Upping My P(doom) | [*pending*](https://agentskillshub.top/skill/JohnHeibel/PDoomVideo/?utm_source=github&utm_medium=awesome-list) |
| [JohnHeibel/ClaudeAnimationBase](https://github.com/JohnHeibel/ClaudeAnimationBase) | 415 | A starter kit for animating hand-painted cartoons with Claude: p5.js + p5.brush, the Clawd character, 31 acted emotions and a guide for the model | [*pending*](https://agentskillshub.top/skill/JohnHeibel/ClaudeAnimationBase/?utm_source=github&utm_medium=awesome-list) |
| [lemomo-ai/lemo-opuscar](https://github.com/lemomo-ai/lemo-opuscar) | 177 | 39 film styles, each a reusable style prompt plus a short film made entirely in code by Claude Opus 5.5. Pick a style, bring your own story, and let… | [SAFE](https://agentskillshub.top/skill/lemomo-ai/lemo-opuscar/?utm_source=github&utm_medium=awesome-list) |
| [ledbetterljoshua/functional-emotions-video](https://github.com/ledbetterljoshua/functional-emotions-video) | 45 | A painted music video for "Functional Emotions", made by Claude Opus 5.5: custom GPU brushstroke renderer, storyboard, and 7 parallel chapter agents. | [*pending*](https://agentskillshub.top/skill/ledbetterljoshua/functional-emotions-video/?utm_source=github&utm_medium=awesome-list) |

<a id="type-general"></a>
## 🧱 Frameworks & toolkits

[Open this type on the live page, sorted by stars →](https://agentskillshub.top/best/opus-5-5-video/?utm_source=github&utm_medium=awesome-list#type-general)

| Repo | Stars | What it does | Security |
|---|---:|---|---|
| [calesthio/OpenMontage](https://github.com/calesthio/OpenMontage) | 61.4k | World's first open-source, agentic video production system. 12 production pipelines, 100+ tools, 700+ agent skill and production-knowledge files. Tur… | [SAFE](https://agentskillshub.top/skill/calesthio/OpenMontage/?utm_source=github&utm_medium=awesome-list) |
| [heygen-com/hyperframes](https://github.com/heygen-com/hyperframes) | 53.4k | Write HTML. Render video. Built for agents. | [SAFE](https://agentskillshub.top/skill/heygen-com/hyperframes/?utm_source=github&utm_medium=awesome-list) |
| [hypit-ai/hypit](https://github.com/hypit-ai/hypit) | 16.4k | Clone any viral video with AI agents. Not just a script, the whole workflow: swap the face, the words, the B-roll, ship 100 variants in one command,… | *pending* |
| [remotion-dev/skills](https://github.com/remotion-dev/skills) | 4.7k | Agent Skills | [SAFE](https://agentskillshub.top/skill/remotion-dev/skills/?utm_source=github&utm_medium=awesome-list) |
| [NarratorAI-Studio/narrator-ai-cli-skill](https://github.com/NarratorAI-Studio/narrator-ai-cli-skill) | 2.7k | AI 解说大师 — Agent skill；封装 narrator-ai-cli 供 Claude/Codex 等工具调用 | [SAFE](https://agentskillshub.top/skill/NarratorAI-Studio/narrator-ai-cli-skill/?utm_source=github&utm_medium=awesome-list) |
| [digitalsamba/claude-code-video-toolkit](https://github.com/digitalsamba/claude-code-video-toolkit) | 2.1k | AI-native video production toolkit for Claude Code | [SAFE](https://agentskillshub.top/skill/digitalsamba/claude-code-video-toolkit/?utm_source=github&utm_medium=awesome-list) |
| [vibe-motion/skills](https://github.com/vibe-motion/skills) | 1.3k | agent skills for vibe motion | [SAFE](https://agentskillshub.top/skill/vibe-motion/skills/?utm_source=github&utm_medium=awesome-list) |
| [bangtutorial/bang-motion](https://github.com/bangtutorial/bang-motion) | 524 | Agent skill for browser motion graphics — openers, promos, bumpers, kinetic typography, and five explainer styles that move like video, not slides. S… | [SAFE](https://agentskillshub.top/skill/bangtutorial/bang-motion/?utm_source=github&utm_medium=awesome-list) |
| [iart-ai/motion-skills](https://github.com/iart-ai/motion-skills) | 516 | 50 open-source skills that teach your AI coding agent to make motion graphics, animation & video — kinetic typography, data-viz, explainers, TikTok/R… | [SAFE](https://agentskillshub.top/skill/iart-ai/motion-skills/?utm_source=github&utm_medium=awesome-list) |
| [kangarooking/director-skills](https://github.com/kangarooking/director-skills) | 147 | 导演Skill：面向 AI 视频创作的开源 Agent Skills \| Director Skills: Open-source Agent Skills for AI video creation. | [SAFE](https://agentskillshub.top/skill/kangarooking/director-skills/?utm_source=github&utm_medium=awesome-list) |
| [video-db/skills](https://github.com/video-db/skills) | 121 | Server-side video workflows for agents: ingest, understand, search, edit, stream. | [SAFE](https://agentskillshub.top/skill/video-db/skills/?utm_source=github&utm_medium=awesome-list) |
| [jhartquist/claude-remotion-kickstart](https://github.com/jhartquist/claude-remotion-kickstart) | 120 | Create videos programmatically with Claude Code and Remotion | [*pending*](https://agentskillshub.top/skill/jhartquist/claude-remotion-kickstart/?utm_source=github&utm_medium=awesome-list) |
| [Johnson-Jia/video-clipforge](https://github.com/Johnson-Jia/video-clipforge) | 39 | AI 驱动的短视频制作系统。给它一个想法，它帮你写稿、配音、做画面、出成片。9 阶段 DAG 管线 + 自进化评分，支持每日自动执行。基于 Claude Code + HyperFrames。 | [SAFE](https://agentskillshub.top/skill/Johnson-Jia/video-clipforge/?utm_source=github&utm_medium=awesome-list) |
| [iart-ai/motion-design-skills](https://github.com/iart-ai/motion-design-skills) | 33 | Motion design fundamentals, engines, and brand elements as installable Claude Code skills — timing, typography, color, composition, After Effects, Re… | *pending* |
| [zhouyuechuan2025-ui/ai-self-media-video-packaging-skill](https://github.com/zhouyuechuan2025-ui/ai-self-media-video-packaging-skill) | 32 | Open Agent Skill for packaging talking-head videos with Remotion, optional HyperFrames, seek-safe motion, and line illustrations. | *pending* |
| [GordenSun/react-bits-video](https://github.com/GordenSun/react-bits-video) | 28 | 结合react-bits、remotion、hyperframe整合的Skill，可以生成华丽的视频。 | *pending* |
| [bbylw/hyperframes-cn](https://github.com/bbylw/hyperframes-cn) | 28 | HyperFrames 是一个开源框架，可将 HTML、CSS、媒体与可定位（seekable）动画转化为确定性的 MP4 视频。你可以在本地通过 CLI 使用它，让 AI 编程智能体借助 skills 使用它，或者把它作为托管创作工作流背后的渲染核心。 | *pending* |
| [smwbev/framewright](https://github.com/smwbev/framewright) | 21 | Agent skill + template: short videos made entirely from code. One HTML file, every frame a pure function of (frame, seed, width). Claude Code, Codex,… | [SAFE](https://agentskillshub.top/skill/smwbev/framewright/?utm_source=github&utm_medium=awesome-list) |
| [doublesq97-ui/su-card-to-video](https://github.com/doublesq97-ui/su-card-to-video) | 18 | Minimal HTML/CSS card-to-video starter skill using HyperFrames, GSAP, and FFmpeg. | *pending* |
| [gloweaseco-leo/hyperdirector](https://github.com/gloweaseco-leo/hyperdirector) | 17 | Hermes Skill Pack for structured AI video production on HyperFrames — brief → storyboard → HTML → lint/render. | *pending* |
| [resemble-ai/remotion-resemble-skill](https://github.com/resemble-ai/remotion-resemble-skill) | 9 |  | *pending* |
| [patraxo/ltx2-vidgen-skill](https://github.com/patraxo/ltx2-vidgen-skill) | 8 | Own your AI video pipeline. LTX-2.3 (22B) self-hosted on your Modal GPU via a Claude Code skill — t2v, i2v, keyframes, v2v + synced audio. ~$0.02 per… | [*pending*](https://agentskillshub.top/skill/patraxo/ltx2-vidgen-skill/?utm_source=github&utm_medium=awesome-list) |
| [molkex/mcp-flow-google](https://github.com/molkex/mcp-flow-google) | 7 | MCP server for Google Flow — Veo video and Nano Banana images inside Claude Code, Cursor or any MCP client. Runs on your own Google account: images f… | [SAFE](https://agentskillshub.top/skill/molkex/mcp-flow-google/?utm_source=github&utm_medium=awesome-list) |
| [vibe-motion/remotion-starter](https://github.com/vibe-motion/remotion-starter) | 7 | 用 Claude Code 指挥 Remotion 出视频的工作台脚手架:三层架构 + hooks 守规矩 + skills 编排流程 \| maintained by 陈与小金 | [*pending*](https://agentskillshub.top/skill/vibe-motion/remotion-starter/?utm_source=github&utm_medium=awesome-list) |
| [VasiniDevi/motion-skills](https://github.com/VasiniDevi/motion-skills) | 6 | Programmatic motion design skills for AI agents — motion graphics, kinetic typography, data viz, slide decks in Python | *pending* |
| [chenyuxiaojin/cyxj-remotion-starter](https://github.com/chenyuxiaojin/cyxj-remotion-starter) | 6 | 用 Claude Code 指挥 Remotion 出视频的工作台脚手架:三层架构 + hooks 守规矩 + skills 编排流程 \| by 陈与小金 | [SAFE](https://agentskillshub.top/skill/chenyuxiaojin/cyxj-remotion-starter/?utm_source=github&utm_medium=awesome-list) |
| [davidcervinka/vibe-editing](https://github.com/davidcervinka/vibe-editing) | 6 | Vibe coding, but for video. Launch films, aftermovies & reels — cut, scored and shipped by talking to Claude Code. Full stack + flow. | *pending* |
| [iart-ai/data-animation-skills](https://github.com/iart-ai/data-animation-skills) | 6 | Data video / animated infographic skills for Claude Code — turn a CSV into a chart that moves, with exact, accurate numbers on every frame. | *pending* |
| [magichourhq/skills](https://github.com/magichourhq/skills) | 6 | AI media generation skills for Codex, Claude Code and other agents. Images, video and audio workflows using Magic Hour MCP or API. | [SAFE](https://agentskillshub.top/skill/magichourhq/skills/?utm_source=github&utm_medium=awesome-list) |

<a id="type-promo"></a>
## 📣 Promo & demos

[Open this type on the live page, sorted by stars →](https://agentskillshub.top/best/opus-5-5-video/?utm_source=github&utm_medium=awesome-list#type-promo)

| Repo | Stars | What it does | Security |
|---|---:|---|---|
| [Vincentwei1021/video-shotcraft](https://github.com/Vincentwei1021/video-shotcraft) | 9.7k | AI video skill for Claude Code & Codex — cinematic product videos with Remotion: 152 shot recipe cards, 209 motion previews, a production-ready templ… | [SAFE](https://agentskillshub.top/skill/Vincentwei1021/video-shotcraft/?utm_source=github&utm_medium=awesome-list) |
| [geekjourneyx/hyperframes-motion-director](https://github.com/geekjourneyx/hyperframes-motion-director) | 447 | Agent Skill for Chinese-first HyperFrames motion-video production from articles, products, websites, and README files. | [SAFE](https://agentskillshub.top/skill/geekjourneyx/hyperframes-motion-director/?utm_source=github&utm_medium=awesome-list) |
| [op7418/guizang-product-video-skill](https://github.com/op7418/guizang-product-video-skill) | 442 | 归藏 product video skill：复用真实产品组件和设计语言，用代码制作软件更新宣传片。包含分镜文案、原创配乐、动作音效与视频渲染，支持 Claude Code 和 Codex。 | [SAFE](https://agentskillshub.top/skill/op7418/guizang-product-video-skill/?utm_source=github&utm_medium=awesome-list) |
| [tugrawork-creator/saas-motion-kit](https://github.com/tugrawork-creator/saas-motion-kit) | 128 | Promo & motion videos for software products with HyperFrames + Claude Code. No two films should feel the same: tone matrix, variety audit, 24-transit… | [SAFE](https://agentskillshub.top/skill/tugrawork-creator/saas-motion-kit/?utm_source=github&utm_medium=awesome-list) |
| [leosssvip-dot/remotion-ad-video-skill](https://github.com/leosssvip-dot/remotion-ad-video-skill) | 108 | Create Remotion ad video projects from a URL with an AI coding agent, no video-generation AI required. | [*pending*](https://agentskillshub.top/skill/leosssvip-dot/remotion-ad-video-skill/?utm_source=github&utm_medium=awesome-list) |
| [kangarooking/promo-creator-skills](https://github.com/kangarooking/promo-creator-skills) | 101 | 产品宣传视频创作 Skills：从产品判断、分镜、素材、HyperFrames 剪辑到 BGM 设计的完整 Agent 工作流 | [*pending*](https://agentskillshub.top/skill/kangarooking/promo-creator-skills/?utm_source=github&utm_medium=awesome-list) |
| [bestagentkits/motion-video-skill](https://github.com/bestagentkits/motion-video-skill) | 70 | Agent skill that produces beat-synced 1080p motion-graphic videos in HyperFrames (HTML + GSAP) with an AI voice-over, karaoke captions, SFX and gener… | [*pending*](https://agentskillshub.top/skill/bestagentkits/motion-video-skill/?utm_source=github&utm_medium=awesome-list) |
| [norahe0304-art/30x-video](https://github.com/norahe0304-art/30x-video) | 63 | One URL in, an agency-grade launch video out. A Claude Code skill (Remotion + React) with a 16-law taste codex — 12 brands, 12 worlds, zero templates. | [SAFE](https://agentskillshub.top/skill/norahe0304-art/30x-video/?utm_source=github&utm_medium=awesome-list) |
| [trunghaiy/appshot](https://github.com/trunghaiy/appshot) | 43 | Generate App Store & Google Play preview videos and screenshots from a simple TypeScript config. Built on Remotion + React + Tailwind. Ships with AI… | [SAFE](https://agentskillshub.top/skill/trunghaiy/appshot/?utm_source=github&utm_medium=awesome-list) |
| [BayramAnnakov/remotion-video-director](https://github.com/BayramAnnakov/remotion-video-director) | 41 | Interactive Claude Code skill for creating Remotion videos through expert-guided deliberation | [*pending*](https://agentskillshub.top/skill/BayramAnnakov/remotion-video-director/?utm_source=github&utm_medium=awesome-list) |
| [kingselyjoe/video-shotcraft-dsh](https://github.com/kingselyjoe/video-shotcraft-dsh) | 35 | 面向 DeepSeek Harness 的电影感产品视频 Agent Skill，包含 152 张镜头配方卡、Remotion 模板、代码组件和音频资产。 | *pending* |
| [mattivilola/brag-codex](https://github.com/mattivilola/brag-codex) | 32 | Codex-compatible clone of latent-spaces/brag for Hyperframes launch videos | *pending* |
| [gorkem-bwl/onboarding-video-generator](https://github.com/gorkem-bwl/onboarding-video-generator) | 31 | Claude Code skill for column-sized web app onboarding videos in Remotion | *pending* |
| [Finderchangchang/promo-video-skill](https://github.com/Finderchangchang/promo-video-skill) | 29 | 精酿 BrewReel：让 DeepSeek 这类便宜模型也能做出好看的竖版宣传片。写一份产品简报，AI 挑镜头、写文案，一条命令出片。3 种配方、6 个行业、广告法校验，开源可商用。 | [*pending*](https://agentskillshub.top/skill/Finderchangchang/promo-video-skill/?utm_source=github&utm_medium=awesome-list) |
| [new-xp/ultrademo](https://github.com/new-xp/ultrademo) | 29 | Ultrademo is an automated demo video generator for any websites, SaaS applications, etc. - executed conveniently through a Claude Code skill. | [*pending*](https://agentskillshub.top/skill/new-xp/ultrademo/?utm_source=github&utm_medium=awesome-list) |
| [Arman-Luthra/aftr](https://github.com/Arman-Luthra/aftr) | 22 | Puppeteer for After Effects. Use AE with Claude Code to make production-ready videos. | *pending* |
| [AmazingAng/ccvideo](https://github.com/AmazingAng/ccvideo) | 20 | Claude-style promo videos from ground-truth captures — a Claude Code skill (Remotion) | [*pending*](https://agentskillshub.top/skill/AmazingAng/ccvideo/?utm_source=github&utm_medium=awesome-list) |
| [derrickgong87/demo-video-creation-skill](https://github.com/derrickgong87/demo-video-creation-skill) | 19 | A reusable Codex skill for creating polished SaaS and product demo videos from a company URL, screenshots, and product flows. | [*pending*](https://agentskillshub.top/skill/derrickgong87/demo-video-creation-skill/?utm_source=github&utm_medium=awesome-list) |
| [dlazy-ai/ai-product-video](https://github.com/dlazy-ai/ai-product-video) | 14 | AI agent skill (Claude Code / Codex) that turns your product into a cinematic promo video: 152 shot recipe cards, 209 style variants, tuned Remotion… | [SAFE](https://agentskillshub.top/skill/dlazy-ai/ai-product-video/?utm_source=github&utm_medium=awesome-list) |
| [kiki-lgtm-dot/cinematic-product-promo-skill](https://github.com/kiki-lgtm-dot/cinematic-product-promo-skill) | 14 | Remotion 产品宣传片 Agent Skill：150+ 镜头配方、200+ 动效预览、2.5D 运镜、节奏剪辑与声音设计。 | *pending* |
| [smit-vanani/claude-promo-video](https://github.com/smit-vanani/claude-promo-video) | 13 | Turn a website URL into a premium, beat-locked product promo video with Remotion — original design system every time, music-onset-locked scenes, self… | [*pending*](https://agentskillshub.top/skill/smit-vanani/claude-promo-video/?utm_source=github&utm_medium=awesome-list) |
| [memex-lab/product-launch-video-skill](https://github.com/memex-lab/product-launch-video-skill) | 12 | AI agent skill for creating cinematic product launch videos with Remotion | [*pending*](https://agentskillshub.top/skill/memex-lab/product-launch-video-skill/?utm_source=github&utm_medium=awesome-list) |
| [iart-ai/ad-video-skills](https://github.com/iart-ai/ad-video-skills) | 8 | Claude Code skills for ad / advertising video — turn one motion-graphics template into batches of on-brand, A/B-testable ad creative, launch films, a… | *pending* |
| [ChenShuo2004/cs-shotcraft-skill](https://github.com/ChenShuo2004/cs-shotcraft-skill) | 5 | CS Skills 产品宣传片 skill：真实产品界面、镜头表运镜、152 张镜头配方卡与 Ink Press 模板。Remotion 出片，配乐默认可选。 | *pending* |
| [mrieck/demoday-claude-plugin](https://github.com/mrieck/demoday-claude-plugin) | 5 | Claude Code plugin that creates demo videos for your projects. Claude is given tools to drive the browser/cli, make recordings, and uses FAL.ai, Elev… | *pending* |
| [opus-pro/opus-video-studio](https://github.com/opus-pro/opus-video-studio) | 5 | Opus Video Tools for Codex and Claude Code, with 43 open-source video templates and motion components, gallery previews, and demos. | *pending* |

<a id="type-explainer"></a>
## 🎓 Explainers

[Open this type on the live page, sorted by stars →](https://agentskillshub.top/best/opus-5-5-video/?utm_source=github&utm_medium=awesome-list#type-explainer)

| Repo | Stars | What it does | Security |
|---|---:|---|---|
| [Alisa0808/vox-director](https://github.com/Alisa0808/vox-director) | 2.0k | Turn one topic into a finished Vox-style paper-collage explainer/ad video — automated end to end on Atlas Cloud + ffmpeg. An agent skill. | [SAFE](https://agentskillshub.top/skill/Alisa0808/vox-director/?utm_source=github&utm_medium=awesome-list) |
| [Vincentwei1021/video-talkcraft](https://github.com/Vincentwei1021/video-talkcraft) | 1.2k | Agent skill that turns Claude Code / Codex into a motion-design studio for voiceover-driven explainer videos — word-level voiceover sync, 109 motion… | [SAFE](https://agentskillshub.top/skill/Vincentwei1021/video-talkcraft/?utm_source=github&utm_medium=awesome-list) |
| [adithya-s-k/manim_skill](https://github.com/adithya-s-k/manim_skill) | 1.1k | Agent skills for Manim to create 3Blue1Brown style animations. | [SAFE](https://agentskillshub.top/skill/adithya-s-k/manim_skill/?utm_source=github&utm_medium=awesome-list) |
| [wshuyi/remotion-video-skill](https://github.com/wshuyi/remotion-video-skill) | 383 | A Claude Code Skill for creating programmatic videos with Remotion framework | [CAUTION](https://agentskillshub.top/skill/wshuyi/remotion-video-skill/?utm_source=github&utm_medium=awesome-list) |
| [shuyicc/MathLens](https://github.com/shuyicc/MathLens) | 360 | MathLens 是一个专注于数学题目视频讲解的 Agent Skill。你只需粘贴一道数学题（图片或文字），它就能自动完成从题目分析、可视化讲解、配音脚本到 Manim 动画视频的全流程制作。单条视频1-10 分钟，成本 0.2-1 元以内。 | [SAFE](https://agentskillshub.top/skill/shuyicc/MathLens/?utm_source=github&utm_medium=awesome-list) |
| [hi-nikola/hand-drawn-explainer-video-nikola](https://github.com/hi-nikola/hand-drawn-explainer-video-nikola) | 347 | 中文手绘知识讲解视频 Codex Skill：逐笔故事、双语义岛、让怪诞小黑动起来与程序动画 | [SAFE](https://agentskillshub.top/skill/hi-nikola/hand-drawn-explainer-video-nikola/?utm_source=github&utm_medium=awesome-list) |
| [Anil-matcha/vox-ai-motion-graphics-generator](https://github.com/Anil-matcha/vox-ai-motion-graphics-generator) | 223 | 🎬 Turn any topic into a finished Vox-style paper-collage explainer / motion graphics video — script, collage keyframes, animation, voice-over, music… | [SAFE](https://agentskillshub.top/skill/Anil-matcha/vox-ai-motion-graphics-generator/?utm_source=github&utm_medium=awesome-list) |
| [runesleo/claude-video-kit](https://github.com/runesleo/claude-video-kit) | 120 | Agent Skill + Remotion pipeline: brief/script → review receipt → narrated 9:16 explainer. RC: video-explainer skill. | [SAFE](https://agentskillshub.top/skill/runesleo/claude-video-kit/?utm_source=github&utm_medium=awesome-list) |
| [sunxiayi/make-blender-education-video-skill](https://github.com/sunxiayi/make-blender-education-video-skill) | 45 | A Codex and Claude Code skill for creating fact-checked cinematic educational videos with Blender | [*pending*](https://agentskillshub.top/skill/sunxiayi/make-blender-education-video-skill/?utm_source=github&utm_medium=awesome-list) |
| [znyupup/knowledge-explainer-skill](https://github.com/znyupup/knowledge-explainer-skill) | 45 | 把一份 markdown 文稿，自动生成讲解动画视频 — Powered by Remotion + AI Agent | *pending* |
| [Anil-matcha/zack-d-films-ai-video-generator](https://github.com/Anil-matcha/zack-d-films-ai-video-generator) | 37 | 🎬 Turn any topic into a finished Zack D Films-style 3D animated short — curiosity-loop script, character sheets, 3D keyframes, Veo 3.1 motion, voiceo… | [*pending*](https://agentskillshub.top/skill/Anil-matcha/zack-d-films-ai-video-generator/?utm_source=github&utm_medium=awesome-list) |
| [santmun/video-vox](https://github.com/santmun/video-vox) | 32 | Crea shorts verticales animados estilo Vox sobre cualquier tema con Claude Code + Remotion (cartoon + voz + música + SFX) | *pending* |
| [Mr-funny/hbg-douyin-code-explainer-video](https://github.com/Mr-funny/hbg-douyin-code-explainer-video) | 31 | HBG Codex skill for deterministic Chinese 9:16 HyperFrames explainer videos with dialogue TTS, global Whisper sync, stable BGM and final visual QA. | [SAFE](https://agentskillshub.top/skill/Mr-funny/hbg-douyin-code-explainer-video/?utm_source=github&utm_medium=awesome-list) |
| [vibe-motion/remotion-code-motion-explainer](https://github.com/vibe-motion/remotion-code-motion-explainer) | 31 | AI Agent skill for continuous, editable Remotion explainers — created by Bingo | [SAFE](https://agentskillshub.top/skill/vibe-motion/remotion-code-motion-explainer/?utm_source=github&utm_medium=awesome-list) |
| [iart-ai/explainer-video-skills](https://github.com/iart-ai/explainer-video-skills) | 26 | Explainer video skills for Claude Code: script, storyboard, and render narrated explainers, year-in-review recaps, and animated diagrams. | *pending* |
| [Phantomlau3674/voxstylehub-steven](https://github.com/Phantomlau3674/voxstylehub-steven) | 24 | Standalone Codex skill for Vox-inspired editorial collage knowledge videos with deterministic Remotion assembly and optional generated motion. | [*pending*](https://agentskillshub.top/skill/Phantomlau3674/voxstylehub-steven/?utm_source=github&utm_medium=awesome-list) |
| [Mng-dev-ai/explainer-video](https://github.com/Mng-dev-ai/explainer-video) | 19 | AI skill that turns any topic into an animated narrated explainer video. Runs locally, free, works with Claude Code / Codex / Cursor. | [*pending*](https://agentskillshub.top/skill/Mng-dev-ai/explainer-video/?utm_source=github&utm_medium=awesome-list) |
| [holy-templar/vox-animated-ad-mcp](https://github.com/holy-templar/vox-animated-ad-mcp) | 19 | Vox-style paper-collage animated video skill for AI agents — Claude + MaxFusion AI MCP (Google Omni). One sentence in, a full explainer or ad out, en… | [*pending*](https://agentskillshub.top/skill/holy-templar/vox-animated-ad-mcp/?utm_source=github&utm_medium=awesome-list) |
| [aijiduonadegou/Paper-Cut](https://github.com/aijiduonadegou/Paper-Cut) | 16 | 无需视频模型，即可制作拼贴动画的skill。用图像模型定稿、原图拆层与 HyperFrames 代码动画制作可编辑 Paper Cut / Vox 风格纸拼贴科普视频；支持三阶段审批、旁白、音效、文字动效与确定性 QA。 | *pending* |
| [chenyuxiaojin/cyxj-hyperframes](https://github.com/chenyuxiaojin/cyxj-hyperframes) | 16 | Open-source HTML+GSAP video projects & reusable toolkit for Claude Code tutorial videos, powered by HeyGen HyperFrames. | *pending* |
| [cclank/lanshu-html2video-skill](https://github.com/cclank/lanshu-html2video-skill) | 14 | Turn web articles into polished 1080p videos with Codex and Remotion | *pending* |
| [kakaxi12/vox-director-codex](https://github.com/kakaxi12/vox-director-codex) | 11 | Codex skill for creating Vox-style editorial paper-collage videos with ImageGen, HyperFrames, and MiniMax narration. | *pending* |
| [ssrajadh/paperview](https://github.com/ssrajadh/paperview) | 9 | Turn research papers, codebases, etc. into explainer videos, local rendering + TTS, Claude Code plugin. | *pending* |
| [pjecuacion/script-to-video-skill](https://github.com/pjecuacion/script-to-video-skill) | 7 | Public script-to-video skill for HyperFrames workflows with sanitized paths and secret-free examples. | *pending* |
| [ahmdd4vd/MotionCraft](https://github.com/ahmdd4vd/MotionCraft) | 6 | Clean, high-taste motion graphics videos made by your AI agent with Remotion. One-command Agent Skill: npx skills add ahmdd4vd/motioncraft | [SAFE](https://agentskillshub.top/skill/ahmdd4vd/MotionCraft/?utm_source=github&utm_medium=awesome-list) |
| [jinjin1/scenewright](https://github.com/jinjin1/scenewright) | 6 | Claude Code-native pipeline: a source text → narrated, Remotion-rendered YouTube explainer video. Any topic, ~$0/video, local Korean TTS (Supertonic)… | *pending* |
| [sukai213/bilibili-ai-video](https://github.com/sukai213/bilibili-ai-video) | 6 | AI 科技测评视频制作与 B 站自动发布技能（Codex Skill）：原创文案 / Qwen3-TTS 配音 / 全息幻灯片 / ffmpeg 剪辑 / 投稿 API 自动发布 | *pending* |
| [BusyBee3333/animated-explainer-skills](https://github.com/BusyBee3333/animated-explainer-skills) | 5 | Build Kurzgesagt-quality animated explainer videos as one self-contained HTML file — GSAP choreography patterns, YouTube-retention method, overlap au… | *pending* |
| [centraltowerlabs/diagram-tour](https://github.com/centraltowerlabs/diagram-tour) | 5 | This Claude Skill makes it easy to generate explainer video tours of your codebase (or any other complex system) | *pending* |
| [coding-ax/docvideoer](https://github.com/coding-ax/docvideoer) | 5 | 文档转视频 skills。用于把文档 URL、网页文章、Markdown 或粘贴文本转换成带中文旁白的 Remotion 讲解视频，包含正文提取、分镜生成、免费 TTS、视频项目搭建和 MP4 渲染。 | *pending* |
| [cymcymcymcym/notes-to-video](https://github.com/cymcymcymcym/notes-to-video) | 5 | Turn notes into animated explainer videos in the style popularized by 3Blue1Brown. Claude Code skill + Manim + TTS + ffmpeg. | [*pending*](https://agentskillshub.top/skill/cymcymcymcym/notes-to-video/?utm_source=github&utm_medium=awesome-list) |
| [git-story-film](https://github.com/EverMind-AI/Raven/tree/HEAD/skills/git-story-film) | in EverMind-AI/Raven: 4.1k | Direct a two-minute hand-drawn animated film from a repository's Git history: story, character, storyboard, HTML review studio, then a 4K/60fps MP4. | [SAFE](https://agentskillshub.top/skill/EverMind-AI/Raven/?utm_source=github&utm_medium=awesome-list) |

<a id="type-editing"></a>
## ✂️ Editing

[Open this type on the live page, sorted by stars →](https://agentskillshub.top/best/opus-5-5-video/?utm_source=github&utm_medium=awesome-list#type-editing)

| Repo | Stars | What it does | Security |
|---|---:|---|---|
| [FireRedTeam/FireRed-OpenStoryline](https://github.com/FireRedTeam/FireRed-OpenStoryline) | 3.4k | FireRed-OpenStoryline is an AI video editing agent that transforms manual editing into intention-driven directing through natural language interactio… | [SAFE](https://agentskillshub.top/skill/FireRedTeam/FireRed-OpenStoryline/?utm_source=github&utm_medium=awesome-list) |
| [Agentchengfeng/chengfeng-videocut-skills](https://github.com/Agentchengfeng/chengfeng-videocut-skills) | 3.0k | 用 Claude Code Skills 做的视频剪辑 Agent | [SAFE](https://agentskillshub.top/skill/Agentchengfeng/chengfeng-videocut-skills/?utm_source=github&utm_medium=awesome-list) |
| [0xsline/OpenChatCut](https://github.com/0xsline/OpenChatCut) | 2.0k | Open-source, local-first conversational AI video editor with a professional multi-track timeline, Agent Skills, MCP integration, and Remotion renderi… | [SAFE](https://agentskillshub.top/skill/0xsline/OpenChatCut/?utm_source=github&utm_medium=awesome-list) |
| [cartesiancs/cartcut](https://github.com/cartesiancs/cartcut) | 756 | Video Editor for AI agents, built on the belief that open source can beat commercial tools | [SAFE](https://agentskillshub.top/skill/cartesiancs/cartcut/?utm_source=github&utm_medium=awesome-list) |
| [hetpatel-11/Adobe_Premiere_Pro_MCP](https://github.com/hetpatel-11/Adobe_Premiere_Pro_MCP) | 610 | Adobe Premiere Pro MCP. Tools for AI-driven video editing via MCP, for Codex, Claude, and other MCP clients. | [SAFE](https://agentskillshub.top/skill/hetpatel-11/Adobe_Premiere_Pro_MCP/?utm_source=github&utm_medium=awesome-list) |
| [zenstory-ai/video-recap-skills](https://github.com/zenstory-ai/video-recap-skills) | 533 | Claude Code / Codex skills that turn a video into a Chinese narration recap (视频解说): scene detection, ASR, VLM, script, TTS, ffmpeg assembly, optional… | [SAFE](https://agentskillshub.top/skill/zenstory-ai/video-recap-skills/?utm_source=github&utm_medium=awesome-list) |
| [hassancs91/claude-youtube-editor](https://github.com/hassancs91/claude-youtube-editor) | 314 | Record the talking head, Claude Code does the rest: the cut, the visuals, the voice, the sound effects, the thumbnail, and the YouTube upload. Every… | [SAFE](https://agentskillshub.top/skill/hassancs91/claude-youtube-editor/?utm_source=github&utm_medium=awesome-list) |
| [leancoderkavy/premiere-pro-mcp](https://github.com/leancoderkavy/premiere-pro-mcp) | 292 | Adobe Premiere Pro MCP — independent, local-first server for supported workflows. Connect Claude, Codex, or Cursor through a local CEP bridge. | [SAFE](https://agentskillshub.top/skill/leancoderkavy/premiere-pro-mcp/?utm_source=github&utm_medium=awesome-list) |
| [AgriciDaniel/claude-shorts](https://github.com/AgriciDaniel/claude-shorts) | 217 | Interactive longform-to-shortform video creator — Claude Code skill with Remotion-rendered animated captions, AI segment scoring, cursor tracking, an… | [SAFE](https://agentskillshub.top/skill/AgriciDaniel/claude-shorts/?utm_source=github&utm_medium=awesome-list) |
| [erduo1998-cell/erduo-broll-loop-engineering](https://github.com/erduo1998-cell/erduo-broll-loop-engineering) | 203 | SRT 驱动的双后端 B-roll Agent Skill：自动路由 HyperFrames / Remotion，集成 152 张 Shotcraft 镜头卡 | [SAFE](https://agentskillshub.top/skill/erduo1998-cell/erduo-broll-loop-engineering/?utm_source=github&utm_medium=awesome-list) |
| [Cassette-Editor/oh-my-cassette](https://github.com/Cassette-Editor/oh-my-cassette) | 154 | 你的随身 AI 剪辑搭档 \| Pocket AI co-editor for video montage — AI video editing plugin & MCP server for Claude Code, Codex, Hermes & OpenCode | [SAFE](https://agentskillshub.top/skill/Cassette-Editor/oh-my-cassette/?utm_source=github&utm_medium=awesome-list) |
| [znyupup/ai-video-editing-skill](https://github.com/znyupup/ai-video-editing-skill) | 135 | AI Agent Skill for automated vlog editing. Feed raw footage, get a finished video. Powered by ffmpeg + Whisper + Vision API. | [SAFE](https://agentskillshub.top/skill/znyupup/ai-video-editing-skill/?utm_source=github&utm_medium=awesome-list) |
| [naive-kun/naive-video-skill](https://github.com/naive-kun/naive-video-skill) | 130 | A Codex skill for turning talking-head videos into captioned, animated final videos. | [SAFE](https://agentskillshub.top/skill/naive-kun/naive-video-skill/?utm_source=github&utm_medium=awesome-list) |
| [Monet-AI-Editor/Monet](https://github.com/Monet-AI-Editor/Monet) | 116 | Edit Videos and Design Images with Claude code or Codex | [SAFE](https://agentskillshub.top/skill/Monet-AI-Editor/Monet/?utm_source=github&utm_medium=awesome-list) |
| [blixvip/easyedit](https://github.com/blixvip/easyedit) | 109 | Type a movie, get a captioned speech + beat-cut fan edit. Local-first, no API keys, works with your AI bot (Claude Code / Codex). | [SAFE](https://agentskillshub.top/skill/blixvip/easyedit/?utm_source=github&utm_medium=awesome-list) |
| [ayushozha/AdobePremiereProMCP](https://github.com/ayushozha/AdobePremiereProMCP) | 106 | 🎬 AI-powered MCP server for Adobe Premiere Pro — 1,027 tools for timeline editing, color grading, audio mixing, effects, export & more. Control video… | [SAFE](https://agentskillshub.top/skill/ayushozha/AdobePremiereProMCP/?utm_source=github&utm_medium=awesome-list) |
| [louisedesadeleer/cut-video](https://github.com/louisedesadeleer/cut-video) | 101 | Claude Code skill: tighten long recordings — remove silences, ums, dead air. Preserves laughs and comedic pauses. Fast on Apple Silicon. | [SAFE](https://agentskillshub.top/skill/louisedesadeleer/cut-video/?utm_source=github&utm_medium=awesome-list) |
| [AKMessi/vex](https://github.com/AKMessi/vex) | 85 | claude code for video editing | [*pending*](https://agentskillshub.top/skill/AKMessi/vex/?utm_source=github&utm_medium=awesome-list) |
| [JUNKDOGE-JOE/after-effects-mcp](https://github.com/JUNKDOGE-JOE/after-effects-mcp) | 75 | Agent-driven Adobe After Effects automation. MCP server + CEP plugin enabling Codex/Cursor/Claude Code to drive AE through 30 ae.* tools. | [SAFE](https://agentskillshub.top/skill/JUNKDOGE-JOE/after-effects-mcp/?utm_source=github&utm_medium=awesome-list) |
| [kurbaitaev/ghost-editor](https://github.com/kurbaitaev/ghost-editor) | 61 | AI video editor for talking-head reels: 7 styles, face-safe captions, motion scenes, reverse-engineer any reference edit. A Claude Code / agent skill… | [*pending*](https://agentskillshub.top/skill/kurbaitaev/ghost-editor/?utm_source=github&utm_medium=awesome-list) |
| [hahadu4520/vlog-cut](https://github.com/hahadu4520/vlog-cut) | 49 | Narration-driven video editing pipeline for Claude Code · 给 Claude Code 用的「按文案剪辑」流水线 | *pending* |
| [ops120/video-recap-skills-plus](https://github.com/ops120/video-recap-skills-plus) | 39 | Clip any video into a narration recap with claude code skill｜用claude code skill把任何视频剪辑成中文解说视频，支持剪映导出 | [*pending*](https://agentskillshub.top/skill/ops120/video-recap-skills-plus/?utm_source=github&utm_medium=awesome-list) |
| [Kappaemme-git/codex-video-short-maker-skill](https://github.com/Kappaemme-git/codex-video-short-maker-skill) | 35 |  | *pending* |
| [darrenli6/JJKoubo](https://github.com/darrenli6/JJKoubo) | 32 | JJ Koubo (JJ口播) is a local-first collection of video editing Skills for talking-head, interview, knowledge-sharing, and other videos centered on spok… | [SAFE](https://agentskillshub.top/skill/darrenli6/JJKoubo/?utm_source=github&utm_medium=awesome-list) |
| [krusemediallc/video-editor-agent](https://github.com/krusemediallc/video-editor-agent) | 17 | Claude Code skill pack: edit short-form videos end to end — style-clone a reference reel, build a branded motion-graphics edit, ElevenLabs sound desi… | [SAFE](https://agentskillshub.top/skill/krusemediallc/video-editor-agent/?utm_source=github&utm_medium=awesome-list) |
| [manthanpatelll/leadgenman-video-skills](https://github.com/manthanpatelll/leadgenman-video-skills) | 17 | Six Claude Code skills for an automated video content pipeline: produce, srt, ytdescription, igcaption, reel-overlay, new-series. By @LeadGenMan. | *pending* |
| [jincheng2026/jc-remotion-skills](https://github.com/jincheng2026/jc-remotion-skills) | 14 | Remotion Koubo Skill — 口播视频的 AI 成片工作流（Codex / Claude Code 双端）：粗剪+SRT 进，带 MG 包装、音效、母带的成片出 | [SAFE](https://agentskillshub.top/skill/jincheng2026/jc-remotion-skills/?utm_source=github&utm_medium=awesome-list) |
| [cocolayuan/videoclip-AI-skill](https://github.com/cocolayuan/videoclip-AI-skill) | 13 | Claude Skill-powered video editing toolkit - 视频全自动剪辑 | [SAFE](https://agentskillshub.top/skill/cocolayuan/videoclip-AI-skill/?utm_source=github&utm_medium=awesome-list) |
| [PoetCoderJun/MotionTalk](https://github.com/PoetCoderJun/MotionTalk) | 12 | Turn an edited talking video into a polished motion-graphics video with one Agent Skill. | [SAFE](https://agentskillshub.top/skill/PoetCoderJun/MotionTalk/?utm_source=github&utm_medium=awesome-list) |
| [ZiadAbdelkarim/beat-synced-edit](https://github.com/ZiadAbdelkarim/beat-synced-edit) | 10 | Automatic beat-synced video editing: feed it a song and raw footage, it analyzes beats, energy, and scenes, then cuts a ready-to-post edit. Pure Pyth… | [SAFE](https://agentskillshub.top/skill/ZiadAbdelkarim/beat-synced-edit/?utm_source=github&utm_medium=awesome-list) |
| [misbahsy/tiktok-ig-shorts](https://github.com/misbahsy/tiktok-ig-shorts) | 10 | Generate Viral Tiktok and Instagram Shorts using Hyperframes with Claude and Codex | *pending* |
| [qingyunAGI/qingyun-cine-skill](https://github.com/qingyunAGI/qingyun-cine-skill) | 10 | qingyun-cine-skill: PLAN-FIRST cinematic video editing Codex skill for trailers, beat-sync edits, promos, and highlights. | *pending* |
| [Fagan1024/smart-video-editor](https://github.com/Fagan1024/smart-video-editor) | 7 | AI video editing skill that watches your footage before cutting. Vision model analyzes every frame, scores usability, drops bad takes, reorders by na… | *pending* |
| [hahadu4520/newcut-video-clipping-skill](https://github.com/hahadu4520/newcut-video-clipping-skill) | 6 | Open-source Codex skill for semantic Chinese video clipping with hooks, captions, cleanup, and FFmpeg rendering | *pending* |
| [jackjls/jtxvideo-skill](https://github.com/jackjls/jtxvideo-skill) | 5 | Codex + HyperFrames 口播视频制作 Skill：按 SRT、结构、分镜、设计、渲染的审核流程生成 AI 金融短视频 | [*pending*](https://agentskillshub.top/skill/jackjls/jtxvideo-skill/?utm_source=github&utm_medium=awesome-list) |

<a id="type-shorts"></a>
## 📱 Shorts & social

[Open this type on the live page, sorted by stars →](https://agentskillshub.top/best/opus-5-5-video/?utm_source=github&utm_medium=awesome-list#type-shorts)

| Repo | Stars | What it does | Security |
|---|---:|---|---|
| [Yuuhann1999/codex-storyboard](https://github.com/Yuuhann1999/codex-storyboard) | 344 | 本地多项目 Codex 视频分镜工作台，支持图片/视频生成任务、HyperFrames 与 Remotion 自动回填。Local multi-project storyboard workspace for Codex. | [SAFE](https://agentskillshub.top/skill/Yuuhann1999/codex-storyboard/?utm_source=github&utm_medium=awesome-list) |
| [hassancs91/claude-faceless-shorts-creator](https://github.com/hassancs91/claude-faceless-shorts-creator) | 267 | A faceless YouTube-Shorts factory driven by Claude Code: pure-TSX Remotion visuals, ElevenLabs voice with word-exact captions, library-first sound de… | [SAFE](https://agentskillshub.top/skill/hassancs91/claude-faceless-shorts-creator/?utm_source=github&utm_medium=awesome-list) |
| [jaxxchen003/book-video-factory](https://github.com/jaxxchen003/book-video-factory) | 105 | Portable Codex skill for auditable, rights-aware Chinese book-review short-video workflows. | [SAFE](https://agentskillshub.top/skill/jaxxchen003/book-video-factory/?utm_source=github&utm_medium=awesome-list) |
| [Maartenlouis/remotion-ads](https://github.com/Maartenlouis/remotion-ads) | 59 | Claude Code skill for creating Instagram Reels & Carousel ads with Remotion | [SAFE](https://agentskillshub.top/skill/Maartenlouis/remotion-ads/?utm_source=github&utm_medium=awesome-list) |
| [pyang5166/gbro-collage-info](https://github.com/pyang5166/gbro-collage-info) | 51 | 半调纸拼贴风信息动画 Agent Skill · Halftone paper-collage info-graphic animations from voiceover scripts (HyperFrames, no image models) | [*pending*](https://agentskillshub.top/skill/pyang5166/gbro-collage-info/?utm_source=github&utm_medium=awesome-list) |
| [liangdabiao/story-handdrawn-video](https://github.com/liangdabiao/story-handdrawn-video) | 48 | 把一段 中文/英文 故事文本变成 9:16 竖屏（720×1280）手绘蜡笔风短视频。Remotion 技术的视频 Skill。基于 Agnes Video V2.0（纯文生视频，当前 $0/秒）+ edge-tts（免费旁白）的全免费视频制作方案。 | *pending* |
| [yuwenbin121/book-video-production-skill](https://github.com/yuwenbin121/book-video-production-skill) | 17 | A Codex skill for producing fact-based vertical book videos | [*pending*](https://agentskillshub.top/skill/yuwenbin121/book-video-production-skill/?utm_source=github&utm_medium=awesome-list) |
| [intelligent-iterations/ii-content-engine](https://github.com/intelligent-iterations/ii-content-engine) | 14 | AI-powered content generation and auto-posting engine built for Claude Code and Codex. Generate viral videos, carousels, and reels for TikTok, Instag… | *pending* |
| [iart-ai/tiktok-video-skills](https://github.com/iart-ai/tiktok-video-skills) | 11 | Short-form video skills for Claude Code — engineer Reels, TikToks, and YouTube Shorts that survive the swipe. | *pending* |
| [adriiita/vertical-video-editing-skill](https://github.com/adriiita/vertical-video-editing-skill) | 10 | Claude skill: turn a script + talking-head media into a polished, creator-grade vertical 9:16 short with HyperFrames — editorial look, A-roll/B-roll… | *pending* |
| [Samin12/samin-reel-engine-plugin](https://github.com/Samin12/samin-reel-engine-plugin) | 8 | A modular Codex plugin for source-backed reels: research, scripting, real B-roll, fast edits, quality review and giveaway handoffs. | *pending* |
| [riffkit/skill](https://github.com/riffkit/skill) | 7 | Official Riffkit skill — riff a winning TikTok into your own short video from your AI agent (Claude Code, Cursor) or the browser. Riff the formula, n… | [SAFE](https://agentskillshub.top/skill/riffkit/skill/?utm_source=github&utm_medium=awesome-list) |
| [zoglmk/codex-video-pipeline](https://github.com/zoglmk/codex-video-pipeline) | 6 | 从选题、脚本和素材到成片、封面与发布包的 AI 视频生产流水线 Skill | *pending* |
| [icytear-svg/podcast-to-video](https://github.com/icytear-svg/podcast-to-video) | 5 | Codex skill for turning podcast episodes into platform-ready captioned videos | [SAFE](https://agentskillshub.top/skill/icytear-svg/podcast-to-video/?utm_source=github&utm_medium=awesome-list) |
| [inematds/skill-video-plan-editor](https://github.com/inematds/skill-video-plan-editor) | 5 | Skill que transforma assunto/link em plano profissional de edição de vídeo (renderer-agnóstico) + render opcional via FFmpeg/Auto-Editor/HyperFrames | *pending* |
| [liangdabiao/wechat-article-remotion](https://github.com/liangdabiao/wechat-article-remotion) | 5 | 动画skill: 把任意一篇微信公众号文章 转成 Studio 风格的 Remotion 视频 —— 暖白画布 + 上下镜像透视格子 + 顶部章节进度 + 公众号原文图完整保留 | *pending* |
| [marketcalls/story-telling](https://github.com/marketcalls/story-telling) | 5 | Turn a context into a narrated story video: Sarvam AI voiceover, FLUX 2 artwork, Remotion render. Ships Claude Code skills. | [*pending*](https://agentskillshub.top/skill/marketcalls/story-telling/?utm_source=github&utm_medium=awesome-list) |
| [ninestonelee/youtube-shorts-factory](https://github.com/ninestonelee/youtube-shorts-factory) | 5 | Claude Code skill — YouTube reference video analysis → benchmarking → 30%+ adaptation → AI Shorts production workflow | *pending* |
| [wendymardigian-prog/Editor-IA-Pro](https://github.com/wendymardigian-prog/Editor-IA-Pro) | 5 | AI-powered video editor built with Remotion and Claude Code | *pending* |

<a id="type-avatar"></a>
## 🧑‍💼 Avatars

[Open this type on the live page, sorted by stars →](https://agentskillshub.top/best/opus-5-5-video/?utm_source=github&utm_medium=awesome-list#type-avatar)

| Repo | Stars | What it does | Security |
|---|---:|---|---|
| [heygen-com/skills](https://github.com/heygen-com/skills) | 454 | HeyGen AI agent skills — avatar creation and video production via the v3 Video Agent pipeline | [SAFE](https://agentskillshub.top/skill/heygen-com/skills/?utm_source=github&utm_medium=awesome-list) |
| [Upload-Post/avatar-mix](https://github.com/Upload-Post/avatar-mix) | 130 | Generate 16:9 & 9:16 videos with your HeyGen avatar, animated backgrounds (HyperFrames), music, SFX and Hormozi captions — then publish them to every… | [*pending*](https://agentskillshub.top/skill/Upload-Post/avatar-mix/?utm_source=github&utm_medium=awesome-list) |
| [AgriciDaniel/lipnardo](https://github.com/AgriciDaniel/lipnardo) | 22 | HeyGen avatar video generation skill for Claude Code. Batch, templates, translation, photo avatars, TTS. Stdlib-only Python. | [*pending*](https://agentskillshub.top/skill/AgriciDaniel/lipnardo/?utm_source=github&utm_medium=awesome-list) |
| [zlong6943-commits/football-prediction-avatar-video](https://github.com/zlong6943-commits/football-prediction-avatar-video) | 9 | Codex skill for verified Chinese football prediction avatar videos with official logos, captions, motion graphics, and approval gates. | [SAFE](https://agentskillshub.top/skill/zlong6943-commits/football-prediction-avatar-video/?utm_source=github&utm_medium=awesome-list) |

<a id="type-story"></a>
## 📖 Stories & animation

[Open this type on the live page, sorted by stars →](https://agentskillshub.top/best/opus-5-5-video/?utm_source=github&utm_medium=awesome-list#type-story)

| Repo | Stars | What it does | Security |
|---|---:|---|---|
| [gnipbao/story-to-handdrawn-video](https://github.com/gnipbao/story-to-handdrawn-video) | 2.1k | Agent skill: convert Chinese story copy or ordered images into a hand-drawn diary-comic animation (silent MP4 picture track). | [SAFE](https://agentskillshub.top/skill/gnipbao/story-to-handdrawn-video/?utm_source=github&utm_medium=awesome-list) |
| [JohnHeibel/ClaudeAnimationBase](https://github.com/JohnHeibel/ClaudeAnimationBase) | 415 | A starter kit for animating hand-painted cartoons with Claude: p5.js + p5.brush, the Clawd character, 31 acted emotions and a guide for the model | [*pending*](https://agentskillshub.top/skill/JohnHeibel/ClaudeAnimationBase/?utm_source=github&utm_medium=awesome-list) |
| [aaronyi97/image-story-video-wizard](https://github.com/aaronyi97/image-story-video-wizard) | 351 | A confirmation-gated Codex and WorkBuddy skill for audio-first image-story video production. | [SAFE](https://agentskillshub.top/skill/aaronyi97/image-story-video-wizard/?utm_source=github&utm_medium=awesome-list) |
| [liyue-aigc/xianxia-cinematic-video-director](https://github.com/liyue-aigc/xianxia-cinematic-video-director) | 268 | Codex Skill for Eastern xianxia storyboards, camera movement and video continuity. | [SAFE](https://agentskillshub.top/skill/liyue-aigc/xianxia-cinematic-video-director/?utm_source=github&utm_medium=awesome-list) |
| [LetMeHappyCode/auto-video-agent](https://github.com/LetMeHappyCode/auto-video-agent) | 216 | 自动流水线化生成成套「分镜插画提示词 → AI 生图 → 拼接成片」的视频，基于 Agent / Skill / Workflow 编排。 | [SAFE](https://agentskillshub.top/skill/LetMeHappyCode/auto-video-agent/?utm_source=github&utm_medium=awesome-list) |
| [lemomo-ai/lemo-opuscar](https://github.com/lemomo-ai/lemo-opuscar) | 177 | 39 film styles, each a reusable style prompt plus a short film made entirely in code by Claude Opus 5.5. Pick a style, bring your own story, and let… | [SAFE](https://agentskillshub.top/skill/lemomo-ai/lemo-opuscar/?utm_source=github&utm_medium=awesome-list) |
| [Mr-funny/hbg-life-simulation](https://github.com/Mr-funny/hbg-life-simulation) | 140 | HBG Agent Skill for Chinese life-simulation narrative videos with consistent comic IP, rapid multi-life openings, Edge TTS, synchronized captions, zo… | [SAFE](https://agentskillshub.top/skill/Mr-funny/hbg-life-simulation/?utm_source=github&utm_medium=awesome-list) |
| [liangdabiao/story-handdrawn-remotion](https://github.com/liangdabiao/story-handdrawn-remotion) | 35 | 视频SKILL: 把一段 中文/英文 故事文本变成 「手绘日记漫画风」竖屏视频。 核心方法论：**不是把一张漂亮图配文字朗读，而是把每句故事拆成「文字 → 黑白画稿 → 彩色插画」三阶段横向擦除揭示，让一句话被画出三次。 | *pending* |
| [AsadMoulviDev/reel-video](https://github.com/AsadMoulviDev/reel-video) | 28 | Create AI videos with Claude Code, Codex, Cursor, and Grok Build, with no extra generation fees beyond the plans you already pay for | *pending* |
| [AllenAI2014/remotion-guofeng-starter](https://github.com/AllenAI2014/remotion-guofeng-starter) | 25 | 国风纸片动画：Remotion 风格资产库 + 制作流程 Skill。给 AI 一首诗/成语，照这套国风纸片拼贴风格从零出片，全程代码渲染不进剪辑。 | *pending* |
| [taylorzhou16/video-gen](https://github.com/taylorzhou16/video-gen) | 9 | AI Video Editing Skill for Claude Code | [SAFE](https://agentskillshub.top/skill/taylorzhou16/video-gen/?utm_source=github&utm_medium=awesome-list) |
| [tuzhechen2005/opus-video-skills](https://github.com/tuzhechen2005/opus-video-skills) | 6 | Video-making skills for Claude Opus 5.5 in Claude Code — every frame and note generated in code, one skill per style: hand-painted animation, kinetic… | [*pending*](https://agentskillshub.top/skill/tuzhechen2005/opus-video-skills/?utm_source=github&utm_medium=awesome-list) |

<a id="type-motion"></a>
## 🎞 Motion graphics

[Open this type on the live page, sorted by stars →](https://agentskillshub.top/best/opus-5-5-video/?utm_source=github&utm_medium=awesome-list#type-motion)

| Repo | Stars | What it does | Security |
|---|---:|---|---|
| [diffusionstudio/lottie](https://github.com/diffusionstudio/lottie) | 5.5k | Generate production-ready Lottie animations with Claude Code or Codex | [SAFE](https://agentskillshub.top/skill/diffusionstudio/lottie/?utm_source=github&utm_medium=awesome-list) |
| [nolangz/pixel2motion](https://github.com/nolangz/pixel2motion) | 2.3k | AI logo animation skill: turn raster logos into smooth SVG animation, animated HTML demos, GIF/video previews, and motion QA evidence. | [SAFE](https://agentskillshub.top/skill/nolangz/pixel2motion/?utm_source=github&utm_medium=awesome-list) |
| [pyang5166/gbro-collage-broll](https://github.com/pyang5166/gbro-collage-broll) | 1.3k | 半调纸拼贴 B-roll 生成 skill：三闸门审批，Gemini Omni Flash 首尾帧组装动画 \| Editorial halftone paper-collage B-roll agent skill | [SAFE](https://agentskillshub.top/skill/pyang5166/gbro-collage-broll/?utm_source=github&utm_medium=awesome-list) |
| [MegaTroll222/VOX-COLLAGE-BROLL](https://github.com/MegaTroll222/VOX-COLLAGE-BROLL) | 211 | Turn one spoken line into a paper-collage explainer video — Claude Code skill + MaxFusion MCP. English adaptation of gbro-collage-broll by pyang5166. | [*pending*](https://agentskillshub.top/skill/MegaTroll222/VOX-COLLAGE-BROLL/?utm_source=github&utm_medium=awesome-list) |
| [Liamrjohnston/remotion-motion-graphics-skill](https://github.com/Liamrjohnston/remotion-motion-graphics-skill) | 72 | Production-ready Remotion motion graphics skills for AI video workflows | [*pending*](https://agentskillshub.top/skill/Liamrjohnston/remotion-motion-graphics-skill/?utm_source=github&utm_medium=awesome-list) |
| [AgriciDaniel/claude-gif](https://github.com/AgriciDaniel/claude-gif) | 28 | Ultimate GIF creator skill for Claude Code. 6 generation pipelines: Remotion, Veo 3.1, SVG-to-transparent-GIF, FFmpeg, image sequences, AI frames. Pa… | *pending* |
| [toufuim/personal-ip-brand-intro-skill](https://github.com/toufuim/personal-ip-brand-intro-skill) | 20 | 開源 Codex Skill：用文字、原創插圖或使用者圖片製作個人 IP 品牌開場，支援上傳音樂對拍與無音樂自主節拍。 | [*pending*](https://agentskillshub.top/skill/toufuim/personal-ip-brand-intro-skill/?utm_source=github&utm_medium=awesome-list) |
| [fernandokaraka/remotion-motion-graphics-skill](https://github.com/fernandokaraka/remotion-motion-graphics-skill) | 11 | Claude Code skill: build animated motion graphics as real video with Remotion — title cards, lower thirds, overlays with real alpha for Premiere/FCP/… | *pending* |
| [zhenwusw/orca-motion-skill](https://github.com/zhenwusw/orca-motion-skill) | 7 | Agent skill for in-scene motion graphics built from abstract, design-token-driven shapes; pairs with orca-transition-skill. | *pending* |
| [acelera-agency/html-animation](https://github.com/acelera-agency/html-animation) | 6 | Motion graphics as code. An agent skill for building frame-exact animated logos, kinetic typography and brand videos as a single HTML file, then expo… | *pending* |

<a id="type-craft"></a>
## 📝 Scripts & learning

[Open this type on the live page, sorted by stars →](https://agentskillshub.top/best/opus-5-5-video/?utm_source=github&utm_medium=awesome-list#type-craft)

| Repo | Stars | What it does | Security |
|---|---:|---|---|
| [jtydhr88/screenwriting-skills](https://github.com/jtydhr88/screenwriting-skills) | 1.4k | Professional agent skills for screenwriting, television writing and dramaturgy | [SAFE](https://agentskillshub.top/skill/jtydhr88/screenwriting-skills/?utm_source=github&utm_medium=awesome-list) |
| [eternityspring/reelbench-skills](https://github.com/eternityspring/reelbench-skills) | 843 | Learning notes and tooling skills for AI video - AI 视频相关的学习与工具 skill | [SAFE](https://agentskillshub.top/skill/eternityspring/reelbench-skills/?utm_source=github&utm_medium=awesome-list) |
| [wyuzhi/qisi-video-remix](https://github.com/wyuzhi/qisi-video-remix) | 111 | 视频创意改编 Agent Skill：参考视频 → 剧本 → 分镜 → 分段生成提示词。By qisi. | [SAFE](https://agentskillshub.top/skill/wyuzhi/qisi-video-remix/?utm_source=github&utm_medium=awesome-list) |
| [adityaarsharma/youtube-marketing-skills](https://github.com/adityaarsharma/youtube-marketing-skills) | 44 | Open-source agent-agnostic YouTube growth toolkit — 21 AI commands + live channel MCP. Works with Claude Code, Cursor, Codex, Windsurf, Gemini CLI &… | [SAFE](https://agentskillshub.top/skill/adityaarsharma/youtube-marketing-skills/?utm_source=github&utm_medium=awesome-list) |
| [wocha-xiaoli/video-shot-analysis-feishu](https://github.com/wocha-xiaoli/video-shot-analysis-feishu) | 36 | 视频拉片到飞书 Base：自动抽帧、逐镜头分析、倒推分镜与视频生成提示词的 Codex/OpenCode skill | [*pending*](https://agentskillshub.top/skill/wocha-xiaoli/video-shot-analysis-feishu/?utm_source=github&utm_medium=awesome-list) |
| [liuliu-66-create/ll-video-decomposer](https://github.com/liuliu-66-create/ll-video-decomposer) | 24 | 专业的五层视频拆解 Codex Skill：支持视频链接、本地媒体和逐字稿。 | [*pending*](https://agentskillshub.top/skill/liuliu-66-create/ll-video-decomposer/?utm_source=github&utm_medium=awesome-list) |
| [chenmisss/laoxu-video-script](https://github.com/chenmisss/laoxu-video-script) | 9 | 老徐·自媒体起号方法论 skill：定位/选题/破立合成稿/五维诊断/去车轱辘话/112条母题库。零基础起号，Claude Code/Codex skill。 | *pending* |
| [erduo1998-cell/video-script-builder](https://github.com/erduo1998-cell/video-script-builder) | 9 | 把中文视频逐字稿转换为可执行 HyperFrames 分镜规格的 AI Agent Skill | [*pending*](https://agentskillshub.top/skill/erduo1998-cell/video-script-builder/?utm_source=github&utm_medium=awesome-list) |
| [sharon-laicc/viral-video-decomposer](https://github.com/sharon-laicc/viral-video-decomposer) | 5 | 拆解爆款短视频，生成镜头级拉片、爆款机制、AI 生产蓝图和视频生成 brief 的 Codex/Claude skill。｜A Codex/Claude skill for decomposing hot short videos into shot-by-shot analysis, reusa… | [*pending*](https://agentskillshub.top/skill/sharon-laicc/viral-video-decomposer/?utm_source=github&utm_medium=awesome-list) |

<a id="type-music"></a>
## 🎵 Music videos

[Open this type on the live page, sorted by stars →](https://agentskillshub.top/best/opus-5-5-video/?utm_source=github&utm_medium=awesome-list#type-music)

| Repo | Stars | What it does | Security |
|---|---:|---|---|
| [JohnHeibel/PDoomVideo](https://github.com/JohnHeibel/PDoomVideo) | 1.1k | Source code for the Claude Opus 5.5 music video for I'm Upping My P(doom) | [*pending*](https://agentskillshub.top/skill/JohnHeibel/PDoomVideo/?utm_source=github&utm_medium=awesome-list) |
| [ledbetterljoshua/functional-emotions-video](https://github.com/ledbetterljoshua/functional-emotions-video) | 45 | A painted music video for "Functional Emotions", made by Claude Opus 5.5: custom GPU brushstroke renderer, storyboard, and 7 parallel chapter agents. | [*pending*](https://agentskillshub.top/skill/ledbetterljoshua/functional-emotions-video/?utm_source=github&utm_medium=awesome-list) |

**Security** is the grade of the repo's README and install steps on Agent Skills Hub. *pending* means the catalog has not graded it yet.

## Related collections

- [opusvideo/awesome-claude-video](https://github.com/opusvideo/awesome-claude-video) — videos people made with Opus 5.5, with the original posts. Works, where this list is tools.
- [TripoGrowthLab/awesome-opus-5-5-prompts](https://github.com/TripoGrowthLab/awesome-opus-5-5-prompts) — Opus 5.5 prompts for 3D scenes, games and simulations.

## Add a repo

Open an issue with the GitHub URL. It goes through the same review as every entry; the rules above decide, stars do not.

---

Machine-readable copy: [`data/skills.json`](data/skills.json). Generated 2026-09-27.
