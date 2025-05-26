---
title: My Third Post1
subtitle: 
date: 2025-05-25T05:34:53+08:00
slug: "3"
author:
  name: 
  link: 
  email: 
  avatar: 
description: 
keywords: 
license: 
comment: false
weight: 0
tags:
  - 收藏贴
categories:
  - 旅游
hiddenFromHomePage: false
hiddenFromSearch: false
hiddenFromRelated: false
hiddenFromFeed: false
summary: 
resources:
  - name: featured-image
    src: featured-image.jpg
  - name: featured-image-preview
    src: featured-image-preview.jpg
toc: true
math: false
lightgallery: false
password: 
message: 
repost:
  enable: true
  url:
---
# 🌄 马克飞象的奇幻漂流：多媒体写作指南

![高山湖泊封面](https://images.unsplash.com/photo-1506748686214-e9df14d4d9d0?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=70)
*▲ 图1：瑞士高山湖泊实景（Unsplash来源）*

## 一、核心语法速查

### 1.1 文字特效
- **重点强调**：`**粗体**` 或 `__粗体__`
- *优雅斜体*：`*斜体*` 或 `_斜体_`
- ~~过时内容~~：`~~删除线~~`
- `行内代码`：`` `代码` ``
<!--more-->
### 1.2 列表系统
```markdown
- [x] 任务列表
- [ ] 未完成项
  - 子项目（缩进2空格）
1. 有序列表
2. 第二项
```

## 二、多媒体完美嵌入

### 2.1 图片最佳实践
**网络图片**（推荐图床）：
```markdown
![熊猫吃竹](https://example.com/panda.jpg "宽度自动适应")
```
**本地图片**（相对路径）：
```markdown
![我的猫](./my-cat.jpg "宽度建议不超过800px")
```

### 2.2 视频解决方案
#### 方案A：通用外链
```markdown
[▶️ 点击观看黄石公园4K视频](https://example.com/yellowstone.mp4)
```

#### 方案B：平台特供
```html
<!-- 支持HTML的平台（如自建博客） -->
<div style="position: relative; padding-bottom: 56.25%; height: 0;">
  <iframe src="//player.bilibili.com/player.html?aid=xxxx" 
          style="position: absolute; width: 100%; height: 100%;" 
          frameborder="0" allowfullscreen>
  </iframe>
</div>
```

#### 方案C：YouTube优雅嵌入
```markdown
[![视频封面](https://img.youtube.com/vi/dQw4w9WgXcQ/maxresdefault.jpg)](https://youtu.be/dQw4w9WgXcQ)
```

## 三、高级排版技巧

### 3.1 响应式表格
| 设备  | 分辨率       | 支持格式     |
| --- | --------- | -------- |
| 手机  | 1080×1920 | MP4/WebM |
| 平板  | 2048×1536 | MOV/AVI  |
| 桌面  | 4K        | 全部       |

### 3.2 折叠内容块
<details>
<summary>点击展开技术细节</summary>

```javascript
// 视频检测函数
function canPlayVideo(type) {
  const video = document.createElement('video')
  return !!video.canPlayType(`video/${type}`)
}
```
</details>

## 四、平台适配指南

| 平台     | 图片支持    | 视频方案     |
| ------ | ------- | -------- |
| GitHub | ✓ 网络图片  | 外链跳转     |
| 语雀     | ✓ 本地/网络 | iframe嵌入 |
| Notion | ✓ 拖拽上传  | 原生嵌入     |
| Hexo博客 | ✓ 图床最佳  | HTML标签   |

> 💡 **最佳实践建议**：
> 1. 图片使用CDN加速（如[Imgur](https://imgur.com/)）
> 2. 视频优先考虑B站/YouTube等平台托管
> 3. 复杂排版建议先用[Markdown预览工具](https://markdownlivepreview.com/)测试

<!--more-->
