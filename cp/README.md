
# 在线图片取色器

一个强大且用户友好的在线工具，可帮助您从任何图片中轻松提取颜色。所有操作都在您的浏览器中完成，确保了您的图片隐私和安全。

### ✨ 功能特性

- **多种上传方式**: 支持拖拽、点击选择文件和直接从剪贴板粘贴图片。
- **精准颜色拾取**: 使用十字光标在图片上移动，实时预览悬停点的颜色，单击即可锁定颜色。
- **全面的颜色信息**:
    - 同时显示**悬停颜色**和**选中颜色**，方便对比。
    - 提供选中颜色的 **HEX** 和 **RGB** 值，并支持一键复制。
- **智能颜色分析**:
    - 自动提取图片的**主色**。
    - 自动生成包含多达10种颜色的**主题色板**。
- **色彩饱和度渐变**:
    - 根据选中的颜色和您设定的百分比，动态生成一系列**亮色 (Tints)** 和**暗色 (Shades)**。
    - 每个渐变色块都显示其HEX值和变化百分比，并支持悬停复制。
- **100% 客户端处理**: 所有图片处理都在您的浏览器本地进行，我们不会上传您的任何图片，完全保护您的隐私。

### 🚀 如何使用

1. **加载图片**:
    - 将图片文件拖拽到虚线框内。
    - 或点击“选择文件”按钮上传。
    - 或直接在页面上按 `Ctrl+V` / `Command+V` 粘贴截图或复制的图片。
2. **拾取颜色**:
    - 在图片上移动鼠标，左上角的“悬停颜色”预览框会实时变化。
    - 在图片上单击，即可将颜色固定在“选中颜色”预览框中，并更新下方的所有颜色信息。
3. **获取颜色**:
    - 从对应的文本框中复制HEX或RGB值。
    - 从“主色”、“主题色”或“色彩饱和度渐变”区域的色块上点击，可将其设为当前选中颜色。
    - 在“色彩饱和度渐变”区域，将鼠标悬停在色块上，点击出现的图标即可复制颜色代码。

### 🛠️ 技术栈

- **HTML5**
- **Tailwind CSS**
- **JavaScript (原生)**
- **Color Thief** - 用于提取图片主色和调色板的库

# Online Image Color Picker

A powerful and user-friendly online tool to help you easily extract colors from any image. All operations are done locally in your browser, ensuring the privacy and security of your images.

### ✨ Features

- **Multiple Upload Methods**: Supports drag-and-drop, file selection via button, and pasting images directly from the clipboard.
- **Precise Color Picking**: Use a crosshair cursor to move over the image, with a real-time preview of the hovered color. Click to select a color.
- **Comprehensive Color Information**:
    - Displays both **Hover Color** and **Selected Color** for easy comparison.
    - Provides **HEX** and **RGB** values for the selected color with one-click copy functionality.
- **Smart Color Analysis**:
    - Automatically extracts the **main color** of the image.
    - Automatically generates a **theme palette** of up to 10 colors.
- **Tints & Shades Generator**:
    - Dynamically generates a series of **tints** (lighter colors) and **shades** (darker colors) based on the selected color and a user-defined percentage.
    - Each gradient color block displays its HEX value and percentage change, with a copy button on hover.
- **100% Client-Side**: All image processing is done locally in your browser. We do not upload any of your images, fully protecting your privacy.

### 🚀 How to Use

1. **Load an Image**:
    - Drag and drop an image file into the dashed box.
    - Or, click the "Select File" button to upload.
    - Or, simply press `Ctrl+V` / `Command+V` on the page to paste a screenshot or a copied image.
2. **Pick a Color**:
    - Move your mouse over the image; the "Hover Color" preview box will update in real-time.
    - Click on the image to set the color in the "Selected Color" preview box, which will update all color information below.
3. **Get the Color**:
    - Copy the HEX or RGB value from the respective text fields.
    - Click on a color swatch in the "Main Color," "Theme Colors," or "Tints & Shades" sections to set it as the current selected color.
    - In the "Tints & Shades" section, hover over a color block and click the icon that appears to copy its color code.

### 🛠️ Tech Stack

- **HTML5**
- **Tailwind CSS**
- **Vanilla JavaScript**
- **Color Thief** - A library for extracting the main color and palette from an image.