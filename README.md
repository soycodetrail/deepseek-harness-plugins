# DeepSeek Harness 插件库

> DeepSeek 开源「一切皆插件」Agent 驾驭层生态精选（按能力域归类 + 热度排序）
>
> 🌐 **主站入口**：https://soycodetrail.top/dsh-plugins  ·  🏠 全站：[https://soycodetrail.top](https://soycodetrail.top)
>
> 🤖 本仓库内容由脚本自动同步自主站，**与网站保持实时同步**（source 数据变更 → GitHub Actions 推送即更新）。最近同步：2026-08-14 00:25:16

## 📑 内容导航（268 个条目 / 8 个分类）

- [🧭 核心引擎](#核心引擎)
- [🎨 界面与体验](#界面与体验)
- [🤖 Agent 与自动化](#agent-与自动化)
- [🧠 记忆与知识](#记忆与知识)
- [🛠️ 工具与连接](#工具与连接)
- [👁️ 多模态与视觉](#多模态与视觉)
- [🛡️ 安全与运维](#安全与运维)
- [🎮 趣味与社区](#趣味与社区)

---

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
- [oh-my-dsh（700+ 全量）](https://github.com/LaplaceYoung/oh-my-dsh) — 面向 DSH 的插件生态——700+ 插件，只通过扩展接缝注册，社区全量聚合。  
  标签：社区 / 700+ 插件
- [DSH 架构上手指南](https://juejin.cn/post/7673390412729155638) — DeepSeek Harness 架构研究与上手指南：扩展接缝、插件开发路径、企微/Issue 社区。  
  标签：文档 / 入门
- [Awesome DSH Plugin 官网](https://awesome-dsh-plugin.com/) — 精选 DSH 插件目录网站：UI 增强、工作流、工具、通知与集成，持续更新。  
  标签：目录 / 网站
- [GitHub topic: dsh-plugin](https://github.com/topics/dsh-plugin) — 给插件仓库打 dsh-plugin topic 即可被发现；官方企微群 + GitHub Issue 社区入口。  
  标签：发现 / 社区

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
- [dsh-memory-bank](https://github.com/vlln/dsh-memory-bank) — 跨会话记忆银行：自动抽取关键决策与偏好，按主题归档检索。  
  标签：记忆 / 归档
- [dsh-changelog](https://github.com/vlln/dsh-changelog) — 自动生成每日工作变更日志，沉淀项目演进脉络。  
  标签：日志 / 记录
- [dsh-flashcards](https://github.com/vlln/dsh-flashcards) — 对话中一键生成记忆卡片，基于间隔重复帮你记住知识点。  
  标签：学习 / 间隔重复
- [dsh-citation](https://github.com/vlln/dsh-citation) — 自动为生成内容附加来源引用，标注出处、可回溯校验。  
  标签：引用 / 溯源

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


---

## 📬 喜欢这个仓库？关注我，获取更多技术干货

![微信二维码](wechat-qrcode.jpeg)

- 💬 **微信**：`Yishisiweikongjian`  
  扫码或搜索微信号添加，备注「学习」更快通过
- 📕 **小红书**：**豆奶与程序猫**  
  搜索「豆奶与程序猫」关注，私信“邀请码”领学习资源  ·  [前往小红书关注 →](https://www.xiaohongshu.com/search_result?keyword=%E8%B1%86%E5%A5%B6%E4%B8%8E%E7%A8%8B%E5%BA%8F%E7%8C%AB)
- 📧 **合作 / 交流**：1019296134@qq.com

> 内容源自 [https://soycodetrail.top](https://soycodetrail.top)，转载请注明出处并保留上述联系方式。
