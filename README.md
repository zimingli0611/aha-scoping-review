# 从零写一篇范围综述 · 配套工具

栗子悟了（Aha Chestnut）视频系列《从零写一篇范围综述》的配套小工具。每个工具都是一个单独的 HTML 文件：下载下来，双击用浏览器打开就能用，不用安装。

> English: see [below](#scoping-review-from-scratch--companion-tools).

| 工具 | 配套视频 | 做什么 | 文件 |
| --- | --- | --- | --- |
| 摘要筛选助手 | 第 7 期：写纳入排除标准与摘要筛选 | 第一轮筛选：导入 bib、自动去重，一条条看题目和摘要，按键判断；可选 AI 预审；多人筛选算一致率和 κ；导出保留的记录和流程图数字 | [abstract-screener.html](abstract-screener/abstract-screener.html) · [使用说明](abstract-screener/摘要筛选助手_使用说明.md) |
| 全文筛选助手 | 第 8 期：全文筛选与 PRISMA 流程图 | 第二轮筛选：导入第一轮的结果和全文 PDF，边读边判断（纳入 / 排除并记一条排除标准 / 没有获取到全文）；多人筛选；自动画 PRISMA 流程图并逐层核对 | [full-text-screener.html](full-text-screener/full-text-screener.html) · [使用说明](full-text-screener/全文筛选助手_使用说明.md) |

## 怎么用

1. **下载**：点开上表里的 html 文件，再点右上角的下载按钮（Download raw file）。或者点本页上方绿色的 Code → Download ZIP，一次下载全部。
2. **打开**：双击下载的 html 文件，用浏览器打开（推荐 Chrome 或 Edge）。界面可以在 ⚙ 设置 → 语言 里切换中文和 English。
3. **两个工具接着用**：
   - 第一轮用摘要筛选助手筛完，在“导出”里下载**保留的记录（.bib）**和**进度备份（JSON）**。
   - 第二轮在全文筛选助手里，把第一轮用的那几个 bib 文件和这份进度备份一起拖进来。保留下来的记录、标准和流程图前半段的数字，都会自动带过来。

## 数据存在哪

- 导入的文献、PDF、判断和进度，都只存在你自己的浏览器里，不会上传。关掉页面再打开，会回到上次的地方。
- 清理浏览器数据会把这些一起删掉。换电脑或清理之前，先导出“进度备份”。
- 摘要筛选助手的 **AI 预审是可选的，默认不用**。打开以后，你写的标准，以及每条记录的题目、关键词和摘要，会发给你自己填的模型服务商（比如 DeepSeek）。API key 只存在你的浏览器里。

视频里演示用的记录和全文 PDF 都是为教学编的模拟数据，不在这个仓库里。

## 许可

[MIT](LICENSE) © 2026 栗子悟了 (Aha Chestnut)。可以自由使用、修改和分享，保留版权声明即可。

---

# Scoping Review from Scratch · Companion tools

Small tools that go with the video series *Scoping Review from Scratch* by Aha Chestnut (栗子悟了). Each tool is a single HTML file: download it and double-click to open it in your browser. Nothing to install.

| Tool | Episode | What it does | Files |
| --- | --- | --- | --- |
| Abstract Screener | Ep. 7: inclusion and exclusion criteria, and abstract screening | Round one: import .bib files with automatic deduplication, read titles and abstracts one by one, decide with the keyboard; optional AI pre-screening; team screening with agreement and κ; export the kept records and the flow-diagram numbers | [abstract-screener.html](abstract-screener/abstract-screener.html) · [guide](abstract-screener/摘要筛选助手_使用说明.md) (English quick guide at the end) |
| Full-Text Screener | Ep. 8: full-text screening and the PRISMA flow diagram | Round two: import round-one results and the full-text PDFs, decide while reading (include / exclude with one exclusion criterion / not retrieved); team screening; draws the PRISMA flow diagram and checks every level | [full-text-screener.html](full-text-screener/full-text-screener.html) · [guide](full-text-screener/全文筛选助手_使用说明.md) (English quick guide at the end) |

## How to use

1. **Download**: open an html file in the table above and click the download button (Download raw file), or use the green Code → Download ZIP button on this page to get everything.
2. **Open**: double-click the downloaded file to open it in your browser (Chrome or Edge recommended). Switch the interface to English under ⚙ Settings → Language.
3. **Use them in sequence**:
   - After round one in the Abstract Screener, download the **kept records (.bib)** and the **progress backup (JSON)** under Export.
   - In the Full-Text Screener, drop in the same .bib files you used in round one together with that backup. The kept records, your criteria and the top of the flow diagram come along automatically.

## Where your data lives

- Records, PDFs, decisions and progress stay in your own browser; nothing is uploaded. Reopen the page to pick up where you left off.
- Clearing browser data deletes them, so download a progress backup first.
- The Abstract Screener's **AI pre-screening is optional and off by default**. When it's on, your criteria and each record's title, keywords and abstract are sent to the model provider you set (e.g., DeepSeek). The API key stays in your browser.

The records and full-text PDFs shown in the videos are simulated data made up for teaching; they are not in this repository.

## License

[MIT](LICENSE) © 2026 栗子悟了 (Aha Chestnut). Free to use, modify and share; keep the copyright notice.
