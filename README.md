# 月隐·微光旅途

[▶ 在线试玩](https://mumumuqingnuan.github.io/microglow-journey/) · [GitHub 仓库](https://github.com/mumumuqingnuan/microglow-journey)

36 张图像卡组成的互动网页，包含一张微光、三张卡故事漫游与五步手记，以及洗牌、放大翻牌、光晕粒子、全屏、音乐、手记保存和结果图导出。

## 故事漫游 v1.1

出发前选择“交给旅途”“来一点奇遇”“想被轻轻接住”或“给我点惊喜”。六段不同的旅途包含十八个分支结局：潮汐邮局、落日列车、雨天面包店、失物旅馆、交换月亮的夜市、会迷路的地图。

第一张卡带来启程风景并影响旅途，第二张卡打开两条可选岔路，第三张卡带来专属小礼物。选择会改变故事中的事件与结局，完成后可回看另一条路。故事、选择和纪念物随手记保存；之前保存的旧版故事保留原文。

## 文件

- `index.html`：可独立运行的完整网页，卡面、样式和脚本均已内嵌。
- `microglow-journey-source.zip`：当前版本可编辑源代码。故事内容位于 `src/storyContent.js`，故事生成与保存位于 `src/story.js`。

## 运行与维护

直接用浏览器打开 `index.html`，或访问上方试玩链接。GitHub Pages 使用 **Deploy from a branch → main → / (root)**。

解压源码后运行 `npm ci`，使用 `npm run dev` 预览；`npm run build:pages` 生成 `pages/index.html`。使用 `npm run test:story` 和 `npm run test:sites` 验证故事与构建。维护时同步更新根目录网页与源代码 ZIP。

手记保存在当前浏览器；结果图片可下载，也可在支持的设备上分享。本应用以图像联想与虚构故事为内容。本仓库独立于 `moonveil-tarot`。
