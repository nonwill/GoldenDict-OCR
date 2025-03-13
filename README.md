<h2 align="center" id="GDUTitle" class="fadebox"><a href="https://www.autoptr.top/gdocr/" style='text-decoration:none;color:chocolate;'>GoldenDict++OCR「<span style="color:#003B7A;">划词翻译</span>」</a></h2>

[More Demos](https://space.bilibili.com/3493095169592137/channel/series):
[Sessions](https://www.bilibili.com/video/BV1Da4y1m7aT/?share_source=copy_web&vd_source=1f8bb4f075a48414a935e9435e7a5b1a "Session resume / 会话恢复")/[Auto Session](https://www.bilibili.com/video/BV1xj41177y3/?share_source=copy_web&vd_source=1f8bb4f075a48414a935e9435e7a5b1a "Authentic Session resume / 自动会话")
Media[①](https://youtu.be/OHN9RqpF4Z0 "Audio Rate / 播放速度调节")|[②](https://www.bilibili.com/video/BV1AQ4y1s7Vo/?share_source=copy_web&vd_source=1f8bb4f075a48414a935e9435e7a5b1a "Media file playing / 媒体文件播放支持")
Groups[①](https://www.bilibili.com/video/BV1Pp42197gH/?share_source=copy_web&vd_source=1f8bb4f075a48414a935e9435e7a5b1a "Automatic Groups by Folder, Language and Type / 自动分组，快速排序")|[②](https://www.bilibili.com/video/BV1EN41177Lx/?share_source=copy_web&vd_source=1f8bb4f075a48414a935e9435e7a5b1a "Automatic Groups by Folder, Language and Type / 以目录、语言和类型对词典自动分组，一键创建群组")
Themes[①](https://www.bilibili.com/video/BV12j411U7rK/?share_source=copy_web&vd_source=1f8bb4f075a48414a935e9435e7a5b1a "Theme or stylesheet / 主题 或 样式表 设置，可自由组配")|[②](https://www.bilibili.com/video/BV1Yu4y1J7gc/?share_source=copy_web&vd_source=1f8bb4f075a48414a935e9435e7a5b1a "Theme or stylesheet / 主题 或 样式表 设置，可自由组配")
[OCR](https://www.bilibili.com/video/BV1Ab411X7aC/?share_source=copy_web&vd_source=1f8bb4f075a48414a935e9435e7a5b1a "OCR support / 划词翻译，OCR 引擎选择")
[ScanFlag](https://www.bilibili.com/video/BV1Es4y1b7UU/?share_source=copy_web&vd_source=1f8bb4f075a48414a935e9435e7a5b1a "Word Picking by ScanFlag on Linux / Linux 系统取词")
[OSX](https://www.bilibili.com/video/BV1WW4y1M7mR/?share_source=copy_web&vd_source=1f8bb4f075a48414a935e9435e7a5b1a "Apple's Dictionary support / 支持 苹果 Apple macOS 内置的词典")
PK[①](https://www.bilibili.com/video/BV1kv4y1L7Cm/?share_source=copy_web&vd_source=1f8bb4f075a48414a935e9435e7a5b1a "HeadWord List PK/ 与其它版本性能对比① - 词汇表阅览")|[②](https://www.bilibili.com/video/BV13N411v7kC/?share_source=copy_web&vd_source=1f8bb4f075a48414a935e9435e7a5b1a "Article View PK / 与其它版本性能对比② - 查询阅览")

0. built-in fixes for a large number of issues with the official version
1. a simple plug-in mechanism added, based on which several OCR and audio playback engines plugged
2. completely refactored all implementations to reduce runtime CPU and memory footprint, also query efficiency improved 
3. the future goal is to abstract functional extensions and dictionary formats processing into complete plug-ins to further enhance the scalability and maintainability

<img src="https://github.com/nonwill/GoldenDict-OCR/assets/46510529/89fd7bcb-2b31-497d-96b6-d6a1dbdad947" alt="ocr划词">

<div align="center" style="margin-bottom:1px">
<a href="https://space.bilibili.com/3493095169592137/lists/2849642?type=series" style="color:#7F0099;font-weight:bold;">演示视频</a> 
<a href="https://www.autoptr.top/gdocr/GoldenDict-OCR-Portable-Mode/" style="color:#7F0099;">便携模式</a> 
<a href="https://www.autoptr.top/gdocr/en/GoldenDict-OCR-Audio-Players/" style="color:#7F0099;font-weight:bold;">音频引擎</a> 
<a href="https://www.autoptr.top/gdocr/en/GoldenDict-OCR-Group-by-Folders/" style="color:#7F0099;">自动分组</a> 
<a href="https://www.autoptr.top/thankyou/" style="color:#7F0099;font-weight:bold;" title="Sponsor · Donations · 赞赏 · 捐赠 · 捐助" >💖</a> 
<a href="https://www.autoptr.top/gdocr/en/GoldenDict-OCR-Reading-Mode/" style="color:#7F0099;">阅读模式</a> 
<a href="https://www.autoptr.top/gdocr/GoldenDict-OCR-Language-Settings/" style="color:#7F0099;font-weight:bold;">划词设置</a> 
<a href="https://www.autoptr.top/gdocr/GoldenDict-OCR-Free-Dictionaries/" style="color:#7F0099;">辞书分享</a> 
<a href="https://www.autoptr.top/gdocr/GoldenDict-OCR-Changelog/" style="color:#7F0099;font-weight:bold;" title="GoldenDict++ Changelog">更新日志</a> 
</div>

<div align="center" style="margin:1px 10%">
<div align="center" style="font-size:.92em;" id="GDPFeatures">
<div><span style="cursor:help" title="太阳都西晒啦，起床都墨迹个半天怎么能行呢"><strong><font color="blue">并发</font>索引</strong>，<strong><font color="blue">加速</font>启动</strong>，辞书<strong>加载</strong>时<strong>信息</strong>全程<font color="blue"><strong>可视</strong></font></span></div>
<div><span style="cursor:help" title="加一次油可多次蓄力，我跑的最远哟"><strong><font color="blue">全文</font>搜索</strong>结果<strong>导出</strong>/<strong>导入</strong>，<font color="blue"><strong>一次</strong></font>搜索<font color="blue"><strong>随时</strong></font>使用</span></div>
<div><span style="cursor:help" title="哑了咋办？换一个呀">多引擎<font color="blue"><a href="https://www.bilibili.com/video/BV1AQ4y1s7Vo?t=0.0" title="内置播放引擎和外置播放器，支持所有音频格式"><strong>媒体播放</strong></a></font>器，支持<font color="blue"><strong>无损音频</strong></font>，随切<strong>随用</strong></span></div>
<div><span style="cursor:help" title="划哪取哪，管它静的还是动的，来者不拒"><a href="https://www.bilibili.com/video/BV1Ab411X7aC?t=0.0" title="支持系统内置OCR引擎和多个自定义引擎，支持多国语言识别"><strong>多语言</strong>OCR<strong>划词</strong></a>，<strong><font color="blue">自动</font>切屏<font color="blue">动态</font>划屏</strong>，<strong>主流引擎</strong>随换<strong>随用</strong></span></div>
<div><span style="cursor:help" title="慵懒不想动...锕？还可以这么分组，介个不要太爽快">辞书信息一览，依<strong>文件根目录</strong>/<strong>格式</strong>或语言<strong><a href="https://www.bilibili.com/video/BV1EN41177Lx?t=0.0" title="GoldenDict++按 词典类型 / 词典语言 / 目录结构 自动为词典分组">自动分组</a></strong></span></div>
<div><span style="cursor:help" title="什么？辞书名字不满意？改，改，不喜欢就改嘛"><strong>自定义</strong>辞书<strong><font color="blue">别名</font></strong></span>，<span style="cursor:help" title="合理配置分组文件夹，过滤、排序、分组一键搞定">按语言/名称/<font color="blue"><strong>存储路径</strong></font>/<strong></strong>格式<a href="https://www.bilibili.com/video/BV1LJ4m1p7an?t=0.0" title="GoldenDict++按 词典类型 / 语言 / 目录 / ID 自动过滤词典"><strong>排序</strong>/<strong>过滤</strong></a>辞书</span></div>
<div><span style="cursor:help" title="不仅能够快速恢复 Tab 页与 群组 搭配，还可以从上次关闭时的会话继续呢"，还需要一个一个的重新打开吗？">查询<strong><font color="blue">会话</font>保存</strong>或<strong><a href="https://www.bilibili.com/video/BV1Da4y1m7aT?t=0.0" title="已保存的会话可随时加载，或在应用启动后自动加载">导入</a></strong>，可在启动时<strong><a href="https://www.bilibili.com/video/BV1xj41177y3?t=0.0" title="启动后从上次关闭时的会话继续，或自动加载已保存的会话">自动<font color="blue">加载</font></a></strong>会话</span></div>
<div><span style="cursor:help" title="咦~，啥年头了还不能多组同查">文章切换时<strong>恢复</strong><font color="blue">分组/关键字/候选词组</font>等<font color="blue"><strong>上下文</strong></font>信息</span></div>
<div><span style="cursor:help" title="好吧，电子书也可以集成进来啦"><strong>阅读模式</strong>，小窗看锚，<font color="blue"><strong>沉浸</strong></font>于<strong>边阅边查</strong>的<strong>读书体验</strong></span></div>
<div><span style="cursor:help" title="Flash还是有用武之地的啦，视频播放更不可少啦">支持<strong> flash 动画</strong>/<font color="blue"><strong>视频</strong></font>播放和<font color="blue"><strong>多种图片</strong></font>格式</span></div>
<div><span style="cursor:help" title="作为一个前端达人，怎么会无用武之地呢"><strong>全局<font color="blue"> js </font>脚本</strong>文件，可<font color="blue"><strong>自主优化</strong></font>查询<font color="blue"><strong>性能</strong></font></span></div>
<div><span style="cursor:help" title="炫彩主题，自由定制！只要一点点儿css知识就够啦"><a href="https://www.bilibili.com/video/BV12j411U7rK?t=0.0" title="窗体界面 和 文章视图 可以混搭不同的 显示风格"><strong>特定主题</strong></a>或<strong>分组</strong>为<strong>文章</strong>(区别)设定<a href="https://www.bilibili.com/video/BV1Yu4y1J7gc?t=0.0" title="区别于不同 显示主题 设置不同的 css 样式表，区别于不同 词典分组 设置不同的 css 样式表"><strong>特定显示样式</strong></a></span></div>
<div><span style="cursor:help" title="告别臃肿，拒绝三高">文章<font color="blue"><strong>缓存</strong>控制</font>，<strong><font color="blue">模块化</font></strong>功能<strong>按需加载</strong>，常量复用，<font color="blue"><strong>低内存</strong></font>占用</span></div>
<div><span style="cursor:help" title="不只是耗能少、速度快！安全、可靠也很重要哟"><strong>全<font color="blue">优化</font>高<font color="blue">效能</font></strong>，<strong>无</strong><font color="blue">内存<strong>泄露</strong></font>及缓冲区<font color="blue"><strong>溢出</strong></font></span>，<span style="cursor:help" title="老旧电脑的救星 - 作为学习机、上网课，一点儿都不耽误"><font color="blue">低配</font>电脑<font color="blue">也</font>能<font color="blue"><strong>顺畅</strong></font>运行</span></div>
</div>

<p align="center" class="gdocr_topic_text"><span style="font-size:16px">声明：仅在<strong>非盈利非商用</strong>及<strong>帮学助教</strong>的前提下您可以下载<strong>使用与分享</strong>GoldenDict++划词版。</span><br>「下载或使用GoldenDict++划词版将视同您已知晓并同意上述声明」</p>

<div class="outer" style="list-style-type:none;margin:1px 6em 1px 3em" align="center">
<ul class="list-group">
<li class="list-group-item title"><a href="https://www.autoptr.top/gdocr/GoldenDict-OCR-Changelog/" style="border-bottom:none" title="2022-03-21 / Changelog of GoldenDict++,划词翻译的升级日志及不同于官方版本GoldenDict的特点与特性">GoldenDict++OCR Changelog</a></li>
<li class="list-group-item title"><a href="https://www.autoptr.top/gdocr/GoldenDict-OCR-Free-Dictionaries/" style="border-bottom:none" title="2022-03-21 / 下载适用于GoldenDict++划词翻译的词典: xdxf,aard,zim,wiki,wikipedia,wikiquote,wikitionary,wikibooks,wikisource,wikiversity,PhET,物理,化学,汉匈,汉法,汉德">Free Dictionaries for Everyone</a></li>
<li class="list-group-item title"><a href="https://www.autoptr.top/gdocr/GoldenDict-OCR-Portable-Mode/" style="border-bottom:none" title="2022-03-21 / GoldenDict++全新的便携模式，可添加自定义辞书目录，无论是查词还是全文搜索，索引一次，随处可用">GoldenDict++ Portable Mode</a></li>
<li class="list-group-item title"><a href="https://www.autoptr.top/gdocr/GoldenDict-OCR-Language-Settings/" style="border-bottom:none" title="2022-03-21 / GoldenDict++支持的OCR语言,如何设置划词翻译选项">GoldenDict++ OCR Setup</a></li>
<li class="list-group-item title"><a href="https://www.autoptr.top/gdocr/GoldenDict-OCR-Deployment/" style="border-bottom:none" title="2022-03-21 / How to download and deploy GoldenDict++,GoldenDict++划词翻译下载和安装指南">GoldenDict++OCR Download and Deployment</a></li>
<li class="list-group-item title"><a href="https://www.autoptr.top/gdocr/GoldenDict-OCR-How-to-Isolate-CSS/" style="border-bottom:none" title="GoldenDict++样式表隔离,如何CSS现定于特定词典或不影响其它词典">GoldenDict++ CSS Isolate</a></li>
<li class="list-group-item title"><a href="https://www.autoptr.top/gdocr/wiki/" data-series="GoldenDict++OCR「划词版」" style="border-bottom:none;color:#428bca">GoldenDict Wiki &amp; Posts</a></li>
<li class="list-group-item title"><a href="https://www.autoptr.top/gdocr/cn/" data-series="GoldenDict++OCR「划词版」" style="border-bottom:none;color:#428bca">GoldenDict++ Chinese Docs</a></li>
<li class="list-group-item title"><a href="https://www.autoptr.top/gdocr/en/" data-series="GoldenDict++OCR「划词版」" style="border-bottom:none;color:#428bca">GoldenDict++ English Docs「箐典·HOWTO」</a></li>
</ul>
</div>
