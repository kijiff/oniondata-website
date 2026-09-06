# oniondata.tech 视觉重制指令 — 深色科技风

## 目标
只动视觉，把"品牌感卡片风"整体换成"深色科技风"，主色科技蓝 #3C7EFF。
内容 / 文案 / 链接 / 板块结构一字不动，不加任何新功能板块。

## 配色 Token（全量替换）
| Token | 旧值 | 新值 |
|-------|------|------|
| 页面背景 | #F7F8FA | #1D2129 |
| 卡片背景 | #FFFFFF | #2A2F38 |
| 分割线 | #E5E6EB | #373C45 |
| 品牌主色 | #165DFF | #3C7EFF |
| 主色 hover | #3C7EFF | #5B93FF |
| 标题字色 | #1D2129 | #FFFFFF |
| 次级文字 | #4E5969 | #C9CDD4 |
| 辅助文字 | #86909C | #86909C |
| 正文 | #4E5969 | #C9CDD4 |

## 必须改的硬编码色
- 卡片阴影：rgba(29,33,41,0.12) → rgba(0,0,0,0.4)
- .about__tag 背景：rgba(22,93,255,0.08) → rgba(60,126,255,0.15)，文字 #3C7EFF
- .work-card__icon 背景：rgba(22,93,255,0.1) → rgba(60,126,255,0.15)
- .work-card__platform 背景：var(--color-bg) → #1D2129
- .capability__icon 背景：var(--color-title) → #3C7EFF
- .capability__summary 左边框：var(--color-primary) → #3C7EFF
- .btn--ghost：边框和文字用 #3C7EFF，hover 背景 rgba(60,126,255,0.1)
- .cert-card border-top：#3C7EFF
- .contact__item-value：#FFFFFF
- .footer 背景：#171A1F，border-top #373C45
- .nav 背景：#1D2129，border-bottom #373C45

## 新增装饰
1. 页面细网格背景：body 加 background-image 细网格（rgba(60,126,255,0.04) 线条，40px 间距），不影响可读性。
2. Hero 数据节点连线 SVG：在 .hero 内加一个绝对定位的 SVG（position:absolute，z-index:0），画若干小圆节点 + 连线，科技蓝半透明，作为背景装饰。文案层 z-index 高于 SVG。

## 禁止
- 不改任何中文文案、链接、板块数量、HTML 结构（除加 Hero SVG 装饰外）。
- 不引入外部资源。
- 不加新功能、新按钮、新板块。
