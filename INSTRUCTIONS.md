# oniondata.tech 洋葱数据公司官网 — Trae 执行指令

## 铁律（先读再改）
1. 只按本指令创建下列文件，**不要新增任何功能、板块、页面、按钮**。
2. **不引入框架**（Vue/React/Next.js），纯 HTML + CSS + 原生 JS。
3. 不引用外部字体/图片 CDN（应用商店图标除外），保证国内可访问。
4. 所有中文文案一字不改（用户定稿）。
5. 不生成/引用未提供的图片资源，图标用占位。

## 项目概述
静态单页公司官网，品牌「洋葱数据 Onion Data」，归属宁夏洋葱数据服务有限公司，域名 oniondata.tech。单页滚动式，7 个板块。

## 文件结构
- `index.html` — 主页面
- `assets/style.css` — 样式（品牌感卡片风）
- `assets/logo.svg` — 品牌 logo（简化洋葱图形 + "洋葱数据"）

## 设计规范（品牌感卡片风）
| Token | 值 |
|-------|----|
| 页面背景 | #F7F8FA |
| 卡片 | #FFFFFF，8px 圆角，0 4px 16px rgba(29,33,41,0.12) |
| 品牌主色 | #165DFF（单一 token，可整体替换） |
| 主色 hover | #3C7EFF |
| 标题字色 | #1D2129 |
| 次级文字 | #4E5969 |
| 辅助文字 | #86909C |
| 分割线 | #E5E6EB |
| 正文 | 14px/22px，#4E5969 |
| H1 | 28px/600；H2 20px/500；H3 16px/500 |
| 字体 | PingFang SC / Microsoft YaHei / system-ui / sans-serif |
| 布局 | 顶部 sticky 导航，单列流式，内容最大宽 1080px 居中，卡片间距 > 卡片内间距 |

禁止：emoji、大红大金、复杂渐变。

## 板块与内容（逐条，勿漏）

### 1. 顶部导航（sticky）
左：logo「洋葱数据 Onion Data」；右：锚点 公司 / 作品 / 能力 / 资质 / 联系

### 2. Hero
- 主标题：洋葱数据
- 副标题：宁夏的 AI 应用开发与数据服务公司
- 副文案：专注人工智能应用软件与大数据服务，提供数据处理、信息系统集成，以及鸿蒙/安卓多语种智能应用开发。
- CTA：查看作品（锚点）/ 联系我们（锚点）

### 3. 公司简介
- 标题：关于我们
- 正文：宁夏洋葱数据服务有限公司，专注人工智能应用软件开发与数据服务，深耕大数据、数据处理与信息系统集成，已取得安卓与鸿蒙开发资质，为深圳数据交易所数据商。
- 标签：宁夏 · 银川

### 4. 作品（5 个卡片）
每个卡片：圆形占位图标、名称、平台标签、一句话功能、跳转链接
1. 中级会计刷题宝｜鸿蒙｜中级会计职称考试备考刷题工具｜https://appgallery.huawei.com/app/detail?id=com.wecan.zjkjstb&channelId=SHARE&source=appshare
2. 时见（TimeAware）｜鸿蒙｜AI 数字生活教练，帮你重新看见并赢回自己的时间｜https://appgallery.huawei.com/app/detail?id=com.wecan.TimeBank&channelId=SHARE&source=appshare
3. 杞遇世界（GojiWorld）｜鸿蒙｜枸杞产业多语种智能接待｜https://appgallery.huawei.com/app/detail?id=com.wecan.GojiWorld&channelId=SHARE&source=appshare
4. 惊殊翻译（TerroirTalk）｜鸿蒙｜葡萄酒行业多语种智能接待｜https://appgallery.huawei.com/app/detail?id=com.wecan.TerroirTalk&channelId=SHARE&source=appshare
5. CTH / China Travel Helper｜Google Play｜来华外国游客的中国旅行翻译助手｜https://play.google.com/store/apps/details?id=com.wecan.chinatravelhelper

### 5. 开发能力
- 卡片：GitHub「kijiff」— https://github.com/kijiff — 公司技术项目开源仓库
- 简述：鸿蒙原生 / Android 原生 / 静态 Web 开发

### 6. 资质（3 张卡片）
1. 鸿蒙开发认证｜华为｜企业开发者 ID 30086000567322799
2. 安卓开发资质｜Google Play 开发者账号 wecan2026（组织账号，ID 5567124822332367198）
3. 数据商资质｜深圳数据交易所数据商（账号 ZHM18895298590）

### 7. 联系方式
- 邮箱：info@oniondata.tech
- 电话：18895298590
- 宁夏 · 银川

### 8. 页脚
© 2026 宁夏洋葱数据服务有限公司 · 洋葱数据 Onion Data
