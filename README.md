# 相恋～直到 tokens 耗尽 · Love ~ Until Tokens Run Out

一款以 2026 年秋天旧金山 AI 编程工具大战为背景的浏览器视觉小说（Galgame）：28 天的赌约、每天早上的「Ship 还是 Reset」、下午 14:00 冒烟的机房、晚上 20:00 的约会，以及一张可以把时间拨回去的重置卡。

**在线游玩：** https://oneline2436.github.io/love-until-tokens-run-out/

## 玩法

- 每天 09:00 选择今天发布什么（正常 Ship / 夹带私货 / 全员 Reset）；平淡的日子会自动发布，可在 ≡ 菜单里关掉。
- 体力不够时，14:00 机房会冒烟，需要选择怎么撑到晚上的约会。
- 剧情抉择、因果点和记忆碎片共同决定 8 个结局；二周目还有隐藏结局。
- 存档、读档、CG 回想、音乐鉴赏与结局图鉴都保存在你自己的浏览器里。

快捷键：空格 / 回车推进，数字键选择，Esc 打开菜单。

## 本地运行

图片和音乐由 `index.html` 从 `assets/` 加载，需要通过本地服务器打开：

```bash
python -m http.server 8765
```

然后访问 http://localhost:8765 。运行时需要联网（React、Tailwind、Babel 从 CDN 加载）。

## 目录

- `index.html`：游戏本体（React 源码内联在页面里）
- `promo.html`：宣传片（标题页「观看宣传片」）
- `assets/`：立绘、背景、CG、UI 插画与配乐

## 声明

本作是虚构的同人喜剧作品。所有角色均为原创二次元形象，剧情纯属虚构，与现实中的任何人物、公司及其关系无关，也不代表任何公司的立场。

## 许可

MIT，见 [LICENSE](LICENSE)。
