# Avatar Battle Game

[▶ 立即游玩](https://childweii.github.io/Avatar-Battle-Game/)

[English](README.md) | **中文**


一个**纯前端、单文件**的小型对战游戏：两枚**图片头像**在场内弹跳、拾取道具并博弈。  
本项目是对原始 **[Emoji Battle Game](https://childweii.github.io/Emoji-Battle-Game/)** 的**重写与扩展**。

> 来源：玩法/机制来自 [Emoji 版本](https://childweii.github.io/Emoji-Battle-Game/)

---

## 相比 Emoji 版本的更新

- **图片头像 + 方形裁剪**  
  支持任意图片上传；在方形视口中**拖拽平移**、**滚轮/滑条缩放**，导出到 canvas。全程本地处理，无需服务器。

- **本地化与轻量**  
  头像与名字仅存在于浏览器内存/canvas；不上传、不持久化。

- **自动本地化（中/英）**  
  根据 `navigator.language` 自动选择 **中文**或**英文**。

- **更简洁的开局**  
  不再有“选阵营”步骤；上传头像 + 命名本身就定义了双方。

- **更简洁的结算**  
  只展示**胜者**（或**平局**），视觉更干净。

- **玩法等效**  
  道具机制与 Emoji 版保持一致；完整道具与说明请直接查看 **[Emoji Battle Game](https://childweii.github.io/Emoji-Battle-Game/)**：  

---

## 快速开始

1. 克隆或下载本仓库。
2. 用现代浏览器直接打开 `index.html`。  

### 游戏玩法
1. 分别上传两张头像，可选填名字（≤ 10 字）。
2. 点击 **开始**。
3. 观战，看它们拾取道具并博弈。
4. 底部 **❔** 按钮会在冷却结束后随机生成一个道具或场地效果。

### 语言说明
- UI 会根据 `navigator.language` 自动选择**中文**或**英文**。
- 为保持界面极简，没有提供手动切换。

### 隐私
- 无网络请求、无存储。刷新或关闭页面即清空。

---

## 部署到你的 GitHub Pages

1. 将仓库推送到 GitHub（默认分支 `main`）。
2. 打开 **Settings → Pages**，设置 **Source** 为 `Deploy from a branch`，**Branch** 选择 `main` 与 `/ (root)`。
3. 等待构建完成，站点地址为：  
   `https://<你的用户名>.github.io/<你的仓库名>/`
4. 回到本文件更新**在线演示**链接。

---

## 许可证

本项目采用 **MIT 许可证**（见 [`LICENSE`](LICENSE)）。  
许可证包含一段对 **Emoji Battle Game** 的来源致谢说明。
