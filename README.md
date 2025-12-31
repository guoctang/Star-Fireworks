# ✨ 星映焰火 Star Fireworks

> 🎆 Interactive Fireworks Celebration for New Year 2026
>
> 一个精美的互动式烟花庆祝页面，为2026年元旦打造的视听盛宴。

![Release](https://img.shields.io/badge/Release-1.0-blue.svg)

## 🔗 在线演示

- **[戳我体验](https://fireworks.chenyande.com/)** - 直接在浏览器中打开

## 🎆 项目特色

### 视觉效果
- 🌟 **璀璨星空背景** - 动态闪烁的星星营造浪漫氛围
- 🎇 **真实烟花动画** - 从底部发射，空中绽放，物理引擎模拟
- ✨ **发光轨迹** - 烟花升空时的拖尾效果
- 💫 **天空照明** - 爆炸瞬间的背景闪光效果
- 🎨 **多彩粒子** - 六种随机颜色的火花粒子系统

### 音效体验
- 🚀 **发射音效** - "唷~" 的升空呼啸声
- 💥 **爆炸音效** - "嘭~啪~" 的真实爆裂声
- ✨ **火花音效** - "嗤嗤嗤..." 的余音效果
- 🔊 **Web Audio API** - 纯代码生成，无需外部音频文件

### 交互功能
- ⏰ **新年倒计时** - 实时显示距离新年的剩余时间
- 🖱️ **点击发射** - 点击屏幕任意位置发射烟花
- ⚙️ **自定义设置** - 调节烟花大小、数量、自动发射等
- 📱 **响应式设计** - 完美适配手机和电脑

### 动画细节
- ⌨️ **打字机效果** - 祝福语逐字显现
- 🌊 **淡入动画** - 页面元素优雅登场
- ✨ **文字发光** - 标题呼吸式光晕效果
- 🎪 **弹跳提示** - 底部提示文字动态跳跃

## 🚀 快速开始

### 方式一：直接打开
1. 下载或克隆本项目
2. 在浏览器中打开 `index.html` 即可

### 方式二：部署到 Vercel

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fguoctang%2FStar-Fireworks)

### 方式三：部署到 Netlify

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https%3A%2F%2Fgithub.com%2Fguoctang%2FStar-Fireworks)


### 方式四：本地服务器
```bash
# 使用 Python 启动
python -m http.server 8080

# 使用 Node.js (需要安装 http-server)
npx http-server -p 8080

# 访问
http://localhost:8080
```

## 🎮 使用说明

### 基础操作
- **点击屏幕** - 在点击位置发射烟花
- **连续点击** - 制造烟花连击效果
- **右下角设置** - 打开设置面板

### 设置选项
- **烟花大小** - 调节爆炸时的粒子扩散范围（50-150%）
- **烟花数量** - 每次发射的烟花数量（1-5个）
- **自动发射** - 每秒自动在随机位置发射烟花
- **音效开关** - 开启/关闭发射和爆炸音效

## 🎨 技术实现

### 前端技术栈
- **HTML5 Canvas** - 烟花粒子系统渲染
- **CSS3 动画** - 文字效果、星空背景、过渡动画
- **原生 JavaScript** - 无任何框架依赖
- **Web Audio API** - 实时音频合成

## 📱 浏览器兼容性

| 浏览器 | 版本 | 支持情况 |
|--------|------|---------|
| Chrome | 60+ | ✅ 完美支持 |
| Firefox | 55+ | ✅ 完美支持 |
| Safari | 11+ | ✅ 完美支持 |
| Edge | 79+ | ✅ 完美支持 |
| 移动浏览器 | - | ✅ 完美支持 |

> 注：需要浏览器支持 Canvas、ES6、Web Audio API

## 🎯 特性详解

### 1. 倒计时功能
- 自动计算距离2026年元旦的剩余时间
- 0天时只显示时分秒格式
- 到达新年自动显示祝福并启动烟花

### 2. 物理引擎
- 真实的重力和摩擦力模拟
- 平滑的抛物线轨迹
- 自然的速度衰减

### 3. 视觉优化
- 渐变夜空背景
- 毛玻璃效果设置面板
- 烟花爆炸时的天空照明
- 火箭发射的白色发光效果

### 4. 性能优化
- Canvas 双缓冲渲染
- 过期粒子自动清理
- 轨迹数组长度限制
- 高效的动画循环

## 🎁 祝福语

```
祝你：
所期皆所念 所念皆所愿
所愿皆所得 所得皆所盼
唯愿烟花像星辰 祝你所愿皆成真 ✨
```

## 📄 许可证

本项目采用 MIT 许可证，可自由使用和修改。

## 🙏 致谢

感谢你的使用！祝你2026年元旦快乐，新年新气象！🎊

---

💝 如果喜欢这个项目，欢迎 Star ⭐

🎉 Happy New Year 2026! 🎉


---
## 📌 关于我
- 作者: [陈延德](https://www.chenyande.com)
- 邮箱: [me@chenyande.com](mailto:me@chenyande.com)
- 站点: [https://www.chenyande.com](https://www.chenyande.com)

Copyright © 2025 陈延德. 保留所有权利