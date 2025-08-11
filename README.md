# 学术主页（纯 HTML + CSS）

一个极简的单页学术主页模板，包含顶部名称与一句话简介、About、Research/Projects（3–5 条示例）、Contact 四个区块。

## 特性
- **语义化结构**：使用 `header`/`main`/`section`/`footer` 与 `nav`、`address` 等语义标签。
- **移动端优先**：默认移动端布局，容器 `max-width: 800px`，流式排版，良好的可读性。
- **纯原生技术栈**：仅 HTML + CSS，无任何框架与外部字体依赖。
- **可访问性**：包含 `meta viewport`、跳转到主内容的 skip-link、键盘焦点样式、深浅色自适应。

## 目录结构
- `index.html`：页面结构与内容
- `style.css`：样式（已在 `index.html` 正确引入）
- `README.md`：项目说明与本地预览方法

## 本地预览
- 方式一（直接打开）：在 Finder 中双击 `index.html`，用浏览器打开即可。
- 方式二（本地静态服务器，推荐用于调试）：
  - macOS 自带 Python，可在项目根目录运行：
    ```bash
    python3 -m http.server 8000
    ```
  - 然后在浏览器访问：`http://localhost:8000/index.html`

## 自定义内容
- 将 `index.html` 里的“你的名字”与“一句话简介”替换为你的真实信息。
- 在 `#about`、`#research`、`#contact` 区块中替换示例文本与链接。
- 如需更多项目，可按现有列表项结构新增。

## Lighthouse 建议
- 用 Chrome 打开页面 → 开发者工具 → Lighthouse → 选择 **Mobile** 并勾选 **Accessibility/Best Practices/SEO** → 生成报告。
- 模板已满足移动端可读与基础可访问性，无需追求满分；如有图片请确保提供 `alt` 文本与足够对比度。

## 许可
可用于个人学术主页，二次修改与分发请注明来源。
