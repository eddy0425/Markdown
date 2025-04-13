# Markdown阅读器

一个简洁、美观的Markdown阅读和编辑工具，完全在浏览器中运行，无需任何后端服务。

## 功能特点

- 📖 **阅读模式**：全屏显示渲染后的Markdown内容，沉浸式阅读体验
- ✏️ **编辑模式**：分栏编辑与实时预览，所见即所得
- 🎨 **主题切换**：支持亮色/暗色主题，呵护您的眼睛
- 💾 **本地存储**：自动保存编辑内容，无需担心数据丢失
- 📝 **GitHub风格Markdown**：支持表格、代码块、任务列表等扩展语法
- 🔆 **代码高亮**：内置多种编程语言的语法高亮
- 🔍 **字体大小调整**：根据个人喜好调整阅读字体大小
- 📄 **本地文件导入/导出**：轻松加载和保存Markdown文件

## 如何使用

1. **打开方式**：
   - 直接在浏览器中打开`index.html`文件
   - 或通过任意HTTP服务器提供访问

2. **基本操作**：
   - 选择文件：点击右上角"选择文件"按钮，导入本地Markdown文件
   - 切换模式：通过左上角的下拉菜单切换"阅读模式"和"编辑模式"
   - 保存文件：在编辑模式下，点击右上角"保存文件"按钮下载当前内容
   - 调整字体：在阅读模式下，使用工具栏中的"A+"和"A-"按钮调整字体大小
   - 切换主题：点击右上角的月亮/太阳图标切换暗色/亮色主题

3. **编辑功能**：在编辑模式下，您可以使用以下工具：
   - 文本格式化（粗体、斜体）
   - 引用块
   - 代码块
   - 链接
   - 表格

## 技术实现

本项目使用纯前端技术构建：

- **HTML5 & CSS3**：基础页面结构和样式
- **JavaScript**：交互逻辑和功能实现
- **[Marked.js](https://marked.js.org/)**：Markdown解析和渲染
- **[highlight.js](https://highlightjs.org/)**：代码语法高亮
- **[SimpleMDE](https://simplemde.com/)**：Markdown编辑器组件

## 本地开发

1. 克隆仓库：
   ```
   git clone https://github.com/yourusername/markdown-reader.git
   cd markdown-reader
   ```

2. 使用本地服务器运行（可选）：
   ```
   # 使用Python简易HTTP服务器
   python -m http.server
   
   # 或使用Node.js的http-server
   npx http-server
   ```

3. 在浏览器中访问：
   - 直接打开`index.html`
   - 或访问`http://localhost:8000`（如使用HTTP服务器）

## 浏览器兼容性

- Chrome 60+
- Firefox 60+
- Safari 12+
- Edge 79+

## 贡献指南

欢迎提交问题和改进建议！请遵循以下步骤：

1. Fork 本仓库
2. 创建您的特性分支：`git checkout -b feature/amazing-feature`
3. 提交您的更改：`git commit -m 'Add some amazing feature'`
4. 推送到分支：`git push origin feature/amazing-feature`
5. 提交Pull Request

## 许可证

本项目采用 MIT 许可证 - 详情请参阅 [LICENSE](LICENSE) 文件

## 致谢

- 感谢所有开源项目的贡献者们
- 特别感谢Marked.js、highlight.js和SimpleMDE的开发者 