# 百廿红模板素材

源文件：`1.百廿红-李一.pptx`

- 源文件 SHA-256：`32bcf709cc46f1824f58cb23c662e9795f7bef71cc06b8a41f6f3f08d4f21ae9`
- 画布：16:9，21 页
- PPTX 媒体：29 个常规位图 + 3 个 WDP；没有 SVG、EMF 或 WMF
- 本目录保留：20 个原始素材 + 1 个 WDP 的浏览器可用无损 PNG
- 所有原始素材均从 PPTX 按字节直接抽取，没有缩放、重压缩或改色

## 建议复用的素材

| 文件 | 所属页 | 用途 | 像素/格式 | CSS/SVG 重画判断 |
|---|---:|---|---:|---|
| `brand/sjtu-seal-red.png` | 14、15、16 | 红色独立校徽；母版一级项目符号 | 142×142 | 不建议重画；应复用官方标志或官方矢量版本 |
| `brand/sjtu-seal-white.png` | 15、20、21 | 白色独立校徽 | 130×130 | 不建议重画；应复用官方标志或官方矢量版本 |
| `brand/sjtu-lockup-red-horizontal.png` | 1、3、5、6、14、18 | 红色横排校徽＋中英文校名 | 1135×373 | 不建议重画；应复用官方标志或官方矢量版本 |
| `brand/sjtu-lockup-red-stacked.png` | 7、8、17、19 | 红色上下组合校徽＋中英文校名 | 924×648 | 不建议重画；应复用官方标志或官方矢量版本 |
| `brand/sjtu-lockup-white-horizontal.png` | 4 | 白色横排校徽＋中英文校名 | 522×171 | 不建议重画；应复用官方标志或官方矢量版本 |
| `ornaments/historic-gate-red.png` | 1、6、7、8、12、19 | 交大历史校门红色线稿 | 2668×859 | 可人工描摹为 SVG，但不适合纯 CSS；当前应保留原图 |
| `ornaments/footer-skyline-red.png` | 1、2、3、5、6、10、11、13、14、16 | 红色超宽页脚线与校园天际线 | 6485×216 | 直线可用 CSS，天际线宜保留原图或转描 SVG |
| `ornaments/footer-skyline-white.png` | 4、15、20、21 | 白色超宽页脚线与校园天际线 | 6485×216 | 直线可用 CSS，天际线宜保留原图或转描 SVG |
| `ornaments/motto-gray.png` | 1、19 | 灰色“饮水思源・爱国荣校”校训字样 | 900×124 | 可用文本近似，但字距与字形要完全一致时应复用原图 |
| `ornaments/motto-gray-wide.png` | 6 | 带左右细线的灰色校训横条 | 1241×66 | 左右线可用 CSS；校训字样可复用 motto-gray 或此原图 |
| `backgrounds/lowpoly-white.png` | 11 | 白灰低多边形底纹 | 1333×750 | 可用 SVG polygon 或 CSS clip-path 重画 |
| `photos/page-02-historic-building.jpeg` | 2 | 老建筑红楼照片 | 2932×1955 | 不能用 CSS/SVG 重画 |
| `photos/page-03-modern-building.jpeg` | 3 | 现代白色建筑照片 | 2493×1651 | 不能用 CSS/SVG 重画 |
| `photos/page-04-08-nanyang-monument.jpg` | 4、8 | 南洋公学纪念碑与校园照片 | 4256×2832 | 不能用 CSS/SVG 重画 |
| `photos/page-05-stadium.jpeg` | 5 | 体育馆夜景照片 | 2472×1648 | 不能用 CSS/SVG 重画 |
| `photos/page-06-campus-building.jpeg` | 6 | 校园教学楼正立面照片 | 2629×1979 | 不能用 CSS/SVG 重画 |
| `photos/page-07-gate-lion.jpg` | 7 | 校门石狮照片 | 1600×1066 | 不能用 CSS/SVG 重画 |
| `photos/page-11-campus-panorama.jpg` | 11 | 校园俯瞰全景照片 | 4256×2832 | 不能用 CSS/SVG 重画 |
| `backgrounds/page-12-campus-aerial-blurred.png` | 12 | 第 12 页实际使用的模糊校园航拍背景 | 2928×2196 | 可由清晰源图配合 CSS filter: blur() 重建；精确复刻可直接复用 |
| `source-originals/page-12-campus-aerial-sharp.wdp` | 12 | 第 12 页模糊背景的清晰 WDP 原始层 | 原始格式 | 原图本身不能重画；网页端建议使用同目录转换出的 PNG |
| `backgrounds/page-12-campus-aerial-sharp.png` | 12 | 第 12 页清晰校园航拍背景的浏览器可用 PNG | 2928×2196 | 不能用 CSS/SVG 重画；可在此清晰图上用 CSS blur() 复现原页 |

## 不应作为独立主题素材复制的对象

| PPTX 原媒体 | 所属页 | 处理判断 |
|---|---:|---|
| `ppt/media/image3.png`、`ppt/media/image11.png` | 1、3、5、6、14 | 低分辨率红色横排校标，已由 image15 高分辨率版本替代。 |
| `ppt/media/image10.png`、`ppt/media/image16.png` | 7、8、19 | 低分辨率红色上下组合校标，已由 image14 高分辨率版本替代。 |
| `ppt/media/image9.png`、`ppt/media/image26.png` | 7、8、12 | 低分辨率历史校门线稿，已由 image2 高分辨率版本替代。 |
| `ppt/media/hdphoto1.wdp` | 4 | image6 白色校标的红色效果源；现有高分辨率红色校标更适合复用。 |
| `ppt/media/hdphoto2.wdp` | 4、15、20、21 | image7 白色页脚的红色效果源；与保留的 image4 红色页脚重复。 |
| `ppt/media/image23.png` | 10 | 第 10 页“目录”合成卡片；应使用保留的校标/校门素材和可编辑 CSS 文本重建。 |
| `ppt/media/image27.png` | 20 | 第 20 页模板缩略图截图，仅用于说明文档，不是主题素材。 |
| `ppt/media/image28.png`、`ppt/media/image29.png` | 21 | 第 21 页 PowerPoint 配色设置截图，仅用于说明文档，不是主题素材。 |

## 重建原则

1. 品牌标志、历史校门线稿和照片直接复用本目录素材；不要手绘校徽。
2. 红色 `#C8161E` 色块、灰白底、斜切图片窗、细边框、编号、渐变带和第 19 页白色折线都用 CSS 重建。
3. 第 9 页四个建筑轮廓图标是 OOXML 自由曲线，适合人工转写为 SVG，不需要截图。
4. 第 10 页“目录”图是已有素材的合成结果，应用 CSS + 可编辑文本 + 本目录品牌素材重建。
5. 第 12 页可直接使用模糊 PNG 精确复刻；更推荐用清晰 PNG 加 `filter: blur(...)`，并保留 WDP 作为原始归档。

完整 SHA、来源成员、替代关系及页面映射见 `manifest.json`。
