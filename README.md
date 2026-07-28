# 🖼️ sgao-images

Personal image asset repository for **sgao.cc**.

用于存储网站、文档以及项目中使用的图片资源，并通过 Cloudflare CDN 提供高速访问。


## ✨ Features

- 集中管理图片资源
- 支持网站静态图片引用
- 配合 Cloudflare CDN 加速访问
- 简单、稳定、低成本
- 适合作为个人项目图片仓库


## 🏗️ Architecture

```
Website / Documentation
          │
          ▼
     Image URL
          │
          ▼
      Cloudflare CDN
          │
          ▼
     sgao-images
```


## 📂 Directory Structure

```
sgao-images
│
├── cloudflare/
│   ├── example.png
│   └── ...
│
├── website/
│   └── ...
│
└── README.md
```


## 🌐 Image CDN

Images are delivered through:

```
https://img.sgao.cc
```


Example:

```
https://img.sgao.cc/cloudflare/example.png
```


## 🔗 Related Projects


### sgao.cc

Personal website:

https://sgao.cc


### sgao-website

Website source code:

https://github.com/skylonely/sgao-website


### sgao-image-center

Image service and management center:

https://github.com/skylonely/sgao-image-center


## 📝 Usage

Add images to this repository, then access them through the CDN URL.

Example:

```html
<img src="https://img.sgao.cc/cloudflare/example.png">
```


## 📌 Notes

This repository only stores image assets.

Image processing and management logic are handled by:

`sgao-image-center`


---

Built with ❤️ by skylonely