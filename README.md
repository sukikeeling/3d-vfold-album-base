# 📖 3D V-Fold Interactive Scrapbook Base (3D 折叠手账画廊纯净底座)

A pure, zero-dependency, single-file 3D folding scrapbook engine built with pure CSS 3D Transforms, custom SVG turbulence watercolor ink-bleed filters, and an embedded vinyl disc audio controller.

> **Designed with love & engineering precision by 阿宁 (sukikeeling).**

---

## ✨ Features (核心亮点)

- **Pure Single-File Zero Dependency (纯单文件零依赖)**: Everything is encapsulated in a single HTML file — styles, 3D transform logic, SVG filters, fonts, and inline Base64 Jay Chou micro-disc soundtrack (~1.14MB).
- **Physical 3D V-Fold Architecture (3D V型折叠连环画卷)**:
  - `perspective: 2400px` & `transform-style: preserve-3d`.
  - Realistic 30° V-fold fanning with continuous depth staging.
  - Progressive two-step page turning: covers turn with smooth rotation, while white cards flatten with a subtle viewing angle (`rotateX(-10deg) rotateY(5deg)`) for optimal viewing.
- **SVG Watercolor & Crayon Shader (水彩渗墨与蜡笔肌理滤镜)**:
  - Custom `feTurbulence` & `feDisplacementMap` procedural shaders simulating rough handmade paper and edge bleed.
- **Collapsible Music Disc Player (悬浮黑胶唱片微型音乐控制器)**:
  - Right-docked collapsible vinyl record.
  - Automatically plays soft romantic acoustic guitar soundtrack upon turning pages.
- **Modular Blank Photo Slots (即插即用照片槽位)**:
  - Four `.photo-slot` containers designed to hold user photos, polaroid cards, or digital illustrations.

---

## 🚀 Quick Start (快速上手)

Just double-click `index.html` or `crayon_v_fold_base.html` in any modern web browser (Chrome, Edge, Safari, Firefox). No build tools, Node.js, or local servers required.

### 🖼️ Inserting Custom Photos (填充专属照片)

Find the `.photo-slot` elements on `Card 1`, `Card 3`, `Card 5`, and `Card 7`, and replace the contents with your own `<img>` tags or Base64 data URIs:

```html
<div class="photo-slot">
  <img src="your_photo_path.jpg" alt="Memory Photo" />
</div>
```

---

## 📜 License

MIT License. Crafted with romance and technical devotion.
