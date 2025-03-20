# webp2png
# WebP to PNG Converter

一个简单易用的在线 WebP 图片批量转换工具，可以将 WebP 格式的图片转换为 PNG 格式。无需安装任何软件，直接在浏览器中运行。

## 功能特点

- 🖼️ 支持批量转换 WebP 图片到 PNG 格式
- 📱 响应式设计，支持移动端和桌面端
- 🔄 拖拽上传文件
- 👀 文件预览功能
- 📦 支持单个下载和批量下载
- 💾 提供 ZIP 打包下载选项
- ⚡ 纯浏览器端处理，无需服务器
- 🔒 安全可靠，所有处理都在本地完成

## 使用方法

1. 打开 `webp_to_png_converter.html` 文件在浏览器中运行
2. 通过以下两种方式添加文件：
   - 将 WebP 文件拖放到指定区域
   - 点击"选择文件"按钮手动选择文件
3. 点击"开始转换"按钮
4. 选择下载方式：
   - 单个文件下载
   - 一键下载所有文件
   - ZIP 打包下载

## 技术栈

- HTML5
- CSS3
- JavaScript (ES6+)
- [JSZip](https://stuk.github.io/jszip/) - 用于生成 ZIP 文件

## 浏览器兼容性

- Chrome (推荐)
- Firefox
- Safari
- Edge

## 本地开发

1. 克隆仓库
2. 确保 `jszip.min.js` 文件可以正常加载
3. 在浏览器中打开 `webp_to_png_converter.html`

## 许可证

MIT License

## 贡献

欢迎提交 Issue 和 Pull Request！

## 注意事项

- 所有图片处理都在浏览器端完成，不会上传到任何服务器
- 大文件处理可能需要较长时间，请耐心等待
- 建议使用现代浏览器以获得最佳体验
