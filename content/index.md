---
seo:
  title: Snowy Wiki
  description: SnowyMC 成立于 2022 年，专注于 Minecraft 服务器制作、插件开发与像素美术创作，致力于用技术与美学打造独特的游戏体验。
---

<style>
/* ===== Hero 背景变量 ===== */
:root {
  --hero-bg-start: #eef4ff;
  --hero-bg-mid: #f6f0ff;
  --hero-bg-end: #ffffff;
}

.dark {
  --hero-bg-start: #0b1020;
  --hero-bg-mid: #11142a;
  --hero-bg-end: #060814;
}

/* ===== 卡片基础 ===== */
.notion-card {
  background: rgba(255, 255, 255, 0.75);
  backdrop-filter: blur(10px);
  border-radius: 16px;
  border: 1px solid rgba(0, 0, 0, 0.06);
  box-shadow:
    0 1px 2px rgba(0,0,0,.04),
    0 8px 24px rgba(0,0,0,.04);
  transition: all .25s ease;
}

.notion-card:hover {
  transform: translateY(-3px);
  box-shadow:
    0 6px 20px rgba(0,0,0,.08),
    0 16px 40px rgba(0,0,0,.06);
}

.dark .notion-card {
  background: rgba(20, 22, 40, 0.65);
  border: 1px solid rgba(255,255,255,.08);
  box-shadow:
    0 1px 2px rgba(0,0,0,.4),
    0 8px 30px rgba(0,0,0,.35);
}

/* ===== Hero 背景 ===== */
.hero-bg {
  position: relative;
  overflow: hidden;
  background:
    radial-gradient(600px circle at 30% 20%, rgba(120,140,255,.18), transparent 60%),
    radial-gradient(500px circle at 70% 40%, rgba(180,120,255,.12), transparent 60%),
    linear-gradient(
      120deg,
      var(--hero-bg-start),
      var(--hero-bg-mid),
      var(--hero-bg-end)
    );
  background-size: 200% 200%;
  animation: heroFlow 40s ease-in-out infinite;
}

@keyframes heroFlow {
  0%   { background-position: 0% 50%; }
  50%  { background-position: 100% 50%; }
  100% { background-position: 0% 50%; }
}
</style>

::u-page-hero
---
align: center
class: "hero-bg py-20 px-6 rounded-2xl shadow-xl ring-1 ring-black/5 dark:ring-white/10"
---


#title
Snowy Wiki

#description
SnowyMC 的官方知识库与团队主页。自 2022 年起，我们专注 Minecraft 服务器搭建、插件开发与像素艺术创作，致力于用技术与美学打造高质量、沉浸式的游戏世界。

#links
  :::u-button
  ---
  color: primary
  size: xl
  to: /main/intro
  trailing-icon: i-lucide-arrow-right
  ---
  快速开始
  :::

  :::u-button
  ---
  color: neutral
  icon: simple-icons-github
  size: xl
  to: https://github.com/SnowyMCT
  variant: outline
  ---
  在 GitHub 上关注我们
  :::
::

---

::u-page-section
#title
我们的核心能力

#description
通过技术、创意与美术表达，为 Minecraft 玩家与服务器管理者提供完整解决方案。

#features
  :::u-page-feature
  ---
  class: "notion-card p-6"
  icon: i-simple-icons-minecraft
  target: _blank
  to: /server-setup
  ---
  #title
  服务器环境搭建
  #description
  从零开始搭建 Minecraft 服务器，支持多版本与跨平台部署。提供自动化安装脚本与详细教程，让你轻松打造稳定可靠的服务器环境。
  :::

  :::u-page-feature
  ---
  class: "notion-card p-6"
  icon: i-lucide-settings
  target: _blank
  to: /plugins
  ---
  #title
  插件开发与定制
  #description
  提供原版插件、拓展玩法系统以及定制化功能开发，满足内容创作与服务器业务发展需求。
  :::

  :::u-page-feature
  ---
  icon: i-lucide-palette
  class: "notion-card p-6"
  target: _blank
  to: /design
  ---
  #title
  像素美术与视觉设计
  #description
  提供 Minecraft 像素美术、界面与品牌设计服务，包含模型贴图、Logo、横幅等视觉素材，为你的服务器打造统一视觉语言。
  :::
::
---

::u-page-section
#title
为什么选择 SnowyMC？
#description
我们追求技术与艺术并重，打造一个真正用心的 Minecraft 生态。

#columns
  :::u-card
  ---
  icon: i-lucide-sparkles
  class: "notion-card p-6"
  ---
  #title
  经验丰富的技术团队
  我们的开发者在 MC 服务端、插件与界面设计领域拥有丰富经验。
  :::

  :::u-card
  ---
  icon: i-lucide-cpu
  class: "notion-card p-6"
  ---
  #title
  自动化与高标准文档
  全流程自动化、清晰的结构化文档，助你快速上手。
  :::

  :::u-card
  ---
  icon: i-lucide-users
  class: "notion-card p-6"
  ---
  #title
  社区驱动与持续更新
  我们持续维护文档内容，并倾听玩家与开发者的反馈。
  :::
::
