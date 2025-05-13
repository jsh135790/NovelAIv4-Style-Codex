# NovelAIv4-Style-Codex

**A Tag-Collection about Artists, including 1000+ Single Artists tags.**

**一个包含1000多个单独画师标签的NovelAI v4风格代码库。**

## 📖 Introduction | 简介

NovelAIv4-Style-Codex is a comprehensive visual reference tool for the NovelAI v4 model's artist styles. This web-based application allows you to browse, compare, and save your favorite artist style tags from a collection of over 1000 artists.

NovelAIv4-Style-Codex 是一个全面的 NovelAI v4 模型画师风格参考工具。这个网页应用程序允许您从超过1000位画师的集合中浏览、比较和保存您喜欢的画师风格标签。

![Preview Image](https://files.catbox.moe/h2hxss.png)

## ✨ Features | 功能特点

- **Extensive Artist Collection** | **丰富的画师收藏**
  - 1000+ artist style tags to explore and experiment with
  - 1000多个画师风格标签供探索和实验

- **Visual Comparison** | **视觉对比**
  - See real examples of each artist's style applied to the same prompt
  - 查看每个画师风格应用于相同提示词的真实示例

- **Favorites System** | **收藏系统**
  - Save your favorite artists for quick access
  - 保存您喜欢的画师以便快速访问

- **Modern Interface** | **现代界面**
  - Dark mode design with smooth animations
  - 带有平滑动画的暗黑模式设计

- **Performance Optimized** | **性能优化**
  - Virtual scrolling for smooth browsing even with 1000+ artists
  - 虚拟滚动技术，即使有1000多位画师也能流畅浏览

- **Responsive Design** | **响应式设计**
  - Works on desktop and mobile devices
  - 适用于桌面和移动设备

## 🚀 Getting Started | 开始使用

### Online Access | 在线访问

NOT SUPPORTED

### Local Installation | 本地安装

1. Clone the repository | 克隆仓库
   ```bash
   git clone https://github.com/jsh135790/NovelAIv4-Style-Codex.git
   cd NovelAIv4-Style-Codex
   ```

2. Download the Assets | 下载资源
   
2. Unzip Assets into assets/ | 将资源解压至assets/文件夹
   
2. Open the project | 打开项目
   
   - Simply open `index.html` in your web browser
   - 只需在网页浏览器中打开 `index.html`

## 🎨 How to Use | 如何使用

1. **Browse Artists** | **浏览画师**
   - Scroll through the list to see different artist styles
   - 滚动列表查看不同的画师风格

2. **Add to Favorites** | **添加到收藏**
   - Click the heart icon to add an artist to your favorites
   - 点击心形图标将画师添加到您的收藏中

3. **Filter Favorites** | **筛选收藏**
   - Click "仅显示收藏" to see only your favorite artists
   - 点击"仅显示收藏"只查看您收藏的画师

4. **View Artist Images** | **查看画师图片**
   - Each artist has a sample image showing their style
   - 每位画师都有一个展示其风格的示例图片

5. **Return to Top** | **返回顶部**
   - Use the arrow button at the bottom right to quickly return to the top
   - 使用右下角的箭头按钮快速返回顶部

## 🔍 Understanding the Examples | 理解示例

All example images are generated with the following parameters:
所有示例图片都使用以下参数生成：

- **Base Model**: NovelAI v4
- **Steps**: 28
- **CFG**: 6
- **Size**: 832x1216
- **Sampler**: DPM++ 2M SDE

The prompt structure follows:
提示词结构如下：

```
girl, x-shaped pupils, long hair, short bangs, hairband, blazer, light blush, taut shirt
```

The only variable is the artist tag, allowing for direct style comparison.
唯一的变量是画师标签，这允许直接进行风格比较。

## 🛠️ Technical Details | 技术细节

### Project Structure | 项目结构

```
NovelAIv4-Style-Codex/
├── index.html        # Main HTML file | 主HTML文件
├── css/              # Stylesheet directory | 样式表目录
│   └── styles.css    # CSS styles | CSS样式
├── js/               # JavaScript directory | JavaScript目录
│   └── script.js     # Main script file | 主脚本文件
└── assets/           # Images and resources | 图片和资源
    └── ...           # Artist example images | 画师示例图片
```

### Technologies Used | 使用的技术

- **HTML5** - For structure | 用于结构
- **CSS3** - For styling and animations | 用于样式和动画
- **JavaScript** - For functionality and interaction | 用于功能和交互
- **LocalStorage** - For saving favorites | 用于保存收藏
- **Virtual Scrolling** - For performance optimization | 用于性能优化

## 💡 Tips for Prompting | 提示技巧

When using these artist tags in NovelAI:
在NovelAI中使用这些画师标签时：

- Add `artist:` before the artist name for stronger style influence
- 在画师名称前添加 `artist:` 以获得更强的风格影响

- Combine multiple artists with weights for mixed styles
- 结合多个画师并设置权重以混合风格

Example | 示例:
```
(artist:greg_rutkowski), (artist:artgerm)
```

## 📝 License | 许可证

This project is licensed under the Apache 2.0 License - see the LICENSE file for details.
该项目采用Apache 2.0许可证 - 详情请参阅LICENSE文件。

## 🙏 Acknowledgements | 致谢

- Thanks to the NovelAI team for the amazing v4 model
- 感谢NovelAI团队开发出色的v4模型

- Thanks to all the artists whose styles inspire AI art generation
- 感谢所有艺术家，他们的风格启发了AI艺术生成

---

Created with ❤️ for the AI art community

[资源下载(Google Drive)](https://drive.google.com/file/d/1EYEZIohV8ncX6N2UPLBT77AFtJL96_4o/view?usp=drive_link) | [Download Assets](https://drive.google.com/file/d/1EYEZIohV8ncX6N2UPLBT77AFtJL96_4o/view?usp=drive_link)

