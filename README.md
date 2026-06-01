# ✨ 挑 战 6 1 ✨

<div align="center">

![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)
![Version](https://img.shields.io/badge/Version-1.0-purple?style=flat-square)

**🎮 一款考察反应速度的互动小游戏**

[🚀 立即体验](https://61-nu.vercel.app) • [📱 完全响应式](https://61-nu.vercel.app) • [🎨 多主题切换](https://61-nu.vercel.app)

</div>

---

## 🎯 游戏介绍

**挑战 61** 是一个简单却有趣的反应速度测试游戏。看你能否精准地在数字滚动到 **61** 时按下？

### 🎮 游戏规则
- 点击屏幕**任意位置**或按**空格键**启动数字滚动
- 在恰当的时机再次点击或按键停止
- 精准命中 **61** 获得胜利！🎉
- 还有其他隐藏反馈等你发现

### ⚡ 速度档位
| 档位 | 速度 | 适合 |
|------|------|------|
| 🚶 热身 | 慢 | 新手入门 |
| 🏃 奔跑 | 中 | **默认难度** |
| 🚀 飞驰 | 快 | 挑战自我 |
| ⚡ 闪电 | 极快 | 高手对决 |

---

## ✨ 功能特色

### 🎨 **多主题系统**
- 🔴 **综艺红黄** - 充满活力与激情（默认）
- 💫 **赛博霓虹** - 科技感、酷炫、炫彩
- 🌳 **森林绿橘** - 护眼、清新、自然
- 🪄 **魔法紫金** - 高级感、神秘、豪华

### 🎵 **沉浸式音效**
- ✅ 点击反馈音
- ✅ 数字滚动音
- ✅ 停止时音效
- ✅ 胜利宣传乐

### 🎆 **视觉特效**
- ✨ 冲击波动画
- 🎯 Q弹弹跳效果
- 🎊 胜利礼花满屏飞
- 🌈 主题色彩平滑过渡

### 📱 **完美适配**
- 💻 桌面大屏
- 📱 平板手机
- 🖥️ 超小屏幕
- ⌨️ 键盘 + 触屏双控制

---

## 🚀 快速开始

### 在线体验
直接访问 🔗 [https://61-nu.vercel.app](https://61-nu.vercel.app)

### 本地运行
```bash
# 克隆仓库
git clone https://github.com/adidalin/61.git
cd 61

# 用浏览器打开 index.html
# macOS
open index.html

# Windows
start index.html

# Linux
xdg-open index.html
```

### Docker 运行
```bash
# 使用 Python 简单服务器
python -m http.server 8000

# 然后访问 http://localhost:8000
```

---

## 🎮 操作指南

### 🖱️ **桌面版**
```
1. 点击屏幕 或 按【空格键】  →  启动游戏
2. 再次点击 或 按【空格键】  →  停止并显示结果
3. 点击右上角色块            →  切换主题
```

### 📱 **手机版**
```
1. 轻拍屏幕任意位置  →  启动游戏
2. 再次轻拍任意位置  →  停止并显示结果
3. 点击右上角色块    →  切换主题
```

---

## 💡 游戏提示

| 反应时间 | 评价 | 提示 |
|---------|------|------|
| **61** ⭐⭐⭐⭐⭐ | 完美命中！ | 🎉 祝贺！精准反应！ |
| **60-62** ⭐⭐⭐⭐ | 非常接近！ | 😫 就差一点点！ |
| **≤10** ⭐⭐⭐ | 反应太快 | 🍼 刚起步就按了 |
| **100** ⭐⭐⭐⭐⭐ | 完美满分 | 💯 100分反应！ |
| **其他** ⭐⭐⭐ | 继续加油 | 再试一次吧！ |

---

## 🛠️ 技术栈

- **HTML5** - 语义化标签 + Canvas绘图
- **CSS3** - Flexbox布局 + 响应式设计 + 复杂动画
- **JavaScript** - 原生 Web Audio API + 游戏逻辑
- **零依赖** - 纯前端实现，无需任何框架

### 核心特性
- 🎵 **Web Audio API** - 实时音效生成
- 🎨 **CSS Variables** - 动态主题切换
- 📐 **Canvas API** - 礼花特效渲染
- ⚙️ **requestAnimationFrame** - 高性能动画

---

## 📊 项目结构

```
61/
├── index.html          # 完整游戏文件（HTML + CSS + JS）
└── README.md          # 项目文档
```

> 💡 采用单文件设计，部署简单高效！

---

## 🎯 适用场景

- 🏫 **教室互动** - 课间反应速度竞赛
- 🎓 **团建活动** - 办公室团队较量
- 🎉 **派对游戏** - 朋友聚会的趣味项目
- 📺 **大屏展示** - 希沃电子白板集成
- 💪 **自我挑战** - 锻炼反应能力

---

## 🎨 自定义主题

编辑 `index.html` 中的 CSS 变量即可自定义主题：

```css
:root {
    --bg-gradient: radial-gradient(circle at center, #2c3e50 0%, #000000 100%);
    --box-bg: #ffffff;
    --box-border: #ff4757;
    --number-color: #ffdd59;
    /* 更多变量... */
}
```

---

## 📦 浏览器兼容性

| 浏览器 | 支持 | 备注 |
|-------|------|------|
| Chrome/Edge | ✅ | 推荐使用 |
| Firefox | ✅ | 完全支持 |
| Safari | ✅ | iOS 12+ |
| Opera | ✅ | 完全支持 |

---

## 🤝 贡献指南

欢迎提交 Issue 和 Pull Request！

```bash
# 1. Fork 此仓库
# 2. 创建特性分支 (git checkout -b feature/amazing)
# 3. 提交更改 (git commit -m 'Add amazing feature')
# 4. 推送到分支 (git push origin feature/amazing)
# 5. 开启 Pull Request
```

---

## 📄 许可证

MIT License © 2025 adidalin

---

## 🌟 致谢

感谢所有用户的支持和反馈！

<div align="center">

**😊 希望你玩得开心！**

⭐ 如果这个项目对你有帮助，请给个 Star 吧！

</div>
