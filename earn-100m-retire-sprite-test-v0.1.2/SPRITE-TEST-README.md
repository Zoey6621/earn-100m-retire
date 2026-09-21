# 咪与母鸡游戏精灵测试

这是《赚够一亿就退休》的独立美术测试，不会修改正式游戏。

## 文件

- `sprite-preview.html`：动作与实际游戏尺寸预览页（已内嵌全部图形，可单文件打开）
- `farm-sprite-test.svg`：透明 SVG Symbol 素材
- `sprite-test.json`：动作帧、速度、坐标和脚底锚点配置

## 预览

只需打开或上传 `sprite-preview.html` 就能查看预览。V0.1.2 不再使用浏览器兼容性不稳定的 SVG `<use>` 渲染，而是把矢量路径直接复制到可见角色中。`farm-sprite-test.svg` 和 `sprite-test.json` 是之后嵌入游戏时使用的独立素材与配置。

如果上传至 GitHub 仓库根目录，可访问：

`https://zoey6621.github.io/earn-100m-retire/sprite-preview.html`

## 当前动作

- 咪：待机、行走 2 帧、坐下、睡觉
- 母鸡：待机、行走 2 帧、啄食

所有精灵使用统一 `64 × 64` viewBox，脚底锚点为 `(32, 54)`，正式游戏预计显示尺寸约为 `44px`。
