# DeepSeek Harness 插件库

> DeepSeek 开源「一切皆插件」Agent 驾驭层生态精选（按能力域归类 + 热度排序）
>
> 👈 **返回主站对应模块**：[DeepSeek Harness 插件库](https://soycodetrail.top/dsh-plugins)  ·  🏠 全站：[https://soycodetrail.top](https://soycodetrail.top)
>
> 🤖 本仓库内容由脚本自动同步自主站，**与网站保持实时同步**（source 数据变更 → GitHub Actions 推送即更新）。最近同步：2026-08-31 01:34:03

## 📚 系列展示站（更多精选内容，互相导流）

- [Vibe Coding 作品展](https://github.com/soycodetrail/vibe-coding-gallery) · [主站模块 ↗](https://soycodetrail.top/vibe-coding) · [在线浏览 ↗](https://soycodetrail.github.io/vibe-coding-gallery/)
- [AI 技能工坊](https://github.com/soycodetrail/ai-skills-workshop) · [主站模块 ↗](https://soycodetrail.top/skills) · [在线浏览 ↗](https://soycodetrail.github.io/ai-skills-workshop/)
- [开源书籍宝库](https://github.com/soycodetrail/ai-books-treasury) · [主站模块 ↗](https://soycodetrail.top/books) · [在线浏览 ↗](https://soycodetrail.github.io/ai-books-treasury/)

## 📑 内容导航（1165 个条目 / 8 个分类）

- [🧭 核心引擎](#cat-核心引擎)
- [🎨 界面与体验](#cat-界面与体验)
- [🤖 Agent 与自动化](#cat-agent-与自动化)
- [🧠 记忆与知识](#cat-记忆与知识)
- [🛠️ 工具与连接](#cat-工具与连接)
- [👁️ 多模态与视觉](#cat-多模态与视觉)
- [🛡️ 安全与运维](#cat-安全与运维)
- [🎮 趣味与社区](#cat-趣味与社区)

---

<a id="cat-核心引擎" name="cat-核心引擎"></a>

### 🧭 核心引擎

- [deepseek-harness](https://github.com/deepseek-ai/deepseek-harness) — DSH 官方本体：一切皆插件的 Agent Harness，由 Cordis 驱动，v0.1 开发者预览（MIT 开源）。  
  标签：官方 / Cordis / Agent 框架
- [Cordis](https://github.com/cordisjs/cordis) — 驱动 DSH 的可插拔运行时内核，插件通过 extension 接缝注册，支持生命周期与依赖编排。  
  标签：运行时 / 依赖注入
- [Oh My DSH](https://github.com/omdsh-dev/omdsh) — 社区维护的实验性插件生态，自带 Hub 目录、Runtime 与插件模板，开箱即用。  
  标签：社区 / 插件平台
- [Awesome DSH Plugins](https://github.com/AdamPlatin123/awesome-dsh-plugins) — DSH 插件总目录，每日追踪全 GitHub 的 dsh-plugin topic 与兼容性状态。  
  标签：索引 / 每日更新
- [awesome-deepseek-harness](https://github.com/0xsline/awesome-deepseek-harness) — DSH 生态精选清单——插件、工具与基础设施，中英双语。  
  标签：索引 / 双语
- [awesome-DSH-plugin](https://github.com/Alex-Yanggg/awesome-DSH-plugin) — 为 DSH 精心整理的实用插件、扩展、工具与开发资源清单。  
  标签：索引
- [awesome-dsh-plugin](https://github.com/bruc3van/awesome-dsh-plugin) — DSH 插件生态的中英双语精选与全量索引。  
  标签：索引 / 双语
- [awesome-deepseek-harness (清单)](https://github.com/Dominic789654/awesome-deepseek-harness) — DSH 的插件、技能、MCP server、编排器、聚合器与 UI 精选清单。  
  标签：索引
- [Plugin Template](https://github.com/omdsh-dev/plugin-template) — 自包含 ESM Cordis 插件仓库模板，一行命令生成可发布插件骨架。  
  标签：模板 / 脚手架
- [dsh-plugin-skills](https://github.com/omdsh-dev/dsh-plugin-skills) — 在 Agent 会话内构建与测试 DeepSeek Harness 插件的技能集。  
  标签：开发 / 技能
- [plugin-registry](https://github.com/vlln/plugin-registry) — DSH 插件生态基建：薄控制台 + make-dsh-plugin skill。  
  标签：基建
- [dsh-hub](https://github.com/omdsh-dev/dsh-hub) — OMDSH Hub：DSH 社区扩展目录与 Profile 生成管理器。  
  标签：目录 / 社区
- [dsh-hub-workshop](https://github.com/omdsh-dev/dsh-hub-workshop) — OMDSH 生态的公共目录、评审投影与不可变 feed 权威。  
  标签：目录 / 评审
- [dsh-find-plugins](https://github.com/Nagi-ovo/dsh-find-plugins) — DSH 找插件技能：从全 GitHub 的 dsh-plugin topic 检索候选插件。  
  标签：发现 / 技能
- [omdsh-runtime](https://github.com/omdsh-dev/omdsh-runtime) — OMDSH Runtime：无头执行层。  
  标签：运行时
- [fabric](https://github.com/omdsh-dev/fabric) — Cordis Fabric 工作区：DSH 的 Fabric/Mixin 扩展层。  
  标签：扩展层
- [toybox](https://github.com/omdsh-dev/toybox) — DSH 插件玩具箱：收藏「有意思」的 DSH 插件。  
  标签：收藏
- [web-components](https://github.com/omdsh-dev/web-components) — DSH Web Component 适配器插件包。  
  标签：适配器
- [oh-my-dsh (社区索引)](https://github.com/wangshunnn/oh-my-dsh) — DeepSeek Harness 社区插件索引：自动发现、证据分级、场景精选。  
  标签：索引
- [dsh-work](https://github.com/vibeinging/dsh-work) — 面向 DSH 插件的本地优先 AI 工作台。  
  标签：工作台
- [dsh-suite](https://github.com/whyihaveyou/dsh-suite) — DeepSeek Harness 插件中英双语精选目录。  
  标签：目录
- [Top](https://github.com/xiaohai-78/Top) — dsh-external 插件生态的每日排行榜。  
  标签：榜单
- [dshfind](https://github.com/hikariming/dshfind) — DSH 学习与分享社区。  
  标签：社区
- [dsh-plugin-dev](https://github.com/omdsh-dev/dsh-plugin-dev) — DSH 插件开发踩坑与做法档案。  
  标签：开发 / 文档
- [cocode](https://github.com/cocode-agency/cocode) — 开箱即用的 DeepSeek Harness 发行版：桌面 GUI、终端 TUI 与 Harness 集成。  
  标签：发行版 / 桌面 / 终端
- [dsh-ecosystem](https://github.com/zoahdev/dsh-ecosystem) — DSH 插件生态的活地图：带质量信号、Bug 雷达、缺口雷达与每周编辑的精选插件目录。  
  标签：索引 / 生态 / 质量信号
- [dsh-subscribe](https://github.com/zoahdev/dsh-subscribe) — DSH 的 Steam 式插件市场：网页一键订阅，一条命令同步进你的 dsh profile。  
  标签：市场 / 订阅 / 一键
- [dsh-market](https://github.com/dsh-market/dsh-market) — DeepSeek Harness 内置插件市场：浏览、搜索、一键安装的可视化市场。  
  标签：市场 / 一键安装 / 可视化
- [dsh-minimal-anchor](https://github.com/rand0wn/dsh-minimal-anchor) — DSH 插件：仅在会话首轮裁剪工具 Schema 并注入结构化前缀，降低上下文噪声。  
  标签：核心 / 上下文 / 前缀
- [deepseek-harness-action](https://github.com/Lixiaoyiao/deepseek-harness-action) — Community GitHub Action for DeepSeek Harness — AI Code Review · CI Diagnosis · Auto Fix · Issue → PR  
  标签：deepseek / Community / GitHub / 核心引擎
- [dsh-pub](https://github.com/dsh-pub/dsh-pub) — The bilingual, source-backed registry and installer for the DeepSeek Harness plugin ecosystem.  
  标签：pub / The / bilingual / 核心引擎
- [dsh-testsuite](https://github.com/cocofhu/dsh-testsuite) — testsuite of dsh plugins  
  标签：testsuite / dsh / plugins / 核心引擎
- [awesome-dsh-plugin](https://github.com/beancookie/awesome-dsh-plugin) — Awesome DeepSeek Harness (DSH) Plugin  
  标签：awesome / 核心引擎
- [dsh-render-engine](https://github.com/CH4ACKO3/dsh-render-engine) — Shiki, syntax highlighting, and code rendering services for DeepSeek Harness  
  标签：render / Shiki / syntax / 核心引擎
- [dsh-routing-suite](https://github.com/yjh051108/dsh-routing-suite) — dsh-routing-suite — injector + router-standard kit: install the runtime injector first, then the task-aware reasoning-mode router preset (measured P1-P23).  
  标签：routing / dsh-routing-suite / injector / 核心引擎
- [dsh-skin-market](https://github.com/kingOfSoySauce/dsh-skin-market) — DeepSeek Harness skin market 皮肤市场 已收录100+DSH 皮肤 完善评分系统加人工审核，有便捷的社区收录入口；有在线页面方便在线浏览，也有插件方便管理本地皮肤  
  标签：plugin-market / skin-market / themes
- [dsh-plugin-hub](https://github.com/Noob-stupid/dsh-plugin-hub) — DeepSeek Harness (DSH) 插件管理面板：一键启用/停用插件 + GitHub dsh-plugin 插件市场，带插件详情与一键安装 | Plugin manager & marketplace for DeepSeek Harness  
  标签：dsh-plugins / github / help-wanted / plugin-manager
- [deepseek-harness-for-vscode](https://github.com/skymecode/deepseek-harness-for-vscode) — deepseek-harness for vscode .This is a community project, and we welcome your valuable feedback!  
  标签：deepseek / dsh-plugin-market / dsh-plugins / vscode
- [dsh-plugin-hub](https://github.com/dshplugin/dsh-plugin-hub) — DeepSeek Harness 社区内置插件市场（dsh-plugin）— 搜索插件、下载并安装 4000+ 人工精选社区插件，每日更新、完全免费。内置在 Harness「设置 → 插件中心」，无需离开应用即可浏览、搜索、安装各类 AI 插件。  
  标签：agent / ai / cli / community-plugins
- [dsh-vision-opencode](https://github.com/poiuyjie/dsh-vision-opencode) — DSH plugin: Auto-convert images to text for pure-text LLMs (DeepSeek etc.) via any vision model. No need to switch your main model.  
  标签：dsh-plugin-market / dsh-plugins
- [Deepseek-Harness-for-VS-Code](https://github.com/Vithrive/Deepseek-Harness-for-VS-Code) — Deepseek Harness for VS Code  
  标签：deepseek / dsh-plugin-market / dsh-plugins
- [dsh-mpkg-wallpaper](https://github.com/XHR666/dsh-mpkg-wallpaper) — Load Wallpaper Engine .mpkg / Steam Workshop folders as the DeepSeek Harness web background: video & web wallpapers, scene static-frame & layer composite, time-of-day switching, carousel rotation lists, unified frosted blur, theme color. 浏览器内加载壁纸引擎 mpkg/创意工坊目录作为 DSH 网页背景：视频/网页壁纸、场景静态帧与图层合成、多时段切换、轮播列表、统一磨砂虚化、主题颜色。  
  标签：background / deepseek / live-wallpaper / theme
- [dsh-mcp-skill-panel](https://github.com/lilyblessing/dsh-mcp-skill-panel) — MCP 与技能管理面板：设置页展示 MCP 服务器与 Skill 目录，随时启停释放上下文占用。  
  标签：dsh-bundle / mcp / settings / skill
- [dsh-plugin.github.io](https://github.com/dsh-plugin/dsh-plugin.github.io) — DeepSeek Harness community plugin workshop and directory  
  标签：dsh-plugin-verify / dsh-plugins
- [dsh-plugin-directory](https://github.com/dingzhenyao/dsh-plugin-directory) — DSH Web GUI plugin: a browsable, searchable, stats-driven directory of GitHub DeepSeek Harness plugins (dsh-plugin topic), with CDN hot update, README-gated install, and live search.  
  标签：核心引擎
- [dsh-toolbox-web](https://github.com/AbcdefgXW/dsh-toolbox-web) — dsh 工具箱：会话/回收站/子目录/搜索/预设/配置管理 + 定时心跳/长消息折叠 | Toolbox plugin for dsh: session/trash/subdir/search/preset/config + scheduled heartbeat & long-message collapse  
  标签：chat / deepseek / dsh-plugins / plugin
- [dsh-msg-hub](https://github.com/AbcdefgXW/dsh-msg-hub) — dsh IM 渠道桥：微信/QQ/飞书接入 + 主动推送 | IM channel bridge for dsh: WeChat/QQ/Feishu with proactive push  
  标签：bot / bridge / channel / channels
- [DSH-Plugin-Hub](https://github.com/usertianziyang/DSH-Plugin-Hub) — DSH Plugin Hub — 基于 GitHub REST Search API 构建的 dsh-plugin 主题仓库索引站。数据每 6 小时自动同步、完整性校验后发布为静态快照；前端基于 React + TypeScript (Vite)，支持中英双语、全文搜索、分类筛选与分页，浏览器零 API 调用、零追踪，即开即用。  
  标签：github-api / plugin-hub / react / search
- [dsh-personal-workbench](https://github.com/Dely0/dsh-personal-workbench) — DSH 个人工作台：日历 + 任务列表 + AI 澄清/拆解/执行/复盘 | Personal workbench for DeepSeek Harness Web: calendar + task list + AI assistant  
  标签：a-agent / dsh-plugin-market / dsh-plugins / task-management
- [dsh-plugin-toolbox](https://github.com/c-ling/dsh-plugin-toolbox) — DeepSeek Harness Web GUI 工具箱插件：打开工作区目录并置顶会话。  
  标签：agent / ai / cordis / deepseek
- [deepseek-harness-background](https://github.com/HaoyueQin/deepseek-harness-background) — 为 DeepSeek Harness Web GUI 添加自定义背景图片：上传本地图片或粘贴图片链接，可调不透明度、遮罩、面板透明与毛玻璃模糊，带实时预览，5% 阻尼滑块松手即存，遮罩自动适配明暗主题。  
  标签：deepseek / dsh-plugin-desktop / dsh-plugin-market / dsh-plugins
- [dsh-market-site](https://github.com/xrj/dsh-market-site) — Automated static site source and Cloudflare Pages deployment for DSH Plugin Marketplace  
  标签：cloudflare-pages / github-actions
- [dsh-agent-plugins-market](https://github.com/Sivan757/dsh-agent-plugins-market) — DeepSeek Harness (DSH) plugin marketplace: install & inject Claude Code / Codex / Cursor agent plugins — skills, MCP servers, hooks & slash commands — from git marketplace repos, with a Web GUI market page.  
  标签：agent-plugins / agentic-ai / ai-agents / claude
- [dsh-beautify](https://github.com/nlqh7/dsh-beautify) — DeepSeek Harness Dream Skin，DSH theme plugin: Dream Skin color presets with a settings-page switcher.  
  标签：dsh-plugin-market / dsh-plugin-theme / dsh-plugins
- [dsh-usage-statistics-panel](https://github.com/HaoyueQin/dsh-usage-statistics-panel) — DSH web plugin: per-day token usage statistics with a GitHub-style activity heatmap, cache hit-rate curve and per-model breakdown  
  标签：cordis / data-visualization / llm / plugin
- [dsh.fish](https://github.com/stvlynn/dsh.fish) — Discover and install DeepSeek Harness plugins, skills, MCP servers, agent presets, bundles, and profiles.  
  标签：agentic-ai / ai-agents / cloudflare-workers / deepseek
- [dsh-plugin-background](https://github.com/haozhu11/dsh-plugin-background) — Background image plugin for the DeepSeek Harness web UI (dsh web): upload local images as the whole-UI background, with a theme-aware readability matte, WebP-first compression and IndexedDB persistence.  
  标签：核心引擎
- [math-research-dsh](https://github.com/xsoc1/math-research-dsh) — DSH adaptation of the math-research Codex plugin marketplace: rigorous-open-math-research, manage-math-research-program, math-research-workflow, lean-verify as DeepSeek Harness skills.  
  标签：核心引擎
- [dsh-growth](https://github.com/robauto-ai/dsh-growth) — Robauto Digital Signal Hub growth plugin — thin MIT-licensed client for Robauto Signal Strength, llms.txt generation, AI search data and the AgentHub catalog.  
  标签：aeo / growth-agent / mcp / robauto
- [DSH-CustomWallpapers-Glassmorphism-Theme](https://github.com/sujiu0616-art/DSH-CustomWallpapers-Glassmorphism-Theme) — dsh可自定义壁纸玻璃风主题  
  标签：deepseek / deepseek-harness-plugins / dsh-plugin-market / dsh-plugins
- [dsh-subagent-model-visibility](https://github.com/AGSQ11/dsh-subagent-model-visibility) — A small DeepSeek Harness plugin that shows the actual provider/model used by a subagent directly inside the existing native subagent tool-call row.  
  标签：dsh-plugin-market / dsh-plugins
- [dsh-sidebar-Explorer-Plus](https://github.com/Wulabalabo/dsh-sidebar-Explorer-Plus) — 一个 dsh-better-sidebar 的消费插件：在侧边栏新增一个「文件」tab，内置一棵固定在工作区（cwd）内的文件树，提供真正的文件管理能力——上传、移动、删除、重命名、新建文件夹。它补充了 better-sidebar 自带 Explorer 缺失的「写」操作（Explorer 只读）  
  标签：dsh-better-sidebar / dsh-plugin-market / dsh-plugins
- [dshplugin](https://github.com/oa1mgo/dshplugin) — Community-built discovery and verification registry for DeepSeek Harness plugins.  
  标签：cloudflare-workers / deepseek / plugin-registry / plugins
- [dsh-jenkins](https://github.com/jsoncode/dsh-jenkins) — 可以在DeepSeek Harness中，快捷配置和管理多台 Jenkins 服务器与 Token， 支持设置页配置、模型工具触发构建、工作区级「执行 Jenkins Job」入口。无硬编码路径、 全量 TypeScript、可发布到 npm / GitHub。界面文案中英双语（跟随主界面语言）。  
  标签：dsh-jenkins / dsh-plugins
- [dsh-music-player](https://github.com/kendu76/dsh-music-player) — music player plugin for deepseek harness  
  标签：dsh-bundle / dsh-plugin-market / dsh-plugins
- [dsh-plugins](https://github.com/messiahyl/dsh-plugins) — DSH 插件总仓库：monorepo 开发 + 安装源（本地归档/npm/GitHub/索引）+ 第三方目录。国内网络友好，归档 sha256 校验。  
  标签：核心引擎
- [oh-my-dsh（700+ 全量）](https://github.com/LaplaceYoung/oh-my-dsh) — 面向 DSH 的插件生态——700+ 插件，只通过扩展接缝注册，社区全量聚合。  
  标签：社区 / 700+ 插件
- [DSH 架构上手指南](https://juejin.cn/post/7673390412729155638) — DeepSeek Harness 架构研究与上手指南：扩展接缝、插件开发路径、企微/Issue 社区。  
  标签：文档 / 入门
- [Awesome DSH Plugin 官网](https://awesome-dsh-plugin.com/) — 精选 DSH 插件目录网站：UI 增强、工作流、工具、通知与集成，持续更新。  
  标签：目录 / 网站
- [GitHub topic: dsh-plugin](https://github.com/topics/dsh-plugin) — 给插件仓库打 dsh-plugin topic 即可被发现；官方企微群 + GitHub Issue 社区入口。  
  标签：发现 / 社区
- [dsh-handbook](https://github.com/Electricitysheep/dsh-handbook) — 从 0 到 1 的 DSH 深度手册，含插件开发指南与架构讲解，社区口碑入门读物。  
  标签：文档 / 手册
- [awesome-deepseek-harness 排行榜](https://github.com/fendouai/awesome-deepseek-harness) — 带每日排行榜的 DSH 生态精选，看看别人都在装什么、怎么用。  
  标签：榜单 / 精选
- [awesome-dsh](https://github.com/stakeswky/awesome-dsh) — DSH 插件与工具精选索引，社区维护、持续更新。  
  标签：索引 / 精选
- [Aegis](https://github.com/GanyuanRan/Aegis) — 面向编码 Agent 的软件工程方法包：基线优先规划、系统化调试、完成前验证与修复/退役双轨跟踪。  
  标签：技能包 / 方法论
- [oh-dsh](https://github.com/hust-open-atom-club/oh-dsh) — 一套 DSH runtime，同时提供 Desktop、Web 与 TUI 三种开发体验。  
  标签：运行时 / 三端
- [dsh-market](https://github.com/2BingLing/dsh-market) — 持续收录 1500+ DSH 插件：中文搜索 + 五维评分 + 一键安装，Web 与侧边栏双形态。  
  标签：市场 / 评分
- [dsh-plugins-store](https://github.com/ZASENJC/dsh-plugins-store) — 自动分类、收录与验证 DeepSeek Harness 社区插件市场。  
  标签：市场 / 自动收录
- [dsh-forge](https://github.com/alex04130/dsh-forge) — DSH 扩展套件：运行时注入器、子代理派发与模型路由、插件市场/技能/管理面板、浏览器桥与 MCP 集成。  
  标签：扩展 / 注入器
- [Agent_Extensions](https://github.com/DDDFXYqiming/Agent_Extensions) — 通用智能体技能（General_skills）+ DSH 标准插件集合，开箱即用的 Agent 能力增强。  
  标签：技能 / 扩展
- [harness-flow-hub](https://github.com/Harzva/harness-flow-hub) — DSH Flow 与插件 Hub：面向 DeepSeek Harness Agent Stacks 的流程与插件聚合。  
  标签：Hub / 流程
- [dsh-plugin-market](https://github.com/NanmiCoder/dsh-plugin-market) — 已验证插件市场：从 Web UI 发现、审查、安装与卸载 DSH 插件。  
  标签：市场 / 安装
- [dsh-plugin-store](https://github.com/wink-run/dsh-plugin-store) — DeepSeek Harness 插件商店。  
  标签：商店
- [dsh-plugin-stars](https://github.com/ywsldxk/dsh-plugin-stars) — DSH 插件排行榜/目录：按 GitHub Stars 排序并自动更新。  
  标签：排行榜 / 目录
- [dsh-plugin-market](https://github.com/TheYoungChen/dsh-plugin-market) — DSH 插件市场：浏览/搜索/安装 dsh-plugin topic 插件。  
  标签：市场 / 安装
- [dsh-plugin-hub](https://github.com/aust24lzy/dsh-plugin-hub) — 开源插件导航站：实时同步 dsh-plugin 生态，按 Stars 动态排行。  
  标签：导航 / 目录
- [dsh-plugins-hub](https://github.com/TYEclipse/dsh-plugins-hub) — 独立插件索引：社区插件精选目录，每日更新。  
  标签：索引 / 目录
- [dsh-plugins](https://github.com/HackSing/dsh-plugins) — 中英双语、持续维护的 DeepSeek Harness 插件目录。  
  标签：目录 / 索引
- [awesome-dsh-plugins](https://github.com/kejixiaoliang/awesome-dsh-plugins) — DSH 插件精选目录：14 类 280+ 社区插件，覆盖 MCP/Skill/TUI/多 Agent/记忆/UI 皮肤。  
  标签：索引 / 目录
- [Oh-My-DSH](https://github.com/like-study1/Oh-My-DSH) — 社区维护的 DSH 插件聚合目录，自动同步 dsh-plugin 生态，每 4 小时维护。  
  标签：索引 / 社区
- [awesome-dsh-plugin](https://github.com/awesome-dsh-plugin/awesome-dsh-plugin) — DeepSeek Harness 插件精选列表（权威合集）。  
  标签：索引 / 合集
- [DSH-Plugins-Marketplace](https://github.com/bradeGithub/DSH-Plugins-Marketplace) — DSH 插件市场：在 Web GUI 一键浏览、安装与更新全部 dsh-plugin 插件。  
  标签：市场 / 安装
- [dsh-plugin-marketplace](https://github.com/YELEBAI/dsh-plugin-marketplace) — 已验证插件市场与自治注册表，面向 DeepSeek Harness。  
  标签：市场 / 注册表
- [awesome-deepseek-harness-plugins](https://github.com/imsai-sh/awesome-deepseek-harness-plugins) — DSH 插件市场/商店：3100+ 插件，含搜索、排行、安装命令与免费公开 API。  
  标签：市场 / API
- [dsh-community-plugins](https://github.com/HubaKing/dsh-community-plugins) — 社区插件生态 skill：教 Agent 从 GitHub dsh-plugin topic、dshmarket、npm 发现/评估/安装插件。  
  标签：skill / 发现
- [dsh-plugin-boundary](https://github.com/KoanJan/dsh-plugin-boundary) — 界定平台能力边界的 skill 插件：明确官方支持/未文档/不可为，避免开发者踩坑。  
  标签：skill / 边界
- [dashr](https://github.com/fgm-builds/dashr) — DSH RLM 模式：iPython 统一工具调用接口，上下文即变量、提示即变量。  
  标签：RLM / iPython
- [dsh-plugin-registry](https://github.com/majiayu000/dsh-plugin-registry) — 可搜索的 DSH 插件注册表：精选列表与 manifest 验证的 GitHub 发现。  
  标签：注册表 / 发现
- [cordis-rs](https://github.com/dshbox/cordis-rs) — Cordis 的 Rust 移植：DSH 核心插件框架，作用域依赖注入、生命周期效应、事件与结构化日志，零依赖。  
  标签：运行时 / Rust
- [dsh-pluginmanager](https://github.com/buhuikongpan/dsh-pluginmanager) — DSH 分层插件管理器：原生插件按系统/WebUI/工具层只读展示，用户扩展支持停用、启用、补登记、卸载与可编辑描述。  
  标签：插件管理 / 启用 / 卸载
- [deepseek-plugin-store](https://github.com/Ericwong5021/deepseek-plugin-store) — DeepSeek Harness 独立社区插件商店：发现、安装并提交经过验证的插件、工具与扩展。  
  标签：插件市场 / 商店 / 社区
- [dsh-plugin (huangrx6)](https://github.com/huangrx6/dsh-plugin) — DeepSeek Harness 插件合集：Skill 管理（导入/详情/多格式预览）、MCP 服务器管理、布局设置。  
  标签：Skill / MCP / 合集
- [dsh-hub (coderPerseus)](https://github.com/coderPerseus/dsh-hub) — DSH 插件发现站：帮你找到最好的 DeepSeek Harness 插件。  
  标签：目录 / 发现 / Hub
- [dsh-plugin-catalog](https://github.com/StarPivotNet/dsh-plugin-catalog) — StarPivot DeepSeek Harness 市场的官方插件目录。  
  标签：目录 / 市场 / StarPivot
- [dsh-plugins-public](https://github.com/StarPivotNet/dsh-plugins-public) — 可安装的 DSH 插件市场（设置 → 插件），公开安装源。  
  标签：市场 / 安装 / 插件
- [awesome-deepseek-harness-plugin](https://github.com/Shiyao-Huang/awesome-deepseek-harness-plugin) — 公开的 DSH 插件商店与生态数据集：安装规格、来源证据、SQLite 历史、媒体与时间线。  
  标签：索引 / 数据集 / 商店
- [dsh-plugin-market (chnjames)](https://github.com/chnjames/dsh-plugin-market) — DSH 插件市场：设置内一键安装社区插件，并提供公开目录站（浏览 / 复制安装命令）。  
  标签：插件市场 / 一键安装 / 目录
- [dsh-plugin-verify](https://github.com/qing3a/dsh-plugin-verify) — 验证 DSH 插件的 CLI：一条命令跑 mock-llm 完整 agent 循环，检查 waterfall 链与零副作用，产出验证报告。  
  标签：验证 / CLI / 测试
- [awesome-deepseek-harness-plugins](https://github.com/vvlife/awesome-deepseek-harness-plugins) — DeepSeek Harness（DSH）插件、工具、皮肤与扩展的中文精选清单。  
  标签：索引 / 清单
- [acks-dsh-plugins](https://github.com/shynloc/acks-dsh-plugins) — ACKS 的 DeepSeek Harness 插件库：AI Agent / 创意 / 知识 / 服务四类插件合集。  
  标签：合集 / 插件库
- [Oh-My-DSH](https://github.com/NoWint/Oh-My-DSH) — DeepSeek Harness 插件生态总览，每小时更新一次插件索引。  
  标签：生态 / 索引
- [dsh-plugin-store](https://github.com/sandbaseai/dsh-plugin-store) — DeepSeek Harness 原生插件市场：发现、筛选、安装并管理 2900+ 社区插件。  
  标签：市场 / 一键安装
- [sandbase-skills](https://github.com/sandbaseai/sandbase-skills) — 88 个可安装的开源 Agent 技能包，兼容 Codex/Claude Code/Cursor/Gemini CLI 与 DeepSeek Harness。  
  标签：技能 / 合集 / 兼容
- [deepfusion](https://github.com/wpc725562-dotcom/deepfusion) — DSH × Reasonix 融合 Agent 引擎：DeepSeek 原生编排 + 前缀缓存优化。  
  标签：编排 / 推理 / 融合
- [genesis-agents/dsh-plugins](https://github.com/genesis-agents/dsh-plugins) — DeepSeek Harness 插件集：读取 72 个 feed 生成播客 / 摘要 / 报告，并支持 Serper/Tavily/Brave 联网搜索。  
  标签：合集 / 资讯 / 搜索
- [awesome-dsh-plugins (dongsheng)](https://github.com/dongsheng123132/awesome-dsh-plugins) — 证据驱动的 DSH 插件雷达 + 2Origin 插件实验室。  
  标签：索引 / 雷达

<a id="cat-界面与体验" name="cat-界面与体验"></a>

### 🎨 界面与体验

- [Better Sidebar](https://github.com/omdsh-dev/DSH-better-sidebar) — 可扩展侧边栏工作台，第三方可注册新 Tab，集文件、Git、终端于一体。  
  标签：侧边栏 / 工作台
- [GenUI](https://github.com/omdsh-dev/dsh-genui) — 在助手回复中内联渲染交互式 UI 组件，让 Agent 直接产出可用界面。  
  标签：生成式 UI / 内联组件
- [Spotlight](https://github.com/0xsline/dsh-spotlight) — 键盘优先的命令面板，模糊搜索任意命令与文件，效率拉满。  
  标签：命令面板 / 快捷键
- [Turn Rewind](https://github.com/Anionex/dsh-turn-rewind) — 对话与时间旅行：回退对话内容与工作区状态，试错零成本。  
  标签：撤销 / 时光机
- [Deep Whale 皮肤](https://github.com/Small-tailqwq/dsh-deep-whale) — 全手绘像素鲸鱼伙伴皮肤系列，把冷清终端变成深海女仆工坊。  
  标签：皮肤 / 桌面宠物
- [DSH Companion](https://github.com/william-jin-cmu/dsh-companion) — 常驻桌面助手，任务完成后提醒你，还能摸鱼养只小猫。  
  标签：桌面助手 / 提醒
- [Orbis 移动端](https://github.com/icodesign/orbis) — 远程控制 DSH 的移动端客户端，手机上也能监控 Agent 打工。  
  标签：移动端 / 远程
- [dsh-visualize](https://github.com/Nagi-ovo/dsh-visualize) — DSH 对话内生成式 UI 插件。  
  标签：生成式 UI
- [dsh-message-edit](https://github.com/Moeblack/dsh-message-edit) — DSH 消息编辑插件：基于事件溯源。  
  标签：编辑
- [dsh-side-panel](https://github.com/ccq1/dsh-side-panel) — DSH Web 右侧工作区面板：Git 审查、文件浏览器与终端。  
  标签：面板
- [dsh-focus-chat](https://github.com/dingyi222666/dsh-focus-chat) — 为 dsh Web GUI 增加「聚焦会话」标签。  
  标签：聚焦
- [dsh-web-review](https://github.com/CanglongCl/dsh-web-review) — DeepSeek Harness Web GUI 的网页预览与元素批注插件。  
  标签：批注
- [dsh-annotation](https://github.com/omdsh-dev/dsh-annotation) — DSH Web 选中批注插件。  
  标签：批注
- [dsh-emoji](https://github.com/hellodigua/dsh-emoji) — 让 Agent 在正文输出受控 ASCII marker、由 Host 确定性转成行内 Markdown 图片。  
  标签：表情
- [dsh-plannotator](https://github.com/titanwings/dsh-plannotator) — DSH 计划批注插件：选中计划原文、逐条批注。  
  标签：计划 / 批注
- [dsh-input-history](https://github.com/lhh010/dsh-input-history) — DSH Web 输入历史插件：Ctrl+Up / Ctrl+Down 召回与切换已发送消息。  
  标签：输入
- [dsh-paste-input](https://github.com/lhh010/dsh-paste-input) — DSH WebUI 文件输入增强：Ctrl+V 粘贴 + 拖拽 + 选择文件。  
  标签：输入
- [dsh-chat-width](https://github.com/chen-001/dsh-chat-width) — DSH Web 消息宽度调节插件。  
  标签：排版
- [dsh-web-archive](https://github.com/renat3u/dsh-web-archive) — 把会话里正文之外的所有 display 折叠成内联小卡片。  
  标签：归档
- [dsh-stickers](https://github.com/william-jin-cmu/dsh-stickers) — DSH Stickers 贴纸插件：同一份 catalog 同时服务 WebUI 表情选择器。  
  标签：贴纸
- [dsh-navbar](https://github.com/vlln/dsh-navbar) — DSH 插件：对话节点导航条。  
  标签：导航
- [dsh-undo](https://github.com/LingLambda/dsh-undo) — 上下文撤销/重做插件。  
  标签：撤销
- [better-sidebar-office](https://github.com/HuanLinOTO/dsh-plugin-better-sidebar-plugin-office) — 为 better-sidebar 编辑器提供 Office 三件套文件预览。  
  标签：预览
- [ya-workspace-sidebar](https://github.com/HuanLinOTO/dsh-plugin-ya-workspace-sidebar) — DSH Web 工作区侧栏替代插件。  
  标签：侧边栏
- [dsh-drag-and-drop](https://github.com/bill9109/dsh-drag-and-drop) — DSH Web UI 文件拖拽插件。  
  标签：拖拽
- [dsh-deeplink](https://github.com/qyw233/dsh-deeplink) — DSH WebUI 深链插件。  
  标签：深链
- [dsh-turn-navigator](https://github.com/vibeinging/dsh-turn-navigator) — DSH Web 长对话回合导航。  
  标签：导航
- [dsh-split-panes](https://github.com/lehhair/dsh-split-panes) — DSH 对话分屏插件（PiUI 风格）。  
  标签：分屏
- [dsh-diff-viewer](https://github.com/lehhair/dsh-diff-viewer) — DSH Web GUI 的 PiUI 风格 diff 查看器插件。  
  标签：Diff
- [dsh-101](https://github.com/bill9109/dsh-101) — DSH 101 文档阅读器 profile bundle。  
  标签：文档
- [dsh-prompt-studio](https://github.com/Moeblack/dsh-prompt-studio) — 带实时预览编辑用户与内置 system prompt 段落。  
  标签：Prompt
- [dsh-web-ui-notify](https://github.com/bill9109/dsh-web-ui-notify) — DSH Web UI 桌面通知插件。  
  标签：通知
- [dsh-session-notification](https://github.com/dingyi222666/dsh-session-notification) — 会话完成、报错、向你提问或需要权限时发出提醒。  
  标签：通知
- [dsh-ultra-ui](https://github.com/havingautism/dsh-ultra-ui) — 把所有 Tool Call 展示为紧凑、可展开、可回放的折叠行。  
  标签：工具调用
- [dsh-custom-css](https://github.com/AnacondaKC/dsh-custom-css) — DSH WebUI 自定义 CSS 插件。  
  标签：CSS
- [dsh-at-file](https://github.com/omdsh-dev/dsh-at-file) — 为 DeepSeek Harness 提供 Codex 风格的 @file 文件引用。  
  标签：引用
- [dsh-open-in-vscode](https://github.com/omdsh-dev/dsh-open-in-vscode) — 从 Web GUI 直接以 VS Code 打开 DeepSeek Harness 工作区目录。  
  标签：VS Code
- [dsh-notification](https://github.com/omdsh-dev/dsh-notification) — DeepSeek Harness 回合完成的桌面通知。  
  标签：通知
- [ex-setting](https://github.com/omdsh-dev/ex-setting) — DSH Web 设置自动扩展包。  
  标签：设置
- [dsh-web-ui](https://github.com/zhu1090093659/dsh-web-ui) — DeepSeek Harness Web UI 的插件与皮肤合集。  
  标签：皮肤 / 合集
- [ui-status-label](https://github.com/alingalingling/ui-status-label) — 把鲸鱼娘思考时的 deep diving 状态文案自定义成任意文字。  
  标签：皮肤
- [dsh-ui-whale](https://github.com/lhh010/dsh-ui-whale) — DSH Web UI 全手绘像素鲸鱼伙伴插件。  
  标签：皮肤
- [dsh-ui-progress](https://github.com/lhh010/dsh-ui-progress) — DSH Web UI 会话进度插件。  
  标签：皮肤
- [tonghuashun-webui](https://github.com/renat3u/tonghuashun-webui) — 同花顺风格股票终端 + AI Agent 工作区融合的 DSH 终端式前端。  
  标签：皮肤 / 终端
- [dsh-plugin-background](https://github.com/gameswu/dsh-plugin-background) — DSH Web 界面背景插件。  
  标签：皮肤
- [dsh-deepcel](https://github.com/Small-tailqwq/dsh-deepcel) — Deepcel 工作簿皮肤（DeepSeek Harness Web GUI）。  
  标签：皮肤
- [dsh-tps](https://github.com/Small-tailqwq/dsh-tps) — DSH Web 实时 TPS 徽标。  
  标签：皮肤
- [dsh-qq2006](https://github.com/LaplaceYoung/dsh-qq2006) — DSH 的 QQ2006 皮肤插件。  
  标签：皮肤
- [dsh-ths-skin](https://github.com/AdamPlatin123/dsh-ths-skin) — DSH harness 客户端插件：同花顺行情终端风格皮肤。  
  标签：皮肤
- [whale-girl](https://github.com/vlln/whale-girl) — DSH Web GUI 桌面宠物插件（QQ 宠物形态）。  
  标签：宠物
- [dsh-plugin-pet-rs](https://github.com/HuanLinOTO/dsh-plugin-pet-rs) — DSH 桌面宠物鲸鱼（Rust 版）。  
  标签：宠物
- [dsh-blue-whale-maid](https://github.com/yuxino/dsh-blue-whale-maid) — 蓝鲸女仆：运行在 DSH Web GUI 里的桌面像素宠物插件。  
  标签：宠物
- [dsh-pet-corner](https://github.com/omdsh-dev/dsh-pet-corner) — DSH Pet Corner 摸鱼角：右下角一只可拖动的小猫。  
  标签：宠物
- [dsh-long-plugins](https://github.com/jackylong1987/dsh-long-plugins) — DSH Web 插件合集：上传管理器、工作区产出文件预览/编辑/最大化、技能文档浏览器与账户余额。  
  标签：Web UI / 合集 / 上传
- [agent-board](https://github.com/meisam2236/agent-board) — 为 DeepSeek Harness Web Profile 提供持久化、按工作区维度的 Agent 追踪管理看板。  
  标签：看板 / Agent / 管理
- [dsh-node-appearance](https://github.com/Max-Null/dsh-node-appearance) — DSH Web GUI 会话节点外观插件：按节点类型/工具名着色（可配置配色）+ 思考过程显示开关。  
  标签：Web UI / 节点 / 配色
- [Tokdash](https://github.com/JingbiaoMei/Tokdash) — Agent 仪表盘：会话与配额用量的可视化分析，跨供应商追踪与优化 Token 消耗。  
  标签：仪表盘 / Token / 配额
- [DSH-EasyRewrite](https://github.com/Renzic-Stone/DSH-EasyRewrite) — DSH Web 内最无感的消息重编辑插件，原版体验、兼容性强、功能可开关、设置丰富。  
  标签：Web UI / 重编辑 / 消息
- [Restart-service-button](https://github.com/DeBug-lzy/Restart-service-button) — DSH Web 插件：在网页界面右上角添加一键重启服务按钮，并提供按钮位置设置页。  
  标签：Web UI / 重启 / 按钮
- [dsh-plugins](https://github.com/onchainyaotoshi/dsh-plugins) — DeepSeek Harness 单仓插件集：dsh-file-explorer 面板文件树 + Web UI 工作区查看器。  
  标签：Web UI / 文件 / 资源管理
- [dsh-chat-rail](https://github.com/Max-Null/dsh-chat-rail) — 画卷式消息导航栏：右侧竖条 hover 展开画卷，scroll-spy 高亮居中跟随，与 better-sidebar 动画同步避让。  
  标签：Web UI / 导航 / 消息
- [dsh-motion-manager](https://github.com/zhoupengjie/dsh-motion-manager) — DeepSeek Harness 可配置的锚定弹层与设置动画。  
  标签：Web UI / 动画 / 弹层
- [dsh-explorer-plugin](https://github.com/dgadelha1/dsh-explorer-plugin) — DeepSeek Harness 轻量级资源管理器插件。  
  标签：资源管理 / Web UI
- [dsh-thinking-levels](https://github.com/drscrewdriver/dsh-thinking-levels) — DSH 思考强度（reasoning level）调节插件，控制推理深度。  
  标签：设置 / 推理 / 强度
- [dsh-window](https://github.com/he110Warudo/dsh-window) — DeepSeek Harness 桌面 GUI 客户端：双击启动，自动拉起 DSH Web 并在桌面窗口中打开。  
  标签：桌面 / GUI / Electron
- [dsh-desktop-browser](https://github.com/Mby159/dsh-desktop-browser) — Cordis 插件：以无地址栏的 --app 模式在浏览器中打开 DSH Web UI。  
  标签：桌面 / 浏览器 / app模式
- [dsh-mobile-ui](https://github.com/Perederey/dsh-mobile-ui) — DSH Web GUI 的移动端响应式布局插件：视口检测、触控友好控件与底部导航栏。  
  标签：Web UI / 移动端 / 响应式
- [dsh-webui](https://github.com/statem-li/dsh-webui) — DSH WebUI 增强：右上角「对话/轨迹」图块视图切换 + 会话消息导航。  
  标签：Web UI / 导航 / 视图
- [dsh-weniger-theme](https://github.com/lesliechowsh/dsh-weniger-theme) — Weniger（少即是好）：受 Dieter Rams 启发的 DSH Web GUI 极简主题。  
  标签：主题 / 极简 / Web UI
- [dsh-conversation-accents](https://github.com/YaoaY/dsh-conversation-accents) — 为 DSH Web 的助手 Markdown、工具调用与 Think 内容提供可自定义语义配色。  
  标签：Web UI / 配色 / 语义
- [dsh-gui](https://github.com/EricXu20266/dsh-gui) — DeepSeek Harness 的 Electron GUI 客户端：WebUI 转桌面，内核不改。  
  标签：桌面 / GUI / Electron
- [dsh-usage-plugin](https://github.com/feiyang-dev/dsh-usage-plugin) — DeepSeek Harness 用量与消耗插件（dsh-usage-plugin）—— 每次调用的 token 用量/缓存命中统计、峰谷计费、余额查询、CSV/JSON/PNG 导出，可经桌面端一键安装或命令行 dsh plugin add 安装。  
  标签：usage / dsh-usage-plugin / token / 界面与体验
- [dsh-tui-pi](https://github.com/fan56/dsh-tui-pi) — pi-style terminal UI for DeepSeek Harness (dsh) — pi-tui look & feel, dsh slash commands, GitHub light/dark themes, powerline footer  
  标签：tui / pi-style / terminal / 界面与体验
- [deepseek-harness-desktop](https://github.com/dsh-tauri-desk/deepseek-harness-desktop) — DeepSeek Harness Tauri 桌面版 | Only 5mb installer, zero environment setup, preset plugins, Windows / macOS / Linux.  
  标签：deepseek / Tauri / Only / 界面与体验
- [dsh-session-settings](https://github.com/u9521/dsh-session-settings) — Session settings, MCP servers, and Skill management plugin for DeepSeek Harness (DSH) Web GUI.  
  标签：session / settings / MCP / 界面与体验
- [dsh-workspace-jump](https://github.com/fogmodel/dsh-workspace-jump) — DSH web plugin: quickly create or switch to a workspace from a directory path via the sidebar Workspace button.  
  标签：workspace / web / quickly / 界面与体验
- [dsh-ui-usage-billing](https://github.com/kenz1117/dsh-ui-usage-billing) — Usage billing dashboard plugin for DeepSeek Harness: sidebar cost metrics, real usage aggregation from session logs, current multi-provider pricing catalog  
  标签：ui / Usage / billing / 界面与体验
- [dsh-webui-installer](https://github.com/FYHC1/dsh-webui-installer) — Legacy dsh plugin (v1.x, EOL): one-click desktop shortcuts that launch the DeepSeek Harness WebUI (dsh web) as a standalone app window on Windows / WSL / Linux. Need tray-based background management (multi-instance, systemd, self-update)? Use dsh-web-manager instead: https://github.com/FYHC1/dsh-web-manager  
  标签：webui / Legacy / dsh / 界面与体验
- [dsh-whale-pet](https://github.com/miku00039-01/dsh-whale-pet) — 🐋 DSH 桌宠:DeepSeek Harness 的 Windows 桌面宠物,一键启动/停止/监测服务,双击唤起 GUI,零依赖单文件 exe  
  标签：whale / Windows / GUI / 界面与体验
- [dsh-advanced-model-editor](https://github.com/u9521/dsh-advanced-model-editor) — DSH WebUI plugin for managing custom LLM providers, model parameters, thinking budgets, and request settings.  
  标签：advanced / WebUI / managing / 界面与体验
- [dsh-plugin-model-follow-search](https://github.com/Elissend/dsh-plugin-model-follow-search) — Make DeepSeek Harness's built-in web_search follow your active chat model — three-tier routing with a Web UI toggle. 让内置联网搜索跟随当前对话主模型  
  标签：plugin / Make / built-in / 界面与体验
- [dsh-solution-explorer](https://github.com/xiaoksio/dsh-solution-explorer) — DSH Web GUI right sidebar: VS Code-style file explorer plus source control (git status, stage/unstage/discard, commit, diff) and a file editor with save.  
  标签：solution / Web / GUI / 界面与体验
- [dsh-web-manager](https://github.com/FYHC1/dsh-web-manager) — dsh-plugin + Windows tray manager for DeepSeek Harness WebUI (dsh web): standalone Edge app-window with the official whale icon, quick-launch desktop shortcuts for Windows/WSL, systemd hosting, runtime bridge, self-update. Legacy shortcut-only plugin (v1.x): https://github.com/FYHC1/dsh-webui-installer  
  标签：web / dsh-plugin / Windows / 界面与体验
- [dsh-tray](https://github.com/nxz1026/dsh-tray) — DeepSeek Harness — Custom Windows Tray Launcher  
  标签：tray / Custom / Windows / 界面与体验
- [star-deepseek-harness-desktop](https://github.com/dabaicai001/star-deepseek-harness-desktop) — StarHub 是一款跨平台桌面应用（Tauri 2 + Rust 主进程 + DeepSeek Harness React 工作台 + Go Sidecar），把开发运维日常高频工具整合到同一个窗口 —— 数据库、SSH/SFTP、Docker 面板与 AI 助手。目标是减少在 Navicat、Xshell、Portainer、文件管理器和 AI 对话窗口之间来回切换的成本。  前端架构：基于 DeepSeek Harness 原生 React 工作台（/starhub-react 路由）。资产、设置、SSH 终端、SFTP、数据库  
  标签：star / StarHub / Tauri / 界面与体验
- [Deepseek-Harness-Desktop](https://github.com/ChisaAlter/Deepseek-Harness-Desktop) — DSH桌面端，支持主题和背景图等多种个性化配置。Electron desktop shell for DeepSeek Harness web UI  
  标签：Deepseek / Electron / desktop / 界面与体验
- [dsh-web-mobile](https://github.com/mexiaosqwq/dsh-web-mobile) — DSH Web UI 移动端适配：窄屏好用，宽屏适用  
  标签：web / 界面与体验
- [dotnet-deepseek-harness-desktop](https://github.com/ZK-Andy/dotnet-deepseek-harness-desktop) — DeepSeek Harness Desktop for .NET — 内置完整运行时的 .NET 桌面客户端（Ryn 原生 WebView），支持 macOS / Windows / Linux  
  标签：dotnet / Desktop / NET / 界面与体验
- [SinglePlayer](https://github.com/nxz1026/SinglePlayer) — 单身汉播放器，适配DeepSeek harness web的播放器，支持多平台聚合。Bachelor Player is a media player designed to integrate with DeepSeek Harness Web, supporting multi-platform content aggregation.  
  标签：harness / web / 界面与体验
- [dsh-theme-whalegirl](https://github.com/ZHOUcourier/dsh-theme-whalegirl) — DeepSeek-鲸鱼娘 (Whale Girl) theme for the DeepSeek Harness Web UI — ported from DreamSkin ver_cb557ececaa5de3f3dbe: full --dsw-* token remap + ambient wallpaper.  
  标签：theme / DeepSeek- / Whale / 界面与体验
- [EchoBird](https://github.com/edison7009/EchoBird) — One-click install + model switch:Claude Code,Codex CLI (OpenAI), Grok Build (xAI), DeepSeek Harness, Kimi Code (Moonshot) ,Qwen Code,Aider,OpenCode,MiMo Code (Xiaomi),ZCode (Z.AI),OpenClaw,Pi,OpenScience,Vibe-Trading,Claude Desktop (3P profile),ChatGPT desktop,OpenCode Desktop,  
  标签：One-click / install / 界面与体验
- [pixel-skin](https://github.com/zhuifengqug/pixel-skin) — dsh像素风皮肤  
  标签：pixel / dsh / 界面与体验
- [dsh-vscode](https://github.com/Lixxx1/dsh-vscode) — 在 VS Code 中使用 DeepSeek Harness. Use DeepSeek Harness in VS Code  
  标签：vscode / Code / Use / 界面与体验
- [DeepSeek-Desktop-Studio](https://github.com/nixiaohao/DeepSeek-Desktop-Studio) — a desktop shell for deepseek-harness (dsh). Import deepseek-harness via zip or git, then self-pack and self-update with one click. Packaging-only: never forks or bundles deepseek-harness source; you bring your own workspace.  deepseek-harness（dsh）的桌面外壳，支持 zip/git 导入后一键自行打包与更新，纯打包项目、不内置官方源码。  
  标签：DeepSeek / desktop / shell / 界面与体验
- [dsh-plugin-message-timeline-navigation](https://github.com/cokiscarazo-rgb/dsh-plugin-message-timeline-navigation) — Codex-style message timeline navigation for DSH web clients: hover to preview a message, click to jump to it, and the currently-read turn stays highlighted.  
  标签：plugin / Codex-style / message / 界面与体验
- [RocketX](https://github.com/lusipad/RocketX) — 以原版 Rocket.Chat 为内核、集成 Codex App Server、Deepseek Harness、Azure DevOps、体验对标飞书的团队协作客户端。  
  标签：Rocket / Chat / 界面与体验
- [dsh-tidychat](https://github.com/BananaSoldier01/dsh-tidychat) — DSH Web 会话时间线整理：自动折叠 / 分隔线 / 左缘定位条 / 四开关设置  
  标签：tidychat / Web / 界面与体验
- [dsh-web-search-free](https://github.com/sheep-programmer/dsh-web-search-free) — DSH 插件：免费网页搜索，双免费后端（Parallel 默认 + Exa 备用，均匿名免 key）+ 设置开关 + MCP server 双传输（stdio + HTTP/SSE 双端口），兼容 Claude Code / Codex | Free web search for DeepSeek Harness: Parallel (default) + Exa (backup) free providers, settings toggle, and dual-transport MCP server (stdio + HTTP/SSE) for Claude Code / Codex  
  标签：web / Parallel / Exa / 界面与体验
- [dsh-top](https://github.com/glenngit/dsh-top) — System monitoring tool for the dsh web GUI: live CPU, RAM, disk, network, and top processes in a floating, collapsible panel.  
  标签：top / System / monitoring / 界面与体验
- [dsh-suggest-reply](https://github.com/pick1e-morty/dsh-suggest-reply) — 帮我想想 —— 一个基于 DSH-better-sidebar 的侧边栏 tab：用你自己写的 system prompt 对主对话最新一条 AI 回复生成候选回复，点击直填输入框。  
  标签：suggest / DSH-better-sidebar / tab / 界面与体验
- [dsh-websearch](https://github.com/240xu/dsh-websearch) — Unified web search provider for DSH  
  标签：websearch / Unified / web / 界面与体验
- [dsh](https://github.com/qomob/dsh) — Home of dsh-plugin-hub: discover, evaluate, and install DeepSeek Harness (dsh) community plugins from inside dsh — plugin_search / plugin_info / plugin_install / plugin_remove tools, supply-chain trust tiers, and a Web Plugins marketplace tab. Also powers dsh.qomob.ai: a Chinese 0-to-1 Wiki and a daily-updated dsh plugin directory  
  标签：Home / dsh-plugin-hub / 界面与体验
- [dsh-desktop](https://github.com/Tinnikx/dsh-desktop) — DeepSeek Harness 的 Linux Electron 桌面客户端，由claude opus生成, 打包后开箱即用, 已更新至0.1.1-rc.2, 插件安装方式与web端一致, 支持'插件市场'插件, 可以安装插件市场后在插件市场中搜索并安装插件, 也可以通过正常命令 ./bin/dsh plugin --profile web add xxxx, download in the Release Page.  
  标签：desktop / Linux / Electron / 界面与体验
- [dsh-balance](https://github.com/mxl2498/dsh-balance) — DSH Web 插件：悬浮显示 DeepSeek 账户余额，点击直达充值页 | DSH widget showing your DeepSeek balance with a top-up link  
  标签：balance / Web / widget / 界面与体验
- [voyager](https://github.com/Nagi-ovo/voyager) — Enhancement suite for Gemini, AI Studio, Claude & ChatGPT — plus a prompt manager for any web UI, DeepSeek Harness included. / 面向 Gemini、AI Studio、Claude 与 ChatGPT 的增强套件；提示词管理器可用于任意 Web UI，含 DeepSeek Harness。  
  标签：Enhancement / suite / 界面与体验
- [dsh-wallpaper-engine](https://github.com/drmi5446/dsh-wallpaper-engine) — Turn Wallpaper Engine wallpapers into a liquid glass background for the DSH web GUI, with video and web support.  
  标签：wallpaper / Turn / Engine / 界面与体验
- [DSH-Desktop](https://github.com/harismuna5268/DSH-Desktop) — Electron desktop shell for DeepSeek Harness, bundling node, pnpm, and the DSH runtime for one-click access to the dsh web UI.  
  标签：Desktop / Electron / shell / 界面与体验
- [dsh-skill-viewer](https://github.com/Failing-coachman563/dsh-skill-viewer) — Manage and organize DSH skills via a web interface with one-click enable/disable, batch migration, and workspace-based grouping.  
  标签：skill / Manage / organize / 界面与体验
- [DeepSeekHarnessDesktop](https://github.com/Capacious-diamondweddinganniversary929/DeepSeekHarnessDesktop) — Package DeepSeek Harness into a cross-platform desktop app with built-in Node runtime — double-click to launch the full web UI on Windows, macOS, and Linux.  
  标签：Package / into / 界面与体验
- [deepseek-harness-desktop](https://github.com/niceberserker38/deepseek-harness-desktop) — Unlock DeepSeek Harness locally with a minimal, cross-platform desktop shell for private AI experimentation.  
  标签：deepseek / Unlock / locally / 界面与体验
- [dsh-plugin-deepseek-usage](https://github.com/xavier711/dsh-plugin-deepseek-usage) — A DeepSeek usage panel plugin for the DeepSeek Harness Web GUI. It adds a 「Usage / 用量」 entry at the bottom of the left sidebar.  
  标签：plugin / usage / panel / 界面与体验
- [deepseek-cost-usage-status-plugin](https://github.com/Zenjibad/deepseek-cost-usage-status-plugin) — Live DeepSeek API cost, usage & balance status line for the DeepSeek Harness (DSH) web UI. Packaged DSH plugin — on/off-peak (Beijing-time), session cost, burn rate, account balance.  
  标签：deepseek / Live / API / 界面与体验
- [dsh-desktop](https://github.com/EternalNight996/dsh-desktop) — dsh-desktop · DeepSeek Harness 桌面工作台 🤖 AI 打工人的快乐老家 —— 双击即用，255+ 像素专家天团（独立插件）可一键加装  
  标签：desktop / dsh-desktop / 界面与体验
- [dsh-plugin-bench](https://github.com/B1lli/dsh-plugin-bench) — Evidence-backed, type-aware quality scorecards for DeepSeek Harness plugins.  
  标签：plugin / Evidence-backed / type-aware / 界面与体验
- [dsh-plugin-session-manager-custom](https://github.com/FloatingLifeTL/dsh-plugin-session-manager-custom) — DeepSeek Harness Web plugin for local session data management  
  标签：plugin / Web / local / 界面与体验
- [dsh-rss-daily](https://github.com/shangjian2023/dsh-rss-daily) — dsh plugin: 46-source daily RSS digest, LLM-edited, delivered via webhook (ServerChan/PushDeer/WxWork/TG/Bark/gotify)  
  标签：rss / dsh / source / 界面与体验
- [dsh-theme-customizer](https://github.com/lxxz1918/dsh-theme-customizer) — DeepSeek Harness（DSH）Web 界面自定义主题插件：背景/文字/框线/细节全可视化调整，预设导入导出，持久化保存。  
  标签：theme / Web / 界面与体验
- [dsh-desktop](https://github.com/Zhanggp98/dsh-desktop) — DeepSeek Harness 桌面客户端：内置 Node.js 免安装、三步启动动画、环境自动修复（dsh 缺失自动 npx 安装）、主题跟随、自定义标题栏、托盘常驻，双击即用零命令行。支持 Windows。  
  标签：desktop / Node / dsh / 界面与体验
- [dsh-ui-three-body](https://github.com/EternalNight996/dsh-ui-three-body) — 把「人话」翻译给智能体的 DSH 插件。开启后，每一次对话都注入「驯兽师内核」——第一性原理 + 需求剖析 + 极简沟通 + 最少 token，让智能体真正「开智」、更懂人类；左上角悬浮一只萌宠做开关，设置面板里可配置内核档位。  
  标签：ui / token / 界面与体验
- [dsh-client-ui-board](https://github.com/LaoQianwocao/dsh-client-ui-board) — DSH Web 展板插件：会话视图第三标签，多层白板 + 锚点连线  
  标签：client / Web / 界面与体验
- [dsh-sound-player](https://github.com/LaoQianwocao/dsh-sound-player) — DSH Web 音效播放器插件（悬浮窗 + 情况触发音效 + 供其他插件使用的 API）  
  标签：sound / Web / API / 界面与体验
- [dsh-searxng-web](https://github.com/maxwell-feng/dsh-searxng-web) — DeepSeek Harness plugin: back the native web_search / web_fetch tools with your self-hosted SearXNG instance — keyless, private, no third-party search vendor.  
  标签：searxng / back / native / 界面与体验
- [dsh-tui-vscode](https://github.com/baobaolaodie/dsh-tui-vscode) — VS Code companion extension for dsh-TUI — an experience almost identical to the official Claude Code VS Code extension  
  标签：tui / Code / companion / 界面与体验
- [seek-soul-in-darkness](https://github.com/Max-Null/seek-soul-in-darkness) — Seek Soul in Darkness (SSiD) — DSH-based desktop AI: finding the soul of silicon life in darkness  
  标签：seek / Soul / Darkness / 界面与体验
- [dsh-session-groups](https://github.com/wheam/dsh-session-groups) — Provider-owned virtual session groups for the DeepSeek Harness Web sidebar.  
  标签：session / Provider-owned / virtual / 界面与体验
- [dsh-gui](https://github.com/xuboboo/dsh-gui) — DeepSeek Harness 桌面版客户端（GUI）：品牌启动动画 + DeepSeek 设计语言界面 + rc.5 启动崩溃修复。第三方非官方项目。  
  标签：gui / 界面与体验
- [dsh-plugin-no-workspace](https://github.com/SpookySandwich/dsh-plugin-no-workspace) — Standalone, workspace-free conversations for DeepSeek Harness without replacing the native workspace UI.  
  标签：plugin / Standalone / workspace-free / 界面与体验
- [dsh-overlay_companion](https://github.com/frankstanmonster/dsh-overlay_companion) — 动态女仆桌面悬浮窗Floating desktop overlay for Deepseek Harness(dsh):  A floating, skinnable Waifu widget for Deepseek Harness. Features  auto-launch on boot, port auto registration, and a clickable waifu GIF that lets you monitor dsh's live status(tool calling,Approval,thinking,browsing etc) and launch dsh with a double click  
  标签：overlay / Floating / desktop / 界面与体验
- [adhdgofly-dsh-ext](https://github.com/zuoguyoupan2023/adhdgofly-dsh-ext) — ADHDGoFly POS highlighting plugin for DeepSeek Harness Web: nouns green, verbs red, adjectives/adverbs purple, others gray in rendered Markdown  
  标签：adhdgofly / POS / highlighting / 界面与体验
- [openharness-reader](https://github.com/zuoguyoupan2023/openharness-reader) — OpenHarness Reader - workspace file browser/editor with Markdown preview for DeepSeek Harness Web  
  标签：openharness / Reader / workspace / 界面与体验
- [dsh-codex-sidebar](https://github.com/NOirBRight/dsh-codex-sidebar) — Codex-app-style sidebar for a DeepSeek Harness 主会话  
  标签：codex / Codex-app-style / sidebar / 界面与体验
- [dsh-model-proxy](https://github.com/biyuhao/dsh-model-proxy) — DSH plugin: per-model proxy routing (http/https/socks5) with a settings UI — e.g. opencode/muse-spark-1.2-contributor needs a proxy while sibling models stay direct  
  标签：model / per-model / proxy / 界面与体验
- [AI-Novel-Writer](https://github.com/EthanYoQ/AI-Novel-Writer) — 本地优先 AI 小说创作工作台，提供 Windows/macOS 桌面版与 DeepSeek Harness 插件开发预览，支持角色、大纲、章节蓝图、审稿修稿和本地模型。  
  标签：AI / Windows / macOS / 界面与体验
- [dsh-llm-ollama](https://github.com/NOirBRight/dsh-llm-ollama) — Native Ollama Cloud provider and Web configuration plugin for DeepSeek Harness  
  标签：llm / Native / Ollama / 界面与体验
- [dsh-Desktop](https://github.com/qinyre/dsh-Desktop) — DeepSeek Harness（dsh）的零配置桌面客户端：自带完整运行时与插件市场，双击即用，无需 Node 与终端。  
  标签：Desktop / dsh / Node / 界面与体验
- [dsh-llm-grok](https://github.com/NOirBRight/dsh-llm-grok) — Grok subscription OAuth provider and Web configuration plugin for DeepSeek Harness  
  标签：llm / Grok / subscription / 界面与体验
- [dsh-polymarket-knowhow](https://github.com/fashionmascherine-svg/dsh-polymarket-knowhow) — DeepSeek Harness plugin (dsh-plugin): complete Polymarket superpowers — 31 verified tools across Gamma/CLOB/Data-API/Perps/RFQ/Bridge, embedded knowhow skill, live WebSocket stream. Read-only by default.  
  标签：polymarket / dsh-plugin / complete / 界面与体验
- [dsh-pin-color](https://github.com/LuckVd/dsh-pin-color) — DeepSeek Harness (DSH) web 插件：会话置顶（本组/工作区全局）+ 会话 tab 颜色 + emoji，host 持久化，纯 DOM 增强不改 DSH 源码  
  标签：pin / web / tab / 界面与体验
- [dsh-session-stats-panel](https://github.com/a1113622001/dsh-session-stats-panel) — DeepSeek Harness client plugin: right-side session stats panel - cache hit rate, session cost (DeepSeek official peak/off-peak pricing), account balance, runtime, request count, cumulative tokens.  
  标签：session / client / right-side / 界面与体验
- [deepseek-harness-desktop](https://github.com/Evan1u/deepseek-harness-desktop) — Light-weight Desktop App for Deepseek Harness  
  标签：deepseek / Light-weight / Desktop / 界面与体验
- [skill-filesystem-plus](https://github.com/sidleo/skill-filesystem-plus) — Configurable skill discovery provider for DeepSeek Harness (DSH): cwd/project/ancestors/global layers with editable parent dirs, plugin card UI, disk persistence  
  标签：skill / Configurable / discovery / 界面与体验
- [dsh-vscode](https://github.com/Fengze233/dsh-vscode) — 在 VS Code 侧边栏内嵌使用 DeepSeek Harness（DSH）网页界面的插件  
  标签：vscode / Code / 界面与体验
- [dsh-tui-app](https://github.com/yhfgyyf/dsh-tui-app) — Readline-based interactive terminal profile bundle for DeepSeek Harness.  
  标签：tui / Readline-based / interactive / 界面与体验
- [dsh-desktop-tauriapp](https://github.com/hyperion2144/dsh-desktop-tauriapp) — Tauri 2 desktop shell wrapping the DeepSeek Harness Web GUI (macOS + Windows) — tray daemon, auto-launch/reuse of local dsh, --patch plugin injection, mobile access via LAN/tunnel pairing with cloudflared one-click tunnel.  
  标签：desktop / Tauri / shell / 界面与体验
- [dsh-plugin-hub](https://github.com/wingsky-1/dsh-plugin-hub) — DSH (DeepSeek Harness) web GUI plugin collection — notifications, provider usage, LAN proxy, MCP manager, idle archive, file preview. Install: dsh plugin --profile web add @wingsky-1/dsh-plugins-all  
  标签：plugin / web / GUI / 界面与体验
- [dsh-side-chat](https://github.com/zclDragon/dsh-side-chat) — DSH web plugin: Codex-style /side side conversations — a temporary fork of the current chat in a floating panel, without interrupting the main task.  
  标签：side / web / Codex-style / 界面与体验
- [dsh-desktop](https://github.com/AQian0/dsh-desktop) — 基于Tauri的简易dsh桌面端套壳 | A simple Tauri-based desktop wrapper for dsh  
  标签：desktop / Tauri / dsh / 界面与体验
- [dsh-endfield-ui](https://github.com/rison114514/dsh-endfield-ui) — Endfield-inspired industrial UI shell for DeepSeek Harness (dsh) — non-official fan theme. Install: dsh plugin --profile web add @rison/dsh-endfield-ui  
  标签：endfield / Endfield-inspired / industrial / 界面与体验
- [awesome-deepseek-harness](https://github.com/libukai/awesome-deepseek-harness) — DeepSeek Harness 终极指南：快速入门、资源推荐、精选插件与实用工具 ｜The Ultimate Guide to DeepSeek Harness: QuickStart, Resources, Plugins&Toolkit  
  标签：awesome / The / Ultimate / 界面与体验
- [dsh-hub-oauth-gateway](https://github.com/lninghaha/dsh-hub-oauth-gateway) — DSH Web plugin: Usage Center with Hub snapshots and cost analytics, coding-plan OAuth, and optional loopback OpenAI-compatible gateway  
  标签：hub / Web / Usage / 界面与体验
- [dsh-tauri-launcher](https://github.com/cilis/dsh-tauri-launcher) — DeepSeek Harness (DSH) Launcher，this is a dsh plugin.  
  标签：tauri / Launcher / this / 界面与体验
- [dsh-session-pin](https://github.com/PerryLink/dsh-session-pin) — Pin sessions and workspaces to the top of the DeepSeek Harness sidebar with per-pin row colors - a dual-face (host + client) dsh plugin.  
  标签：session / Pin / sessions / 界面与体验
- [voice_for_dsh](https://github.com/junarch/voice_for_dsh) — DSH Web 语音朗读插件：每轮输出口语化转写后朗读（代码/表格自动跳过）；免费浏览器 TTS + 可选豆包云 TTS。Read-aloud plugin for DeepSeek Harness web.  
  标签：voice / Web / TTS / 界面与体验
- [deepseek-harness-desktop](https://github.com/chokwinlee/deepseek-harness-desktop) — Compact DeepSeek Harness desktop host with a native SwiftUI iPhone Remote source preview.  
  标签：deepseek / Compact / desktop / 界面与体验
- [mira_live2d](https://github.com/xhqm-xyz/mira_live2d) — DSH Live2D 看板娘插件：会话界面浮层（拖拽/滚轮缩放/右键表情菜单）+ 模型可说话（OpenAI/阿里 TTS）+ MCP 工具（状态/切模型/表情动画开关/思考等待表情）  
  标签：mira / Live / OpenAI / 界面与体验
- [ds-balance](https://github.com/JovanHE/ds-balance) — A minimal DeepSeek account balance widget for the DeepSeek Harness web GUI  
  标签：ds / minimal / account / 界面与体验
- [dsh-research-report](https://github.com/PerryLink/dsh-research-report) — Verifiable research-report engine for DeepSeek Harness: content-addressed evidence ledger (claim-snapshot binding, tamper-evident) plus versioned sealed reports with per-claim verification verdicts and a manifest-sealed directory.  
  标签：research / Verifiable / research-report / 界面与体验
- [dsh-talk](https://github.com/PerryLink/dsh-talk) — Voice-first session loop for DeepSeek Harness: a composer microphone button with browser/local speech-to-text (Web Speech, FunASR, whisper.cpp), a speak tool for text-to-speech replies (browser, edge-tts, piper), event announcements with mute, and speak-to-interrupt.  
  标签：talk / Voice-first / session / 界面与体验
- [deepseek-harness-desktop](https://github.com/anywhere-labs/deepseek-harness-desktop) — 为 DeepSeek Harness (DSH) 插件生态打造的现代化桌面端解决方案。万物皆「插件」，桌面本身也是「插件」。  
  标签：cordis / cordis-plugin / deepseek / desktop
- [deepseek-harness-desktop](https://github.com/hairyf/deepseek-harness-desktop) — DeepSeek Harness Tauri 桌面版 | Only 5mb installer, zero environment setup, preset plugins, Windows / macOS / Linux.  
  标签：deepseek / desktop / tauri
- [dsh-context](https://github.com/bowenliang123/dsh-context) — The best DeepSeek Harness plugin for context insight and management, with context dashboard / browser and context command, for context statistics, composition, breakdown, evolution details, understanding how the context is made of, and how it evolves. 一站式 DeepSeek Harness 上下文可视化插件，Context 面板及浏览器与 Context 命令，透视上下文组成、演进、压缩、剪枝等事件与动作。  
  标签：cordis-plugin / dsh-external / dsh-plugins
- [DeepSeek-Balance-Whale-Widget](https://github.com/MeteorNOX/DeepSeek-Balance-Whale-Widget) — DeepSeek Harness（DSH）一只住在 DSH 界面右下角的小鲸鱼娘，帮你盯着DeepSeek账户余额。QQ弹弹，支持拖拽吸附、左吸附翻转、数字滚动动画，随界面自动启用，建议直接喊来你的dsh安装  
  标签：cordis / deepseek / developer-tools / dsh-plugins
- [dsh-code](https://github.com/UNLINEARITY/dsh-code) — Claude-Code-style TUI bundle for DeepSeek Harness. 充分结合 DSH 的核心机制和高级特性与Codex CLI 、Claude Code 等主流交互机制，打造的 DSH-Code. （对齐DSH官方上游最新版本！持续更新中！支持DSH 特殊模式，插件系统，模型管理，子代理管理，切换模型特殊动画）  
  标签：claude-code / cli / codex / deepseek
- [dsh-desktop](https://github.com/liguobao/dsh-desktop) — An independent, open-source desktop wrapper for DeepSeek Harness. It starts the bundled @deepseek-ai/dsh Web UI locally and loads it in a hardened Electron window on Linux, macOS, and Windows.  
  标签：界面与体验
- [webdsh](https://github.com/futrime/webdsh) — Browser-only build of DeepSeek Harness  
  标签：deepseek
- [dsh-plugin-notify](https://github.com/c-ling/dsh-plugin-notify) — DeepSeek Harness 消息提醒插件：回合结束或等待确认时向浏览器、系统、飞书/钉钉/企业微信/通用 Webhook 发送通知  
  标签：badge / cordis / deepseek / deepseek-ai
- [dsh-codex-timeline](https://github.com/Wine-Red/dsh-codex-timeline) — Codex-style turn timeline and local conversation search for DeepSeek Harness Web | Codex风格的对话节点时间线导航栏，提供会话内容搜索等增强  
  标签：conversation / deepseek / timeline / web-ui
- [deepseek-harness-plugin-manager](https://github.com/hrhgit/deepseek-harness-plugin-manager) — Web plugin manager for DeepSeek Harness (DSH): inspect, search, group, enable, and disable Cordis plugins.  
  标签：cordis / deepseek / plugin-management / plugin-manager
- [dsh-pomodoro](https://github.com/causebefore/dsh-pomodoro) — DeepSeek Harness Web 番茄钟插件：可配置专注与休息时长，提供侧栏入口和可拖动浮动面板  
  标签：javascript / pomodoro / pomodoro-timer / productivity
- [OLEDCare](https://github.com/domparent/OLEDCare) — OLED burn-in care plugin for the DeepSeek Harness Web GUI: true-black nap screensaver, pure-black surfaces, gamma-aware dimming, hue rotation  
  标签：oled
- [dsh-prompt-library](https://github.com/master1Sun/dsh-prompt-library) — DSH（DeepSeek Harness）Web 插件：在 composer 工具栏注入一个「提示词库」按钮，管理可复用的 prompt 片段，点击即可插入当前输入框。支持自动学习：输入复杂 prompt 文案时，插件会自动识别并保存到提示词库。  
  标签：cordis / dsh-bundle / dsh-plugin-bundle / dsh-plugin-desktop
- [dsh-desktop](https://github.com/Yuel25/dsh-desktop) — A Windows desktop client for DeepSeek Harness.  
  标签：desktop / electron
- [dsh-workspace-groups](https://github.com/z-col/dsh-workspace-groups) — DeepSeek Harness web client plugin: group sidebar workspaces into a configurable three-level tree (分类→项目→会话). Sidecar YAML rules. dsh-plugin.  
  标签：sidebar / workspace / workspace-groups
- [dsh-https-fix](https://github.com/MingYU-kalo/dsh-https-fix) — DeepSeek Harness plugin: built-in HTTPS reverse proxy with configurable settings (设置→插件配置→Https Fix)  
  标签：界面与体验
- [blue](https://github.com/dsh-blue/blue) — Blue: a TUI is not a package, it is a Cordis plugin tree — a modern terminal UI for DeepSeek Harness with hot-swappable render, interaction, and command plugins.  
  标签：cordis / deepseek / tui
- [dsh-remote-plugin](https://github.com/Blank-not-black/dsh-remote-plugin) — DSH Remote 插件独立包：DSH 原生侧边栏入口 + 右侧抽屉管理页；内置网关随 DSH 自动启停  
  标签：remote-control
- [dsh-better-at](https://github.com/Ruiming-cn/dsh-better-at) — Fast @ file/session reference caching for DeepSeek Harness Web / DSH @ 引用菜单加速插件  
  标签：at-menu / performance / typescript
- [dsh-usage-lite](https://github.com/ericw0315/dsh-usage-lite) — 为 DeepSeek Harness Web 界面提供简洁、优雅的余额与 Token 用量面板。  Compact provider balances and local token-usage analytics for the DeepSeek Harness Web UI.  
  标签：界面与体验
- [dsh-auto-mode](https://github.com/log-li/dsh-auto-mode) — CC-style auto approval layer for DeepSeek Harness: deterministic rules + two-stage classifier, circuit breaker, fail-to-human. Shadow mode day one.  
  标签：auto-approval
- [dsh-convmap](https://github.com/GeekRicardo/dsh-convmap) — DeepSeek Harness web 插件：在主对话区左缘中部渲染「对话地图」刻度（每条 = 一轮用户提问），hover 梯度展开并预览该轮提问/回复摘要，点击跳转（未渲染的老轮次自动分页加载后再跳），滚动时当前轮次自动高亮。  
  标签：minimap / navigation / web-ui
- [dsh-model-garden](https://github.com/mrdevlorx/dsh-model-garden) — A searchable, sortable model picker for the DeepSeek Harness Web UI — provider groups, favorites, models.dev prices, context windows, live per-task token cost and a local-model filter. One-command install: dsh plugin add dsh-model-garden.  
  标签：deepseek-harness-desktop / deepseek-harness-plugins / javascript / large-language-models
- [dsh-comfyui](https://github.com/fandc520/dsh-comfyui) — 一个基于DeepSeek-Harness的ComfyUI插件  
  标签：界面与体验
- [dsh-widgets-plugin](https://github.com/zhangsaizz/dsh-widgets-plugin) — 支持 deepseek-harness 各类小组件  
  标签：界面与体验
- [dsh-balance-by-token](https://github.com/jsoncode/dsh-balance-by-token) — DeepSeek Harness（dsh）双面插件（宿主 + 浏览器半边）：查看 DeepSeek 账户余额， 按 token 用量估算费用，价格按模型 × 高峰/空闲时段在线配置。所有能力收敛在 统一弹框中（侧边栏底部「余额」入口），另在会话头部提供实时 「当前会话 ≈xx CNY | 余额 xx CNY」按钮。界面中英双语（跟随宿主 UI 语言）。  
  标签：dsh-balance-by-token
- [dsh-software-tools](https://github.com/AllenLogo/dsh-software-tools) — DSH 侧边栏【软件工具】管理器:勾选本机 WSL/Windows 软件工具并注入模型系统提示,随插件自带 add-software-tool 技能。Sidebar software-tools manager for DeepSeek Harness Web.  
  标签：界面与体验
- [proactive-notify](https://github.com/DemoJ/proactive-notify) — 一个运行在 DeepSeek Harness（DSH）Web GUI 上的消息通知插件  
  标签：界面与体验
- [dsh-user-message-navigation](https://github.com/walnut-a/dsh-user-message-navigation) — DSH User Message Minimap（用户消息导航轨）— 长对话中的用户指令快速导航插件  
  标签：conversation-navigation / minimap
- [dsh-lan-proxy](https://github.com/mariGoIds/dsh-lan-proxy) — DeepSeek Harness 的远程访问插件：让手机/公网能打开 dsh 界面，支持 IP 白名单、密码登录、HTTPS 和IPv6 直连。  
  标签：界面与体验
- [dsh-session-cleaner](https://github.com/haoranwang0921/dsh-session-cleaner) — DeepSeek Harness dynamic Cordis plugin: manage and delete conversation records (whole sessions or individual messages) from the web GUI.  
  标签：cordis-plugin / session-management
- [clutch-dsh](https://github.com/Cerbur/clutch-dsh) — Open-source DSH plugins for DeepSeek Harness, starting with a Git worktree-aware Session view for the DSH Web UI.  
  标签：界面与体验
- [dsh-ui-translate](https://github.com/RadicalGitter/dsh-ui-translate) — Privacy-first browser-local Chinese-to-English translation for DeepSeek Harness Web using OPUS-MT.  
  标签：opus-mt / privacy / translation
- [dsh-money](https://github.com/yanhuifair/dsh-money) — 一个显示回复和对话费用的 deepseek harness 插件  
  标签：cost / deepseek / dsh-plugins / money
- [dsh-plugin-message-edit](https://github.com/SpookySandwich/dsh-plugin-message-edit) — Edit a sent message and branch the conversation from that point — version counter under the bubble, plus a tree view. Placement presets modelled on ChatGPT, Claude and DeepSeek.  
  标签：ai-chat / chat-ui / conversation-branching / cordis-plugin
- [dsh-mcp-setting](https://github.com/belowthetree/dsh-mcp-setting) — 在「设置」界面管理 DSH 配置文件里的 MCP 服务器。setup mcp server in setting panel  
  标签：deepseek / dsh-plugins
- [DSH-Console](https://github.com/limbo947/DSH-Console) — DeepSeek Harness local service control panel - WPF tray tool to start/stop dsh web with one click, status monitoring, auto-launch and auto-start | DSH 本地服务控制面板  
  标签：csharp / dotnet-framework / service-manager / windows-desktop
- [dsh-client-ui-period-hint](https://github.com/aqiane/dsh-client-ui-period-hint) — 在输入栏显示当前dsAPI价格时段  
  标签：界面与体验
- [dsh-tianshu-tui](https://github.com/huiliyi37/dsh-tianshu-tui) — DeepSeek Harness 终端 UI。  
  标签：TUI
- [dsh-cc-tui](https://github.com/ccch1mneyyy/dsh-cc-tui) — Claude Code 风格全屏交互终端插件。  
  标签：TUI
- [oh-dsh-desktop](https://github.com/hust-open-atom-club/oh-dsh-desktop) — 面向 DeepSeek Harness 的可扩展 macOS 工作台。  
  标签：桌面
- [dsh-grok-tui](https://github.com/chen-001/dsh-grok-tui) — 把 grok-build 的 TUI 作为 DeepSeek Harness 的前端。  
  标签：TUI
- [dsh-launcher](https://github.com/Ruler4396/dsh-launcher) — DeepSeek Harness 的轻量 Windows 启动器。  
  标签：启动器
- [dsh-working-activity](https://github.com/ccch1mneyyy/dsh-working-activity) — DSH 实时模型工作状态行。  
  标签：状态
- [dsh-desktop-electron](https://github.com/Void0312Aurora/dsh-desktop-electron) — DSH Web GUI 的跨平台 Electron 桌面壳。  
  标签：桌面
- [dsh-launcher (便携版)](https://github.com/SnowCrescenter-tech/dsh-launcher) — DeepSeek Harness 一键启动器｜Windows 便携免安装版。  
  标签：启动器
- [dsh-mobile](https://github.com/lehhair/dsh-mobile) — DSH WebUI 移动端适配插件。  
  标签：移动端
- [dsh-desktop](https://github.com/bruc3van/dsh-desktop) — DeepSeek Harness Desktop：独立的 dsh Electron 桌面客户端。  
  标签：桌面
- [dsh-tui](https://github.com/orriduck/dsh-tui) — 为 DeepSeek Harness 打造的会话感知终端 UI。  
  标签：TUI
- [dsh-task-board](https://github.com/vlln/dsh-task-board) — DSH Web UI 任务看板插件：任务卡片拖拽、状态流转与进度可视化。  
  标签：看板 / 任务
- [dsh-git-graph](https://github.com/vlln/dsh-git-graph) — DSH 侧栏 Git 提交图可视化，一眼看清分支与提交历史。  
  标签：Git / 可视化
- [dsh-remote-mobile](https://github.com/vlln/dsh-remote-mobile) — 远程移动端控制面板，手机上查看 Agent 会话并下达指令。  
  标签：移动端 / 远程
- [dsh-command-k](https://github.com/vlln/dsh-command-k) — Command+K 快速唤起命令面板，搜索命令、文件与插件一气呵成。  
  标签：命令面板 / 快捷键
- [dsh-mermaid](https://github.com/vlln/dsh-mermaid) — 在对话中实时渲染 Mermaid 图表：流程图、时序图、甘特图。  
  标签：图表 / Mermaid
- [dsh-markdown-preview](https://github.com/vlln/dsh-markdown-preview) — 实时 Markdown 预览侧栏，编辑与渲染同步，支持 GFM 与数学公式。  
  标签：Markdown / 预览
- [dsh-theme-manager](https://github.com/vlln/dsh-theme-manager) — 一键切换 DSH Web UI 主题，内置多套配色并支持自定义导入。  
  标签：主题 / 皮肤
- [dsh-catppuccin](https://github.com/zhijun-dai/Catppuccin-dsh-theme) — Catppuccin 柔色主题，给 DSH 换上低饱和奶油色界面。  
  标签：主题 / 配色
- [solarized-dsh-theme](https://github.com/zhijun-dai/Solarized-dsh-theme) — Solarized 经典配色主题，护眼舒适，长时编码不累眼。  
  标签：主题 / 配色
- [dsh-skin](https://github.com/KinGao294/dsh-skin) — Codex 风格皮肤切换器 + 自定义壁纸层，可调透明度与模糊。  
  标签：皮肤 / 壁纸
- [dsh-web-attention-badge](https://github.com/Luaphes/dsh-web-attention-badge) — 会话需要你时三处同时亮起：角标、标签页标题计数、按状态换色的鲸鱼 favicon。  
  标签：提醒 / 角标
- [dsh-builtin-toggles](https://github.com/Starfie1d1272/dsh-builtin-toggles) — 官方内置插件目录、搜索与状态说明，附安全 UI 插件开关。  
  标签：开关 / 目录
- [dsh-sticky-disclosure](https://github.com/Han-1413141/dsh-sticky-disclosure) — 一键收起会话中所有展开区块（Think、工具卡），常驻计数按钮 + 快捷键。  
  标签：收起 / 折叠
- [dsh-sticky-note](https://github.com/Meredith2328/dsh-sticky-note) — 编辑框工具栏便签，随手记点子与 TODO，自动保存为 Markdown。  
  标签：便签 / TODO
- [dsh-balance-meter](https://github.com/Ghost011118/dsh-balance-meter) — 输入框 dock 显示 DeepSeek 账户余额与会话花费，自动拉取官方定价。  
  标签：余额 / 计价
- [dsh-cost-meter](https://github.com/Han-1413141/dsh-cost-meter) — 会话与当日 API 费用统计、预算图框、历史看板，支持峰谷计价。  
  标签：费用 / 预算
- [dsh-spend](https://github.com/nonewind/dsh-spend) — 右下角悬浮用量与费用统计窗，按模型/按天/按会话多维聚合。  
  标签：统计 / 费用
- [dsh-deepseek-quota](https://github.com/yingjunnan/dsh-deepseek-quota) — DeepSeek API 配额与用量展示插件，额度消耗一目了然。  
  标签：配额 / 用量
- [dsh-hud](https://github.com/a903067276-rgb/dsh-hud) — 会话 HUD 抬头显示：Token、成本、耗时等关键指标一屏尽览。  
  标签：HUD / 指标
- [dsh-view-modes](https://github.com/NigelYao/dsh-view-modes) — DSH 多视图模式切换：极简/代码/完整布局随心换。  
  标签：视图 / 布局
- [dsh-milestone](https://github.com/SnowCrescenter-tech/dsh-milestone) — 右侧圆点时间轴导航，点击跳转到任意用户消息。  
  标签：时间轴 / 导航
- [dsh-outline](https://github.com/urzeye/dsh-outline) — 会话大纲插件：自动生成对话结构目录，快速定位关键节点。  
  标签：大纲 / 目录
- [dsh-smooth-stream](https://github.com/SpookySandwich/dsh-smooth-stream) — 让模型流式输出更平滑，减少抖动卡顿，阅读体验更顺。  
  标签：流式 / 优化
- [dsh-web-mobile-fix](https://github.com/AcidGr/dsh-web-mobile-fix) — Web UI 移动端布局修复：窄屏设置全屏化、导航单行、弹层居中。  
  标签：移动端 / 修复
- [dsh-TUI](https://github.com/ccch1mneyyy/dsh-TUI) — Claude Code 风格全屏终端插件：像素鲸鱼顶栏、实时状态行、流式思考、上下文进度条 + TPS 仪表。  
  标签：TUI / 终端
- [dsh-oc](https://github.com/chiro2001/dsh-oc) — 把 DSH 的 Agent、会话、工具接入官方 OpenCode 终端前端。  
  标签：TUI / OpenCode
- [dsh-skill-viewer](https://github.com/Fishquito7/dsh-skill-viewer) — Web 界面 skill 管理：一键启停、删除与新增，workspace 分组。  
  标签：技能 / 管理
- [dshcode](https://github.com/whitelonng/dshcode) — 社区桌面伴侣：一键安装的 Electron 应用，支持 macOS 与 Windows。  
  标签：桌面 / Electron
- [dsh-history-tree](https://github.com/z953218350/dsh-history-tree) — Codex 风格对话回合时间线树，左侧边栏展示历史概览。  
  标签：时间线 / 历史
- [dsh-archive-manager](https://github.com/z953218350/dsh-archive-manager) — 会话归档管理：在设置页列出并删除已归档会话。  
  标签：归档 / 会话
- [dsh-session-delete](https://github.com/WSL043/dsh-session-delete) — 给原生会话菜单增加二次确认永久删除，防误删。  
  标签：删除 / 确认
- [dsh-notifier](https://github.com/nanami-0713/dsh-notifier) — 任务结束 / 需要决策时弹窗提醒（web toast + 桌面通知），类似 Codex / Claude Code 体验。  
  标签：通知 / 提醒
- [dsh-skill-fuzzy](https://github.com/Kevoyuan/dsh-skill-fuzzy) — / 技能菜单模糊搜索 + 描述预览，快速定位想要的 skill。  
  标签：搜索 / 技能
- [dsh-plugin-vscode-sidebar](https://github.com/gameswu/dsh-plugin-vscode-sidebar) — 提供 vscode 风格与功能的侧栏。  
  标签：侧栏 / VS Code
- [dsh-settings-search-plugin](https://github.com/DoiiarX/dsh-settings-search-plugin) — 设置面板搜索框：独立候选列表，点击跳转到所属分组并聚焦该设置项。  
  标签：设置 / 搜索
- [dsh-usage-balance](https://github.com/zdjmrq/dsh-usage-balance) — 侧边栏用量/余额插件，余额与消耗一目了然。  
  标签：用量 / 余额
- [dsh-theme-switch](https://github.com/kinmat-A/dsh-theme-switch) — 轻量主题外观切换：自动检测已装皮肤，一键互斥切换，停用回退官方外观。  
  标签：主题 / 切换
- [dsh-zh-hant-hk](https://github.com/Argonaut790/dsh-zh-hant-hk) — 香港繁体中文用词插件（對話、設定、儲存）。  
  标签：繁体 / 本地化
- [ATRI-Theme-DSH](https://github.com/DKthreeFR/ATRI-Theme-DSH) — 亚托莉（ATRI）主题的 DeepSeek Harness 界面装饰。  
  标签：主题 / 装饰
- [dsh-island](https://github.com/cdxiaodong/dsh-island) — 把 DSH agent 实时状态（会话/工具/审批）桥接到 CodeIsland 刘海面板。  
  标签：刘海 / 状态
- [dsh-remote-public](https://github.com/nanami-0713/dsh-remote-public) — 基于 DSH 的手机远程控制客户端（公开脱敏镜像）。  
  标签：移动端 / 远程
- [dsh-sounds](https://github.com/DNNCOVO/dsh-sounds) — 任务完成/失败、回合结束、等待审批、agent 提问等声音提醒。  
  标签：音效 / 提醒
- [deepseek-harness-android-app](https://github.com/Jensen-Yao/deepseek-harness-android-app) — 安卓通用控制端：Termux 引导、一键部署、内置浏览器与存储管理。  
  标签：安卓 / 控制端
- [dsh-desktop](https://github.com/xiaowei2025cqu23phy/dsh-desktop) — DSH 桌面端：内嵌 Web UI、AI 屏保、全模型切换、手机 PWA 远程控制、QQ 机器人通道。  
  标签：桌面端 / PWA
- [dsh-turn-rail](https://github.com/Luoji-Yuli/dsh-turn-rail) — 仿 DeepSeek 官网样式的对话时间轴侧栏（History Jump Sidebar）。  
  标签：时间轴 / 侧栏
- [dsh-tui-plugin](https://github.com/JimLuan/dsh-tui-plugin) — DSH CLI 终端 UI 插件：交互式会话、流式对话、工具卡、审批、子代理等。  
  标签：TUI / 终端
- [dsh-canvas-preview](https://github.com/jiuyuechuwuhao/dsh-canvas-preview) — 画板预览插件：AI 生成网页产物实时预览，PNG/JPG/SVG 一键导出（对标 Gemini Canvas）。  
  标签：画板 / 预览
- [dsh-settings-organizer](https://github.com/xiajiajun516/dsh-settings-organizer) — 设置呈现层：分组插件、隐藏设置、搜索与恢复，低侵入式。  
  标签：设置 / 组织
- [dsh-notification-sounds](https://github.com/qq33357486/dsh-notification-sounds) — 跨平台等待与完成音效通知。  
  标签：通知 / 音效
- [dsh-conversation-language](https://github.com/Dingpenghui-good/dsh-conversation-language) — 中英文会话语言切换插件。  
  标签：语言 / 切换
- [dsh-pet](https://github.com/PC2005-cloud/dsh-pet) — DSH 桌面宠物：一行命令安装 28 个透明动画宠物，或内置素材链自造专属宠物。  
  标签：宠物 / 桌面
- [dsh-file-preview](https://github.com/UndeadSheep/dsh-file-preview) — 悬浮文件预览插件：偷瞄工作区文件。  
  标签：文件 / 预览
- [dsh-conversation-outline](https://github.com/lzbaclz/dsh-conversation-outline) — Codex 风格对话大纲：右缘轨道，悬停预览、点击跳转。  
  标签：大纲 / 导航
- [DeepSeek-Harness-Token-Free](https://github.com/Djokovical5294/DeepSeek-Harness-Token-Free) — 零 token 成本桌面 GUI：在 macOS/Windows 上免费运行 DeepSeek Harness。  
  标签：桌面端 / 免费
- [deepseek-harness-ux](https://github.com/ayuanwong/deepseek-harness-ux) — 长任务进度可视化：关键进度清晰可见，完成后自动折叠，详情随时展开。  
  标签：进度 / UX
- [dsh-focus-overlay](https://github.com/boogoo619/dsh-focus-overlay) — 专注模式：全屏阅读视图，将 AI 工具调用折叠为摘要。  
  标签：专注 / 阅读
- [dsh-pixel-icons](https://github.com/TableRogue/dsh-pixel-icons) — 把 DSH GUI 矢量 SVG 图标转为像素风的插件。  
  标签：像素 / 图标
- [dsh-pixel-probe](https://github.com/TableRogue/dsh-pixel-probe) — DSH 动态 Client 插件浏览器能力探测工具。  
  标签：探测 / 调试
- [dsh-fusion-pixel-ui-adapt](https://github.com/TableRogue/dsh-fusion-pixel-ui-adapt) — 让 DSH GUI 适配 Fusion Pixel 像素字体的 UI 排版插件。  
  标签：像素 / 字体
- [dsh-fusion-pixel-font](https://github.com/TableRogue/dsh-fusion-pixel-font) — 用 Fusion Pixel 12px 像素字体替换 DSH GUI 界面与代码字体。  
  标签：像素 / 字体
- [DshCockpit](https://github.com/Lxiayu/DshCockpit) — DSH 桌面驾驶舱：成本/用量监控、预算告警、自动更新回滚、Quick Ask 热键、定时任务、会话搜索（Win+macOS）。  
  标签：桌面端 / 成本
- [dsh-tui](https://github.com/riesbri/dsh-tui) — DeepSeek Harness 终端界面：进程内 Cordis bundle + 零依赖渲染器。  
  标签：终端 / TUI / Cordis
- [dsh-stats-board](https://github.com/PastSheep/dsh-stats-board) — DSH Web 统计看板：对话/工具统计的第三视图标签。  
  标签：统计 / 看板 / Web
- [dsh-ux-simple](https://github.com/KhalilYamber/dsh-ux-simple) — DSH 界面两档模式：简化/原生一键切换，工具卡片白话化，降低上手门槛。  
  标签：界面模式 / 简化 / 上手
- [dsh-plugin-prompt-tool](https://github.com/Czerror/dsh-plugin-prompt-tool) — DSH 插件：简体中文行为规范三层注入（常驻层 + prompt 技能 + 锚定预设）+ Web UI 编辑 prompt.md。  
  标签：Prompt / 行为规范 / Web UI
- [dsh-web-scroll-flow](https://github.com/TYOPXN360/dsh-web-scroll-flow) — DSH Web 对话滚动动效：自动跟随动画、边缘橡皮筋回弹、流式逐字打字机。  
  标签：滚动 / 动效 / 打字机
- [Minke](https://github.com/lencx/Minke) — 🐳 DeepSeek Harness 桌面客户端。  
  标签：桌面端 / 客户端 / Electron
- [dsh-any-background](https://github.com/Tkingxiao/dsh-any-background) — 自定义主题插件：背景图（大小/位置）、主界面与设置界面（透明度、色轮主题色）。  
  标签：皮肤 / 背景 / 主题
- [dsh-right-drawer](https://github.com/PastSheep/dsh-right-drawer) — DSH Web 右侧抽屉宿主：dockPanels 注册、边缘标签堆叠、宽度可调。  
  标签：抽屉 / 面板 / Web
- [dsh-soln-panel](https://github.com/PastSheep/dsh-soln-panel) — DSH Web 右侧 HTML 方案面板：分页、可缩放、未读提示、按工作区持久化。  
  标签：方案 / 面板 / Web
- [dsh-wallpaper-engine](https://github.com/elysia395/dsh-wallpaper-engine) — 让你的 DSH 自由切换 Wallpaper Engine 壁纸，并调节模糊、亮度、边框与对话框液态玻璃效果。  
  标签：皮肤 / 壁纸 / Wallpaper
- [dsh-client-ui-skin-denia](https://github.com/Ewnscat-ya/dsh-client-ui-skin-denia) — DSH Web GUI 皮肤·鸣潮达妮娅主题「虚无之泡」：双形态亮/暗、侧边立绘、玻璃卡片、浮动泡泡粒子。  
  标签：皮肤 / 主题 / 鸣潮
- [cc-dsh-notifier](https://github.com/baobaolaodie/cc-dsh-notifier) — Windows 桌面通知：Claude Code 与 DeepSeek Harness 会话提醒，点击 toast 还原会话窗口。  
  标签：通知 / 桌面 / Windows
- [dsh_for_mac](https://github.com/rogerhorsley/dsh_for_mac) — 一键 macOS 桌面客户端：本地 dsh web 运行时的 Electron 外壳。  
  标签：桌面端 / macOS / Electron
- [dsh-enter-approve](https://github.com/abcofabc/dsh-enter-approve) — 在 DSH WebUI 中按回车即可批准沙箱提权提示，无需鼠标点击。  
  标签：审批 / 回车 / 权限
- [dsh-plugin-session-delete](https://github.com/Geralt4/dsh-plugin-session-delete) — DSH 插件：从 Web UI 永久删除会话的磁盘日志与附件（头部按钮 + 确认框）。  
  标签：会话 / 删除 / Web
- [dsh-conversation-landmarks](https://github.com/mantonlove/dsh-conversation-landmarks) — 对话地标：为长 Agent 对话提供固定导航与悬停预览。  
  标签：导航 / 地标 / 长对话
- [deepseek-code](https://github.com/HQ1995/deepseek-code) — 驱动 DeepSeek Harness 的 grok-build 终端 UI。  
  标签：终端 / grok-build / UI
- [dsh-think-summary](https://github.com/oakcakerolls/dsh-think-summary) — DSH 思考流分段总结插件。  
  标签：思考 / 总结 / 分段
- [dsh-input-traffic](https://github.com/drscrewdriver/dsh-input-traffic) — 打断输入与下一轮插入不再二选一：支持红色打断插入、黄色下一轮插入、绿色逻辑完成后输入，并支持邻近高峰冻结会话。  
  标签：输入 / 打断 / 会话
- [dsh-turn-fold](https://github.com/CH4ACKO3/dsh-turn-fold) — 为 DeepSeek Harness 提供 Codex 风格已完成回合折叠（dsh-harmony 驱动）。  
  标签：折叠 / 回合
- [dsh-logcat](https://github.com/WindyPro-rourou/dsh-logcat) — DSH Web GUI 的 Android Logcat 查看器：自动连接 adb、实时日志流、级别/关键词过滤与导出。  
  标签：Android / 日志 / 调试
- [dsh-code-studio](https://github.com/WindyPro-rourou/dsh-code-studio) — DSH Web GUI 的 Code Studio：文件树 + 高亮编辑器 + Cline 风格行级 diff。  
  标签：编辑器 / diff
- [mddl-harness](https://github.com/taltara/mddl-harness) — DeepSeek Harness 可视化编排器：拖拽模型与工具到画布，导出真实 cordis.patch.yml 覆盖层。  
  标签：编排 / 可视化
- [dsh-toolfold](https://github.com/Minecraftbe/dsh-toolfold) — DSH Web GUI 的 Codex 风格工具调用折叠。  
  标签：折叠 / 工具调用
- [dsh-brand-landingpage](https://github.com/satan9394/dsh-brand-landingpage) — DSH 技能：品牌落地页设计，从访谈到可部署 HTML。  
  标签：落地页 / 设计
- [dsh-hermit](https://github.com/jorinyang/dsh-hermit) — Hermit（小寄）——基于 DeepSeek Harness 插件组合实现的常驻用户侧多模态交互中枢。  
  标签：多模态 / 交互
- [balance-show](https://github.com/JavierNier/balance-show) — DSH Web GUI 的余额与用量卡片：DeepSeek 账户余额分级 + 实时单会话 Token 用量与成本。  
  标签：余额 / Token
- [dsh-usage-record](https://github.com/kkishapppy/dsh-usage-record) — DSH Web 对话区左侧提问导航轨：横线=提问，点击跳转 + 鱼眼 + 滚动跟随。  
  标签：导航 / 会话
- [dsh-webui-studio](https://github.com/memorax-ai/dsh-webui-studio) — 面向交互式、可视化优先的 DSH 客户端插件开发 Studio。  
  标签：开发 / Studio
- [dsh-prompt-stash](https://github.com/Wine-Red/dsh-prompt-stash) — DeepSeek Harness Web 的本地、分对话提示词暂存架，临时存放未完成的想法。  
  标签：提示词 / 草稿
- [dsh-inline-diff](https://github.com/JanEickholt/dsh-inline-diff) — 在 DeepSeek Harness 对话内直接显示文件编辑的内联 / 并排 diff，覆盖 edit/write 工具调用。  
  标签：diff / 文件 / 可视化
- [dsh-ENHANCED](https://github.com/HIT-HTML/dsh-ENHANCED) — 一站式增强：多引擎免费联网搜索、Skills/MCP 管理、自动压缩调参、实例 RESTART/SHUTDOWN 控制与主题。  
  标签：增强 / 搜索 / MCP / 主题
- [dsh-turn-notify](https://github.com/Ruiming-cn/dsh-turn-notify) — DSH 插件：Agent 需要你时（回合完成、阻塞、报错、审批、提问、计划审阅）触发 Windows 弹窗与提示音。  
  标签：通知 / 桌面 / 提醒
- [dsh-ask-in-sidebar](https://github.com/Ruiming-cn/dsh-ask-in-sidebar) — 在侧边栏基于当前会话上下文向助手提问所选内容，不干扰主对话。  
  标签：侧边栏 / 问答
- [dsh-voice](https://github.com/Lorodn4x/dsh-voice) — DSH Web UI 语音消息：Edge TTS 朗读按钮 + Agent 发送语音便签。  
  标签：语音 / TTS
- [dsh-web-restart](https://github.com/bigfurma-bot/dsh-web-restart) — DeepSeek Harness Web UI 一键重启：设置页常驻确认按钮 + 实时状态点 + 分离式 Linux 重启器。  
  标签：重启 / Web UI
- [dsh-drop-any-file](https://github.com/Zenjibad/dsh-drop-any-file) — DSH Web 聊天支持拖拽任意文件：非图片文件存入当前会话工作区供 Agent 读取。  
  标签：拖拽 / 文件 / 工作区
- [llmtrim-stats-plugin](https://github.com/Zenjibad/llmtrim-stats-plugin) — DSH Web UI 实时 llmtrim 节省看板：设置面板 + 输入框下方轮播统计条。  
  标签：Token / 统计 / 压缩
- [dsh-guarded-live-voice](https://github.com/Jstn-1g/dsh-guarded-live-voice) — 带显式同意的实时语音：精确会话绑定 + 仅提案式 composer 交接。  
  标签：语音 / 实时 / 隐私
- [dsh-mobile-ui](https://github.com/lan450/dsh-mobile-ui) — DSH Web UI 移动端布局适配：溢出自适应、底部抽屉、安全区处理。  
  标签：移动端 / 响应式
- [dsh-better-sidebar-lite](https://github.com/pixellover1433/dsh-better-sidebar-lite) — 轻量改善 DSH Web 的 UX/UI 的侧边栏插件。  
  标签：侧边栏 / UX
- [dsh-liquid-glass-input](https://github.com/jkamkk/dsh-liquid-glass-input) — DSH Web GUI 液态玻璃输入卡片：SVG 折射 + 弹簧按压动画。  
  标签：输入 / 玻璃拟态
- [dsh-safe-tui](https://github.com/aorucshiea/dsh-safe-tui) — DSH 安全模式恢复控制台：极简 TUI、历史、修复、模型 / 供应商管理。  
  标签：TUI / 恢复 / 安全
- [deepseek-harness-GUI](https://github.com/festoney8/deepseek-harness-GUI) — 基于 Tauri 的 DeepSeek Harness 超轻量桌面版，支持升级内核与免安装便携版。  
  标签：桌面 / Tauri / 便携
- [dsh-easy-start](https://github.com/aorucshiea/dsh-easy-start) — DSH 浏览器生命周期管理：关闭浏览器时询问 / 保持服务、一键重启并自动刷新。  
  标签：生命周期 / 重启
- [dshline](https://github.com/riesbri/dshline) — DeepSeek Harness 插件生态的终端原生前端。  
  标签：终端 / TUI / 前端
- [dsh-russian-lang](https://github.com/GooDAnDReaDY/dsh-russian-lang) — DSH Web UI 俄语本地化：核心命名空间词典 + 语言列表新增俄语选项。  
  标签：本地化 / 俄语

<a id="cat-agent-与自动化" name="cat-agent-与自动化"></a>

### 🤖 Agent 与自动化

- [Deep Research](https://github.com/omdsh-dev/dsh-deep-research) — 自适应深度研究编排器，自动拆解、检索、核查并产出报告。  
  标签：研究 / 编排
- [Agent Teams](https://github.com/NanmiCoder/dsh-agent-teams) — 多 Agent 团队协作框架，任务分派、结果汇总一站式。  
  标签：多智能体 / 协作
- [Automation](https://github.com/titanwings/dsh-automation) — 按计划在新 Agent Session 中跑 Coding 任务，睡一觉代码就写好。  
  标签：定时 / 自动化
- [Evolve](https://github.com/william-jin-cmu/dsh-evolve) — 会话内随对话自生长/削减能力，越用越懂你的 Agent。  
  标签：自进化 / 元能力
- [Advisor](https://github.com/btspoony/dsh-advisor) — 双模型顾问：主模型干活，顾问模型挑刺，质量有保障。  
  标签：双模型 / 评审
- [Sentinel](https://github.com/fuhefei/dsh-sentinel) — 条件驱动唤醒：满足触发条件才启动 Agent，省 Token 又及时。  
  标签：条件触发 / 唤醒
- [OpenBiliClaw](https://github.com/whiteguo233/OpenBiliClaw) — 本地私有、开源的跨平台 AI 内容发现 Agent。  
  标签：内容 / Agent
- [phi](https://github.com/pulseaiclub/phi) — 用 Go 写的最小终端编码 Agent。  
  标签：终端 Agent
- [mstar-harness](https://github.com/btspoony/mstar-harness) — Morning Star：面向 harness 工程工作流的 Agent 插件。  
  标签：工程
- [dsh_workflow](https://github.com/icetomoyo/dsh_workflow) — 把 Claude Code 的 UltraCode 模式带给 DSH。  
  标签：工作流
- [illusion-agent](https://github.com/YunTaiHua/illusion-agent) — Illusion-Agent：幻想与功能相遇的 AI Agent 平台。  
  标签：Agent 平台
- [distill](https://github.com/LoserFox/distill) — 自动对话蒸馏：后台 subagent 反省 + 技能 create/update。  
  标签：蒸馏 / subagent
- [dsh-interconnect](https://github.com/Chinesezjc/dsh-interconnect) — DSH 的跨实例消息/事件交接插件。  
  标签：跨实例
- [dsh-openbiliclaw](https://github.com/whiteguo233/dsh-openbiliclaw) — 把 OpenBiliClaw 装进 DeepSeek Harness 的客户端插件。  
  标签：内容
- [dsh-loop](https://github.com/vlln/dsh-loop) — 定时循环插件。  
  标签：循环
- [dsh-task-status](https://github.com/vlln/dsh-task-status) — 后台任务状态条。  
  标签：状态
- [dsh-auto-approval](https://github.com/Andy8647/dsh-auto-approval) — 为审批策略增加 auto 档：用预执行分类器判定每个工具调用。  
  标签：审批
- [dsh-deepresearch](https://github.com/havingautism/dsh-deepresearch) — 把证据优先的深度研究工作区带到 DSH。  
  标签：研究
- [dsh-inspect](https://github.com/omdsh-dev/dsh-inspect) — 发现问题→修复交付→质量复查的对抗式闭环插件。  
  标签：闭环
- [dsh-llm-fallbacks](https://github.com/btspoony/dsh-llm-fallbacks) — 当 LLM 请求持续失败时沿备用链自动切换 provider/模型。  
  标签：容错
- [dsh-agent-budget](https://github.com/vibeinging/dsh-agent-budget) — 给单个 live agent 会话设定持久的 Token 上限与绝对截止时间。  
  标签：预算
- [session-teleport](https://github.com/omdsh-dev/session-teleport) — DSH 多设备 Session 接力插件。  
  标签：多设备
- [dsh-sidechain](https://github.com/Buyi-wsgzg/dsh-sidechain) — DSH 侧会话插件：/side 持续性侧会话与 /btw 一次性侧问。  
  标签：侧会话
- [dsh-github-integration](https://github.com/omdsh-dev/dsh-github-integration) — GitHub 集成工作流技能包。  
  标签：GitHub
- [dsh-artifact](https://github.com/william-jin-cmu/dsh-artifact) — 文件交付协议插件。  
  标签：交付
- [yet-another-subagent](https://github.com/HuanLinOTO/dsh-plugin-yet-another-subagent) — 可配置的 subagent profile 系统。  
  标签：subagent
- [dsh-track](https://github.com/fakechris/dsh-track) — DSH Track Bridge 插件：嵌入式任务管理引擎。  
  标签：任务管理
- [dsh-plugin-sleep](https://github.com/HuanLinOTO/dsh-plugin-sleep) — 向模型暴露 sleep 工具。  
  标签：工具
- [dsh-humanize](https://github.com/zevorn/dsh-humanize) — Humanize：提供带独立 AI 评审的迭代开发。  
  标签：评审
- [dsh-revive](https://github.com/omdsh-dev/dsh-revive) — 一键复活：重启后给所有被打断的会话自动发送「继续」指令。  
  标签：复活
- [dsh-crew](https://github.com/stuarthu/dsh-crew) — DSH 插件：把工作拆给一支角色化 Agent 小队（产品经理、研究员、架构师、工程师、QA、代码评审、安全评审）。  
  标签：Agent / 多角色 / 协作
- [Codex-Co-Engineer](https://github.com/ajhcs/Codex-Co-Engineer) — 面向独立 DeepSeek Harness 的 Codex 优先控制面：Codex 担任首席工程师与操作员，DeepSeek Harness 协同执行。  
  标签：Agent / Codex / 控制面
- [dsh-subagent-team](https://github.com/xuqingsakura/dsh-subagent-team) — 一个官方 bundle 形态的独立插件，可经 GitHub / npm 安装到 DSH（桌面端与 web 端皆可）。 提供模型可见的角色工具（team_read / team_write / team_code_write / team_code_review …）， 以及一套真正的事件驱动团队运行时（建队 / 成员 / 任务依赖 / 邮箱 / 自动调度 / 右下角活动浮层）。  
  标签：subagent / bundle / GitHub / Agent 与自动化
- [iPolloWork](https://github.com/Devin-AXIS/iPolloWork) — Enterprise-grade, local-first Agent Workbench for people and agent teams. A unified multi-engine workspace for Codex Harness, DeepSeek Harness, and OpenCode, with unified plugins and Skills, multi-agent projects and tasks, and editable code, documents, presentations, design, and video.  
  标签：Enterprise-grade / local-first / Agent 与自动化
- [dsh-whale-girl-pet](https://github.com/yanzwzz/dsh-whale-girl-pet) — 🐋 DeepSeek 娘桌宠：住进 DeepSeek Harness Web 界面的蓝发鲸鱼女仆。工作链路、任务完成统计（用时/消耗/花费）、睡眠系统、时间感知、余额/天气/喂食按钮、完整设置面板。  
  标签：whale / Web / Agent 与自动化
- [dsh-mattpocock-skills-deck](https://github.com/FeatherHunter/dsh-mattpocock-skills-deck) — 拨开迷雾看见终点，剩下的交给任务栏。Part the fog, see the end — the task bar handles the rest. 🎮 mattpocock/skills 的 DSH 游戏任务系统：map 拨迷雾，任务栏推进一步。A game-like mission system for Matt Pocock skills in DeepSeek Harness. More by @FeatherHunter: 🎨 dsh-opencode-palette · ⚡ dsh-prompt  
  标签：mattpocock / Part / fog / Agent 与自动化
- [dsh-agent-sticky-note](https://github.com/alanpaul1969/dsh-agent-sticky-note) — 📌 Sticky-note plugin for DeepSeek Harness — agent notices & pending decisions visible in the Web GUI (Tailscale-friendly)  
  标签：agent / Sticky-note / notices / Agent 与自动化
- [dsh-subagent-profile](https://github.com/muzyLink/dsh-subagent-profile) — DeepSeek Harness 子 Agent 派发方案化插件：按任务指定预设/模型/推理强度/工具范围，常用组合存成命名方案一键派发，内置成本护栏。  
  标签：subagent / Agent / Agent 与自动化
- [recursus](https://github.com/OpenCnid/recursus) — A durable, full-access runtime agent built on DeepSeek Harness  
  标签：durable / full-access / Agent 与自动化
- [dsh-tradingagents](https://github.com/megatronyy/dsh-tradingagents) — TradingAgents for DeepSeek Harness: the 14-role A-share multi-agent analysis pipeline behind /trading-agent  
  标签：tradingagents / role / A-share / Agent 与自动化
- [dsh-harness-ally](https://github.com/BaronCyrus/dsh-harness-ally) — DeepSeek Harness 联盟模式：自由组合 DSH、Claude Code、Codex 与全部已配置模型，保留原生 Agent 生命周期与实时执行过程。  
  标签：harness / Claude / Code / Agent 与自动化
- [deepseek-harness-control-center](https://github.com/feibi-mochi/deepseek-harness-control-center) — DeepSeek Harness account monitoring, usage accounting, completion alerts, official recharge, flexible layout, and agent-assisted session controls. / 账户监控、提醒、充值与会话控制中心  
  标签：deepseek / account / monitoring / Agent 与自动化
- [dsh-novel-writing](https://github.com/peterwangze/dsh-novel-writing) — DSH (DeepSeek Harness) 自动化小说写作发布流水线插件：claude-writing-workflow 迁移版 agent 预设 + 小说工作台（可视化/实时渲染/章节编辑）+ 多平台发布配置与数据驱动优化闭环  
  标签：novel / claude-writing-workflow / agent / Agent 与自动化
- [awesome-deepseek-harness-plugins](https://github.com/walkinglabs/awesome-deepseek-harness-plugins) — A curated directory of source-verified DeepSeek Harness (DSH) plugins, tools, design workflows, and official resources.  
  标签：awesome / curated / directory / Agent 与自动化
- [hanai-investment-dsh](https://github.com/hancao97/hanai-investment-dsh) — Local-first A-share research workbench for DeepSeek Harness: market dashboards, watchlists, valuation, four investor agents, versioned reports, and continuous post-report chat.  
  标签：hanai / Local-first / A-share / Agent 与自动化
- [dsh-ios](https://github.com/Kickstartparty3459/dsh-ios) — Run live iOS simulators and your real iPhone over USB inside DeepSeek Harness conversations with 22 agent tools, MJPEG previews, and SwiftUI hot reload.  
  标签：ios / Run / live / Agent 与自动化
- [dsh-cortex](https://github.com/iguowz/dsh-cortex) — 低成本多模型编排插件（Cortex）：大模型规划验收，子agent小模型执行，降本保质  
  标签：cortex / agent / Agent 与自动化
- [clat](https://github.com/artec/clat) — Cmd-Line Agent, a Rust basement compatible with the DeepSeek Harness framework. 命令行智能体，兼容深度探索驾具的 Rust 基座。  
  标签：Cmd-Line / Agent / Agent 与自动化
- [dsh-notifier](https://github.com/THEWOLFWALKER/dsh-notifier) — Unified notification push plugin for DeepSeek Harness (DSH): one minimal notify() API, 8 channel adapters (telegram/dingtalk/feishu/wxpusher/pushplus/serverchan/bark/webhook), dual trigger (auto session events + agent tool).  
  标签：notifier / Unified / notification / Agent 与自动化
- [dsh-commander](https://github.com/qwert702/dsh-commander) — Commander for the DeepSeek Harness Web GUI: one conversation orchestrates others via <dsh-dispatch> protocol blocks, with automatic result receipts.  
  标签：commander / Web / GUI / Agent 与自动化
- [dsh-ui-agents-pixe](https://github.com/EternalNight996/dsh-ui-agents-pixe) — 🧑‍💼为 DeepSeek Harness Web 主窗口添加「工作角色」页签 + 「像素办公室」浮层：内置 508 张完整角色卡（The Agency 255 + agency-agents-zh 253），支持搜索 / 中英切换 / 分部分类选人；Canvas 2D 像素小人可站立、打字、踱步，浮层可拖动折叠缩放，选人即入列；闲聊台词可接 AI（内置或外部接口，20 字内中文）。npm 双面包 + cordis 组合补丁层（dsh.bundle.patch），一条命令安装，不改 dsh 源码，重启不丢。  
  标签：ui / Web / The / Agent 与自动化
- [flow-comet](https://github.com/baobaolaodie/flow-comet) — An automated execution engine that turns AI coding discipline into a verifiable state machine — for the flow-kit 9-stage workflow, built for Claude Code, Codex, and DeepSeek Harness.  
  标签：flow / automated / execution / Agent 与自动化
- [pptpress](https://github.com/liustack/pptpress) — Stable, editable PPTX generation for AI agents — semantic IR in, native DrawingML out. DSH plugin + Claude Code plugin + CLI. | 给 AI agent 的稳定可编辑 PPTX 生成：语义 IR 进，原生 DrawingML 出。DSH 插件 / Claude Code 插件 / CLI。  
  标签：Stable / editable / Agent 与自动化
- [dsh-open-a2a-net](https://github.com/NelsonLongxiang/dsh-open-a2a-net) — Open A2A network plugin for DeepSeek Harness: signed agent cards, decentralized peer/zone discovery, direct routing model tools, and joinable session nodes in the web sidebar  
  标签：open / network / signed / Agent 与自动化
- [dsh-router-standard](https://github.com/yjh051108/dsh-router-standard) — Task-aware reasoning-mode router for DeepSeek Harness: three measured behavior bands (spec/mixed/react) with phase-transition evidence, persona + first-turn tool injection, agent-visible tuning. Dual-attractor policy paper included.  
  标签：router / Task-aware / reasoning-mode / Agent 与自动化
- [dsh-automation-center](https://github.com/usersx/dsh-automation-center) — Root-level automation center for DeepSeek Harness: scheduled tasks, fresh Result Sessions, and cross-workspace run history.  
  标签：automation / Root-level / center / Agent 与自动化
- [dsh-smart-restart](https://github.com/edusrez/dsh-smart-restart) — Wakes the main agent after any DSH restart so interrupted work resumes automatically — adds a restart tool and an optional canary that validates the boot and warns instead of breaking.  
  标签：smart / Wakes / main / Agent 与自动化
- [dsh-lens](https://github.com/coffee-man666/dsh-lens) — Repository and agent-runtime analysis skills as an installable DeepSeek Harness (dsh) plugin  
  标签：lens / Repository / agent-runtime / Agent 与自动化
- [dsh-token-anxiety](https://github.com/mov-eax-eax/dsh-token-anxiety) — plugin for deepseek harness (dsh) to show the Cost Per Task , support multiple currencies, subagents.  
  标签：token / deepseek / harness / Agent 与自动化
- [dsh-llama-responses](https://github.com/SnowRikka/dsh-llama-responses) — DeepSeek Harness plugin: run subagents on a local llama.cpp model via the OpenAI Responses (/v1/responses) protocol — LLM adapter + delegation skill  
  标签：llama / run / subagents / Agent 与自动化
- [dsh-supervisor](https://github.com/dat-lequoc/dsh-supervisor) — Always-on supervisor agent bundle for DeepSeek Harness: main-agent preset + schedule overlay, one dsh plugin add away  
  标签：supervisor / Always-on / agent / Agent 与自动化
- [smart-subagent](https://github.com/ZekaiShi/smart-subagent) — 按 agent_key 将 DeepSeek Harness subagent 严格路由到已注册 provider/model 的轻量插件  
  标签：smart / agent / key / Agent 与自动化
- [dsh-cae-agent](https://github.com/Fisfzy/dsh-cae-agent) — 让 DeepSeek Harness (DSH) 通过原生工具直接操控本机 Abaqus/CAE 的 Cordis 插件。21 个 DSH 原生工具覆盖完整建模链（几何/材料/网格/接触/分析步/载荷/边界/作业/ODB），TypeScript 编写，socket bridge 直连本机（不走 MCP）。  
  标签：cae / Abaqus / ODB / Agent 与自动化
- [dsh-holdem](https://github.com/BubblePtr/dsh-holdem) — Six-max No-Limit Hold'em for DeepSeek Harness: one human and five LLM agents.  
  标签：holdem / Six-max / No-Limit / Agent 与自动化
- [dsh-cron-scheduler](https://github.com/AlexZhou19871030/dsh-cron-scheduler) — dsh-cron-scheduler  
  标签：cron / dsh-cron-scheduler / Agent 与自动化
- [dsh-subagent-library](https://github.com/MaRi23333/dsh-subagent-library) — DeepSeek Harness 具名子代理库插件：settings 驱动的角色名册，list_subagents / delegate 工具与设置页。Named subagent roster plugin for DeepSeek Harness.  
  标签：subagent / settings / list / Agent 与自动化
- [deepseek-harness-desktop](https://github.com/baihejiangnan/deepseek-harness-desktop) — DeepSeek Harness 三端兼容桌面启动器：多实例完全隔离、并行协作，协作画布编排 Agent 工作流；便携版 Exe 一键启动、仅约 18M（不超过 20M）；双隔离机制让兼容性极强，无论 DSH 本体如何更新，兼容原生到野生狗奶。  
  标签：deepseek / Agent / Exe / Agent 与自动化
- [dsh-timer](https://github.com/life1996cou/dsh-timer) — 能自由设置计划任务时间,含一键避开高峰模式,只用低峰价格跑.  
  标签：timer / Agent 与自动化
- [dsh-plugin-doctor](https://github.com/zoahdev/dsh-plugin-doctor) — Health checks for DeepSeek Harness plugins: manifest, patch, entry, build, pack, fresh-profile install verification — CLI + agent-callable plugin_check tool (RFC #1629 dsh plugin check).  
  标签：plugin / Health / checks / Agent 与自动化
- [amber-protocol](https://github.com/Bandersnatch0x/amber-protocol) — Amber Protocol: repository-local governance for coding agents, including a DeepSeek Harness (dsh) patch overlay.  
  标签：amber / Protocol / repository-local / Agent 与自动化
- [dsh-worktable](https://github.com/Aisland-SJL/dsh-worktable) — 🖥️ Agent-project workbench for DeepSeek Harness — sidebar app drawer + dockable split workspace + a live control room watching every project.  
  标签：worktable / Agent-project / workbench / Agent 与自动化
- [dsh-plugin-proxy](https://github.com/LucienLL/dsh-plugin-proxy) — Global proxy for DeepSeek Harness: route agent tools, model requests and web fetches through the Windows system proxy or a custom proxy with one persistent toggle and agent-visible status  
  标签：plugin / Global / proxy / Agent 与自动化
- [dsh-subagent-pro](https://github.com/hyperion2144/dsh-subagent-pro) — DSH Web extension: live subagent monitor + role-based subagent routing + Claude Code style .dsh/agents/*.md persona injection  
  标签：subagent / Web / extension / Agent 与自动化
- [dsh-cron](https://github.com/ZhuoSir/dsh-cron) — DeepSeek Harness 定时任务插件：对话中自然语言创建，到点自动执行并在会话中回复，支持 cron 表达式与 Web 管理面板  
  标签：cron / Web / Agent 与自动化
- [dsh-feishu-bot](https://github.com/TingRuDeng/dsh-feishu-bot) — Feishu (Lark) private-chat frontend for DeepSeek Harness: drive, monitor, and approve local agents from Feishu, sharing sessions with the Web GUI  
  标签：feishu / Lark / private-chat / Agent 与自动化
- [dsh-tab-status](https://github.com/cmhaoren-sudo/dsh-tab-status) — DSH plugin: leave long-running tasks and watch yellow/green/blue on the Firefox, Chrome, or Edge tab. 长程任务可切出去，标签仍能看到状态。  
  标签：tab / leave / long-running / Agent 与自动化
- [dsh-browser-control](https://github.com/caob23/dsh-browser-control) — Chrome 浏览器扩展 + DeepSeek Harness 插件，让 AI Agent 直接操控你的真实浏览器。  
  标签：browser / Chrome / Agent / Agent 与自动化
- [dsh-awake](https://github.com/htfc786/dsh-awake) — dsh-awake · 守夜人：在 agent 任务执行期间阻止操作系统休眠  
  标签：awake / dsh-awake / agent / Agent 与自动化
- [dsh-browser](https://github.com/Nono-neko/dsh-browser) — Cordis bundle plugin for DeepSeek Harness(DSH). Built‑in multi‑tab browser powered by Puppeteer, provides browser_open/browser_read agent tools & workspace file preview inside DSH Web GUI.  
  标签：browser / bundle / Built / Agent 与自动化
- [harbor-self-evolving](https://github.com/istarwyh/harbor-self-evolving) — DeepSeek Harness plugin and Harbor template for reproducible Agent evaluation, self-evolution, and controlled promotion.  
  标签：harbor / template / reproducible / Agent 与自动化
- [dsh-job-hunting](https://github.com/allentnetus/dsh-job-hunting) — DeepSeek Harness job hunting plugin and runtime skill for local job intelligence workflows.  
  标签：job / hunting / runtime / Agent 与自动化
- [deepseek-harness-cloud](https://github.com/AgentsDanceAI/deepseek-harness-cloud) — Accounts, credits and cloud agent workspaces for DeepSeek Harness — run it as a hosted product, or self-host in 5 minutes.  
  标签：deepseek / Accounts / credits / Agent 与自动化
- [dsh-meow-smooth](https://github.com/Phant0Meow/dsh-meow-smooth) — 手机端ui交互优化，让手机端dsh真正可用。你可以躺着coding了。 电脑、手机都支持的通知系统。AI跑任务，你切出去刷b站了，AI跑完任务或者中途提问，会发通知给你。 还有一些ui交互方面的细节优化。  
  标签：meow / dsh / coding / Agent 与自动化
- [dsh-fun-turn-status](https://github.com/Ycet/dsh-fun-turn-status) — 替换 DSH 任务运行中的 Deep diving... 状态文案：30 秒随机轮换幽默文案，设置-插件-插件配置页可增删改（最多 50 条），与其他同类插件共存时优先级最高。  
  标签：fun / Deep / diving / Agent 与自动化
- [dsh-punky-swarm](https://github.com/Punky971210/dsh-punky-swarm) — expandable-coding-team and plugins on dsh  
  标签：punky / expandable-coding-team / plugins / Agent 与自动化
- [dsh-emu-workbench](https://github.com/tinchak0207/dsh-emu-workbench) — Emu 影像工作台 for DeepSeek Harness — 多供应商生图/改图/模型可用性探测 + Emu 独家 opencode 许愿 Agent  
  标签：emu / opencode / Agent / Agent 与自动化
- [dsh-agent-plugin-market](https://github.com/Diluka/dsh-agent-plugin-market) — DSH（DeepSeek Harness）插件：以 git 仓库为 agent 插件市场，安装并原地加载 Codex/Claude 格式的技能  
  标签：agent / git / Codex / Agent 与自动化
- [dsh-subagent-model](https://github.com/Momojie-S/dsh-subagent-model) — DSH plugin: subagent_model tool — delegate to a subagent with a per-call selected model route (minimal fork of dsh-tool-subagent)  
  标签：subagent / model / tool / Agent 与自动化
- [dsh-workspace-mcp](https://github.com/Momojie-S/dsh-workspace-mcp) — DSH 插件: 按 workspace 加载 MCP server (agent-scoped)  
  标签：workspace / MCP / server / Agent 与自动化
- [dsh-better](https://github.com/wackyju2-beep/dsh-better) — 更好的 DSH | Unofficial dsh plugin: archived sessions & task notifications / 已归档会话管理 · 任务系统通知  
  标签：better / Unofficial / dsh / Agent 与自动化
- [open-design](https://github.com/nexu-io/open-design) — 🎨 Best DeepSeek Harness Design Plugin. The open-source Claude Design alternative. 🖥️ Local-first desktop app. 🖼️ Your coding agent becomes the design engine: prototypes, landing pages, dashboards, slides, images & video — real files, HTML/PDF/PPTX/MP4 export. 🤖 Claude Code / Codex / Cursor / DeepSeek Harness / OpenCode & 20+ CLIs via BYOK.  
  标签：agent-skills / ai-design / byok / claude-code-for-design
- [dsh-im](https://github.com/xmanrui/dsh-im) — 通过扫码或机器人凭据把IM机器人接入DeepSeek Harness（支持飞书、微信、钉钉、企业微信、QQ、Slack、Telegram、Discord和WhatsApp）。 Connect IM bots to DeepSeek Harness via QR code or credentials (9 channels).  
  标签：ai-agents / chatbot / cordis / deepseek
- [Martty](https://github.com/openma-ai/Martty) — deepseek-harness-tui before. Self-Improvement TUI Plugin of DeepSeek Harness. Everything Here Is Also A Plugin. dsh-tui  
  标签：agent / agents / deepseek-harness-plugin-dev / deepseek-harness-plugins
- [dsh-ego-browser](https://github.com/Fisfzy/dsh-ego-browser) — DSH（DeepSeek Harness）插件：把 ego-lite 浏览器（给 AI Agent 用的 Chromium）接入 HARNESS——13 个结构化 ego_* 工具（文本语义快照、语义定位点击、表单填充、截图、CDP 控制、任务空间隔离），内置 ego 运行时，Linux + Chrome 开箱即用，无需克隆官方仓库或手动构建。  
  标签：agent-browser / browser-automation / dshx / ego-lite
- [hedgehog](https://github.com/skyf0xx/hedgehog) — HEDGEHOG codes Cleaner, Faster and with Fewer Tokens. Hedgehog\'s AI-driven development builds a task dependency graph from your spec-driven, BMAD-METHOD plan, so Claude Code, Cursor & Gemini CLI stay locked to it. A CLI-enforced state machine for agentic coding. Now builds DeepSeek DSH Plugins. DeepSeek Harness、DSH 插件、AI 编程、BMAD 方法  
  标签：agent-skills / agentic-coding / ai-agents / ai-assisted-development
- [deepseek-harness-mobile](https://github.com/sorsama/deepseek-harness-mobile) — Android companion for DeepSeek Harness | chat, goals, approvals & notifications from your phone, over your LAN. Kotlin + Jetpack Compose.  
  标签：ai-agents / cordis / deepseek / dsh-plugins
- [dsh-tavern](https://github.com/flizzywine/dsh-tavern) — 基于 DeepSeek Harness（DSH）的 SillyTavern 类文字游戏 Agent，支持候选项生成、对话式人物卡编辑、剧本模式与素材抽取。  
  标签：Agent 与自动化
- [deepseek-harness-acp](https://github.com/openma-ai/deepseek-harness-acp) — ACP server implementation for DeepSeek harness. dsh-acp  
  标签：acp / agent-client-protocol / deepseek / dsh-plugins
- [DSH-EvoResearch](https://github.com/Karbo123/DSH-EvoResearch) — 自进化科研工作流  
  标签：autonomous-research / dsh-plugins / self-evolving
- [dsh-plugin-collection](https://github.com/daha1216/dsh-plugin-collection) — A collection of plugins for DeepSeek Harness (DSH)  
  标签：ai-agent
- [deepseek-harness-desktop](https://github.com/LBurny/deepseek-harness-desktop) — Windows desktop shell for DeepSeek\'s agent harness CLI (dsh). The installer bundles Node.js and dsh, so the official Web UI runs as a native app with tray, notifications, and theme following. No prerequisites.  
  标签：deepseek / desktop-app
- [dsh-awiki](https://github.com/AgentConnect/dsh-awiki) — AWiki identity and messaging plugin for DeepSeek Harness  
  标签：Agent 与自动化
- [dsh-desktop](https://github.com/zsyu9779/dsh-desktop) — Unofficial cross-platform desktop app for DeepSeek Harness. Native Wails shell for the DSH Web UI on macOS, Windows, and Linux.  
  标签：ai-agent / cross-platform / deepseek / desktop
- [dsh-landscape](https://github.com/cyanseek/dsh-landscape) — Agent-first DeepSeek Harness plugin intelligence: verify existing plugins, identify missing capabilities, and generate build-ready briefs.  
  标签：agent-skills / codex / ecosystem / gap-analysis
- [DSH-AUX](https://github.com/DoloresCaritasAngelus/DSH-AUX) — Auxiliary model system for DeepSeek Harness: unified aux-LLM routing (per-task model, timeout, concurrency, failure cooldown, main-model fallback) + vision_analyze / web_extract / compress_text tools, settings page, and session image lifecycle cleanup.  
  标签：auxiliary-model / cordis / llm / vision
- [deepseek-harness-desktop](https://github.com/HaoyueQin/deepseek-harness-desktop) — A desktop shell for DeepSeek Harness — the pluggable AI agent harness from DeepSeek. Wrap the official dsh web UI into a native-feeling, always-on desktop app. / 为 DeepSeek Harness（DeepSeek 开源的可插拔 AI Agent harness）打造的桌面应用壳，把官方 dsh web 界面包装成原生质感、常驻后台的桌面应用。  
  标签：deepseek / deepseek-ai / deepseek-v4 / dsh-plugins
- [dsh-channels](https://github.com/wsz987/dsh-channels) — 把微信 / QQ / 钉钉 / 飞书 / Telegram 接入 DeepSeek Harness：统一配置、扫码授权，直接在各 IM 与 Agent 对话；支持图片与文件收发，Agent 可读取 PDF、DOCX、XLSX 和文本内容。  
  标签：ai-agent / deepseek / dingding / dsh-channels
- [dsh-plugin-pet](https://github.com/c-ling/dsh-plugin-pet) — DeepSeek Harness 桌面电子宠物插件：跟随 agent 状态变换心情的内置/自定义/Codex 精灵图伙伴。  
  标签：codex / companion / cordis / deepseek
- [dsh-ponytail](https://github.com/Wenaixi/dsh-ponytail) — DSH 完整移植版 DietrichGebert/ponytail — 懒惰 senior 模式，6 个中文 Skill，无空 tool  
  标签：agent-skills / claude-code / lazy / over-engineering
- [dsh-coding-preset](https://github.com/Saikel-Orado-Liu/dsh-coding-preset) — Windows-adapted DSH coding agent preset with persistent PowerShell 7 (pwsh) and str_replace_editor, mirroring the official minimal preset.  
  标签：agent-preset / coding-agent / conpty / dsh-plugins
- [dsh-superpower](https://github.com/Wenaixi/dsh-superpower) — DSH port of obra/superpowers — 14 技能完整移植、中文化、DSH 原生 SkillProvider (sync v6.3.0)  
  标签：ai-agent / brainstorming / chinese / cordis
- [dsh-multiple-chat-panels](https://github.com/WilliamShi666/dsh-multiple-chat-panels) — DeepSeek Harness 多对话面板：并排查看并与多个 Agent 会话同时交互。  
  标签：mission-control / multi-pane
- [dhs-tuicode](https://github.com/BenHuHuan/dhs-tuicode) — DSH plug -- cli coding agent with Minimal/Router profiles, [Windows] support, MCP, agents, and a polished TUI.  
  标签：cli / coding-agent / deepseek / dsh-terminal
- [dsh-plugin-goldboard](https://github.com/c-ling/dsh-plugin-goldboard) — DeepSeek Harness 黄金实时看板插件：Au99.99/XAU 实时报价、可拖拽浮窗、招行积存金估算与日内买卖参考。  
  标签：agent / ai / au9999 / cordis
- [DeepDeck](https://github.com/jo32/DeepDeck) — DeepDeck — an extensible desktop workspace for DeepSeek Harness.  
  标签：ai-agent / cordis / deepdeck / deepseek
- [dsh-legion](https://github.com/wxxb789/dsh-legion) — Multi-agent orchestration and LLM model routing for DeepSeek Harness (DSH): semantic AI agent profiles, exact model routes, declarative teams and strategies, and bounded subagent delegation - a TypeScript plugin that adds no second runtime.  
  标签：agent-client-protocol / agent-orchestration / agentic-ai / ai-agents
- [dsh-generative-ui](https://github.com/CNSeniorious000/dsh-generative-ui) — Generative UI for DeepSeek Harness — the agent writes TSX, dsh web renders it live, inline in chat and in a canvas panel  
  标签：artifacts / canvas / cordis / cordis-plugin
- [dsh-more-session-operations](https://github.com/Ruiming-cn/dsh-more-session-operations) — DeepSeek Harness Web sidebar session-row menu enhancements: copy session ID, delete session with confirmation, archive confirmation, and recursive subagent-session deletion.  
  标签：session-manager / session-operations / web-ui
- [deepseek-kanban-plugin](https://github.com/callmesoul/deepseek-kanban-plugin) — DSH (DeepSeek Harness) 任务看板插件：主机状态机 + git 调度 + 浏览器看板 UI，agent 自动执行任务、审核后自动合并回基础分支  
  标签：agent / deepseek / kanban / plugin
- [dsh-plus](https://github.com/A-G-guy/dsh-plus) — DSH+ —— DeepSeek Harness 自定义插件 monorepo：移动端窄屏适配 / 任务结束邮件通知 / 子代理独立模型 / 自定义 LLM 路由 / ......  
  标签：ai-agents
- [dsh-taffy-theme](https://github.com/lengzhanbao/dsh-taffy-theme) — Taffy Live Atelier / 塔菲直播工房 — DSH Web 粉金亚克力主题：浅色花房、深色舞台、粉金对话框与塔菲立绘，可选 Agent 预设。  
  标签：acrylic / taffy / theme / ui
- [DHS-multi-agent-plugin](https://github.com/Li3NGa/DHS-multi-agent-plugin) — agent工厂 让多个agent协同 deepseek harness插件  
  标签：codex-cli / codex-skills / dedeepseek / python
- [dsh-cli-bridge](https://github.com/hviana/dsh-cli-bridge) — DeepSeek Harness (DSH) plugin that delegates coding tasks to the Claude Code and Codex agent CLIs and streams the whole run live — autonomous control, multi-account, automatic install, git worktrees, and any Anthropic-compatible endpoint.  
  标签：ai / ai-agent / anthropic / automation
- [dsh-tool-vision](https://github.com/TNTsama11/dsh-tool-vision) — DeepSeek Harness (DSH) plugin that lets a text-only agent call DeepSeek-V4-Flash-Vision-Exp to see images on demand, without manually switching models.  
  标签：deepseek
- [dsh-qingagent](https://github.com/void2anything/dsh-qingagent) — 在 DeepSeek Harness 里使用青简 — 一行命令安装的 DSH 插件：对话里起草改稿，右侧长出与青简桌面端同源的宣纸面板，逐条审阅后落稿  
  标签：ai-agent / ai-writing / deepseek / llm
- [dsh-model-router](https://github.com/thedeveloper256/dsh-model-router) — DeepSeek Harness plugin: role-based model routing — planner (root agent) on deepseek-v4-pro, delegated executor subagents on deepseek-v4-flash; ships a prompt section and a pro-flash-routing skill.  
  标签：ai-agents / coding-agent / cordis / deepseek
- [mathmodel-agent](https://github.com/ubggyhjb/mathmodel-agent) — 数学建模竞赛 Agent（DeepSeek Harness preset）：头脑风暴→分析→建模→代码图表→论文→六门验收，含 17 套中英文 Typst/LaTeX 模板  
  标签：Agent 与自动化
- [duhai-vision](https://github.com/hamliy-feng/duhai-vision) — Visual model adapter for Codex and DeepSeek Harness, powered by PaddleOCR-VL and Qwen.  
  标签：ai-agents / codex / ocr / openai-codex
- [dsh-fork-to-preset](https://github.com/bpc-oss/dsh-fork-to-preset) — Fork any DeepSeek Harness session into a different agent preset — a UI button with preset picker in the conversation header.  
  标签：Agent 与自动化
- [dsh-network-settings](https://github.com/dsh-plugins/dsh-network-settings) — A DeepSeek Harness plugin that bundles three network capabilities — User-Agent rewriting (from @dsh-plugin/dsh-user-agent), a HTTP / HTTPS-CONNECT / SOCKS5 proxy (from dsh-net-proxy), and configurable request auto-retry — all driven from a single 网络设置 (Network) tab in the Web settings.  
  标签：dsh-plugins / proxies / proxy / retry
- [dsh-pet-sprite](https://github.com/BlackBearCC/dsh-pet-sprite) — A playable pixel companion plugin for DeepSeek Harness (DSH): platform-jumps over chat messages, WASD controllable, with a full nurture system fed by your agent\'s real token usage.  
  标签：cordis
- [dsh-web-search-router](https://github.com/Kerberos255/dsh-web-search-router) — Priority-ordered multi-provider web_search router for DeepSeek Harness with automatic fallback.  
  标签：brave-search / deepseek / duckduckgo / exa
- [keep-reminder](https://github.com/imlishiyuan/keep-reminder) — Inject a user-defined .keep-reminder file into DeepSeek Harness conversations as a <system-reminder>, with session / turn / request modes.把 .keep-reminder 文件里的重要内容以 <system-reminder> 注入 DeepSeek Harness 上下文，支持 session / turn / request 三种注入模式。  
  标签：ai-agents
- [dsh-desktop-mac](https://github.com/enoughpower/dsh-desktop-mac) — DeepSeekHarnessMac精简版  
  标签：ai-agents / dsh-plugin-desktop
- [dsh-file-edit](https://github.com/justarook1e/dsh-file-edit) — DSH WebUI workspace file browser: agent-change review (accept/reject + undo), inline editing, diff view and rendered markdown  
  标签：Agent 与自动化
- [dsh-subagent-roles](https://github.com/vlln/dsh-subagent-roles) — 预定义角色 subagent 库：评审员、测试员、安全员一键派发。  
  标签：subagent / 角色
- [dsh-pipeline](https://github.com/vlln/dsh-pipeline) — 声明式流水线编排：多阶段 Agent 任务串行/并行执行，失败自动重试。  
  标签：流水线 / 编排
- [dsh-multi-turn-planner](https://github.com/vlln/dsh-multi-turn-planner) — 多轮任务规划器：把复杂目标拆解成可追踪的步骤清单并持续更新。  
  标签：规划 / 拆解
- [dsh-retry-policy](https://github.com/vlln/dsh-retry-policy) — 可配置重试策略：指数退避、抖动与熔断，让 Agent 调用更稳健。  
  标签：重试 / 容错
- [dsh-cost-guard](https://github.com/vlln/dsh-cost-guard) — 实时 Token 与成本看板，超预算自动熔断，用量心中有数。  
  标签：成本 / 预算
- [dsh-auto-continue](https://github.com/HsiangNianian/dsh-auto-continue) — 自动恢复中断请求：失败分类、自适应退避重试、可配置续写消息与通知。  
  标签：重试 / 自愈
- [dsh-continual-evolve](https://github.com/ZK-Andy/dsh-continual-evolve) — 持续自进化：从会话轨迹沉淀版本化、可审计、可回滚的 harness 状态。  
  标签：自进化 / 审计
- [dsh-plans](https://github.com/Optim-Agent/dsh-plans) — 声明式计划插件：把复杂目标拆成可追踪步骤并持续更新。  
  标签：规划 / 拆解
- [dsh-agent-team-gui](https://github.com/toolclub/dsh-agent-team-gui) — 多 Agent 团队的 GUI 面板：可视化团队分工与任务流转。  
  标签：多智能体 / 可视化
- [dsh-collaboration](https://github.com/Socialist-Sister/dsh-collaboration) — 多会话协作插件：让多个 Agent 会话协同完成同一任务。  
  标签：协作 / 多会话
- [dsh-review-loop](https://github.com/wuxiangru915/dsh-review-loop) — 评审闭环：代码产出后自动触发审查与修复循环，质量有保障。  
  标签：评审 / 闭环
- [dsh-checkpoint-rewind](https://github.com/PerryLink/dsh-checkpoint-rewind) — 检查点回退：把会话恢复到任意历史快照，试错零成本。  
  标签：回退 / 快照
- [dsh-doublecheck](https://github.com/PerryLink/dsh-doublecheck) — 双重检查：关键操作前二次确认，减少 Agent 误操作。  
  标签：确认 / 防护
- [dsh-yolo-mode](https://github.com/SeverusZh/dsh-yolo-mode) — YOLO 模式：自动批准所有工具调用，跑长任务不打断。  
  标签：自动审批 / 效率
- [dsh-smart-route](https://github.com/Semidia/dsh-smart-route) — 智能路由：按任务类型自动选择最优模型与 provider。  
  标签：路由 / 模型
- [dsh-prompt-enhancer](https://github.com/Fishsb/dsh-prompt-enhancer) — 一键优化草稿、增强提示词。  
  标签：提示词 / 优化
- [dsh-tool-council](https://github.com/vinoth4v/dsh-tool-council) — 让多模型（不同 provider）回答同一问题，报告共识与分歧。  
  标签：多模型 / 共识
- [octie-dsh-plugin](https://github.com/StarChen-Cycler/octie-dsh-plugin) — 状态导向任务图内核 bundle：13 个 octie 工具 + Cordis 服务 + 实时 DAG 任务面板。  
  标签：DAG / 任务图
- [dsh-shadow-mind](https://github.com/winterhuan/dsh-shadow-mind) — 并行认知运行时：从 pi-shadow-mind 移植到 DeepSeek Harness。  
  标签：认知 / 运行时
- [dsh-task-modes](https://github.com/GraySilver/dsh-task-modes) — 任务模式：常规执行、第一性原理提示、独立对抗审查。  
  标签：模式 / 审查
- [agentrq](https://github.com/agentrq/agentrq) — 人在环实时对话式任务管理器（自托管），移动/Web/桌面控制自己的 Agent，兼容 DSH。  
  标签：任务管理 / 协作
- [dsh-loom](https://github.com/ZTCNO0NE/dsh-loom) — Loom（织机）：外部教练/第二验证器，静默演化 Agent 的工具/技能/配置/模型，带确定性验证与冷应用。  
  标签：自进化 / 验证
- [dsh-auto-mode](https://github.com/NanmiCoder/dsh-auto-mode) — 为 DeepSeek Harness 提供安全的自动权限（自动审批）。  
  标签：权限 / 自动
- [context-assembler-DSH](https://github.com/i1j/context-assembler-DSH) — DSH 上下文汇编插件：话题块汇编、水位压力切割、工具轮压缩/改写、reality 召回注入、handoff 规划。  
  标签：上下文 / 压缩 / 召回
- [dsh-see-world](https://github.com/windygo123/dsh-see-world) — DSH 插件：决定何时联网搜索、强制搜索优先作答，本地任务则自动让路。  
  标签：Web / 搜索 / 策略
- [dsh-mission](https://github.com/qiaoy01/dsh-mission) — DeepSeek Harness 任务（Mission）插件。  
  标签：任务 / Mission
- [dsh-plugin-anti-rot](https://github.com/orangelightening/dsh-plugin-anti-rot) — DSH 插件：在冗长工具错误到达模型上下文前先压缩。  
  标签：压缩 / 错误 / 上下文
- [dsh-wayfinder](https://github.com/satan9394/dsh-wayfinder) — DSH 技能：大工程决策地图，决策票据逐个解析。  
  标签：决策 / 地图
- [dsh-to-questionnaire](https://github.com/satan9394/dsh-to-questionnaire) — DSH 技能：决策转问卷，提取他人知识。  
  标签：问卷 / 知识提取
- [dsh-teach](https://github.com/satan9394/dsh-teach) — DSH 技能：教学与讲解，教学工作区与合意困难。  
  标签：教学 / 讲解
- [dsh-issue-triage](https://github.com/satan9394/dsh-issue-triage) — DSH 技能：Issue/PR 分流，状态机与简报。  
  标签：Issue / PR / 分流
- [dsh-full-stack-orchestration](https://github.com/satan9394/dsh-full-stack-orchestration) — DSH 技能：全栈功能编排，状态机与检查点。  
  标签：编排 / 全栈
- [dsh-sales-automation](https://github.com/satan9394/dsh-sales-automation) — DSH 技能：销售自动化与客服，冷邮序列与异议处理。  
  标签：销售 / 客服
- [dsh-content-marketing](https://github.com/satan9394/dsh-content-marketing) — DSH 技能：内容营销，SEO 与多渠道分发。  
  标签：营销 / SEO
- [dsh-operating-kit](https://github.com/satan9394/dsh-operating-kit) — DSH 技能：会话操作纪律，开始简报与结束收尾。  
  标签：操作纪律 / 简报
- [dsh-track-driven-dev](https://github.com/satan9394/dsh-track-driven-dev) — DSH 技能：Track 驱动开发，spec/plan 与质量门。  
  标签：Track / 开发
- [dsh-x-twitter-research](https://github.com/satan9394/dsh-x-twitter-research) — DSH 技能：X/Twitter 研究，社交倾听与受控发帖。  
  标签：Twitter / 研究
- [dsh-ai-council](https://github.com/AGSQ11/dsh-ai-council) — 面向 DeepSeek Harness 的按角色驱动的企业级 AI 审议插件。  
  标签：审议 / 企业
- [dsh-omp-advisor](https://github.com/AndrasSama/dsh-omp-advisor) — 把 oh-my-pi 顾问子系统移植到 DSH：独立审查模型观察并建议（注入 nit、阻断 / 关切转向）。  
  标签：顾问 / 评审 / review
- [dsh-trajectory-ablation](https://github.com/Ardig24/dsh-trajectory-ablation) — 通过重建、diff 与消融 Agent 上下文，定位失败真正原因的 DSH 插件。  
  标签：诊断 / 上下文 / debug
- [dsh-study-buddy](https://github.com/V-Reason/dsh-study-buddy) — 使用 DeepSeek Harness 进行学习与笔记的插件。  
  标签：学习 / 笔记

<a id="cat-记忆与知识" name="cat-记忆与知识"></a>

### 🧠 记忆与知识

- [Mnemon](https://github.com/omdsh-dev/dsh-mnemon) — 本地三层记忆体（情景/语义/程序），跨会话长期记忆的完整实现。  
  标签：长期记忆 / 本地优先
- [dsh-memory-evolve](https://github.com/csyangwen/dsh-memory-evolve) — 为 DeepSeek Harness 带来「跨会话长期记忆 + 后台自我进化」能力。  
  标签：长期记忆 / 进化
- [nowledge-mem](https://github.com/nowledge-co/nowledge-mem-deepseek-harness) — Nowledge Mem 的 DeepSeek Harness 社区插件包。  
  标签：记忆
- [dsh-postmortem](https://github.com/zzh-newlearner/dsh-postmortem) — DeepSeek Harness 会话的本地优先失败复盘。  
  标签：复盘
- [zotero-harvest](https://github.com/Fisfzy/zotero-harvest) — Zotero 文献采集入库插件。  
  标签：Zotero / 文献
- [dsh-explain](https://github.com/yuezengwu/dsh-explain) — DSH 本地优先学习模式插件。  
  标签：学习
- [KB Sieve](https://github.com/omdsh-dev/dsh-kb-sieve) — 从 md/txt/docx/pdf 构建可审计知识库包，检索可控可追溯。  
  标签：知识库 / 审计
- [zotero-wave-rag](https://github.com/Fisfzy/zotero-wave-rag) — 面向 Zotero 论文库的浪潮式 RAG 细节检索系统。  
  标签：RAG / 论文
- [Scholar](https://github.com/lzszq/dsh-scholar) — 面向纯计算研究的 AI 科研工作台，推导、实验、论文一条龙。  
  标签：科研 / RAG
- [dsh-notebooks](https://github.com/havingautism/dsh-notebooks) — 把 Codemini 风格的持久随手记带到 DSH。  
  标签：笔记
- [OpenMAIC](https://github.com/THU-MAIC/dsh-openmaic) — 课堂、幻灯片、交互组件与苏格拉底式教学，把 DSH 变成老师。  
  标签：教学 / 交互
- [dsh-book2skill](https://github.com/omdsh-dev/dsh-book2skill) — 书籍转技能：5 阶段长任务工作流。  
  标签：技能生成
- [dsh-tutorials](https://github.com/zoahdev/dsh-tutorials) — DeepSeek Harness 中英双语教程：入门、架构、插件开发、发布前自检与贡献者路线图。  
  标签：教程 / 双语 / 入门
- [dsh-session-handoff](https://github.com/snow-The/dsh-session-handoff) — DSH 会话交接与上下文管理：结构化交接文档（导出/恢复/状态）+ 活动上下文裁剪。  
  标签：会话 / 上下文 / 交接
- [dsh-memory](https://github.com/QIANLING-0831/dsh-memory) — DSH 记忆插件：CJK 感知的会话全文检索、工具结果去重与向量+FTS5 混合记忆，降低 Token 消耗。  
  标签：记忆 / 检索 / 向量
- [dsh-solo-leveling](https://github.com/zzyyyds88/dsh-solo-leveling) — DeepSeek Harness（DSH）插件集：访问门禁（登录 + HTTPS 反代）、默认值、手机端适配、桌宠、任务套件（看板 / 统计 / Git 图谱 / 皮肤）。Linux 服务器部署 DSH，浏览器 / 手机 / 局域网公网随时调用。  
  标签：solo / HTTPS / Git / 记忆与知识
- [dsh-evolve](https://github.com/chenzheshushi-commits/dsh-evolve) — Self-evolving memory + skill lifecycle for DeepSeek Harness — durable cross-session memory with zero-token deterministic recall, tiered approval, reinforcement learning from repetition, and anti-bloat convergence for both skills and memory.  
  标签：evolve / Self-evolving / memory / 记忆与知识
- [dsh-mnemosyne](https://github.com/rebron1900/dsh-mnemosyne) — Mnemosyne 记忆层在 DeepSeek Harness 中的插件 — 本地优先、SQLite 支持的跨会话记忆。  
  标签：mnemosyne / SQLite / 记忆与知识
- [AIsChat](https://github.com/Coprexist/AIsChat) — AIsChat 是一个开源 AI 群聊框架：让 AI 拥有自己的状态、记忆与生命节奏——不只是工具，是陪伴。群视界（Group World）让每个群聊绑定一个活的世界（网页 + 世界 AI + 代码 + 时间），并支持 DSH 工作区镜像双向同步。  
  标签：AIsChat / Group / 记忆与知识
- [dsh-plugin-zhishe-common](https://github.com/siweimofang/dsh-plugin-zhishe-common) — 知设 DSH 插件共享基础设施 - 知识库加载/检索/基准价格/风险评估  
  标签：plugin / 记忆与知识
- [zhishe-a2a](https://github.com/siweimofang/zhishe-a2a) — 知设AI装修顾问 - 主仓库(知识库+DSH插件+GEO)  
  标签：zhishe / GEO / 记忆与知识
- [dsh-memory-manager](https://github.com/MoonlitDropOfBlood/dsh-memory-manager) — DSH基本的记忆功能  
  标签：memory / 记忆与知识
- [dsh-memory](https://github.com/qwert702/dsh-memory) — Long-term memory plugin for the DeepSeek Harness Web GUI: project+global stores, auto extraction/injection, small-model consolidation, Obsidian-style link graph.  
  标签：memory / Long-term / Web / 记忆与知识
- [dsh-memory-note](https://github.com/DecarbonizedGlucose/dsh-memory-note) — Lightweight local cross-session memory for DeepSeek Harness  
  标签：memory / Lightweight / local / 记忆与知识
- [dsh-background-web](https://github.com/gubai-future/dsh-background-web) — Self-contained whole-window background plugin for DeepSeek Harness web: browser file picker, host-side single-slot storage, and a General-settings preference row.  
  标签：background / Self-contained / whole-window / 记忆与知识
- [dsh-tavern](https://github.com/chen731215-dev/dsh-tavern) — DSH 原生酒馆管理面板，入口：设置 → 通用设置 → 酒馆管理（原生）。多角色卡/多世界书/多预设，会话级预设隔离；世界书智能关键词注入省 60-70% 上下文；记忆总结 + 角色关系网；剧情选项一键发送；创作/扮演双模式；NSFW 成人模式。免费非商用（CC BY-NC-SA 4.0）。安装：dsh plugin --profile web add dsh-tavern  
  标签：tavern / NSFW / BY-NC-SA / 记忆与知识
- [clawock](https://github.com/KCNyu/clawock) — AI argues. Code settles. The losses stay on the page. A real HK + US brokerage account run by agents that must debate every call, settled by code the model never touches. Install the same decision workflow into your own agent: OpenClaw, Claude Code, Codex, or DeepSeek Harness.  
  标签：argues / Code / 记忆与知识
- [dsh-brainagent](https://github.com/stas130286-blip/dsh-brainagent) — BrainAgent - brain-inspired cognitive plugin for DeepSeek Harness (dsh): memory, emotions, learning, autonomy, self-regulation. 571 tests. Free noncommercial use.  
  标签：brainagent / brain-inspired / cognitive / 记忆与知识
- [dsh-patchouli](https://github.com/memorax-ai/dsh-patchouli) — Agent knowledge hub and deepseek-harness plugin  
  标签：patchouli / Agent / knowledge / 记忆与知识
- [dsh-output-styles](https://github.com/PerryLink/dsh-output-styles) — Claude Code outputStyles for DeepSeek Harness - session-scoped, durable, runtime-switchable model output styles (/style command, output_style storage domain, systemPrompt injection)  
  标签：output / Claude / Code / 记忆与知识
- [dsh-context-pro](https://github.com/kiwifruit13/dsh-context-pro) — DSH Agent 上下文浸泡器：注入五维认知图鉴 + 链协议模式（prestep 零干预）+ JSON 快照链演化提取  
  标签：context / Agent / prestep / 记忆与知识
- [dsh-dream-skin](https://github.com/RevolutionLA/dsh-dream-skin) — DeepSeek Harness 换肤 / 壁纸 / 主题包插件 (dsh-plugin) — 8 套 Mirage 主题、每用户强调色、壁纸2.0、主题包导入导出/分享链接、收藏与随机，纯原生 token 系统实现。  
  标签：dsh-plugin-theme / skin / theme / wallpaper
- [dsh-Mmem](https://github.com/mianyoubiaoqing/dsh-Mmem) — 这是一个支持同dsh进程多记忆空间的dsh记忆插件  
  标签：dsh-plugins / memory / memory-safety / memory-space
- [dsh-memo](https://github.com/lesliechowsh/dsh-memo) — Memo — session memory search for DeepSeek Harness agents (memo_search / memo_remember / memo_stats on the official sessionQuery service). Every benchmark number is the shipped product\'s own, with the experiment trail published.  
  标签：agent-memory / memory
- [mindspace-dsh-local-rag](https://github.com/Spirtxiaoqi7/mindspace-dsh-local-rag) — ARPM-derived local hybrid RAG plugin for DeepSeek Harness  
  标签：arpm / bm25 / hybrid-search / local-rag
- [mindspace-dsh-session-memory](https://github.com/Spirtxiaoqi7/mindspace-dsh-session-memory) — Editable, session-isolated personalization memory for DeepSeek Harness  
  标签：agent-memory / memory / personalization / roleplay
- [dsh-session-search-toggle](https://github.com/drscrewdriver/dsh-session-search-toggle) — 给 DeepSeek Harness 侧边栏加一个会话内容检索——标题/内容一键切换，还能按用户/回复/工具筛选  
  标签：dedeepseek-harness / dsh-bundle / dsh-plugin-market / dsh-plugins
- [runtime36](https://github.com/398894496-arch/runtime36) — DSH-KRouter — Agent knowledge OS. Self-evolution. First qualifying day auto-provisional; second accepted task → formal. Correction-first. Retrieval is the lock, not the product. Timer off ≠ optional. Cursor, Codex, Claude Code, DeepSeek Harness.  
  标签：deepseek / knowledge-base / memory / obsidian
- [dsh-memory](https://github.com/zhouzhencheng07/dsh-memory) — Cross-session memory for DeepSeek Harness (dsh): Auto-Memory per-turn capture, memory_search, Dream consolidation  
  标签：agent-memory / automemory / dream / memory
- [dsh-wiki-bridge](https://github.com/xiaomao49/dsh-wiki-bridge) — WikiBridge：DSH × Obsidian 知识库桥接插件（约束工具 + 自动词典检索 + 零补丁配置）  
  标签：agent-memory / knowledge-base / obsidian / second-brain
- [dsh-lite-memory](https://github.com/SiriusWJ/dsh-lite-memory) — DSH 简化版记忆插件:SQLite 条目化记忆(标题/重要程度/来源/内容,增删改查)+ 日历与到点提醒(月视图+时间轴+待执行/已完成双tab),对话面板记忆 tab 与设置二级菜单,中英双语自动跟随。  
  标签：记忆与知识
- [dsh-better-reasoning-effort](https://github.com/HaoyueQin/dsh-better-reasoning-effort) — Reasoning-effort editing for third-party models in DeepSeek Harness: per-model thinking levels with a knowledge base + protocol inference, edited inside the official Models page card.  
  标签：automation / deepseek / llm / plugin
- [dsh-model-memory](https://github.com/Mutx163/dsh-model-memory) — 🧠 DSH 自定义模型思考等级管理与偏好持久记忆插件 | Custom model reasoning effort management & cross-session memory for DeepSeek Harness  
  标签：cordis / deepseek / model-memory / reasoning-effort
- [distill-kura](https://github.com/lna-lab/distill-kura) — 蒸留蔵 — distilled long-term memory for agents: recall by meaning, writing gated by evidence, one kura per agent mode. Ships as a DeepSeek Harness plugin and an MCP server.  
  标签：agent-memory / llm-memory / long-term-memory / mcp-server
- [dsh-daoing-memory](https://github.com/daoing/dsh-daoing-memory) — deepseek harness  memory plugin  
  标签：dsh-plugin-market / dsh-plugins
- [dsh-NotEMD](https://github.com/Jacobinwwey/dsh-NotEMD) — Portable NoteMD workflow bundle for DeepSeek Harness: approval-gated markdown automation, knowledge indexing, diagrams, SVG previews, and Slidev exports.  
  标签：ai-workflows / approval-workflow / cordis / deepseek
- [dsh-plugin-thread](https://github.com/zhaoyuntao-wl/dsh-plugin-thread) — DeepSeek Harness plugin - Thread session memory adapter (dsh-thread)  
  标签：ai-agents / coding-agent / memory / session-memory
- [dsh-cost-tracker](https://github.com/Angelyeye/dsh-cost-tracker) — DeepSeek Harness plugin: LLM token usage & cost tracking dashboard (CNY, peak/off-peak pricing), agent tools, HTTP API, persistent storage  
  标签：cordis / cost-tracking / llm
- [dsh-memory-bank](https://github.com/vlln/dsh-memory-bank) — 跨会话记忆银行：自动抽取关键决策与偏好，按主题归档检索。  
  标签：记忆 / 归档
- [dsh-changelog](https://github.com/vlln/dsh-changelog) — 自动生成每日工作变更日志，沉淀项目演进脉络。  
  标签：日志 / 记录
- [dsh-flashcards](https://github.com/vlln/dsh-flashcards) — 对话中一键生成记忆卡片，基于间隔重复帮你记住知识点。  
  标签：学习 / 间隔重复
- [dsh-citation](https://github.com/vlln/dsh-citation) — 自动为生成内容附加来源引用，标注出处、可回溯校验。  
  标签：引用 / 溯源
- [dsh-mneme](https://github.com/modusensus/dsh-mneme) — 跨会话记忆：SQLite + 可人工编辑的 Markdown 镜像，后台自动巩固去重。  
  标签：记忆 / SQLite
- [dsh-memory-vault](https://github.com/flymysql/dsh-memory) — 跨会话记忆库：remember/recall/forget 工具，每轮提示注入。  
  标签：记忆 / 召回
- [dsh-memoria](https://github.com/jiayan-xu/dsh-memoria) — Memoria 记忆插件：让 Agent 记住项目约定与关键决策。  
  标签：记忆 / 项目
- [dsh-memory-gate](https://github.com/GIT121995/dsh-memory-gate) — 记忆门：控制哪些信息进入长期记忆，敏感内容自动过滤。  
  标签：记忆 / 过滤
- [dsh-deepread](https://github.com/xiehuan123/dsh-deepread) — 深度阅读插件：长文档分段精读，逐章提炼要点。  
  标签：阅读 / 提炼
- [dsh-learn-everything](https://github.com/cendaifeng/dsh-learn-everything) — 学习一切：把任意资料转化为结构化学习路径。  
  标签：学习 / 路径
- [Code2Skill](https://github.com/leechen298/Code2Skill) — 代码转技能：把代码库自动提炼为可复用的 Agent Skill。  
  标签：技能 / 提炼
- [dsh-file-mount](https://github.com/acefun29/dsh-file-mount) — 文件挂载插件：把外部目录/文件挂载进工作区。  
  标签：挂载 / 文件
- [dsh-bookmarks](https://github.com/penguin-oo/dsh-bookmarks) — 书签插件：收藏常用文件、路径与命令，一键召回。  
  标签：书签 / 收藏
- [dsh-report-studio](https://github.com/ciceroyang/dsh-report-studio) — 报告工作室：把会话产出编排成结构化报告文档。  
  标签：报告 / 交付
- [sgme 拾光记忆](https://github.com/freehul/sgme) — 拾光记忆引擎：记得你们聊过的每一件事，还会主动关心你。  
  标签：记忆 / 引擎
- [deepddw](https://github.com/ccch713/deepddw) — DeepSeek Harness 记忆与知识库，局域网内任意设备可达。  
  标签：记忆 / 知识库
- [dsh-statecore](https://github.com/yul761/dsh-statecore) — 原生记忆插件：带证据链的可审计事实，StateCore 驱动。  
  标签：记忆 / 证据链
- [dsh-memory-ai](https://github.com/wang-jie-git/dsh-memory-ai) — AI-memory 深度集成的 DSH 语义记忆插件。  
  标签：记忆 / 语义
- [dsh-md-notes](https://github.com/XieZongChen/dsh-md-notes) — 笔记插件：保存与编辑对话中想记录的内容。  
  标签：笔记 / 记录
- [dsh-plugin-sodamem](https://github.com/SodaMem/dsh-plugin-sodamem) — 原生 DSH 记忆插件：每轮自动注入证据锚定记忆，并摄取每个已结束的回合。  
  标签：记忆 / 证据
- [MisakaNet](https://github.com/Ikalus1988/MisakaNet) — 零依赖、git 支撑的 Agent 微课程库：异步共享与检索已验证的调试经验。  
  标签：经验 / 知识库
- [dsh-layered-memory](https://github.com/DDDFXYqiming/dsh-layered-memory) — DeepSeek Harness 跨会话长期记忆插件。  
  标签：长期记忆
- [dsh-workshpace-plugin](https://github.com/kaiqiangh/dsh-workshpace-plugin) — 检视 Agent 触碰过的文件、审查会话产物、预览边界内容、管理本地工作区记忆。  
  标签：工作区 / 记忆
- [dsh-writing-for-agents](https://github.com/satan9394/dsh-writing-for-agents) — DSH 技能：写给 agent 的文档，指针与信息层级。  
  标签：文档 / 写作
- [dsh-knowledge-graph](https://github.com/cwbcheng/dsh-knowledge-graph) — DSH Cordis 插件：将任意源文本转为 AI 知识图谱，图谱与原文双向链接。  
  标签：知识图谱 / 双向链接
- [graph-memory](https://github.com/adoresever/graph-memory) — DSH/Openclaw 知识图谱记忆插件：从对话抽取结构化三元组，压缩上下文 75%，支持跨会话经验复用。  
  标签：知识图谱 / 记忆 / 上下文
- [dsh-plugin-mnemosyne](https://github.com/xuviga/dsh-plugin-mnemosyne) — DSH 错误记忆插件：从 Agent 自身失误中学习并阻断重复错误。  
  标签：记忆 / 错误 / 自愈

<a id="cat-工具与连接" name="cat-工具与连接"></a>

### 🛠️ 工具与连接

- [Better Browser](https://github.com/titanwings/dsh-better-browser) — 让 Agent 用你已登录的真实浏览器操控网页，绕过验证码与登录墙。  
  标签：浏览器 / 真实环境
- [Computer Use](https://github.com/Anionex/dsh-computer-use) — 为 DSH 提供电脑控制能力，点击、输入、截图全交给 Agent。  
  标签：GUI 操作 / 自动化
- [Toolkit](https://github.com/omdsh-dev/dsh-toolkit) — 零依赖工具包合集：计算器、正则、JSON、CSV、时间、哈希一应俱全。  
  标签：工具集 / 零依赖
- [Custom Tool](https://github.com/omdsh-dev/dsh-custom-tool) — 用 Monaco 编辑器写沙箱化 JS 工具，即时注册给模型调用。  
  标签：自定义 / 沙箱
- [SSH Remote](https://github.com/UynajGI/dsh-ssh) — SSH 远程执行插件，把 Agent 的能力延伸到服务器集群。  
  标签：SSH / 远程执行
- [Telegram Bridge](https://github.com/LoserFox/telegram) — Telegram Bot API 桥接，把 DSH 接到你的聊天软件里随时使唤。  
  标签：IM / 桥接
- [Mobile Control](https://github.com/PangYiMing/dsh-mobile-control) — 通过 ADB / WDA 驱动 Android 与 iOS 设备，手机也能被 Agent 操控。  
  标签：手机控制 / ADB
- [modlens](https://github.com/liustack/modlens) — ModLens：给纯文本模型「视力」的插件式视觉引擎。  
  标签：视觉 / 引擎
- [argo](https://github.com/taxueseek/argo) — Argo：专为 Agent 打造的搜索与核查工具。  
  标签：搜索 / 核查
- [browser-bridge](https://github.com/hanelalo/browser-bridge) — Browser Bridge：通过 WebSocket 把本地工具和真实浏览器连接起来的桥。  
  标签：桥接
- [dsh-acp-for-bitfun](https://github.com/bobleer/dsh-acp-for-bitfun) — 把 BitFun 接入 dsh 的插件 bundle。  
  标签：桥接
- [dsh-git-identity](https://github.com/LoserFox/dsh-git-identity) — git 提交固定使用环境自身作者身份。  
  标签：Git
- [dsh-data-agent](https://github.com/omdsh-dev/dsh-data-agent) — 数据 Agent：让 AI 连上数据库并形成 Agent Loop。  
  标签：数据库
- [dsh-browser](https://github.com/Lum1104/dsh-browser) — dsh Browser Control：把 DSH 连接到你自己正在用的 Chrome 标签页。  
  标签：浏览器
- [dsh-tool-csv](https://github.com/omdsh-dev/dsh-tool-csv) — DSH CSV 数据工具插件。  
  标签：CSV
- [dsh-tool-time](https://github.com/omdsh-dev/dsh-tool-time) — DSH 时间工具插件。  
  标签：时间
- [dsh-tool-encoding](https://github.com/omdsh-dev/dsh-tool-encoding) — DSH 编码/哈希工具插件。  
  标签：哈希
- [dsh-tool-json](https://github.com/omdsh-dev/dsh-tool-json) — DSH JSON 查询工具插件。  
  标签：JSON
- [dsh-tool-calculator](https://github.com/omdsh-dev/dsh-tool-calculator) — DSH 计算器工具插件。  
  标签：计算
- [dsh-tool-regex](https://github.com/omdsh-dev/dsh-tool-regex) — DSH 正则工具插件。  
  标签：正则
- [dsh-tool-schema](https://github.com/omdsh-dev/dsh-tool-schema) — DSH JSON Schema 验证工具插件。  
  标签：Schema
- [dsh-tool-diff](https://github.com/omdsh-dev/dsh-tool-diff) — DSH Diff 工具插件。  
  标签：Diff
- [dsh-tool-markdown](https://github.com/omdsh-dev/dsh-tool-markdown) — DSH Markdown 工具插件。  
  标签：Markdown
- [dsh-tool-stat](https://github.com/omdsh-dev/dsh-tool-stat) — DSH 统计工具插件。  
  标签：统计
- [dsh-cc-connect](https://github.com/whiteguo233/dsh-cc-connect) — dsh 与 cc-connect 的双向桥接。  
  标签：桥接
- [deepseek-harness-huggingface](https://github.com/emredeveloper/deepseek-harness-huggingface) — 社区插件：为 DeepSeek Harness 增加只读的 Hugging Face Hub 模型发现能力。  
  标签：HuggingFace
- [sandbox-micro](https://github.com/omdsh-dev/sandbox-micro) — microsandbox 沙盒插件包。  
  标签：沙箱
- [dsh-tool-search](https://github.com/vibeinging/dsh-tool-search) — 为 DeepSeek Harness 提供按 Agent 的按需工具发现与渐进式 schema 暴露。  
  标签：工具发现
- [dsh-tool-browser](https://github.com/omdsh-dev/dsh-tool-browser) — 浏览器控制配置。  
  标签：浏览器
- [dsh-tool-approval](https://github.com/ilharp/dsh-tool-approval) — 为任意工具调用添加预审批。  
  标签：审批
- [math-lean](https://github.com/Fisfzy/math-lean) — dsh-lean-prover：基于 Lean 内核验证的数学推理插件。  
  标签：数学 / Lean
- [ego-browser](https://github.com/Fisfzy/ego-browser) — 把 ego-lite 浏览器接入 HARNESS。  
  标签：浏览器
- [dsh-onlyne](https://github.com/dbydd/dsh-onlyne) — 通过 Onlyne 给 dsh Agent 一个真实的 IM 收件箱/发件箱。  
  标签：IM
- [dsh-plugin-interpreters](https://github.com/HuanLinOTO/dsh-plugin-interpreters) — 向模型暴露 run_python 与 run_node 两个工具。  
  标签：解释器
- [dsh-plugin-mineru](https://github.com/HuanLinOTO/dsh-plugin-mineru) — 向模型暴露 MinerU 文档解析工具。  
  标签：文档解析
- [dsh-plugin-auto-blame](https://github.com/HuanLinOTO/dsh-plugin-auto-blame) — 模型完成一轮对话后生成批判性跟进请求。  
  标签：评审
- [dsh-super-injector](https://github.com/yjh051108/dsh-super-injector) — 超级模组注入器：BepInEx 式运行时模组注入入口。  
  标签：注入
- [dsh-session-search](https://github.com/Tieboyh/dsh-session-search) — 跨 Agent 会话搜索。  
  标签：搜索
- [sandbox-mxc](https://github.com/omdsh-dev/sandbox-mxc) — MXC 沙盒 provider（独立外部 bundle）。  
  标签：沙箱
- [sandbox-nono](https://github.com/omdsh-dev/sandbox-nono) — nono（Landlock/Seatbelt）沙盒后端插件包。  
  标签：沙箱
- [dsh-openai-codex-auth](https://github.com/yoke233/dsh-openai-codex-auth) — 为 DeepSeek Harness 提供 OpenAI Codex 订阅登录与用量展示。  
  标签：Codex / 鉴权
- [dsh-longbridge](https://github.com/omdsh-dev/dsh-longbridge) — DSH 长桥（Longbridge）港美股数据接入插件。  
  标签：行情
- [dsh-worktree](https://github.com/FlashingChen/dsh-worktree) — Codex 风格的永久 git worktree。  
  标签：Git
- [dsh-screenshot-diff](https://github.com/PangYiMing/dsh-screenshot-diff) — 像素对比工具。  
  标签：对比
- [dsh-browser-control](https://github.com/PangYiMing/dsh-browser-control) — 操控浏览器插件：通过 CDP / Playwright 驱动浏览器。  
  标签：浏览器
- [dsh-batch-regression](https://github.com/PangYiMing/dsh-batch-regression) — 批量回归统计插件。  
  标签：回归
- [dsh-bisect-debug](https://github.com/PangYiMing/dsh-bisect-debug) — 二分定位 bug 插件。  
  标签：调试
- [dsh-feishu](https://github.com/PGZXB/dsh-feishu) — DeepSeek Harness 的飞书 UI：面板驱动的控制台，每个斜杠命令都是控制面板卡片上的按钮。  
  标签：飞书 / 控制台 / UI
- [dsh-worktree-studio](https://github.com/Palaiologos1453/dsh-worktree-studio) — 面向 DeepSeek Harness 的手动 Git worktree 任务看板。  
  标签：Git / worktree / 任务
- [dsh-api-balance](https://github.com/Badegg404/dsh-api-balance) — DSH 插件：多平台 AI 账户余额悬浮监控。  
  标签：监控 / 余额 / 多平台
- [dsh-geodesy](https://github.com/TYEclipse/dsh-geodesy) — DSH 的大地测量数学工具箱：大圆距离、方位角、目的地点与 DMS 坐标解析。  
  标签：工具 / 大地测量 / 数学
- [deepseek-harness-workbench-plugin](https://github.com/loadingvx/deepseek-harness-workbench-plugin) — DeepSeek Harness 工作台（Workbench）插件。  
  标签：工作台 / Workbench
- [dsh-rigorquant](https://github.com/linxichen/dsh-rigorquant) — 为 DeepSeek Harness 增加严谨的量化金融分析能力。  
  标签：量化 / 金融
- [dsh-plugin-llm-verifier](https://github.com/uson1x/dsh-plugin-llm-verifier) — DSH 的 LLM-as-a-Verifier：通过选择/比较/追踪提供持续奖励信号。  
  标签：验证 / LLM / 奖励
- [deepseek-harness-fnos](https://github.com/techysy/deepseek-harness-fnos) — DeepSeek Harness（官方 Agent 浏览器 UI）的 fnOS 应用，本地常驻服务。  
  标签：fnOS / 桌面 / 常驻
- [dsh-voice](https://github.com/KotDath/dsh-voice) — DSH 语音输入插件。  
  标签：语音 / 输入
- [DeepSeek-Harness-for-VS-Code](https://github.com/NEXTINDIE/DeepSeek-Harness-for-VS-Code) — VS Code 版 DeepSeek Harness：@dsh 聊天参与者、侧边栏与独立聊天、计划模式、目标与子 Agent。  
  标签：VS Code / 编辑器 / 子Agent
- [dsh-git-rescue](https://github.com/EIGHTfs/dsh-git-rescue) — DSH Git 版本管理 + 崩溃自动救援插件（仅 GitHub token 方案）。  
  标签：Git / 救援 / 版本
- [DSh-feishu-bot](https://github.com/wangsan71/DSh-feishu-bot) — 连接飞书/Lark 与本地 DSH 的机器人组件。  
  标签：飞书 / 机器人 / Lark
- [deepsiper-enthea](https://github.com/8b-is/deepsiper-enthea) — 从 deepseek-harness 派生的主权化、Agent 驱动的 LLM 评测 Harness，采用 Cordis 插件架构。  
  标签：评测 / Harness / 派生
- [dsh-wsl-keepalive](https://github.com/TheColdWorld/dsh-wsl-keepalive) — a Ai-Gererated plugin for Dsh alive in Windows Subsystem of Linux  
  标签：wsl / Ai-Gererated / Dsh / 工具与连接
- [dsh-complete-chime](https://github.com/Whale-Zhang/dsh-complete-chime) — DSH plugin: play a chime when a conversation turn finishes. Built-in tones plus custom upload in Settings → Plugins.  
  标签：complete / play / chime / 工具与连接
- [dev-flow](https://github.com/Innocent-children/dev-flow) — Local process control and recovery for Codex and DeepSeek Harness: explicit scope, verification budgets, and durable task state.  
  标签：dev / Local / process / 工具与连接
- [dsh-run2skill](https://github.com/qkycir-123/dsh-run2skill) — DSH-native, local-first Run-to-Skill plugin for DeepSeek Harness  
  标签：run2skill / DSH-native / local-first / 工具与连接
- [dsh-ros2](https://github.com/StvLi/dsh-ros2) — The Deepseek Harness ROS 2 plugin can be used to efficiently diagnose issues and perform joint debugging.  
  标签：ros2 / The / Deepseek / 工具与连接
- [dsh-plugins](https://github.com/lwmxiaobei/dsh-plugins) — DeepSeek Harness 社区插件目录，自动汇总并基础校验 GitHub 插件，支持搜索、筛选、双语详情与最新版本安装命令复制。Community directory for DeepSeek Harness plugins with automated discovery, basic validation, search, filters, bilingual details, and latest version install commands.  
  标签：plugins / GitHub / Community / 工具与连接
- [dsh-profile-settings](https://github.com/XMoon/dsh-profile-settings) — Per-profile settings overlay for DeepSeek Harness: global settings.yaml plus profiles/<name>/settings.patch.yml, transparently layered under ctx.settings  
  标签：profile / Per-profile / settings / 工具与连接
- [EzDSH](https://github.com/Tiee7/EzDSH) — Easy Way to the DeepSeek‑Harness.  
  标签：Easy / Way / 工具与连接
- [dsh-quick-toc](https://github.com/LyaxZ/dsh-quick-toc) — DeepSeek Harness 对话大纲插件：按回合分组的 Markdown 标题目录，自动跟随高亮，平滑跳转导航。  
  标签：quick / Markdown / 工具与连接
- [dsh-mcp-connector](https://github.com/duhu2000/dsh-mcp-connector) — DeepSeek Harness 通用 MCP连接器、连接管理与扩展市场：连接 MCP Server，发现工具与 Prompt，扩展 AI 技能；支持 OAuth/PKCE、API Key、JSON 导入。由企查查（Qichacha/QCC）团队发起维护。General-purpose MCP connector, connection manager, plugin, extension and integration marketplace.  
  标签：mcp / Server / Prompt / 工具与连接
- [dsh-bridge](https://github.com/wenbin-wb/dsh-bridge) — DeepSeek Harness 多通道远程访问插件 | 手机扫码秒连本地 AI、微信/QQ 直接对话、流式输出、按钮交互、多工作区切换、会话持久化 | 无需公网服务器，支持局域网直连、Cloudflare 隧道、自建隧道 | QQ Bot  + 微信 ClawBot  
  标签：bridge / Cloudflare / Bot / 工具与连接
- [dsh-thunderforge](https://github.com/oneinitAI/dsh-thunderforge) — ⚡ ThunderForge — 励志做 0 元以内最 nb 的 DSH 插件（产品目标）：一站式 DSH 插件开发套件（单一 Bundle）  
  标签：thunderforge / Bundle / 工具与连接
- [dsh-local-voice-dictation](https://github.com/LionGateOS/dsh-local-voice-dictation) — Local voice plugin for DeepSeek Harness: microphone dictation with local STT plus assistant-response Kokoro TTS playback.  
  标签：local / voice / microphone / 工具与连接
- [dsh-plugin-confirmo](https://github.com/purezhi/dsh-plugin-confirmo) — 复刻 confirmo for DeepSeek Harness  
  标签：plugin / confirmo / 工具与连接
- [dsh-plogin-plugin-recommender](https://github.com/tanle-mtr/dsh-plogin-plugin-recommender) — The most comprehensive AI-curated list of DeepSeek Harness (DSH) plugins - 190+ plugins, 12 categories, updated hourly by AI.  
  标签：plogin / The / most / 工具与连接
- [dsh-trading](https://github.com/maddogfinance/dsh-trading) — Trading research workbench for DeepSeek Harness (dsh): typed market-data seam, deterministic indicators, interactive chart cards ｜ 交易研究工作台插件：数据接缝 · 确定性指标 · 交互式K线卡  
  标签：trading / research / workbench / 工具与连接
- [dsh-quota-meter](https://github.com/ai-shushu/dsh-quota-meter) — Per-session quota meter for DSH: real-token billing, live progress bar, budget blocking, configurable multi-model pricing. 会话额度监控：真实记账、进度条、额度拦截、价目可配。  
  标签：quota / Per-session / meter / 工具与连接
- [dsh-shanhai-stats](https://github.com/cn-zhangpeng/dsh-shanhai-stats) — 山海系列 DeepSeek Harness 用量统计插件：总量徽章、每日走势、GitHub 风格热力图、按模型/提供商分组明细  
  标签：shanhai / GitHub / 工具与连接
- [Weave-for-DSH](https://github.com/Quan-Chan/Weave-for-DSH) — DeepSeek Harness上的一个离线可用的单HTML节点图编辑器  
  标签：Weave / HTML / 工具与连接
- [dsh-reasoning-level](https://github.com/peterwangze/dsh-reasoning-level) — DSH (DeepSeek Harness) plugin: unified default reasoning level (thinking effort) for all models — per-model defaults with capability probing, live call statistics, one-command install via dsh plugin  
  标签：reasoning / unified / default / 工具与连接
- [dsh-llm-fallbacks](https://github.com/omdsh-dev/dsh-llm-fallbacks) — An dsh plugin for role-based LLM retry&fallback strategy. 基于角色的模型重试备用策略插件  
  标签：llm / dsh / role-based / 工具与连接
- [dsh-bili-asr](https://github.com/rudyz666/dsh-bili-asr) — 解析 B站视频链接，提取完整脚本/字幕：优先字幕轨，无字幕用本地 whisper 转写，导出 SRT/TXT/JSON。DeepSeek Harness 插件，跨平台 Windows/macOS/Linux（纯 Node）。  
  标签：bili / whisper / SRT / 工具与连接
- [shl-session-history](https://github.com/sunyuhuirong/shl-session-history) — DeepSeek Harness plugin: conversation history request rail (ZCode-style) - 会话历史请求迷你滑轨  
  标签：shl / conversation / history / 工具与连接
- [dsh-harmony](https://github.com/enoughpower/dsh-harmony) — DSH Harmony 客户端 搭配 dsh-pocket 使用  
  标签：harmony / dsh-pocket / 工具与连接
- [deepseek-plugin-store](https://github.com/Pericardiac-podzolsoil527/deepseek-plugin-store) — 发现、安装 DeepSeek Harness 生态中的社区插件、工具与扩展，探索 1493+ 精选主题插件并实时更新目录。  
  标签：deepseek / 工具与连接
- [dsh-mcp-lens](https://github.com/Andrietteprotective835/dsh-mcp-lens) — Shrink massive MCP catalogs to two tools, letting DeepSeek Harness search and call 1,000+ remote APIs efficiently.  
  标签：mcp / Shrink / massive / 工具与连接
- [dsh-archive-manager](https://github.com/MoonlitDropOfBlood/dsh-archive-manager) — DSH的归档管理插件  
  标签：archive / 工具与连接
- [dsh-token-stats](https://github.com/MoonlitDropOfBlood/dsh-token-stats) — dsh的token消耗的统计插件  
  标签：token / dsh / 工具与连接
- [dsh-plugins](https://github.com/winliyou/dsh-plugins) — deepseek harness plugin set  
  标签：plugins / deepseek / harness / 工具与连接
- [dsh-mindmap](https://github.com/guhanfei-ai/dsh-mindmap) — 让DSH帮你快速制作思维脑图  
  标签：mindmap / 工具与连接
- [the-binding-of-dsh](https://github.com/CH4ACKO3/the-binding-of-dsh) — Bidirectional DSH Connection and Typert Gateway integration  
  标签：the / Bidirectional / Connection / 工具与连接
- [dsh-document-review](https://github.com/yabo083/dsh-document-review) — DeepSeek Harness plugin: review Markdown documents in a local browser with annotations, replacements, and deletion suggestions. Supports single files and whole directories.  
  标签：document / review / Markdown / 工具与连接
- [dsh-plugin-hub](https://github.com/pax-beehive/dsh-plugin-hub) — DSH plugin registry, version-locked Profiles, CLI, and rollback tooling for DeepSeek Harness.  
  标签：plugin / registry / version-locked / 工具与连接
- [dsh-sound-lab](https://github.com/miiaowuwu/dsh-sound-lab) — 语音控制插件（安洁莉娜「hirari do～」）  
  标签：sound / hirari / 工具与连接
- [dsh-save-money](https://github.com/zhu168/dsh-save-money) — Save-money plugin for DSH (DeepSeek Harness) — define your own 'pause / resume' time windows; at pause time running long tasks are paused (not stopped) automatically, and they resume when the window ends.  
  标签：save / Save-money / define / 工具与连接
- [dsh-multi-folder-workspace](https://github.com/Boy-Grid/dsh-multi-folder-workspace) — Multi-folder workspaces for DeepSeek Harness: one workspace spanning several folders, with sessions able to read and write every member. Core patch set + plugin + a one-command npx launcher.  
  标签：multi / Multi-folder / workspaces / 工具与连接
- [dsh-ears](https://github.com/WizisCool/dsh-ears) — A voice-input plugin for DeepSeek Harness that supports multiple ASR backends and polishing through dsh's own LLM route.  
  标签：ears / voice-input / that / 工具与连接
- [dshhub-market](https://github.com/dshhub-co/dshhub-market) — DeepSeek Harness 口令插件市场客户端：输码解锁插件，连接创作者与买家（DSHHub.co 驱动）  
  标签：hub / DSHHub / 工具与连接
- [dsh-1clickreport](https://github.com/1clickreport/dsh-1clickreport) — Connect your marketing data (Google Ads, Meta, GA4, Search Console, Shopify, Stripe) to DeepSeek Harness via MCP  
  标签：1clickreport / Connect / marketing / 工具与连接
- [dsh-uni-editor](https://github.com/creativedswork/dsh-uni-editor) — All Editors, one DSH Editor. Unified Editor runtime for DeepSeek Harness, powered by MCP Apps.  
  标签：uni / All / Editors / 工具与连接
- [dsh-balance-plugin](https://github.com/yxxbc/dsh-balance-plugin) — deepSeek 余额监控与用量统计（DSH 动态 Cordis 插件）：余额监控 · 官方充值入口 · 用量统计 · 三方插件管理  
  标签：balance / deepSeek / 工具与连接
- [dsh-vibe](https://github.com/lhf6623/dsh-vibe) — DeepSeek Harness 输入氛围插件：为输入过程增添氛围。  
  标签：vibe / 工具与连接
- [trajectory-clean](https://github.com/gaogx96/trajectory-clean) — Clean trajectory view plugin for DeepSeek Harness（DeepSeek Harness 的清洁轨迹视图插件）  
  标签：trajectory / Clean / view / 工具与连接
- [dsh-remote](https://github.com/SCSpotato/dsh-remote) — Native Android client to remotely control DeepSeek Harness (DSH) from your phone  
  标签：remote / Native / Android / 工具与连接
- [dsh-session-kit](https://github.com/ltxlong/dsh-session-kit) — A DeepSeek Harness plugin that adds practical session utilities without patching DSH core code. 一个 DeepSeek Harness 插件，用于增强会话页的日常管理能力。它不修改 DSH 核心源码，而是通过官方扩展点为会话增加管理菜单、归档会话管理、轮次级删除/重新生成，以及右侧话题快捷导航。  
  标签：session / that / adds / 工具与连接
- [dsh-grok-auth](https://github.com/Gyanano/dsh-grok-auth) — DeepSeek Harness plugin that reuses the official Grok CLI login (SuperGrok / X Premium OAuth) for an xai LLM route  
  标签：grok / that / reuses / 工具与连接
- [dsh-auto-preset-router](https://github.com/yhfgyyf/dsh-auto-preset-router) — Routes the first DSH prompt to Standard, PTC, Minimal, or Cordis with DeepSeek V4 Flash.  
  标签：auto / Routes / first / 工具与连接
- [dsh-assistant-optimization](https://github.com/qianshe/dsh-assistant-optimization) — DSH plugin: fold mis-rendered thinking/reasoning content into collapsible blocks and render mermaid diagrams inline.  
  标签：assistant / fold / mis-rendered / 工具与连接
- [dsh-bio-genie](https://github.com/moonbowterfly/dsh-bio-genie) — 🧬 dsh bio analysis plugin for DeepSeek Harness — wish-style bioinformatics & biology analysis: Biopython-powered sequence analysis, genomics, zero-install Python env (uv+venv)  
  标签：bio / dsh / analysis / 工具与连接
- [DeepSeek_Harness_Balance_Banner](https://github.com/iskshadow195563/DeepSeek_Harness_Balance_Banner) — 💵 DeepSeek 余额横幅(dsh 插件):页面顶部右侧(主题切换按钮左侧)同时显示 USD/CNY 余额,负值高亮,60s 自动刷新,一条命令安装  
  标签：DeepSeek / dsh / USD / 工具与连接
- [dsh-plugin-install](https://github.com/qinyre/dsh-plugin-install) — 给 dsh 设置页加「安装」标签页，按包名安装任意第三方插件。  
  标签：plugin / dsh / 工具与连接
- [dsh-zai-coding-models](https://github.com/auuduu/dsh-zai-coding-models) — DeepSeek Harness bridge plugin: newest Zhipu/Z.AI coding-plan models (glm-5.3) on zai-coding-cn before the bundled pi-ai catalog catches up  
  标签：zai / bridge / newest / 工具与连接
- [dsh-usage-monitor](https://github.com/NOirBRight/dsh-usage-monitor) — Session-log usage dashboard for DeepSeek Harness  
  标签：usage / Session-log / dashboard / 工具与连接
- [dsh-llm-codex](https://github.com/NOirBRight/dsh-llm-codex) — ChatGPT Codex login, sortable catalog, and Fast models for DeepSeek Harness  
  标签：llm / ChatGPT / Codex / 工具与连接
- [dsh-llm-cursor](https://github.com/NOirBRight/dsh-llm-cursor) — Cursor subscription login and chat for DeepSeek Harness  
  标签：llm / Cursor / subscription / 工具与连接
- [dsh-interview-forge](https://github.com/Co-Kyo/dsh-interview-forge) — interview-forge-plugin for deepseek harness  
  标签：interview / interview-forge-plugin / deepseek / 工具与连接
- [dsh-plugin-capabilities](https://github.com/qinyre/dsh-plugin-capabilities) — 在 dsh 设置页管理技能与 MCP 服务器，支持从 Claude Code、Codex 导入。  
  标签：plugin / dsh / MCP / 工具与连接
- [dsh-grafana](https://github.com/guhanfei-ai/dsh-grafana) — 让DSH帮你丰富对物理世界的可观测  
  标签：grafana / 工具与连接
- [dsh-cross-session-bridge](https://github.com/red000000/dsh-cross-session-bridge) — 适用于deepseek harness的根会话桥插件，可令根会话间双向通信  
  标签：cross / deepseek / harness / 工具与连接
- [dsh-standard-toolkit](https://github.com/suanniniu/dsh-standard-toolkit) — DeepSeek Harness 标准工具插件(Standard ToolKit):工具管家——平时工具不占位,会话按需自动装载/用完自动收纳,省token;支持 load_tool / register_new_tool 现场造工具。Tool manager plugin for DeepSeek Harness / dsh.  
  标签：standard / ToolKit / token / 工具与连接
- [dsh-bloub-mood](https://github.com/Yuuhann1999/dsh-bloub-mood) — 动态心情图标 · DeepSeek Harness 插件 — bloub 表情随会话状态切换 favicon 与 logo，形状/颜色/文字可配置（8 shapes × 12 colors, animated SVG, MIT）  
  标签：bloub / favicon / logo / 工具与连接
- [dsh-quant](https://github.com/pengpengyi92/dsh-quant) — '🐳 Dsh-Quant: The Everything-Plugin Ai native Quant OS '  
  标签：quant / Dsh-Quant / The / 工具与连接
- [dsh-ark-plan](https://github.com/snow-The/dsh-ark-plan) — Correctly activate DeepSeek v4 flash on the Volcano Ark plan API for DeepSeek Harness: default config injection (reasoningEfforts + effort=max) + ark_plan_doctor self-check  
  标签：ark / Correctly / activate / 工具与连接
- [dsh-dynamic-background](https://github.com/njuptlzf/dsh-dynamic-background) — DeepSeek Harness (DSH) 动态背景切换插件：上传 GIF/静态图与内置 12 色纯色调色板，定时丝滑交叉淡入淡出切换页面背景，聊天区自动叠加主题色保护层。安装：dsh plugin add github:njuptlzf/dsh-dynamic-background  
  标签：dynamic / GIF / dsh / 工具与连接
- [dsh-bluebubbles](https://github.com/vINyLogY/dsh-bluebubbles) — Who needs openclaw?  
  标签：bluebubbles / Who / needs / 工具与连接
- [dsh-interview](https://github.com/codingayice/dsh-interview) — 面向开发岗位的 DSH 面试训练插件，支持八股复习、模拟面试、场景题、力扣 Hot 100 和可视化练习管理。  
  标签：interview / Hot / 工具与连接
- [dsh-meow-cachebilling](https://github.com/Phant0Meow/dsh-meow-cachebilling) — 喵账单：DSH 缓存账单插件——本轮请求的缓存命中/未命中/输出实时计费读数，峰谷自动计价。Cache billing readout for DeepSeek Harness: per-round cache-hit / miss / output costs with peak & off-peak pricing.  
  标签：meow / Cache / billing / 工具与连接
- [dsh-flowglass](https://github.com/Iwctwbh/dsh-flowglass) — 流镜 Flowglass — DeepSeek Harness session flowgraph，实时可视化消息、工具组、子代理分支与步骤详情。  
  标签：flowglass / session / flowgraph / 工具与连接
- [dsh-damage-pulse](https://github.com/wssfk12138/dsh-damage-pulse) — DeepSeek Harness Token 余额监控插件：鲸鱼娘待机/扣费/复苏动画、峰谷计费、连续扣费飘字与会话费用统计。  
  标签：damage / Token / 工具与连接
- [dsh-at-file](https://github.com/FSMargoo/dsh-at-file) — Codex-style @file mentions for DeepSeek Harness: search workspace files in the composer and attach their path to prompts.  
  标签：at / Codex-style / file / 工具与连接
- [zhihu-search](https://github.com/klarkxy/zhihu-search) — DeepSeek Harness plugin, Skill, CLI and MCP for Zhihu search, Zhida ask, and official open-platform APIs  
  标签：zhihu / Skill / CLI / 工具与连接
- [dsh-fish-tts](https://github.com/MaRi23333/dsh-fish-tts) — Fish Audio TTS plugin for DeepSeek Harness — per-reply read-aloud, auto-read toggle, BYOK, third-party. 语音合成插件：逐条朗读、自动朗读；仅支持 Fish Audio API，需自备 Key；第三方非官方。  
  标签：fish / Audio / TTS / 工具与连接
- [dsh-test-drive](https://github.com/PerryLink/dsh-test-drive) — Isolated install-and-smoke test drives for DeepSeek Harness plugins: installs a repo or npm package into a throwaway DSH_HOME profile, verifies the bundle patch layer and boot logs, records a structured pass/fail result matrix (JSON/Markdown) for scoring pipelines, and quarantines every temp directory it owns  
  标签：test / Isolated / install-and-smoke / 工具与连接
- [DshVibeLearning](https://github.com/EarzuChan/DshVibeLearning) — A Vibe Learning Plugin made for DeepSeek Harness  
  标签：VibeLearning / Vibe / Learning / 工具与连接
- [dsh-whale-status](https://github.com/qinyuehuan/dsh-whale-status) — 把鲸鱼娘思考时的 deep diving 状态文案换成任意多句随机播放，蓝青水流动画，颜色/流速可自定义（DeepSeek Harness plugin）  
  标签：whale / deep / diving / 工具与连接
- [dsh-translate](https://github.com/PerryLink/dsh-translate) — Vendor parameter translation and deterministic JSON repair for DeepSeek Harness: /translate maps temperature/top_p/max_tokens/stop/system across 11 vendors, and the post-execute repair layer (plus fix_json) fixes broken JSON tool output without ever fabricating data  
  标签：translate / Vendor / parameter / 工具与连接
- [dshsearch-multi](https://github.com/abcdream-Lary/dshsearch-multi) — DeepSeek Harness (DSH) 的多提供商网页搜索和页面获取插件：AnySearch、Bing、DuckDuckGo、Tavily、Exa  
  标签：search / AnySearch / Bing / 工具与连接
- [DSH-Balance-display](https://github.com/yoiizesdev-crypto/DSH-Balance-display) — DSH plugins  
  标签：Balance / plugins / 工具与连接
- [dsh-mnemon-gc](https://github.com/Zn-Dk/dsh-mnemon-gc) — 接入 dsh-mnemon GC 治理插件：冲突驱动的正确性纠错，自动巡检报告。  
  标签：mnemon / dsh-mnemon / 工具与连接
- [dsh-observe](https://github.com/PerryLink/dsh-observe) — OpenTelemetry and Langfuse observability exporter for DeepSeek Harness: turn/step/tool/LLM spans, token and cost metrics, sanitized prompt/completion capture, async batching, bounded offline buffering, retry with backoff  
  标签：observe / OpenTelemetry / Langfuse / 工具与连接
- [dsh-session-sync](https://github.com/PerryLink/dsh-session-sync) — Cross-device DeepSeek Harness session sync: a dedicated git mirror with append-only keep-both conflict resolution (fork files, never silently overwritten), /sync command and sync_* tools  
  标签：session / Cross-device / sync / 工具与连接
- [dsh-workspace-env](https://github.com/Momojie-S/dsh-workspace-env) — DSH plugin: per-workspace .env injection for shell subprocesses  
  标签：workspace / per-workspace / env / 工具与连接
- [deepseek-harness-101](https://github.com/Momojie-S/deepseek-harness-101) — DeepSeek Harness 插件开发集 (submodule 索引)  
  标签：deepseek / submodule / 工具与连接
- [dsh-obsidian](https://github.com/wozoulesky/dsh-obsidian) — DSH（DeepSeek Harness）嵌入 Obsidian 的 AI 协作者插件：聊天侧边栏、内联编辑、@提及与计划模式（连接本地 http://127.0.0.1:3080）  
  标签：obsidian / http / 工具与连接
- [pi2dsh](https://github.com/weijiafu14/pi2dsh) — Bridge the Pi and DeepSeek Harness ecosystems: one Pi Host ABI runs unmodified Pi extensions as native DSH plugins. 打通 Pi 与 DSH 生态。  
  标签：Bridge / ecosystems / 工具与连接
- [dsh-univer-office](https://github.com/dream-num/dsh-univer-office) — Preview, create, edit office spreadsheets, docs & slides inside DeepSeek Harness. Power by Univer.  
  标签：office / office-harness
- [dsh-better-edit](https://github.com/Rianico/dsh-better-edit) — Hash-anchored read/edit/undo_last_edit tools for DeepSeek Harness (dsh), fewer token consumption, lower cost.  
  标签：edit / hashline / hashline-edit / oh-my-pi
- [awesome-dsh-plugin](https://github.com/billLiao/awesome-dsh-plugin) — A curated list of plugins for DeepSeek Harness (dsh) — 精选 DeepSeek Harness 插件列表  
  标签：awesome / awesome-list / curated-list / deepseek
- [dsh-novel-writer](https://github.com/siweina/dsh-novel-writer) — DSH / DeepSeek Harness 小说写作助手插件：章节库管理、句式模式分析（九类句式/情感曲线/风格指纹）、风格自检、伏笔登记、批量导入、续写辅助。Novel writing assistant plugin for DeepSeek Harness: chapter library, sentence pattern analysis, style check, plot tracking, batch import, AI-assisted novel writing. dsh-plugin novel-writing ai-writing  
  标签：ai-writing / chinese-novel / cordis / creative-writing
- [dsh-doctor](https://github.com/astra3294/dsh-doctor) — Deterministic diagnostics and recovery for DeepSeek Harness  
  标签：deepseek / diagnostics / dsh-plugins / recovery
- [deepseek-harness-plugins](https://github.com/writeCasually/deepseek-harness-plugins) — deepseek harness plugins view  
  标签：工具与连接
- [DSH-Launcher](https://github.com/tttnny/DSH-Launcher) — DSH Launcher — macOS menu bar app that manages the DeepSeek Harness web service via launchd  
  标签：工具与连接
- [dsh-plugin-rollout-scout](https://github.com/SpookySandwich/dsh-plugin-rollout-scout) — DSH 刷灰测模型插件。DeepSeek Harness plugin: fish for a limited-rollout conversation model by scoring live chain-of-thought.  
  标签：ab-test / cordis-plugin / deepseek / llm
- [dsh-rules-manager](https://github.com/jilian-dsh/dsh-rules-manager) — Rules & commands manager for DeepSeek Harness: /rules command + settings panel + custom commands  
  标签：工具与连接
- [dsh-web-remote-access](https://github.com/studyzy/dsh-web-remote-access) — 让DSH能够支持远程访问Web的插件，可指定WebToken进行认证  
  标签：工具与连接
- [dsh-plugins](https://github.com/kazecreator/dsh-plugins) — Monorepo of DeepSeek Harness (dsh) plugins — including dsh-im (Telegram & WeChat IM bridge)  
  标签：telegram / wechat
- [dsh-lcx-codex](https://github.com/kk3ya03-star/dsh-lcx-codex) — DSH web search and native Responses V2 compaction for Sub2API or NewAPI GPT routes  
  标签：newapi / openai-responses / sub2api / web-search
- [dsh-web-search-ext](https://github.com/fno2010/dsh-web-search-ext) — Multi-backend web_search provider for DeepSeek Harness (DSH): Exa + Firecrawl with automatic failover, key-free capable  
  标签：工具与连接
- [dsh-audio-copilot](https://github.com/ai-yucheng/dsh-audio-copilot) — Audio Copilot for DeepSeek Harness — transcribe audio (ASR) , with an in-composer voice-input mic button. 🎤  
  标签：asr / audio / faster-whisper / gemini
- [dsh-plugins-plus](https://github.com/SparkElf/dsh-plugins-plus) — SparkElf-maintained independent plugins for DeepSeek Harness (dsh), installable on upstream dsh via profile composition bundles.  
  标签：工具与连接
- [luxueliu-usage-command](https://github.com/luxueliu/luxueliu-usage-command) — 内置DSH指令，一键展示今日全局付费模型总消耗账单（人民币版）！按模型×分小时查当日¥消费，缓存命中/未命中/输出三档单价，官方/中转/套餐全覆盖 — DeepSeek Harness 插件  
  标签：cost / litellm / luxueliu / token-usage
- [dsh-cc-studio](https://github.com/xia-sc/dsh-cc-studio) — dsh-cc-studio · CCv3 角色卡工坊 从一句话点子到可导入 SillyTavern / Risu 的 chara_card_v3。专治「只有点子，世界观薄弱」。  
  标签：dsh-plugins
- [dsh-habit](https://github.com/Max-Null/dsh-habit) — Self-learning habit engine for the DeepSeek Harness - correction signals, threshold judgment, two-level human gate  
  标签：工具与连接
- [dsh-all-search](https://github.com/RealAlexandreAI/dsh-all-search) — dsh search: AnySearch web search provider for DeepSeek Harness (ctx.web)  
  标签：工具与连接
- [dsh-git-conventions](https://github.com/CN-WenYu/dsh-git-conventions) — Configurable Git commit and pull-request conventions for DeepSeek Harness — enforce user-defined rules on commit messages and PR titles/descriptions. ｜ DeepSeek Harness 的可配置 Git 提交与拉取请求规范插件，按用户自定义规则校验提交信息与 PR 标题/描述。  
  标签：工具与连接
- [dsh-updater-npm](https://github.com/SiriusWJ/dsh-updater-npm) — DSH updater + official docs sync plugin: one-click npm update with live progress, incremental docs sync with progress, dsh_docs_search/read tools. DSH 更新器+官方文档同步器（进度显示）。  
  标签：updater
- [dsh-session-manager](https://github.com/EIGHTfs/dsh-session-manager) — DSH 会话功能增强插件（重命名/分支/归档）  
  标签：工具与连接
- [dsh-git-push](https://github.com/EIGHTfs/dsh-git-push) — DSH git 自动提交推送插件：扫描仓库 + 一键 commit/push（工具 + HTTP API）  
  标签：工具与连接
- [dsh-skillopt](https://github.com/WODE25500/dsh-skillopt) — Microsoft SkillOpt-Sleep integration for DeepSeek Harness (dsh): nightly sleep cycle - harvest sessions, replay recurring tasks, consolidate validated skills behind a held-out gate. ?? DSH ? SkillOpt ??  
  标签：cordis / plugin / self-improvement / skillopt
- [dsh-plugin-mcp](https://github.com/menotbobbybrown/dsh-plugin-mcp) — Universal Model Context Protocol (MCP) Bridge Plugin for DeepSeek Harness (dsh) — Everything is a Plugin  
  标签：mcp / model-context-protocol
- [dsh-manage](https://github.com/elmaxid/dsh-manage) — Instalacion y administracion de DeepSeek Harness (dsh): install/start/stop/update/status para puestos dev  
  标签：工具与连接
- [dsh-browser-plus](https://github.com/ParticleLight/dsh-browser-plus) — Enhanced shared browser for DeepSeek Harness: visible + AI-driven WebContentsView, ego-style page chrome, operation trail, JS dialog auto-accept, per-task windows & spaces, Electron 42.x pinned  
  标签：工具与连接
- [dsh-plugins](https://github.com/koji-xiaoer/dsh-plugins) — DSH(DeepSeek Harness)插件仓库:增强主页、模型选择器增强、费用预估等插件与一键安装脚本  
  标签：工具与连接
- [dsh-webview-wrapper](https://github.com/no1xsyzy/dsh-webview-wrapper) — 贯彻 "一切皆插件" 的 DeepSeek Harness webview 封装。 A DeepSeek Harness webview wrapper in the everything-is-a-plugin spirit.  
  标签：工具与连接
- [dsh-global-proxy](https://github.com/TTsdzb/dsh-global-proxy) — 更好的代理支持。  
  标签：工具与连接
- [dsh-a-share-screener](https://github.com/Gaines-cz/dsh-a-share-screener) — A-share stock screening plugin for DeepSeek Harness (dsh): pluggable strategies, Tushare token via credentials ref, free Eastmoney/Tencent fallback.  
  标签：a-share / stock-screener / tushare
- [luxueliu-reasoning-efforts](https://github.com/luxueliu/luxueliu-reasoning-efforts) — DSH里只有ds能选推理强度？20个常用模型推理强度按钮已就位！涵盖grok/Gemini / Kimi/glm……20个模型仅预设，实际槽位无上限！可以任意添加你的本地网关模型！（非 ds 系网关模型推理强度档位插件 + 路由级 llm-pi-ai 补丁）  
  标签：gateway / litellm / llm / luxueliu
- [deepseek-harness-plugin-list](https://github.com/chenshutian9610/deepseek-harness-plugin-list) — 个人 deepseek-harness 插件集合  
  标签：工具与连接
- [dsh-win-multi-bash](https://github.com/Dinosaur-MC/dsh-win-multi-bash) — Multi-bash plugin for dsh. Add Git Bash / WSL Bash support for Windows.  
  标签：bash / shell / windows / wsl
- [dsh-cordis-mcp](https://github.com/GeekRicardo/dsh-cordis-mcp) — DeepSeek Harness 插件：把 DSH 的动态 Cordis 工具集（inspect/define/run/stop/undefine）以 MCP 暴露给 Claude Code。端点强制身份认证，token 可在 DSH 设置页配置。  
  标签：claude-code / cordis / mcp / model-context-protocol
- [dsh-weneedfirst](https://github.com/XiaoWind/dsh-weneedfirst) — DeepSeek Harness plugin: make the chain of thought open with We need instead of Let me  
  标签：工具与连接
- [dsh-my-go](https://github.com/daizihan233/dsh-my-go) — My tasks, where to GO?????  
  标签：工具与连接
- [dsh-jmcomic](https://github.com/lywusichen/dsh-jmcomic) — DeepSeek Harness 插件:JMComic 搜索下载、本地漫画库、窗内阅读器,内置源码离线可用。  
  标签：comics / deepseek / deepseek-v4 / javascript
- [dsh-qqbot](https://github.com/belowthetree/dsh-qqbot) — qqbot 连接QQ机器人插件，方便易用，安装快捷  
  标签：ai / deepseek
- [dsh-openai-server-compaction](https://github.com/ylxmf2005/dsh-openai-server-compaction) — OpenAI Responses adapter with durable server-side compaction for DeepSeek Harness.  
  标签：compaction / openai / responses-api
- [dsh-paseo](https://github.com/renat3u/dsh-paseo) — 把 dsh 作为 Paseo 的 ACP provider。  
  标签：桥接
- [dsh-plugin-claude-bridge](https://github.com/YYTbit/dsh-plugin-claude-bridge) — 把 Claude Code 的记忆、技能与配置桥接进 DeepSeek Harness，无缝迁移工作流。  
  标签：桥接 / Claude Code
- [dsh-webbridge](https://github.com/bill9109/dsh-webbridge) — 把 Kimi WebBridge 的本地守护进程桥接成模型工具，网页能力接入 Agent。  
  标签：桥接 / Kimi
- [dsh-http-client](https://github.com/vlln/dsh-http-client) — 内置 HTTP 客户端工具，Agent 可直接调用 REST API、调试接口。  
  标签：HTTP / API
- [dsh-file-search](https://github.com/vlln/dsh-file-search) — 工作区全文模糊检索，支持 glob 与 ripgrep 语法，秒定位代码。  
  标签：搜索 / 文件
- [dsh-env-manager](https://github.com/vlln/dsh-env-manager) — 环境变量与密钥管理，敏感信息脱敏，Agent 安全读取凭据。  
  标签：环境变量 / 密钥
- [dsh-docker](https://github.com/vlln/dsh-docker) — Docker 容器管理工具，Agent 可构建、运行、编排容器环境。  
  标签：Docker / 容器
- [dsh-cron](https://github.com/vlln/dsh-cron) — 类 cron 定时调度，配置周期性任务交给 Agent 自动执行。  
  标签：定时 / 调度
- [dsh-slack](https://github.com/vlln/dsh-slack) — Slack 集成桥接，Agent 消息直达频道，团队协作无缝衔接。  
  标签：IM / Slack
- [dsh-notion](https://github.com/vlln/dsh-notion) — Notion 集成：Agent 读写数据库与页面，知识库自动同步。  
  标签：Notion / 知识库
- [dsh-jira](https://github.com/vlln/dsh-jira) — Jira 工单集成，Agent 读取/创建/更新 Issue，研发流程自动化。  
  标签：Jira / 工单
- [dsh-office](https://github.com/Fayelin12/dsh-office) — 读写 docx/pdf/pptx 办公文档，让 Agent 处理 Office 三件套。  
  标签：Office / 文档
- [dsh-chat-import](https://github.com/Nwflower/dsh-chat-import) — 把 Claude Code/Codex/ChatGPT/Cursor/Gemini 聊天记录保真导入为可续聊会话。  
  标签：迁移 / 导入
- [dsh-movein](https://github.com/sjh9714/dsh-movein) — 把整个 Claude Code 设置迁移到 DSH：Session、Memory、Skills 全带走。  
  标签：迁移 / Claude Code
- [dsh-file-uploads](https://github.com/l541402398/dsh-file-uploads) — 从输入框上传任意本地文件，以待发送卡片展示。  
  标签：上传 / 文件
- [dsh-bash-rtk](https://github.com/DeepTrial/dsh-bash-rtk) — Bash 运行时工具包：命令执行、输出捕获与重试。  
  标签：Bash / 执行
- [dsh-tool-github](https://github.com/NEAZ71eve/dsh-tool-github) — GitHub 工具：让 Agent 在对话里查仓库、读 Issue、管 PR。  
  标签：GitHub / 工具
- [dsh-mcp-panel](https://github.com/PerryLink/dsh-mcp-panel) — MCP 面板：可视化配置与监控 MCP 服务器连接。  
  标签：MCP / 面板
- [dsh-web-search-pro](https://github.com/anweat/dsh-web-search-pro) — 专业网络搜索：多引擎聚合、结果去重与结构化摘要。  
  标签：搜索 / 聚合
- [dsh-web-search-exa](https://github.com/TonyDua/dsh-web-search-exa) — Exa 语义搜索接入：按语义找网页，而非关键词。  
  标签：搜索 / 语义
- [dsh-tavily](https://github.com/moguiyu/dsh-tavily) — Tavily 搜索 API 接入，为 Agent 提供实时检索能力。  
  标签：搜索 / API
- [dsh-mcp-manager](https://github.com/hyqhyq3/dsh-mcp-manager) — MCP 服务器管理：集中配置、启停与监控 MCP 连接。  
  标签：MCP / 管理
- [dsh-mcp-lens](https://github.com/labmimors/dsh-mcp-lens) — MCP 透镜：可视化查看 MCP 工具调用与数据流。  
  标签：MCP / 可视化
- [dsh-harness-mcp-server](https://github.com/chushixixin/dsh-harness-mcp-server) — 把 DSH 暴露为 MCP 服务器，供其他 Agent 调用。  
  标签：MCP / 服务器
- [treg](https://github.com/superdesigndev/treg) — 给 Agent 的工具目录：按「要做的事」检索约 2600 个外部接口。  
  标签：目录 / 检索
- [mirage](https://github.com/strukto-ai/mirage) — 把文件系统与 bash 换成 mirage 虚拟工作区（RAM/S3/Redis/Slack/Gmail/Notion）。  
  标签：虚拟工作区 / 沙箱
- [dsh-xiaohongshu-viral-note](https://github.com/xuboboo/dsh-xiaohongshu-viral-note) — 小红书爆款笔记生成器，一句话产出爆款文案。  
  标签：小红书 / 文案
- [dsh-lark-bot](https://github.com/PlutoKeating/dsh-lark-bot) — 飞书（Lark）机器人：在飞书里 @Agent 干活，群聊单聊都支持。  
  标签：飞书 / 机器人
- [DSH-WX-Msg-Tool](https://github.com/yauntyour/DSH-WX-Msg-Tool) — 微信消息工具：让 DSH 收发微信消息，IM 里直接调 Agent。  
  标签：微信 / 消息
- [super-wechat-bridge](https://github.com/Qshuai0213/super-wechat-bridge) — 微信桥接：把微信个人号接进 DSH，收发消息与文件。  
  标签：微信 / 桥接
- [dsh-qqbot](https://github.com/tencent-connect/dsh-qqbot) — QQ 机器人（腾讯官方）：单聊/群聊独立会话，扫码绑定即可用。  
  标签：QQ / 机器人
- [dsh-free-search](https://github.com/DDDMUC/dsh-free-search) — 免费联网搜索 provider：DuckDuckGo 后端，无需 API key。  
  标签：搜索 / 免费
- [dsh-tavily-search](https://github.com/zhouzhencheng07/dsh-tavily-search) — 免 key 的 Tavily 联网搜索工具。  
  标签：搜索 / Tavily
- [dsh-lark-link](https://github.com/amlyczz/dsh-lark-link) — 高可靠飞书/Lark 桥接：二维码一键授权、多模式 agent、卡片命令、零丢失发件箱。  
  标签：飞书 / 桥接
- [dsh-gpt-bridge](https://github.com/sl82976818/dsh-gpt-bridge) — DSH 与 Custom GPT 之间的只读工程证据桥。  
  标签：桥接 / GPT
- [dsh-codex-subscription](https://github.com/WSL043/dsh-codex-subscription) — 在 DSH 中使用 ChatGPT/Codex 订阅：OAuth 登录、额度与重置时间。  
  标签：Codex / 订阅
- [dsh-rollback](https://github.com/Taler97/dsh-rollback) — 文件变更回滚插件，误改可撤销。  
  标签：回滚 / 撤销
- [dsh-units](https://github.com/TYEclipse/dsh-units) — 单位换算工具箱：长度/质量/温度/数据量/速度/时间等，零运行时依赖。  
  标签：换算 / 工具
- [jacobian](https://github.com/morluto/jacobian) — 面向 agent 的纯数学：搜反例、精确计算、独立验证证明结论。  
  标签：数学 / 定理
- [dsh-usage-cost-dashboard](https://github.com/NeverToEver/dsh-usage-cost-dashboard) — LLM 用量与成本分析 Web 面板，token 计量可视化。  
  标签：成本 / 面板
- [dsh-browser](https://github.com/wqty123/dsh-browser) — 共享真实浏览器插件，让 DSH 用真实浏览器干活。  
  标签：浏览器 / 工具
- [dsh-web-restart](https://github.com/jifeng15/dsh-web-restart) — 真·热装载：装插件/改配置/升级后自动安全重启，无需手动命令行重启。  
  标签：热重启 / 运维
- [dsh-update-checker](https://github.com/Airmetro/dsh-update-checker) — 自动检查 npm 最新版，GUI 顶部横幅提示，一键安装更新并重启服务。  
  标签：更新 / 检测
- [dsh-tool-writing](https://github.com/x2802490130-prog/dsh-tool-writing) — 长篇网文写作引擎：独立 DeepSeek key、世界观管理、语义检索与语料库。  
  标签：写作 / 网文
- [dsh-llm-cost](https://github.com/chenyinrusi/dsh-llm-cost) — 每轮/每步 LLM 成本计量：costUsage 预测、逐条成本、LLM+网页价格自动维护。  
  标签：成本 / 计量
- [dsh-config-manager](https://github.com/xiajiajun516/dsh-config-manager) — 配置备份/导出/导入/迁移：双面 Cordis 插件（宿主引擎 + Web UI），任意机器一键恢复。  
  标签：配置 / 迁移
- [dsh-fovea](https://github.com/monotykamary/dsh-fovea) — 注视点式仓库情报：token 预算代码图，聚焦/影响/持续同步。  
  标签：代码图 / 情报
- [dsh-codebuddy-auth](https://github.com/cainiao1992/dsh-codebuddy-auth) — CodeBuddy（腾讯 IOA）提供商插件：OAuth 登录、令牌刷新、模型同步。  
  标签：提供商 / 登录
- [dsh-computer-use-windows](https://github.com/nanbbb/dsh-computer-use-windows) — Windows 电脑控制工具：自包含 UIA 原生助手、遮挡感知截图、安全门控输入。  
  标签：电脑控制 / Windows
- [dsh-gateway-billing](https://github.com/LeslieWylie/dsh-gateway-billing) — Web 编辑器每会话 LLM 计费显示，适配自托管 New API / One API 兼容网关。  
  标签：计费 / 网关
- [dsh-file-picker](https://github.com/JackeyWilder/dsh-file-picker) — DSH Web 插件：原生 Windows 文件选择器，向草稿注入 @path 引用。  
  标签：文件 / 选择器
- [leantoken](https://github.com/morluto/leantoken) — 面向 Agent 的代码情报：找出关键代码，保持上下文窗口与 token 精简（Rust/MCP）。  
  标签：代码情报 / token
- [dsh-finance](https://github.com/TYEclipse/dsh-finance) — 金融数学工具箱：贷款分期摊销、复利增长、利率换算，零运行时依赖。  
  标签：金融 / 计算
- [dsh-model-switch](https://github.com/lincong1987/dsh-model-switch) — DSH 插件：为子代理与计划执行灵活切换更合适的模型。  
  标签：模型 / 切换
- [dsh-yzj](https://github.com/GuoxinShan/dsh-yzj) — 云之家（Yunzhijia）插件包：yzj-cli 桥接、41 个面向模型的工具、悬浮工作区面板。  
  标签：集成 / 云之家
- [dsh-session-search-pro](https://github.com/LeslieWylie/dsh-session-search-pro) — 高级跨会话全文搜索：用内置 sessionQuery 服务检索过往与当前 DSH 会话。  
  标签：搜索 / 会话
- [everyconnect](https://github.com/baiyingawa/everyconnect) — 将 DSH 连接至微信/QQ 等软件，通过微 claw 插件、QQ 机器人等方式实现。  
  标签：IM / 桥接
- [dsh-gh-plugin](https://github.com/king-bcolor/dsh-gh-plugin) — 封装 GitHub CLI（gh）的 DeepSeek Harness 插件。  
  标签：GitHub / CLI
- [dsh-opencode-zen](https://github.com/xiaozhe7772222/dsh-opencode-zen) — 0 元接入 6 个免费大模型：OpenCode Zen 免费档零配置接入 DSH，多 Key 轮换与限流退避。  
  标签：免费模型 / 提供商
- [dsh-file-fix](https://github.com/re-ITRT/dsh-file-fix) — 统一文件导入：字节级上传存储、文件列表上下文注入、read/place_attachment 工具、历史文件气泡。  
  标签：文件 / 导入
- [dsh-plugin-usage](https://github.com/GHJIVHIDD/dsh-plugin-usage) — 用量部署级插件：会话视图新增「用量」页签，实时跟踪输入/输出/缓存命中 tokens 与费用，动态渐变状态条、自定义价格表、CSV/JSON 导出。  
  标签：用量 / 计费
- [dsh-lark](https://github.com/sugarforever/dsh-lark) — DeepSeek Harness 飞书（Lark）集成插件，把 DSH 接入企业 IM。  
  标签：飞书 / Lark / IM
- [dsh-web-search-brave](https://github.com/gravitylow/dsh-web-search-brave) — DeepSeek Harness 的 Brave 网页搜索插件。  
  标签：搜索 / Brave / Web
- [dsh-tool-web-enhanced](https://github.com/edusrez/dsh-tool-web-enhanced) — DSH 原生 dsh-tool-web 的增强替换：新增可选 topic 参数与第二个 SearXNG 后端。  
  标签：Web / SearXNG / 增强
- [dsh-model-probe](https://github.com/AGSQ11/dsh-model-probe) — DSH Web UI 的持久模型健康监测插件。  
  标签：模型 / 监测 / 健康检查
- [dsh-remote](https://github.com/Hyna-hla/dsh-remote) — DSH Remote 手机遥控端：把电脑上的 DSH 装进口袋，支持局域网/内网穿透、扫码连接、审批通知与多主题换装。  
  标签：手机 / 遥控 / 远程
- [dsh-tool-docx](https://github.com/BroBFG/dsh-tool-docx) — 面向模型的 MS Word（.docx）工具：docx_read / docx_create / docx_edit。  
  标签：docx / Word / 文档
- [dsh-ipcalc](https://github.com/TYEclipse/dsh-ipcalc) — DSH 的 IP 与子网计算工具箱：IPv4 子网布局、CIDR 汇总、IPv4/IPv6 解析（RFC 5952）。  
  标签：IP / 子网 / CIDR
- [dsh-coding-subscription-oauth](https://github.com/lninghaha/dsh-coding-subscription-oauth) — DSH 编程订阅 OAuth：SuperGrok / Grok Build、ChatGPT Plus Codex、Kimi Code、Claude Code，无需 API Key。  
  标签：OAuth / 订阅 / API
- [dsh-deepseek-usage](https://github.com/mmzm0808/dsh-deepseek-usage) — DeepSeek API 用量监测：悬浮球 + 展开面板，展示真实余额、累计/今日消费、请求次数、Tokens 与分模型用量。  
  标签：用量 / API / 余额
- [dsh-agent-shell](https://github.com/PastSheep/dsh-agent-shell) — Bash/cmd/shell 工具 + 命令记录 Shell 抽屉。  
  标签：Shell / 命令记录 / Bash
- [dsh-prototype](https://github.com/satan9394/dsh-prototype) — DSH 技能：原型验证，用可丢弃代码回答设计问题。  
  标签：原型 / 验证
- [dsh-codebase-design](https://github.com/satan9394/dsh-codebase-design) — DSH 技能：深模块设计，接口与接缝。  
  标签：设计 / 模块
- [dsh-api-scaffolding](https://github.com/satan9394/dsh-api-scaffolding) — DSH 技能：FastAPI 脚手架，异步与分层结构。  
  标签：FastAPI / 脚手架
- [dsh-web-scripting](https://github.com/satan9394/dsh-web-scripting) — DSH 技能：PHP/Ruby Web 开发，现代惯用法。  
  标签：Web / PHP / Ruby
- [dsh-api-documentation](https://github.com/satan9394/dsh-api-documentation) — DSH 技能：API 文档与开发者体验，OpenAPI 与门户。  
  标签：API / 文档
- [dsh-tech-debt](https://github.com/satan9394/dsh-tech-debt) — DSH 技能：技术债治理，审计与还债优先级。  
  标签：技术债 / 审计
- [dsh-functional-programming](https://github.com/satan9394/dsh-functional-programming) — DSH 技能：函数式编程，Elixir/OTP 与 Haskell 类型。  
  标签：函数式 / Elixir
- [dsh-distributed-debugging](https://github.com/satan9394/dsh-distributed-debugging) — DSH 技能：分布式排障，应急响应与根因分析。  
  标签：排障 / 分布式
- [dsh-observability-tools](https://github.com/satan9394/dsh-observability-tools) — DSH 技能：可观测性工具，Prometheus/Grafana/追踪。  
  标签：可观测性 / 监控
- [dsh-dotnet-backend](https://github.com/satan9394/dsh-dotnet-backend) — DSH 技能：.NET 后端模式，Clean Architecture 与 EF Core。  
  标签：.NET / 后端
- [dsh-kpi-dashboard-design](https://github.com/satan9394/dsh-kpi-dashboard-design) — DSH 技能：KPI 仪表盘设计，指标选型与治理。  
  标签：KPI / 仪表盘
- [dsh-bash-testing](https://github.com/satan9394/dsh-bash-testing) — DSH 技能：Shell 脚本测试，BATS 单元测试。  
  标签：Shell / 测试
- [dsh-plugin-eval](https://github.com/satan9394/dsh-plugin-eval) — DSH 技能：插件质量评估方法论，三层评估与改进。  
  标签：评估 / 质量
- [dsh-framework-migration](https://github.com/satan9394/dsh-framework-migration) — DSH 技能：框架迁移，Angular/React 与依赖升级。  
  标签：迁移 / 框架
- [dsh-reverse-engineering](https://github.com/satan9394/dsh-reverse-engineering) — DSH 技能：逆向工程，二进制分析与取证。  
  标签：逆向 / 取证
- [dsh-kubernetes-operations](https://github.com/satan9394/dsh-kubernetes-operations) — DSH 技能：Kubernetes 运维，Helm 与安全策略。  
  标签：K8s / 运维
- [dsh-data-engineering](https://github.com/satan9394/dsh-data-engineering) — DSH 技能：数据工程，Airflow/dbt/Spark。  
  标签：数据工程 / ETL
- [dsh-codebase-scanner](https://github.com/satan9394/dsh-codebase-scanner) — DSH 技能：代码库扫描，项目文档与漂移检测。  
  标签：扫描 / 漂移
- [dsh-plugins](https://github.com/iia-arg/dsh-plugins) — DeepSeek Harness 社区插件：首发一个 Harness 未自带的 Telegram 频道。  
  标签：Telegram / 社区
- [dsh-checkdigit](https://github.com/TYEclipse/dsh-checkdigit) — DeepSeek Harness 校验位数学工具箱：生成/校验 Luhn/Verhoeff/Damm/ISBN/EAN/IBAN 等。  
  标签：校验位 / 数学
- [dsh-factor-mining-plugin](https://github.com/Rtyyy233/dsh-factor-mining-plugin) — 面向 DSH 的 Agent 化因子挖掘插件，适配 qwen 等小模型，核心包可独立运行。  
  标签：因子 / 量化
- [dsh-llm-retry-infinite](https://github.com/PineappleTwilight/dsh-llm-retry-infinite) — 为 DSH 提供更好的 LLM 重试处理。  
  标签：重试 / 稳定性
- [dsh-backup](https://github.com/xiaoyuyu6420/dsh-backup) — 一键备份 DeepSeek Harness 用户数据：/backup、定时自动备份、sha256 校验与轮转。  
  标签：备份 / 运维
- [dsh-firecrawl](https://github.com/Lorodn4x/dsh-firecrawl) — 为 DeepSeek Harness ctx.web 提供 Firecrawl 网页搜索与 Markdown 抓取 provider。  
  标签：爬虫 / 搜索 / web
- [dsh-plugin-toggle](https://github.com/Zenjibad/dsh-plugin-toggle) — 在设置 → 插件页直接启用 / 停用 DSH 插件，实时起停 loader 并持久化。  
  标签：插件管理 / 设置
- [dsh-mcp-toggle](https://github.com/Zenjibad/dsh-mcp-toggle) — 在 DSH 设置页直接启用 / 停用 MCP 服务器，实时起停连接并持久化。  
  标签：MCP / 设置
- [Remote_DSH_Center](https://github.com/shendeguize/Remote_DSH_Center) — 本地 / 远程 dsh web 实例的单页管理器与 CLI，支持 SSH 隧道。  
  标签：远程 / SSH / 管理
- [dsh-netdoctor](https://github.com/TYEclipse/dsh-netdoctor) — DSH 网络诊断工具箱：DNS 查询、ICMP ping、TCP 端口、TLS 证书、traceroute、WHOIS、公网 IP，零运行时依赖。  
  标签：网络 / 诊断 / 运维
- [dsh-llm-mlx](https://github.com/robbywang25/dsh-llm-mlx) — DSH 本地 MLX-LM 模型插件：默认仅回环、可选托管服务启动。  
  标签：本地模型 / MLX / Apple
- [dsh-visual-workbench](https://github.com/Destined-at-Dawn/dsh-visual-workbench) — DSH 可视化工作台：Obsidian 式知识空间 + 本地 Comfy MCP 工作流。  
  标签：知识空间 / Comfy / 可视化
- [dsh-force-compact](https://github.com/falling-ts/dsh-force-compact) — 为本地优先 Agent 做激进上下文压缩：自托管 llama.cpp 低上下文运行 Qwen3.8-27B 收缩历史，零 API 成本。  
  标签：压缩 / 上下文 / 本地
- [dsh-remote-exec](https://github.com/moreWax/dsh-remote-exec) — DSH 的 SSH/MOSH/SAM 远程执行 provider：本地跑 Agent，远端执行命令。  
  标签：SSH / 远程执行 / 运维

<a id="cat-多模态与视觉" name="cat-多模态与视觉"></a>

### 👁️ 多模态与视觉

- [Vision Toolkit](https://github.com/Anionex/dsh-vision-toolkit) — 让纯文本模型获得视觉：视图工具桥接任意 OpenAI 兼容 VLM。  
  标签：VLM / 视觉
- [AIGC Canvas](https://github.com/HuanLinOTO/dsh-plugin-aigc-canvas) — provider 无关的图像生成 HTTP 桥 + 自由画布 + ffmpeg 后处理。  
  标签：文生图 / 画布
- [Paddle OCR](https://github.com/omdsh-dev/dsh-paddle-ocr) — 百度 PaddleOCR-VL 文档布局解析，扫描件也能结构化入库。  
  标签：OCR / 文档
- [FunASR Voice](https://github.com/omdsh-dev/dsh-voice-funasr) — 本地离线语音输入，说话即可驱动 Agent，隐私不出本机。  
  标签：语音 / 离线
- [dsh-openpencil](https://github.com/ZSeven-W/dsh-openpencil) — DSH OpenPencil：在对话中预览和编辑 OpenPencil .op 设计文档的插件。  
  标签：设计
- [dsh-vision](https://github.com/william-jin-cmu/dsh-vision) — 给纯文本 DeepSeek 加视觉：view_image 工具桥接任意 OpenAI 兼容 VLM。  
  标签：VLM
- [Qwen-MM-Plugins](https://github.com/omdsh-dev/Qwen-MM-Plugins) — Qwen-MM 多模态能力插件包。  
  标签：多模态
- [dsh-ernie-image](https://github.com/omdsh-dev/dsh-ernie-image) — 百度 ERNIE-Image-Turbo 文生图插件。  
  标签：文生图
- [dsh-cursor-theme](https://github.com/auki-zy/dsh-cursor-theme) — Per-state mouse cursor theme plugin for DeepSeek Harness (DSH). 18 original preset themes covering 14 UI states, ZIP image pack import/export, hotspot/size editing, and one-click system-level cursor apply on Windows (registry + SPI_SETCURSORS) with an experimental macOS overlay. 为 DSH 自定义鼠标各种状态的图案，覆盖 14 种 UI 状态。  
  标签：cursor / Per-state / mouse / 多模态与视觉
- [vision-exp-tile](https://github.com/Nicholas023/vision-exp-tile) — DSH 插件：大图切 800×800 无损小块 + 坐标标注 + 分块聚合逻辑，直连 deepseek-v4-flash-vision-exp 识别；仅用纯官方 DSH 功能，零依赖第三方插件，不统计 token/费用。  
  标签：vision / deepseek-v / flash-vision-exp / 多模态与视觉
- [dsh-plugin](https://github.com/wangzhanchao883/dsh-plugin) — DeepSeek Harness plugin collection: self-developed DSH plugins (screenshot capture, OCR, Obsidian). ?? DSH ??????  
  标签：plugin / collection / self-developed / 多模态与视觉
- [dsh-deepseek-vision](https://github.com/siegfly/dsh-deepseek-vision) — Vision-language gateway plugin for DeepSeek Harness - paste an image, DeepSeek sees text  
  标签：deepseek / Vision-language / gateway / 多模态与视觉
- [dsh-chat-image-lightbox](https://github.com/loyalchiiina/dsh-chat-image-lightbox) — DSH plugin: display images inline in chat with lightbox zoom, download (save-as), and prev/next navigation  
  标签：chat / display / images / 多模态与视觉
- [dsh-docs](https://github.com/protoctistmoses143/dsh-docs) — Convert PDFs, Office docs, scanned images, and more to clean Markdown, JSON, or text locally with offline OCR—no servers, no API keys, fully private.  
  标签：docs / Convert / PDFs / 多模态与视觉
- [dsh-file-upload](https://github.com/a903067276-rgb/dsh-file-upload) — One upload button plus drag-and-drop files into the conversation as local paths: save to project uploads/, path text into the input box, works with any vision tool  
  标签：file / One / upload / 多模态与视觉
- [dsh-memory-eternal](https://github.com/EternalNight996/dsh-memory-eternal) — 记忆核心（Memory Eternal）：把 boujoy-harness 记忆模块搬进任意 DeepSeek Harness 的独立插件——对话自动沉淀知识卡到本地 Markdown Vault（去重/检索/知识图谱），零人工干预  
  标签：memory / Eternal / boujoy-harness / 多模态与视觉
- [dsh-theme](https://github.com/EternalNight996/dsh-theme) — DeepSeek Harness theme skin plugin - built-in themes / static image / dynamic 360-follow video.  
  标签：theme / skin / built-in / 多模态与视觉
- [dsh-design-mode](https://github.com/KaichenCurry/dsh-design-mode) — Agentic image Design Mode for DeepSeek Harness: infinite canvas, ask_user clarification, image tools, comments, and provider routing.  
  标签：design / Agentic / image / 多模态与视觉
- [dsh-resume](https://github.com/L3n3L/dsh-resume) — AI 写简历容易，但写完总会遇到模板难看、排版溢出、页面留白、改一处全局变形等问题。dsh-resume 专注解决“内容生成后的视觉复核”：让 AI 和用户一起把简历调到真正适合投递的刚好一页。AI can write a resume, but the result often looks unbalanced, overflows the page, leaves large blank areas, or breaks after a small edit. dsh-resume focuses on visual review after generation, helping AI and users refine the resume into a polished.  
  标签：resume / dsh-resume / can / 多模态与视觉
- [dsh-plugin-bridge](https://github.com/Totoro-qaq/dsh-plugin-bridge) — DeepSeek Harness plugin for previewable cross-preset session migration. Fixed-schema handoffs preserve state, source-model intent, and unresolved images; the original session stays untouched.  
  标签：plugin / previewable / cross-preset / 多模态与视觉
- [dsh-medomni](https://github.com/bowang-lab/dsh-medomni) — deepseek harness plugin for medical image analysis  
  标签：medomni / deepseek / harness / 多模态与视觉
- [dsh-labnana](https://github.com/exoticknight/dsh-labnana) — Labnana image generation for DeepSeek Harness: text-to-image / image-to-image / precise editing — chat image cards, credentials-domain API key, settingsScope UI  
  标签：labnana / image / generation / 多模态与视觉
- [DeepSeek_Harness_Files_Panel](https://github.com/iskshadow195563/DeepSeek_Harness_Files_Panel) — 📁 右侧可折叠的 DeepSeek 上传文件管理面板(dsh 插件):列出/复制/清理 DeepSeek Files API 上传的图片,密钥零暴露,一条命令安装  
  标签：DeepSeek / dsh / Files / 多模态与视觉
- [DeepSeek-Harness-Token-Free](https://github.com/hyqibot/DeepSeek-Harness-Token-Free) — A token-free desktop client for the DeepSeek Harness，enjoy！为 DeepSeek Harness (DSH)     生态打造的全免Token费的桌面端 ，极简极易。内置多模态+顶尖工具链能力的大模型 HYQi（Flash / Image / Video）：生图+生视频均免token费，无需API  
  标签：DeepSeek / token-free / desktop / 多模态与视觉
- [SuperMate-Harness-System](https://github.com/SuperMate-Ai/SuperMate-Harness-System) — Give DeepSeek Eyes · 给 DeepSeek 装眼睛 — a DeepSeek Harness (DSH) Skill: local vision models or vision APIs let DeepSeek read images and graphic files  
  标签：SuperMate / Give / Eyes / 多模态与视觉
- [screenshot-feedback-hook-mcp](https://github.com/lkh081231/screenshot-feedback-hook-mcp) — Let your coding agent SEE what it builds. Cross-platform screenshot feedback for AI agents: an MCP server, a Claude Code hook, and a native DeepSeek Harness plugin that drops screenshots straight into the conversation as images. Python + uv, zero install via uvx. Windows / Linux / macOS.  
  标签：screenshot / Let / coding / 多模态与视觉
- [dsh-trace-compare](https://github.com/lamost423/dsh-trace-compare) — Trace Compare & Live Maze for DeepSeek Harness: visualize agent exploration (main path, detours, backtracks) from session logs or live sessions  
  标签：trace / Compare / Live / 多模态与视觉
- [dsh-rollback-visual](https://github.com/QinLuza/dsh-rollback-visual) — Visual plugin for dsh /rollback: trajectory anchor badges with click-to-rollback. Data layer ready; native-node rendering planned.  
  标签：rollback / Visual / dsh / 多模态与视觉
- [dsh-image-pathify](https://github.com/dami9527/dsh-image-pathify) — DeepSeek Harness 插件：让 deepseek-v4-flash 等不能看图的模型也能处理聊天图片，内置识图工具。安装：dsh plugin --profile web add dsh-image-pathify  
  标签：deepseek / image / plugin / vision
- [dsh-screenshot](https://github.com/Alain-Prot0s5/dsh-screenshot) — DeepSeek Harness Desktop 截图自动粘贴插件（需安装 DSH Desktop 版，仅 Win10/11，纯 AI 生成）：相机按钮 / 全局热键 Alt+A → 系统截图 → 自动粘贴进输入框 | Screenshot-to-input plugin for DeepSeek Harness Desktop (DSH Desktop app required; Windows 10/11 only; AI-generated): camera button & global hotkey Alt+A -> snip -> auto-paste into composer  
  标签：ai-generated / clipboard / hotkeys / powershell
- [dsh-APEX_Plugin](https://github.com/GTC2080/dsh-APEX_Plugin) — DeepSeek Harness 的 APEX 实验插件：Minimal 锚定、Pro 主导、视觉版 Flash Max 有界协作与宿主级 Web 验收。  
  标签：deepseek / deepseek-api / deepseek-v4
- [dsh-pseudo-vision](https://github.com/DDDFXYqiming/dsh-pseudo-vision) — Local OCR, color-statistics, pixel-scan, and metadata bridge for text-only DeepSeek Harness models; no external vision API.  
  标签：ocr / vision
- [dsh-composer-image-tools](https://github.com/ai-yucheng/dsh-composer-image-tools) — DSH 聊天输入框图片工具(自研):上传图片 + 区域截图,注入草稿图片轨。零依赖,纯客户端+Electron desktopCapturer 截屏。  
  标签：composer / desktopcapturer / image / screen-capture
- [dsh-local-llm-controller](https://github.com/Lbunc/dsh-local-llm-controller) — DSH 插件：在「设置→插件」页一键启停本地 llama.cpp 大模型（35B/9B，视觉×文本×快速/长上下文），卡片内配置、一条命令安装、自动注册，装完即用。 | start/stop a local llama.cpp llama-server right from Settings → Plugins, with Qwen3.6-35B / Qwen3.5-9B (vision × text, fast × long-context) as session models — card config, one-command install, auto-registered.  
  标签：cordis / llama-cpp / llama-server / local-llm
- [dsh-media-gen](https://github.com/ant404/dsh-media-gen) — DSH plugin: generate images and videos via OpenAI-compatible providers, with dedicated settings menu and workspace media_gen output.  
  标签：image-generation / media-generation / openai-compatible / video-generation
- [dsh-vision-bench](https://github.com/xingyingyuzhui/dsh-vision-bench) — DSH plugin: Vision bench — Keil debug and Modbus HMI in the session view  
  标签：多模态与视觉
- [dock-media](https://github.com/AKS1st/dock-media) — Media player for the DSH dock: plays audio (music player) and video (fullscreen) files, streamed over HTTP Range.  
  标签：audio / dock / media / video
- [dsh-codex-media](https://github.com/yujianjian1013/dsh-codex-media) — DeepSeek Harness 的 Codex 扩展：粘贴识图、生图/改图，本机 Codex CLI 子代理干活  
  标签：ai / codex / deepseek / image-generation
- [dsh-tts](https://github.com/vlln/dsh-tts) — 文本转语音，Agent 回复可朗读，本地离线引擎保护隐私。  
  标签：TTS / 语音
- [dsh-image-gen](https://github.com/vlln/dsh-image-gen) — 多 provider 文生图聚合，Stable Diffusion / DALL·E 一键切换。  
  标签：文生图 / 聚合
- [dsh-video-understand](https://github.com/vlln/dsh-video-understand) — 视频理解工具，抽帧 + 语音转写，让 Agent 看懂视频内容。  
  标签：视频 / 理解
- [dsh-screenshot](https://github.com/vlln/dsh-screenshot) — 网页/桌面截图工具，Agent 可抓取页面快照做视觉分析。  
  标签：截图 / 视觉
- [dsh-barcode](https://github.com/vlln/dsh-barcode) — 二维码/条形码识别与生成，扫码场景接入 Agent。  
  标签：二维码 / 识别
- [dsh-vision-router](https://github.com/ysr666/dsh-vision-router) — 视觉路由：让文本 Agent 自动获得图像识别、OCR 与像素工具。  
  标签：视觉 / 路由
- [dsh-plugin-vision](https://github.com/tdf1995/dsh-plugin-vision) — 视觉插件：view_image 工具桥接任意 OpenAI 兼容 VLM。  
  标签：VLM / 视觉
- [context-vista](https://github.com/GooodWei/context-vista) — 上下文可视化：直接看 Token 都被谁吃了，精准瘦身。  
  标签：上下文 / Token
- [dsh-deepseek-vision](https://github.com/Argonaut790/dsh-deepseek-vision) — 图像理解、OCR 与持久视觉证据，让纯文本 DSH 模型获得视觉能力。  
  标签：视觉 / OCR
- [dsh-image-bridge](https://github.com/haitang1/dsh-image-bridge) — 让文本模型也能发图：图片落盘、消息转成模型可见路径，由视觉/MCP 工具识别。  
  标签：图片 / 桥接
- [dsh-directorx](https://github.com/LaplaceYoung/dsh-directorx) — DirectorX 插件：AI 视频/图像/音频技能、知识语料与可配置视觉模型工具。  
  标签：视频 / 多模态
- [vision-translation](https://github.com/BingL-Li/vision-translation) — DSH 视觉翻译：经辅助 VLM 桥，将图像转为结构化 vision-context 原语。  
  标签：视觉 / 翻译 / VLM
- [deepseek-visionary](https://github.com/xlight/deepseek-visionary) — 用 DeepSeek 官方多模态视觉模型让 Agent 不再眼瞎（支持 DSH、Zed、OpenCode、Codex、Claude Code、Cursor、Claude Desktop）。  
  标签：视觉 / 多模态 / DeepSeek
- [dsh-ai-image-design](https://github.com/satan9394/dsh-ai-image-design) — DSH 技能：AI 图像生成工作流，提示词与批量派生。  
  标签：图像 / AIGC

<a id="cat-安全与运维" name="cat-安全与运维"></a>

### 🛡️ 安全与运维

- [Security Audit](https://github.com/omdsh-dev/dsh-security-audit) — 本机只读安全审计：防御性扫描，不改动任何文件，安心使用插件。  
  标签：安全审计 / 只读
- [Tool Policy](https://github.com/Drifter-yh/dsh-tool-policy) — 声明式、fail-closed 的工具治理，未授权一律拒绝，最小权限原则。  
  标签：权限治理 / fail-closed
- [Harness Ops](https://github.com/fakechris/dsh-harness-ops) — 升级、重启、故障自愈一条龙，DSH 运维不再手忙脚乱。  
  标签：运维 / 自愈
- [Doctor](https://github.com/coppynight/dsh-doctor) — flutter-doctor 风格诊断与一键修复，环境问题秒定位。  
  标签：诊断 / 修复
- [dsh-session-health](https://github.com/omdsh-dev/dsh-session-health) — DSH 会话健康检查插件：多帧 zstd 会话文件的帧级扫描诊断。  
  标签：诊断
- [dsh-plugin-check](https://github.com/omdsh-dev/dsh-plugin-check) — DSH 插件健康检查工具。  
  标签：诊断
- [dsh-context-doctor](https://github.com/Zhenyu98/dsh-context-doctor) — DSH 上下文注入审计插件（Context Doctor）。  
  标签：审计
- [dsh-bash-encoding](https://github.com/lhh010/dsh-bash-encoding) — DSH bash 输出编码自动识别插件。  
  标签：编码
- [dsh-trace](https://github.com/vibeinging/dsh-trace) — DeepSeek Harness 遥测后端：通过 HTTP 导出到 yiTrace。  
  标签：遥测
- [Lujo-MCP](https://github.com/lujoai/Lujo-MCP) — 基于 MCP 协议的 AI 调试追踪平台。  
  标签：MCP / 调试
- [RemoteOps](https://github.com/jark006/RemoteOps) — 面向远程系统维护和嵌入式 Linux 开发的 MCP 工具。  
  标签：MCP / 运维
- [dsh-plugin-anti-ads](https://github.com/HuanLinOTO/dsh-plugin-anti-ads) — 给 DSH Web UI 装的广告拦截器。  
  标签：拦截
- [dsh-port-guard](https://github.com/PangYiMing/dsh-port-guard) — 端口占用处置插件。  
  标签：端口
- [dsh-scout](https://github.com/omdsh-dev/dsh-scout) — 面向 DeepSeek Harness 的只读环境探测工具。  
  标签：探测
- [dsh-tailscale-surface](https://github.com/mrlfarano/dsh-tailscale-surface) — DSH 插件：Tailscale serve 表面，提供规范外部 URL 与身份门控的特权 RPC 中继。  
  标签：安全 / Tailscale / RPC
- [dsh-gpt-compat](https://github.com/YaoaY/dsh-gpt-compat) — DSH 的 GPT/Codex 沙箱提权参数兼容插件，默认失败关闭（fail-closed）。  
  标签：安全 / 沙箱 / 权限
- [dsh-trapstreet](https://github.com/trapstreet/dsh-trapstreet) — 检查哪些 DSH 插件真正加载成功，并查询 trapstreet.run 上的公开评测榜。  
  标签：安全 / 加载 / 评测
- [dsh-runtime-xray](https://github.com/hollis-openlab/dsh-runtime-xray) — DeepSeek Harness 只读运行时 X-Ray 透视工具。  
  标签：安全 / 运行时 / 透视
- [dshscan](https://github.com/shaoshi20/dshscan) — DShScan —— 受 NVIDIA SkillSpector 启发的 DSH 插件安全扫描器。  
  标签：安全 / 扫描 / SkillSpector
- [iterate-plugin](https://github.com/jingzhao-l/iterate-plugin) — DeepSeek Harness (dsh) plugin that turns the iterate skill into an autonomous closed-loop code iteration — parallel reviews, deterministic dedup convergence, atomic fix + verify auto-stop, meta-review consistency audit, and dry-run read-only review. Maintained from the iterate-skill monorepo.  
  标签：iterate / dsh / that / 安全与运维
- [dsh-delegate](https://github.com/FEOH333/dsh-delegate) — dsh-delegate: model-aware subagent delegation for DeepSeek Harness — per-call models, depends_on dependency gating, per-child personas, a durable run roster, audit events, and conversation-flow tool cards. | 给 DeepSeek Harness 的子代理委派加上：按次选模型、依赖门控、角色人设、任务花名册。  
  标签：delegate / dsh-delegate / model-aware / 安全与运维
- [dsh-server-login](https://github.com/pointer-a/dsh-server-login) — 面向公网的多租户 DSH 托管平台 —— 部署到一台公网服务器后，多个用户注册并经管理员审核，各自获得一套相互隔离的 deepseek-harness（DSH）环境，随时通过域名安全访问。  
  标签：server / deepseek-harness / 安全与运维
- [dsh-safe-plugin-manager](https://github.com/AI-Scarlett/dsh-safe-plugin-manager) — DSH STORE — third-party plugin marketplace and guarded lifecycle manager for DeepSeek Harness.  
  标签：safe / STORE / third-party / 安全与运维
- [npm-safe-forDSH](https://github.com/nisconder/npm-safe-forDSH) — 本地优先的 npm 包供应链安全扫描引擎，deepseek harness 插件版本  
  标签：npm / deepseek / harness / 安全与运维
- [dsh-permgate](https://github.com/MrWeiCodes/dsh-permgate) — 为 DeepSeek Harness（DSH）提供的细粒度权限控制插件  
  标签：permgate / 安全与运维
- [dsh-cc-ecosystem](https://github.com/Bcy2020/dsh-cc-ecosystem) — 让 DeepSeek Harness 用上 Claude Code 全家桶:技能、命令、规则、权限、子代理、hooks—— .claude/ 资产原样加载,正在逐步做到全兼容。  
  标签：cc / Claude / Code / 安全与运维
- [dsh-multi-tenant](https://github.com/GuoMonth/dsh-multi-tenant) — Multi-tenant SaaS extension for DeepSeek Harness (DSH): tenant identity, session isolation, authorization, tenant-aware MCP, and audit.  
  标签：multi / Multi-tenant / SaaS / 安全与运维
- [dsh-orcana](https://github.com/Leo-Ayh-Oday/dsh-orcana) — Runtime governance for DeepSeek Harness: progress governor, evidence freshness, completion guard, capability router (Same model. Same DSH. One runtime intervention.)  
  标签：orcana / Runtime / governance / 安全与运维
- [dsh-updater-plugin](https://github.com/StefanIsMe/dsh-updater-plugin) — Never lose a draft. Stay up to date in one click — draft-safe self-updater for DeepSeek Harness  
  标签：updater / Never / lose / 安全与运维
- [dsh-project-orchestrator](https://github.com/zhangz-2018/dsh-project-orchestrator) — Local-first AI project orchestration workbench and CLI plugin for DeepSeek Harness: approval-gated planning, Git worktrees, task execution, Issues, and auditable evidence.  
  标签：project / Local-first / orchestration / 安全与运维
- [dsh-squad](https://github.com/zhouCode/dsh-squad) — 让分布在不同设备与网络中的个人 Agent，在各自的工作区与权限边界内组成可持久委派的团队。 DSH-native delegation for personal Agents across devices and networks, without giving up local workspaces, credentials, or control.  
  标签：squad / Agent / DSH-native / 安全与运维
- [dsh-agent-approval](https://github.com/MoonlitDropOfBlood/dsh-agent-approval) — DSH 的自动审批权限插件  
  标签：agent / 安全与运维
- [dsh-secure-audit](https://github.com/PensiveFei/dsh-secure-audit) — Read-only security & compliance plugin for DeepSeek Harness: prompt-injection detection, Chinese-PII redaction, and local configuration audit with redacted, reproducible reports.  
  标签：secure / Read-only / security / 安全与运维
- [dsh-full-with-approval](https://github.com/zjuhbh/dsh-full-with-approval) — DSH profile plugin: full-access (GPU-capable) sandbox with per-operation approval for writes outside the workspace or to protected files.  
  标签：full / profile / full-access / 安全与运维
- [deep-tui](https://github.com/pmorgan3/deep-tui) — deep-tui is a plugin-first coding-agent harness built on Cordis. Providers, tools, prompts, permissions, storage, themes, commands, renderers, and the agent loop are all replaceable plugins.  
  标签：deep / deep-tui / plugin-first / 安全与运维
- [dsh-undo-savepoint](https://github.com/lire1131/dsh-undo-savepoint) — DSH crash-rescue plugin: undo config & plugin-code changes, secret-safe snapshots, one-click SAFE MODE, plus offline CLI/GUI that work even when DSH won't boot.  
  标签：undo / crash-rescue / config / 安全与运维
- [dsh-web-launcher](https://github.com/LVSUGARS/dsh-web-launcher) — Windows desktop launcher for DeepSeek Harness (DSH) Web: install the official CLI, manage local workspaces, and safely start, stop, and update DSH.  
  标签：web / Windows / desktop / 安全与运维
- [dsh-seatbelt-sandbox](https://github.com/drscrewdriver/dsh-seatbelt-sandbox) — dsh-seatbelt 方面沙箱增强尝试使用非exec工具直接对接系统seatbelt相关api  
  标签：seatbelt / dsh-seatbelt / exec / 安全与运维
- [dsh-quota-meter-plus](https://github.com/Lstalu/dsh-quota-meter-plus) — DSH 会话额度监控增强版：真实 token 计费、实时进度条、额度耗尽拦截、峰谷定价、右上角余额校准胶囊（官方基线 + 同源防护 + inputWrite 计费档）  
  标签：quota / token / inputWrite / 安全与运维
- [dsh-remote-mobile](https://github.com/IceApriler/dsh-remote-mobile) — DeepSeek Harness 远程与移动端安全网关插件：零修改 DSH 底层代码安全开放局域网与 Tailscale 连接 | DeepSeek Harness (DSH) Remote & Mobile Security Guard: safely opens Tailscale/LAN with zero core modifications, QR scan auth, RSA encryption & brute-force defense.  
  标签：remote / Tailscale / Mobile / 安全与运维
- [dsh-tailscale-console](https://github.com/evanfang0054/dsh-tailscale-console) — 为 DeepSeek Harness 提供基于 Tailscale 的安全远程访问运营面板：一键健康检查、HTTPS 入口开关、macOS 代理绕过、中继服务器运维、ACL 生成。Tailscale remote-access control panel for DeepSeek Harness: health checks, HTTPS serve toggle, proxy bypass, relay ops, ACL helper.  
  标签：tailscale / HTTPS / macOS / 安全与运维
- [dsh-score](https://github.com/PerryLink/dsh-score) — Multi-dimensional quality scoring for DeepSeek Harness plugins: scores a repo or npm package across install success (consuming dsh-test-drive results), maintenance activity, documentation completeness, security scan, and protocol compliance — every conclusion backed by real CLI evidence with audit timestamps.  
  标签：score / Multi-dimensional / quality / 安全与运维
- [dsh-memento](https://github.com/PerryLink/dsh-memento) — Bounded, layered, approval-gated, auditable cross-session memory for DeepSeek Harness (capability seam: ctx.memory + SQLite provider + memory tool + frozen snapshot injection)  
  标签：memento / Bounded / layered / 安全与运维
- [deepseek-harness-remote](https://github.com/liguobao/deepseek-harness-remote) — 基于 DeepSeek Harness 插件机制的多端远程访问方案，让桌面端与 Android 端安全连接并操作远程 Harness。（A multi-device remote access solution built on the DeepSeek Harness plugin system, enabling desktop and Android clients to securely connect to and operate a remote Harness.）  
  标签：deepseek
- [dsh-Remote](https://github.com/Blank-not-black/dsh-Remote) — DSH Remote · 口袋里的 DSH 控制台 会话 · 审批 · 提问 · 文件传输，局域网 / Tailscale 直连 多服务器自动选优，聊天记录离线可看 带 Token 鉴权，数据只在你的设备之间流动 Sessions · approvals · questions · file transfer over LAN / Tailscale. Automatic fastest-server selection. Chat history available offline. Token-authenticated — your data flows only between your devices.  
  标签：mobile / remote-control
- [dsh-win32](https://github.com/sjh9714/dsh-win32) — Native Windows shell and sandbox presets for DeepSeek Harness. No WSL. One command. | DSH 原生 Windows Shell 与沙箱预设  
  标签：ai-agent / busybox / conpty / deepseek
- [dsh-auth-gateway](https://github.com/xbzbing/dsh-auth-gateway) — 为 DeepSeek Harness 增加远程访问能力，并通过密码和 OTP 进行安全加固。 Adds secure remote access to DeepSeek Harness with password auth and TOTP two-factor authentication (2FA).  
  标签：2fa / auth-gateway / security
- [kimi-tide](https://github.com/tafcear/kimi-tide) — 🌊 kimi-tide（月汐）— DSH 模型路由插件：预设+规则驱动，每步自动在 Kimi 与 DeepSeek 间选路；图像护栏 + 配额面板 + 决策可观测 · preset+rule model router for DeepSeek Harness  
  标签：kimi / kimi-code / llm-router / model-routing
- [deepseekeyes](https://github.com/dttxorg/deepseekeyes) — Auditable vision and cross-platform Computer Use runtime for DeepSeek Harness — strict evidence, health-checked failover, original pixels, and Token accounting.  
  标签：ai-agent / ai-evaluation / auditable-ai / browser-automation
- [dsh-plugin-vet](https://github.com/wulun811/dsh-plugin-vet) — Trust pipeline for deepseek-harness plugins: deterministic static scan (11 rules) + LLM-driven audit protocol + two-part scorecard, with optional runtime guard (T1 sentinel / T2 fs & child_process hooks) and honeypot decoys. Monitor-and-alert only — vet never blocks or kills on its own.  
  标签：dsh-plugin-market / dsh-plugins
- [dsh-auth-everying](https://github.com/chenbin-dev/dsh-auth-everying) — 导入本地 Claude、Codex、Grok、Gemini、Copilot、OpenCode 与 CC Switch 配置。 为支持的官方供应商提供 OAuth 登录。 从 OpenAI 兼容网关的 /v1/models 与 /models 发现 CC Switch 模型。  
  标签：安全与运维
- [dsh-injection-guard](https://github.com/loeanxi/dsh-injection-guard) — Source-aware prompt injection protection for DeepSeek Harness  
  标签：cordis
- [dsh-guardian](https://github.com/Max-Null/dsh-guardian) — Event-driven mission guardian for the DeepSeek Harness - assertion rules, correction detection, review queue  
  标签：安全与运维
- [WhaleHarness](https://github.com/WhaleHarness/WhaleHarness) — A curated DeepSeek Harness plugin store: 79 verified plugins with reproducible builds, sandboxed review, and sha256-pinned tarballs, plus transparent stats and a public audit of 871+ DSH repos. https://whaleharness.com  
  标签：plugin-store / whaleharness
- [dsh-strip-sandbox-permissions](https://github.com/Sharl210/dsh-strip-sandbox-permissions) — Strip sandbox_permissions/justification from model tool-call arguments to avoid false sandbox escalation errors  
  标签：安全与运维
- [dsh-malware-audit](https://github.com/rand0wn/dsh-malware-audit) — DeepSeek Harness (dsh) plugin: real AST-based scan of installed plugins for malicious-intent patterns, with an optional periodic schedule and auto-quarantine on critical findings. Advisory-by-default, not an antivirus signature database.  
  标签：cordis / security
- [deepseek-harness-relay](https://github.com/sorsama/deepseek-harness-relay) — Authenticated remote access for a DeepSeek Harness web profile: TLS, QR/passcode device pairing, password sign-in, and per-device revocation in front of an untouched loopback harness.  
  标签：android / authentication / mdns / mobile
- [dsh-identity-control](https://github.com/orpheus0829/dsh-identity-control) — 为 DeepSeek Harness (DSH) 打造的自定义人设控制插件。 在对话输入栏旁自由填写你的人设文本，一键开关，所有新对话自动生效、免重启。 人设纯粹是你设定的风格，不覆盖 DSH 安全护栏，安装即用、状态持久化。  
  标签：ai-assisted / cordis / custom-personas / deepseek
- [dsh-whale-picks](https://github.com/LeeKai233/dsh-whale-picks) — 🐳 鲸选 dsh-whale-picks — 敢装，值得装：有品味的 DeepSeek Harness 插件精品商店（创始人亲测 + 安全体检 + 四维评分）  
  标签：curated
- [dsh-secret-scan](https://github.com/vlln/dsh-secret-scan) — 密钥泄露扫描，检出代码与日志中的 API Key、密码等敏感信息。  
  标签：安全 / 密钥扫描
- [dsh-log-tail](https://github.com/vlln/dsh-log-tail) — 实时日志追踪，Agent 可监控应用日志、快速定位异常。  
  标签：日志 / 监控
- [dsh-health-check](https://github.com/vlln/dsh-health-check) — 服务健康检查探针，定时探测端口与接口可用性并告警。  
  标签：健康检查 / 探针
- [dsh-backup](https://github.com/vlln/dsh-backup) — 会话与配置自动备份，一键恢复到历史快照。  
  标签：备份 / 恢复
- [dsh-firewall](https://github.com/vlln/dsh-firewall) — 网络访问白名单/黑名单，限制 Agent 出站请求目标域。  
  标签：防火墙 / 白名单
- [dsh-telemetry-redactor](https://github.com/030611/dsh-telemetry-redactor) — 遥测脱敏：在导出/上报前自动清洗敏感信息。  
  标签：脱敏 / 隐私
- [dsh-verification-receipt](https://github.com/030611/dsh-verification-receipt) — 验证回执：任务完成生成可审计的执行凭证。  
  标签：审计 / 回执
- [dsh-passwords](https://github.com/slywalker2006/dsh-passwords) — 登录网关：首次设置、静态加密、暴力破解锁定、审计日志、HTTPS。  
  标签：登录 / 加密
- [dsh-command-quarantine](https://github.com/sutimee/dsh-command-quarantine) — 命令隔离：拦截 agent 直接执行命令，规则 + LLM 审查，危险命令人工确认，全程审计。  
  标签：隔离 / 审计
- [readonly-security-audit](https://github.com/my-dsh-plugin/readonly-security-audit) — 只读安全审计模式，让 DSH 在只读约束下工作。  
  标签：只读 / 审计
- [dsh-careful-full-access](https://github.com/zdjmrq/dsh-careful-full-access) — 命令防护：拦截灾难级删除、高危升级，附 careful-full-access 删除预览与模型复核。  
  标签：防护 / 删除
- [upstream-radar](https://github.com/MicroMilo/upstream-radar) — 插件安全与依赖监控：精确漏洞路径、破坏性更新与 agent 跟进。  
  标签：依赖 / 漏洞
- [dsh-clawrouter](https://github.com/BlockRunAI/dsh-clawrouter) — DSH 安全闸门：强模型在危险工具调用执行前审查；附视觉与 67 个模型统一钱包（x402 按次付费）。  
  标签：安全 / 审查
- [openguardrails](https://github.com/openguardrails/openguardrails) — AI Agent 安全与安保的中立协议，及对各厂商排名的中立基准。  
  标签：安全 / 协议
- [dsh-plugin-inspector](https://github.com/CharlotteN7/dsh-plugin-inspector) — 安装前看清 DSH 插件做了什么（供应链安全）。  
  标签：供应链 / 审查
- [dsh-ocsf-forwarder](https://github.com/CharlotteN7/dsh-ocsf-forwarder) — 把 DSH 会话活动以 OCSF 1.9.0 记录转发到你的 SIEM。  
  标签：SIEM / 转发
- [dsh-dlp](https://github.com/CharlotteN7/dsh-dlp) — 阻止 DSH Agent 读取你的凭证文件并把密钥粘贴进工具调用。  
  标签：DLP / 防泄漏
- [hol-guard](https://github.com/hashgraph-online/hol-guard) — 面向 AI Agent 的开源杀毒：运行时拦截危险工具、密钥访问、提示注入、恶意包、MCP 服务器、插件与技能。  
  标签：杀毒 / 运行时
- [dsh-fleet-audit](https://github.com/LeslieWylie/dsh-fleet-audit) — Agent 集群卫生审计：凭证文件权限、内嵌 git 远程凭证（脱敏）、provider 令牌字面量。只读、零依赖、确定性。  
  标签：审计 / 安全
- [dsh-tool-codereview](https://github.com/chengganping-ship-it/dsh-tool-codereview) — DeepSeek Harness 专业代码审查与安全扫描插件：SARIF 输出、OWASP Top 10、AI 增强分析。  
  标签：代码审查 / 安全 / SARIF
- [dsh-netguard](https://github.com/CharlotteN7/dsh-netguard) — DSH web_fetch / web_search 的主机白名单，连接时强制校验。  
  标签：安全 / allowlist / 网络
- [dsh-server-deployment](https://github.com/AnkoCD/dsh-server-deployment) — DSH 多用户服务器部署：登录门户、每用户独立实例与 OS 级隔离、独立 API Key、交付文件抽屉（sudo 助手降权执行）。  
  标签：部署 / 多用户 / 隔离
- [dsh-git-guardrails](https://github.com/satan9394/dsh-git-guardrails) — DSH 技能：Git 安全护栏，拦截危险命令。  
  标签：Git / 护栏
- [dsh-security-compliance](https://github.com/satan9394/dsh-security-compliance) — DSH 技能：安全审计与合规，DevSecOps 与框架。  
  标签：合规 / 审计
- [dsh-deployment-validation](https://github.com/satan9394/dsh-deployment-validation) — DSH 技能：部署验证与配置管理，schema 与密钥扫描。  
  标签：部署 / 密钥
- [dsh-threat-modeling](https://github.com/satan9394/dsh-threat-modeling) — DSH 技能：威胁建模，攻击树与 STRIDE。  
  标签：威胁建模 / STRIDE
- [dsh-before-you-build](https://github.com/satan9394/dsh-before-you-build) — DSH 技能：建前风险预审，七维检查与最小验证。  
  标签：风险 / 预审
- [dsh-hr-legal-compliance](https://github.com/satan9394/dsh-hr-legal-compliance) — DSH 技能：HR 与法律合规，雇佣文档与 GDPR。  
  标签：HR / 合规
- [dsh-ankh-guard](https://github.com/Khorsheed/dsh-ankh-guard) — 防止 Agent 自我修改把服务改崩的守护插件：绿色构建凭证绑定 git HEAD，watchdog 重启 + canary 回滚。  
  标签：守护 / 回滚
- [dsh-auto-approval-llm](https://github.com/cuddly-guacamole/dsh-auto-approval-llm) — 为 DeepSeek Harness Auto 预设提供 LLM 辅助自动审批 + 超时兜底。  
  标签：自动审批 / 安全
- [dsh-stability-audit](https://github.com/chunfenxiazhi-collab/dsh-stability-audit) — 扫描已安装的 dsh 插件并评估稳定性风险（hook 面、启动负载、preflight、依赖），可选隔离安装验证。  
  标签：审计 / 稳定性 / 依赖
- [DeepGuard](https://github.com/SoberReport-AI/DeepGuard) — DSH 插件安全审计：提交 issue 即可触发安全审计团队生成审计报告。  
  标签：审计 / 安全 / issue
- [dsh-approval-first](https://github.com/joao-paulo-santos/dsh-approval-first) — DSH 编辑 / 写入前审批：在 sandbox 会拒绝的变更前先请求用户确认。  
  标签：审批 / 安全 / 沙箱
- [dsh-code-security](https://github.com/ihuajiu/dsh-code-security) — DSH 代码安全：13 个审计技能 + 5 个扫描工具预设，本地模型自动审计新插件，无需 API key。  
  标签：代码审计 / 安全 / 扫描

<a id="cat-趣味与社区" name="cat-趣味与社区"></a>

### 🎮 趣味与社区

- [Gomoku](https://github.com/omdsh-dev/dsh-gomoku) — 侧边栏 15×15 五子棋，与模型对弈，摸鱼也能卷。  
  标签：小游戏 / 对弈
- [Mini Games](https://github.com/lhh010/dsh-minigames) — 右侧面板 18 款离线小游戏，模型生成卡顿时随手来一局。  
  标签：小游戏 / 离线
- [Share Card](https://github.com/hellodigua/dsh-share) — 把一轮问答生成精美 PNG 卡片，一键分享到社交媒体。  
  标签：分享 / 截图
- [Stock Market](https://github.com/AnacondaKC/dsh-stock-market) — 沪深 A 股行情侧栏 + 免费股票数据工具，边写代码边盯盘。  
  标签：行情 / A股
- [dsh-ads](https://github.com/Nagi-ovo/dsh-ads) — DSH Web UI 广告：2005 年中文站点风格的侧栏广告/信息流/角落弹窗。  
  标签：整活
- [dsh-group-photo](https://github.com/SenmuuuuW/dsh-group-photo) — DSH 内测收官合影墙。  
  标签：社区
- [dsh-mygo](https://github.com/omdsh-dev/dsh-mygo) — DSH 的受管插件层「轻量核心 + 一切皆扩展」。  
  标签：社区
- [dsh-auto-chess](https://github.com/omdsh-dev/dsh-auto-chess) — 简化自走棋：DSH 会话标签栏里藏着的棋桌。  
  标签：小游戏
- [dsh-plugin-d399](https://github.com/HuanLinOTO/dsh-plugin-d399) — 深夜寂寞？来玩 D399 — 当模型生成时弹出小游戏菜单。  
  标签：小游戏
- [7d7d](https://github.com/omdsh-dev/7d7d) — 7k7k 风格的 DSH 游戏门户。  
  标签：游戏
- [dsh-douyin](https://github.com/AnacondaKC/dsh-douyin) — DSH WebUI 侧栏短视频插件。  
  标签：短视频
- [dsh-conversation-share](https://github.com/bill9109/dsh-conversation-share) — DSH 对话分享截图插件。  
  标签：分享
- [deepseek-manners](https://github.com/Moeblack/deepseek-manners) — 每次发消息后给鲸鱼娘说谢谢的礼貌整活插件。  
  标签：整活
- [dsh-fun-weather](https://github.com/omdsh-dev/dsh-fun-weather) — DSH Fun Weather 天气插件。  
  标签：天气
- [dsh-daily-fortune](https://github.com/omdsh-dev/dsh-daily-fortune) — DSH Daily Fortune 每日一签。  
  标签：签运
- [dsh-fun-typewriter](https://github.com/omdsh-dev/dsh-fun-typewriter) — 为 DSH Web 增加打字机/机械键盘氛围音。  
  标签：音效
- [dsh-fun-ticker](https://github.com/omdsh-dev/dsh-fun-ticker) — 会话底部常驻横向跑马灯。  
  标签：跑马灯
- [dsh-daily-progress](https://github.com/omdsh-dev/dsh-daily-progress) — 每日进度成就系统。  
  标签：成就
- [graycode-for-dsh](https://github.com/Komeiji-Shiki/graycode-for-dsh) — 社区插件，用途待确认，收录备查。  
  标签：未知
- [dsh-plugin-spur](https://github.com/HuanLinOTO/dsh-plugin-spur) — 一根悬挂在 DSH 聊天流中的「辫子」（皮鞭）纯整活插件。  
  标签：整活
- [dsh-pomodoro](https://github.com/vlln/dsh-pomodoro) — 番茄钟效率插件，边写代码边计时，专注力拉满。  
  标签：番茄钟 / 效率
- [dsh-sound](https://github.com/vlln/dsh-sound) — 任务完成/报错提示音效，让 Agent 状态「听得见」。  
  标签：音效 / 提示
- [dsh-achievement](https://github.com/vlln/dsh-achievement) — 编程成就徽章系统，解锁里程碑，写代码也有游戏感。  
  标签：成就 / 徽章
- [dsh-lucky](https://github.com/vlln/dsh-lucky) — 每日抽签 + 幸运色，摸鱼小确幸，开工前先来一发。  
  标签：抽签 / 整活
- [dsh-counter](https://github.com/vlln/dsh-counter) — 写代码行数/提交次数趣味统计，卷王排行榜。  
  标签：统计 / 排行
- [dsh-fortune-cookie](https://github.com/vlln/dsh-fortune-cookie) — 幸运签语饼，每次会话结束送上一条程序员专属鸡汤。  
  标签：鸡汤 / 整活
- [dsh-motivation](https://github.com/vlln/dsh-motivation) — 随机激励语录，在 Agent 卡壳时给你打气，绝不摆烂。  
  标签：激励 / 语录
- [dsh-tamagotchi](https://github.com/vlln/dsh-tamagotchi) — 电子宠物养成，喂食、玩耍、进化，陪你在终端养只小鲸鱼。  
  标签：宠物 / 养成
- [dsh-clippy](https://github.com/sjh9714/clippy-harness) — Clippy 助手：把微软经典回形针请回你的 DSH 界面。  
  标签：整活 / 怀旧
- [dsh-MusicPlayer](https://github.com/xiekai886/dsh-MusicPlayer) — 音乐播放器：边写代码边听歌，内置播放列表。  
  标签：音乐 / 娱乐
- [dsh-digipet](https://github.com/swaylq/dsh-digipet) — 数字宠物：在终端养一只会互动的电子宠物。  
  标签：宠物 / 养成
- [dsh-weather](https://github.com/sunshine-lang/dsh-weather) — 天气插件：随手查当地天气与预报。  
  标签：天气 / 生活
- [dsh-recommend](https://github.com/zp-home/dsh-recommend) — 插件透明排行与推荐：每日抓取 dsh-plugin 生态，公开评分排序。  
  标签：推荐 / 排行
- [dsh-whale-galgame](https://github.com/JAdpp/dsh-whale-galgame) — 多角色 Galgame 界面 + 可选桌面伴侣插件。  
  标签：Galgame / 桌面
- [dsh-ventus-whale](https://github.com/mmzm0808/dsh-ventus-whale) — 蓝色大肥鱼·DeepSeek 虎鲸 3D 桌宠插件：悬浮角落可拖拽旋转、360° 转圈、爱心互动、悬停工具栏与本地持久化配置。  
  标签：桌宠 / 3D / 鲸鱼
- [petdex](https://github.com/crafter-station/petdex) — 面向 Codex、Claude Code、DeepSeek Harness、Hermes、OpenCode、Gemini CLI 等的动态桌宠公开画廊。  
  标签：桌宠 / 画廊 / 动画
- [dsh-wallpaper_share](https://github.com/YRN-playmaker/dsh-wallpaper_share) — 挂载于 DeepSeek Harness 的壁纸引擎同步插件，可同步不同显示器的静态壁纸。  
  标签：壁纸 / 桌面 / 同步
- [dsh-BigfishPet](https://github.com/s17179XTY/dsh-BigfishPet) — dsh-BigfishPet —— DeepSeek Harness 桌面宠物插件。  
  标签：桌宠 / 宠物
- [dsh-niulai-pet](https://github.com/whitefirer/dsh-niulai-pet) — 牛来桌宠：Agent 任务完成时蹦出来喊「妈～妈～」的 DSH 纯客户端桌宠插件（5 皮肤/签名动作/合成叫声）。  
  标签：桌宠 / 宠物 / 牛来
- [dsh-bgm](https://github.com/skymecode/dsh-bgm) — DSH 插件：把 AI 对话变成节奏游戏，开启你的 BGM！  
  标签：节奏游戏 / 趣味
- [dsh-personal-center](https://github.com/PolinniZhong/dsh-personal-center) — DeepSeek Harness 个人中心:用量统计 / 自定义指令 / 成本估算 / 桌面宠物(纯本地，不联网）。 Personal center & custom instructions for DSH  
  标签：personal-center
- [Sidor_UI](https://github.com/AKI2253/Sidor_UI) — SIDOR starfield skin for DeepSeek Harness Web GUI: intro animation, starfield, balance badge, settings FX, low-balance alerts  
  标签：cordis / plugin / skin / starfield
- [dsh-web-notes](https://github.com/Shrbuz/dsh-web-notes) — Floating notes for the dsh web GUI: keep commands, credentials and snippets at hand, insert any note into the composer, save any selection as a note  
  标签：notebook / notes
- [dsh-liuli-ui-enhance](https://github.com/LilycleHeart/dsh-liuli-ui-enhance) — 琉璃 UI 增强 —— DSH 主题插件:M3 动态取色、壁纸磨砂材质、声纹可视化、dock shell、嵌入式浏览器  
  标签：enhance / ui
- [my-dsh](https://github.com/tttnny/my-dsh) — DeepSeek Harness 插件合集：dsh-client-ui-deepseek-bg（仿 Harness 官网深色皮肤：极光/粒子鲸鱼/星座网格/玻璃拟态/Border Beam/Thinking Orbs）+ dsh-escalation-noop + ptc-creative-cordis  
  标签：趣味与社区
- [dsh-815-skin](https://github.com/lengduan/dsh-815-skin) — 1945-08-15 世界名画 dsh皮肤  
  标签：趣味与社区
- [dsh-doro](https://github.com/Baizhuojielan/dsh-doro) — Doro-themed skin plugin for the DeepSeek Harness web GUI (粉丝向非商用皮肤插件)  
  标签：doro / nikke / skin
- [dsh-web-icon-indicator](https://github.com/waknow/dsh-web-icon-indicator) — DSH browser tab favicon reflecting session state: idle / running / asking / done. · DSH 标签页 favicon 实时反映会话状态：待机 / 运行中 / 提问 / 完成  
  标签：deepseek / favicon
- [dsh-voice-ai-girlfriend](https://github.com/beiyege-01/dsh-voice-ai-girlfriend) — 语音 AI 女友（Voice AI girlfriend for DeepSeek Harness）：Whisper 语音输入 + Qwen3-TTS 声音克隆 + 句子级流式朗读 + 数字人动画窗。插话/排队双模式，说话即打断。  
  标签：voice / girlfriend / Whisper / 趣味与社区
- [dsh-funasr-voice](https://github.com/fenglin-ai/dsh-funasr-voice) — DeepSeek Harness 本地离线语音输入插件：麦克风 → FunASR(SenseVoice) → 输入框，全离线识别。  
  标签：funasr / SenseVoice / 趣味与社区
- [dsh-coding-remote-kit](https://github.com/lninghaha/dsh-coding-remote-kit) — DeepSeek Harness mobile pairing remote: E2EE companion over dual-plane allowlisted RPC  
  标签：coding / mobile / pairing / 趣味与社区


---

## 📬 喜欢这个仓库？关注我，获取更多技术干货

![微信二维码](wechat-qrcode.jpeg)

- 💬 **微信**：`Yishisiweikongjian`  
  扫码或搜索微信号添加，备注「学习」更快通过
- 📕 **小红书**：**豆奶与程序猫**  
  搜索「豆奶与程序猫」关注，私信“邀请码”领学习资源  ·  [前往小红书关注 →](https://www.xiaohongshu.com/search_result?keyword=%E8%B1%86%E5%A5%B6%E4%B8%8E%E7%A8%8B%E5%BA%8F%E7%8C%AB)
- 📧 **合作 / 交流**：1019296134@qq.com

> 内容源自 [https://soycodetrail.top](https://soycodetrail.top)，转载请注明出处并保留上述联系方式。
