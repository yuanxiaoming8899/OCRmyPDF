<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text">


<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/ocrmypdf/OCRmyPDF/blob/main/docs/images/logo.svg"><img src="/ocrmypdf/OCRmyPDF/raw/main/docs/images/logo.svg" width="240" alt="OCR我的PDF" style="max-width: 100%;"></a></p>
<p dir="auto"><a href="https://github.com/ocrmypdf/OCRmyPDF/actions/workflows/build.yml"><img src="https://github.com/ocrmypdf/OCRmyPDF/actions/workflows/build.yml/badge.svg" alt="构建状态" style="max-width: 100%;"></a> <a href="https://pypi.org/project/ocrmypdf/" rel="nofollow"><img src="https://camo.githubusercontent.com/8dbde8b0f482c2e5e920470d12f7df9b253dfffca0b345da01fd4408adc4604c/68747470733a2f2f696d672e736869656c64732e696f2f707970692f762f6f63726d797064662e737667" alt="PyPI 版本" title="PyPI 版本" data-canonical-src="https://img.shields.io/pypi/v/ocrmypdf.svg" style="max-width: 100%;"></a> <a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/d5784edb7fe3c4506e664e09c8aa9fcd24f12a296d67f806e1b5339fbaa52e2b/68747470733a2f2f696d672e736869656c64732e696f2f686f6d65627265772f762f6f63726d797064662e737667"><img src="https://camo.githubusercontent.com/d5784edb7fe3c4506e664e09c8aa9fcd24f12a296d67f806e1b5339fbaa52e2b/68747470733a2f2f696d672e736869656c64732e696f2f686f6d65627265772f762f6f63726d797064662e737667" alt="自制版本" title="自制版本" data-canonical-src="https://img.shields.io/homebrew/v/ocrmypdf.svg" style="max-width: 100%;"></a> <a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/f1122c2e08cea6c8c3a3798391ecd8be6058aa0f478c6b6fc9b788d2845f6967/68747470733a2f2f72656164746865646f63732e6f72672f70726f6a656374732f6f63726d797064662f62616467652f3f76657273696f6e3d6c6174657374"><img src="https://camo.githubusercontent.com/f1122c2e08cea6c8c3a3798391ecd8be6058aa0f478c6b6fc9b788d2845f6967/68747470733a2f2f72656164746865646f63732e6f72672f70726f6a656374732f6f63726d797064662f62616467652f3f76657273696f6e3d6c6174657374" alt="阅读文档" title="热电阻" data-canonical-src="https://readthedocs.org/projects/ocrmypdf/badge/?version=latest" style="max-width: 100%;"></a> <a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/17a2fb65298c0e6bd22cea96c477e399347f0c47a357b4393e0eb382658b2712/68747470733a2f2f696d672e736869656c64732e696f2f707970692f707976657273696f6e732f6f63726d79706466"><img src="https://camo.githubusercontent.com/17a2fb65298c0e6bd22cea96c477e399347f0c47a357b4393e0eb382658b2712/68747470733a2f2f696d672e736869656c64732e696f2f707970692f707976657273696f6e732f6f63726d79706466" alt="Python 版本" title="支持的 Python 版本" data-canonical-src="https://img.shields.io/pypi/pyversions/ocrmypdf" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">OCRmyPDF 为扫描的 PDF 文件添加 OCR 文本层，以便搜索或复制粘贴。</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>ocrmypdf                      <span class="pl-c"><span class="pl-c">#</span> it's a scriptable command line program</span>
   -l eng+fra                 <span class="pl-c"><span class="pl-c">#</span> it supports multiple languages</span>
   --rotate-pages             <span class="pl-c"><span class="pl-c">#</span> it can fix pages that are misrotated</span>
   --deskew                   <span class="pl-c"><span class="pl-c">#</span> it can deskew crooked PDFs!</span>
   --title <span class="pl-s"><span class="pl-pds">"</span>My PDF<span class="pl-pds">"</span></span>           <span class="pl-c"><span class="pl-c">#</span> it can change output metadata</span>
   --jobs 4                   <span class="pl-c"><span class="pl-c">#</span> it uses multiple cores by default</span>
   --output-type pdfa         <span class="pl-c"><span class="pl-c">#</span> it produces PDF/A by default</span>
   input_scanned.pdf          <span class="pl-c"><span class="pl-c">#</span> takes PDF input (or images)</span>
   output_searchable.pdf      <span class="pl-c"><span class="pl-c">#</span> produces validated PDF output</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="ocrmypdf                      # it's a scriptable command line program
   -l eng+fra                 # it supports multiple languages
   --rotate-pages             # it can fix pages that are misrotated
   --deskew                   # it can deskew crooked PDFs!
   --title &quot;My PDF&quot;           # it can change output metadata
   --jobs 4                   # it uses multiple cores by default
   --output-type pdfa         # it produces PDF/A by default
   input_scanned.pdf          # takes PDF input (or images)
   output_searchable.pdf      # produces validated PDF output" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><a href="https://ocrmypdf.readthedocs.io/en/latest/release_notes.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有关最新更改的详细信息，请参阅发行说明</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">主要特点</font></font></h2><a id="user-content-main-features" class="anchor" aria-label="永久链接：主要特点" href="#main-features"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">从常规 PDF</font><font style="vertical-align: inherit;">生成可搜索的</font></font><a href="https://en.wikipedia.org/?title=PDF/A" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">PDF/A文件</font></font></a><font style="vertical-align: inherit;"></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将 OCR 文本准确放置在图像下方，以方便复制/粘贴</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">保持原始嵌入图像的精确分辨率</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果可能，请以“无损”操作插入 OCR 信息，而不会破坏任何其他内容</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">优化 PDF 图像，通常生成比输入文件更小的文件</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果需要，在执行 OCR 之前校正倾斜和/或清洁图像</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">验证输入和输出文件</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将工作分配到所有可用的 CPU 核心上</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用</font></font><a href="https://github.com/tesseract-ocr/tesseract"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Tesseract OCR</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">引擎识别</font></font><a href="https://github.com/tesseract-ocr/tessdata"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">100多种语言</font></font></a></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">确保您的私人数据保持私密。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">适当扩展以处理包含数千页的文件。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">经过数百万份 PDF 的实战测试。</font></font></li>
</ul>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/ocrmypdf/OCRmyPDF/blob/main/misc/screencast/demo.svg"><img src="/ocrmypdf/OCRmyPDF/raw/main/misc/screencast/demo.svg" alt="终端会话中的 OCRmyPDF 演示" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">详情请查阅</font></font><a href="https://ocrmypdf.readthedocs.io/en/latest/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文档</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">动机</font></font></h2><a id="user-content-motivation" class="anchor" aria-label="永久链接：动机" href="#motivation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我在网上搜索了用于 OCR PDF 文件的免费命令行工具：我找到了很多，但没有一个真正令人满意：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">他们制作的 PDF 文件的图像下方文本位置错误（无法复制/粘贴）</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或者他们没有处理口音和多语言字符</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或者他们改变了嵌入图像的分辨率</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或者他们生成了非常大的 PDF 文件</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或者在尝试 OCR 时崩溃</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或者他们没有制作有效的 PDF 文件</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">最重要的是，它们都没有生成 PDF/A 文件（专用于长期存储的格式）</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">...所以我决定开发自己的工具。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装</font></font></h2><a id="user-content-installation" class="anchor" aria-label="固定链接：安装" href="#installation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">支持 Linux、Windows、macOS 和 FreeBSD。还提供适用于 x64 和 ARM 的 Docker 镜像。</font></font></p>
<table>
<thead>
<tr>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">操作系统</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装命令</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Debian、Ubuntu</font></font></td>
<td><code>apt install ocrmypdf</code></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">适用于 Linux 的 Windows 子系统</font></font></td>
<td><code>apt install ocrmypdf</code></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Fedora</font></font></td>
<td><code>dnf install ocrmypdf</code></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">macOS (自制)</font></font></td>
<td><code>brew install ocrmypdf</code></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">macOS（MacPorts）</font></font></td>
<td><code>port install ocrmypdf</code></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">macOS（不支持）</font></font></td>
<td><code>nix-env -i ocrmypdf</code></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LinuxBrew</font></font></td>
<td><code>brew install ocrmypdf</code></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">FreeBSD</font></font></td>
<td><code>pkg install py-ocrmypdf</code></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">康达</font></font></td>
<td><code>conda install ocrmypdf</code></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Ubuntu Snap</font></font></td>
<td><code>snap install ocrmypdf</code></td>
</tr>
</tbody>
</table>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对于其他人，</font></font><a href="https://ocrmypdf.readthedocs.io/en/latest/installation.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅我们的文档</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">了解安装步骤。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">语言</font></font></h2><a id="user-content-languages" class="anchor" aria-label="固定链接：语言" href="#languages"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">OCRmyPDF 使用 Tesseract 进行 OCR，并依赖其语言包。对于 Linux 用户，您通常可以找到提供语言包的软件包：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c"><span class="pl-c">#</span> Display a list of all Tesseract language packs</span>
apt-cache search tesseract-ocr

<span class="pl-c"><span class="pl-c">#</span> Debian/Ubuntu users</span>
apt-get install tesseract-ocr-chi-sim  <span class="pl-c"><span class="pl-c">#</span> Example: Install Chinese Simplified language pack</span>

<span class="pl-c"><span class="pl-c">#</span> Arch Linux users</span>
pacman -S tesseract-data-eng tesseract-data-deu <span class="pl-c"><span class="pl-c">#</span> Example: Install the English and German language packs</span>

<span class="pl-c"><span class="pl-c">#</span> brew macOS users</span>
brew install tesseract-lang</pre><div class="zeroclipboard-container">
    
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">然后，您可以将</font></font><code>-l LANG</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">参数传递给 OCRmyPDF，以提示它应该搜索哪些语言。可以请求多种语言。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">OCRmyPDF 支持 Tesseract 4.1.1+。它将自动使用在</font></font><code>PATH</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">环境变量中首先找到的版本。在 Windows 上，如果</font></font><code>PATH</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">没有提供 Tesseract 二进制文件，我们将使用根据 Windows 注册表安装的最高版本号。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文档和支持</font></font></h2><a id="user-content-documentation-and-support" class="anchor" aria-label="永久链接：文档和支持" href="#documentation-and-support"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">一旦安装了 OCRmyPDF，就可以通过以下方式访问内置帮助，其中解释了命令语法和选项：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>ocrmypdf --help</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="ocrmypdf --help" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们的</font></font><a href="https://ocrmypdf.readthedocs.io/en/latest/index.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文档可在阅读文档中查阅</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请在我们的</font></font><a href="https://github.com/ocrmypdf/OCRmyPDF/issues"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GitHub 问题</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">页面上报告问题，并按照问题模板进行快速响应。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要求</font></font></h2><a id="user-content-requirements" class="anchor" aria-label="固定链接：要求" href="#requirements"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">除了所需的 Python 版本 (3.8+) 之外，OCRmyPDF 还需要安装 Ghostscript 和 Tesseract OCR 的外部程序。OCRmyPDF 是纯 Python 的，几乎可以在所有平台上运行：Linux、macOS、Windows 和 FreeBSD。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">新闻与媒体</font></font></h2><a id="user-content-press--media" class="anchor" aria-label="固定链接：新闻与媒体" href="#press--media"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><a href="https://medium.com/@ikirichenko/going-paperless-with-ocrmypdf-e2f36143f46a" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 OCRmyPDF 实现无纸化</font></font></a></li>
<li><a href="https://medium.com/@treyharris/converting-a-scanned-document-into-a-compressed-searchable-pdf-with-redactions-63f61c34fe4c" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将扫描的文档转换为带有删节的压缩可搜索 PDF</font></font></a></li>
<li><a href="https://heise.de/-2279695" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">c't 1-2014，第 59 页</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：德国领先 IT 杂志 c't 详细介绍了 OCRmyPDF v1.0</font></font></li>
<li><a href="https://heise.de/-2356670" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">heise Open Source，2014 年 9 月：使用 OCRmyPDF 识别文本</font></font></a></li>
<li><a href="https://www.heise.de/ratgeber/Durchsuchbare-PDF-Dokumente-mit-OCRmyPDF-erstellen-4607592.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">全部使用 OCRmyPDF 创建 PDF 文档</font></font></a></li>
<li><a href="https://www.linuxlinks.com/excellent-utilities-ocrmypdf-add-ocr-text-layer-scanned-pdfs/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">优秀实用程序：OCRmyPDF</font></font></a></li>
<li><a href="https://www.linux-community.de/ausgaben/linuxuser/2021/06/texterkennung-mit-ocrmypdf-und-scanbd-automatisieren/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Linux用户使用OCRmyPDF和自动扫描识别文本</font></font></a></li>
<li><a href="https://news.ycombinator.com/item?id=32028752" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Y Combinator 讨论</font></font></a></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">业务咨询</font></font></h2><a id="user-content-business-enquiries" class="anchor" aria-label="永久链接：业务咨询" href="#business-enquiries"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果没有公司和用户选择为功能开发和咨询咨询提供支持，OCRmyPDF 就不会成为如今的软件。我们很乐意讨论所有咨询，无论是扩展现有功能集，还是将 OCRmyPDF 集成到更大的系统中。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">执照</font></font></h2><a id="user-content-license" class="anchor" aria-label="永久链接：许可证" href="#license"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">OCRmyPDF 软件根据 Mozilla 公共许可证 2.0 (MPL-2.0) 获得许可。此许可证允许将 OCRmyPDF 与其他代码（包括商业和闭源代码）集成，但要求您发布对 OCRmyPDF 所做的源代码级修改。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">OCRmyPDF 的某些组件具有其他许可证，如标准 SPDX 许可证标识符或 DEP5 版权和许可信息文件所示。一般而言，非核心代码在 MIT 下获得许可，文档和测试文件在 Creative Commons ShareAlike 4.0（CC-BY-SA 4.0）下获得许可。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">免责声明</font></font></h2><a id="user-content-disclaimer" class="anchor" aria-label="永久链接：免责声明" href="#disclaimer"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该软件以“原样”分发，不附带任何明示或暗示的保证或条件。</font></font></p>
</article></div>
