# 打印排版工具箱

打印前的两件麻烦事，一个网页解决。不联网、不上传、不安装 —— 打开就能用。

**👉 [点这里直接使用](https://brokencake.github.io/print-layout-toolkit/)**

---

## 两个工具

### 双面打印

打印机不支持自动双面时，把一份 PDF 拆成「正面」和「反面」两个文件，按顺序打完再翻面就行。可以留装订边，避免打孔时切到字。

- 输入：PDF
- 输出：两个 PDF（正面页 / 反面页）
- 页序按翻面方向自动排好，不用自己数页码

### 横线纸排版

把文档排到已经打好孔、印好横线的笔记纸上，让文字正好压在横线上，不会一行高一行低。

- 输入：直接打字 / .txt / .docx
- 拍一张横线纸的照片，自动量出行距和页边距（在浏览器本地算，不传任何图片出去）
- 输出：对齐好的打印页面

---

## 怎么用

1. 下载 [`index.html`](index.html)（或者用上面的在线地址）
2. 双击，用浏览器打开
3. 上面两个 tab，选你要的那个

整个工具是**一个 HTML 文件**，所有代码和依赖都在里面。断网也能用。

## 隐私

所有处理都在你自己的浏览器里完成。没有服务器，没有上传，没有统计。PDF、文档、照片都不会离开你的电脑。

## 技术

单文件 HTML，内嵌 [pdf-lib](https://github.com/Hopding/pdf-lib) 和 fflate，无构建、无框架、无网络请求。

## 授权

[PolyForm Noncommercial 1.0.0](LICENSE) —— 非商业用途免费。

- ✅ 免费下载、使用、修改、转发，用于个人、学习、爱好
- ✅ 学校、公益组织、政府机构可以直接用
- ❌ **任何商业/盈利用途，需要事先取得作者书面同意** —— 包括打包进付费产品、作为收费服务的一部分、公司内部生产使用

想商用请开一个 [issue](https://github.com/BrokenCake/print-layout-toolkit/issues) 联系我。

---

Free for noncommercial use. **Commercial use requires prior written permission**
— open an issue to ask.
