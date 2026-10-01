# 第三方组件与许可

Seed Library 安装包附带以下第三方组件。它们各自的许可证继续有效；本说明不改变任何第三方组件的许可，也不为 Seed Library 本身授予新的许可。安装后，许可文本位于 `程序目录\app\licenses` 与 `程序目录\app\tools`。

| 组件 | 版本 | 许可 | 来源 |
|---|---|---|---|
| Tauri（桌面外壳） | 2.x | MIT / Apache-2.0 | https://github.com/tauri-apps/tauri |
| Node.js（`node.exe`） | 24.11.0 | MIT 及其第三方许可（`Node-LICENSE.txt`） | https://nodejs.org/ |
| yt-dlp（Windows 独立版） | 2026.08.19 | Unlicense 及其第三方许可（`yt-dlp-UNLICENSE.txt`、`yt-dlp-THIRD-PARTY.txt`） | https://github.com/yt-dlp/yt-dlp/releases/tag/2026.08.19 |
| FFmpeg / ffprobe（Gyan essentials build） | 9.0.2 | GPLv3（`FFMPEG-LICENSE.txt`） | 见下文 |
| Web Awesome | 3.14.0 | MIT | https://github.com/shoelace-style/webawesome |
| marked、DOMPurify、turndown、opencc-js 等 npm 依赖 | 见 `app\node_modules` | 各包自带许可文件 | npm |
| Simple Icons 平台标志 | — | CC0；商标归各自所有者 | https://simpleicons.org/ |

界面运行依赖系统自带的 Microsoft Edge WebView2 Runtime，安装包不包含它。

## FFmpeg 源代码

安装包中的 `ffmpeg.exe` / `ffprobe.exe` 为未经修改的 Gyan essentials build（GPLv3）：

- 构建发布页：https://www.gyan.dev/ffmpeg/builds/
- FFmpeg 9.0.2 源代码：https://ffmpeg.org/releases/ffmpeg-9.0.2.tar.xz
- 构建依赖与构建脚本：https://github.com/GyanD/codexffmpeg

如需这些二进制对应的完整源代码，也可以在 Issues 中提出。

## 小耳 VideoLab（MIT）

B站下载的请求参数参考自小耳 VideoLab，许可如下：

```
MIT License

Copyright (c) 2026 Jane (小耳 / Xiaoer) <xiaoerzhan@gmail.com>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
