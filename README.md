<h2 align="center" id="GDUTitle" class="fadebox"><a href="https://www.autoptr.top/gdocr/" style='text-decoration:none;color:chocolate;'>GoldenDict++OCR「<span style="color:#003B7A;">划词翻译</span>」</a></h2>

More Demos:
[Sessions](https://www.bilibili.com/video/BV1Da4y1m7aT?t=0.0 "Session resume / 会话恢复")
[Media](https://www.bilibili.com/video/BV1AQ4y1s7Vo?t=0.0 "Media file playing / 媒体文件播放支持")
[Groups](https://www.bilibili.com/video/BV1dp4y1w75t?t=0.0 "Slim or normal Group box / 群组显示方式: 传统模式 和 紧凑模式")
[Themes](https://www.bilibili.com/video/BV12j411U7rK?t=0.0 "Theme or stylesheet / 主题 或 样式表 设置，可自由组配")
[OCR](https://www.bilibili.com/video/BV1Ab411X7aC?t=0.0 "OCR support / 划词翻译，OCR 引擎选择")
[ScanFlag](https://www.bilibili.com/video/BV1Es4y1b7UU?t=0.0 "Word Picking by ScanFlag on Linux / Linux 系统取词")
[OSX](https://www.bilibili.com/video/BV1WW4y1M7mR?t=0.0 "Apple's Dictionary support / 支持 苹果 Apple macOS 内置的词典")
[PK①](https://www.bilibili.com/video/BV1kv4y1L7Cm?t=0.0 "HeadWord List PK/ 与其它版本性能对比① - 词汇表阅览")
[PK②](https://www.bilibili.com/video/BV13N411v7kC?t=0.0 "Article View PK / 与其它版本性能对比② - 查询阅览")

![reading_on_macos](https://github.com/nonwill/nonwill.github.io/assets/46510529/cbcf7702-c683-469f-afb7-a02697a57615 "Reading Apple's Dictionary on macOS")

0. built-in fixes for a large number of issues with the official version
1. a simple plug-in mechanism added, based on which several OCR and audio playback engines plugged
2. completely refactored all implementations to reduce runtime CPU and memory footprint, also query efficiency improved 
3. the future goal is to abstract functional extensions and dictionary formats processing into complete plug-ins to further enhance the scalability and maintainability

<div align="center" style="margin-bottom:1px">
<a href="https://www.autoptr.top/gdocr/GoldenDict-OCR-Free-Dictionaries/" style="color:#7f0099">辞书分享</a> 
<a href="https://www.autoptr.top/gdocr/en/GoldenDict-OCR-Audio-Players/">音频引擎</a> 
<a href="https://www.autoptr.top/gdocr/en/GoldenDict-OCR-Web-History-Cache/">文章缓存</a> 
<a href="https://www.autoptr.top/gdocr/en/GoldenDict-OCR-Group-by-Folders/" style="color:#7f0099;font-weight:700">自动分组</a> 
<a href="https://www.autoptr.top/gdocr/en/GoldenDict-OCR-Reading-Mode/">阅读模式</a> 
<a href="https://www.autoptr.top/gdocr/en/GoldenDict-OCR-QA-Help/" style="color:#7f0099;font-weight:700">问题帮助</a> 
<a href="https://www.autoptr.top/gdocr/GoldenDict-OCR-Language-Settings/">划词设置</a> 
<a href="https://www.autoptr.top/gdocr/GoldenDict-OCR-Changelog/" style="color:blue">更新日志</a> 
<a href="https://www.autoptr.top/gdocr/GoldenDict-OCR-Deployment/" style="color:blue;font-weight:700">升级下载</a></div><div align="center" style="margin:1px 10%">
<img src="https://z3.ax1x.com/2021/04/25/czQaN9.gif" alt="ocr划词">
<div><span style="cursor:help" title="太阳都西晒啦，起床都墨迹个半天怎么能行呢"><strong><font color="blue">并发</font>索引</strong>，<strong><font color="blue">加速</font>启动</strong>，<strong>信息</strong>全程<font color="blue"><strong>可视</strong></font></span> | <span style="cursor:help" title="加一次油可多次蓄力，我跑的最远哟"><strong><font color="blue">全文</font>搜索</strong>结果<strong>导入导出</strong>，<font color="blue">一次搜索，随时使用</font></span></div><div><span style="cursor:help" title="哑了咋办？换一个呀">多个<strong>音频引擎</strong><font color="blue">插件，<strong>随切随用</strong></font></span> | <span style="cursor:help" title="划哪取哪，管它静的还是动的，来者不拒">多引擎<font color="blue"><strong>OCR划词</strong>，支持<strong>自动切屏</strong>、<strong>动态划屏</strong></font></span></div><div><span style="cursor:help" title="锕？还可以这么分组，介个不要太爽快">依辞书<strong>根目录</strong>的<font color="blue"><strong>自动</strong>群组</font>，<strong>一键分组</strong></span> | <span style="cursor:help" title="什么？辞书名字不满意？改，改，不喜欢就改嘛">支持<strong>字典<font color="blue">别名</font></strong>，支持<strong>按<font color="blue">目录+文件名</font>排序</strong>辞书</span></div><div><span style="cursor:help" title="咦~，啥年头了还不能多组同查">文章切换，<strong>恢复</strong><font color="blue">群组/关键字/候选词</font>等<font color="blue"><strong>上下文</strong></font>信息</span></div><div><span style="cursor:help" title="好吧，电子书也可以集成进来啦"><strong>阅读模式</strong>，<font color="blue"><strong>沉浸</strong></font>于<strong>边阅边查</strong>的<font color="blue">读书体验</font></span> | <span style="cursor:help" title="Flash还是有用武之地的啦，视频播放更不可少啦">支持<strong>动画</strong>、<font color="blue"><strong>视频</strong>播放</font>和<font color="blue"><strong>tif</strong>格式</font>图片</span></div><div><span style="cursor:help" title="作为一个前端达人，怎么会无用武之地呢"><strong>全局<font color="blue">js</font>脚本</strong>，可<font color="blue"><strong>自主优化</strong></font>查询<font color="blue"><strong>性能</strong></font></span> | <span style="cursor:help" title="炫彩主题，自由定制！只要一点点儿css知识就够啦">可依<font color="blue">特定</font><strong>主题</strong>或<strong>分组</strong>，为辞书设置<font color="blue">特定<strong>样式</strong></font></span></div><div><span style="cursor:help" title="老旧电脑的救星 - 作为学习机、上网课，一点儿都不耽误">文章<font color="blue"><strong>历史总量</strong>控制</font>，<font color="blue">低配</font>PC<font color="blue">也</font>能<font color="blue"><strong>顺畅</strong></font>运行</span> | <span style="cursor:help" title="告别臃肿，拒绝三高"><strong>功能</strong><font color="blue">模块化</font>，插件<strong>按需加载</strong>，<font color="blue"><strong>低内存</strong>占用</font></span></div><div><span style="cursor:help" title="不只是速度快！安全、可靠也很重要哟"><strong>全<font color="blue">优化</font></strong>，<strong>查询<font color="blue">加速</font></strong>，<font color="blue"><strong>无</strong></font>内存<font color="blue"><strong>泄露</strong></font>及缓冲区<font color="blue"><strong>溢出</strong></font>等问题</span></div></div><p align="center" class="gdocr_topic_text"><span style="font-size:.9em">「本应用<strong>未与任何商业个体合作</strong>且完全免费，请<a href="https://www.autoptr.top/gdocr/cn/GoldenDict-OCR-QA-Help/" title="来信举报，仅限简体中文/普通话交流">抵制</a>任何以附赠或售卖等形式分发本程序文件或文档的<a href="https://autoptr.lanzoui.com/iC3Q8qlvlnc" style="color:#818">行为</a>」</span><br><span style="font-size:16px">声明：仅在<strong>非盈利非商用</strong>及<strong>帮学助教</strong>的前提下您可以下载<strong>使用与分享</strong>GoldenDict++划词版。</span><br>「下载或使用GoldenDict++划词版将视同您已知晓并同意上述声明」<br><span style="font-size:.9em;color:#d2691e">「请学友们在词典论坛寻求学习资料时收集资料适可而止，坚持以学研为重」</span></p></div><div class="outer" style="list-style-type:none;margin:1px 6em 1px 3em" align="center"><ul class="list-group"><li class="list-group-item title"><a href="https://www.autoptr.top/gdocr/GoldenDict-OCR-Changelog/" style="border-bottom:none" title="2022-03-21 / Changelog of GoldenDict++,划词翻译的升级日志及不同于官方版本GoldenDict的特点与特性">GoldenDict++OCR Changelog「更新日志」</a></li><li class="list-group-item title"><a href="https://www.autoptr.top/gdocr/GoldenDict-JavaScript-Privilge-Escalation/" style="border-bottom:none" title="2022-03-21 / 关于GoldenDict的JS提权漏洞的一点思考,Thinking on JavaScript Privilge Escalation of  GoldenDict">关于GoldenDict的JavaScript提权漏洞的思考</a></li><li class="list-group-item title"><a href="https://www.autoptr.top/gdocr/GoldenDict-OCR-Free-Dictionaries/" style="border-bottom:none" title="2022-03-21 / 下载适用于GoldenDict++划词翻译的词典: xdxf,aard,zim,wiki,wikipedia,wikiquote,wikitionary,wikibooks,wikisource,wikiversity,PhET,物理,化学,汉匈,汉法,汉德">Free Dictionaries for Everyone「辞书分享」</a></li><li class="list-group-item title"><a href="https://www.autoptr.top/gdocr/GoldenDict-OCR-Portable-Mode/" style="border-bottom:none" title="2022-03-21 / GoldenDict++全新的便携模式，可添加自定义辞书目录，无论是查词还是全文搜索，索引一次，随处可用">GoldenDict++ Portable Mode「全新的便携模式」</a></li><li class="list-group-item title"><a href="https://www.autoptr.top/gdocr/GoldenDict-OCR-Language-Settings/" style="border-bottom:none" title="2022-03-21 / GoldenDict++支持的OCR语言,如何设置划词翻译选项">GoldenDict++ OCR Setup「划词及语言设置」</a></li><li class="list-group-item title"><a href="https://www.autoptr.top/gdocr/GoldenDict-OCR-Deployment/" style="border-bottom:none" title="2022-03-21 / How to download and deploy GoldenDict++,GoldenDict++划词翻译下载和安装指南">GoldenDict++OCR Deployment「安装」</a></li><li class="list-group-item title"><a href="https://www.autoptr.top/gdocr/GoldenDict-OCR-How-to-Isolate-CSS/" style="border-bottom:none" title="GoldenDict++样式表隔离,如何CSS现定于特定词典或不影响其它词典">GoldenDict++ CSS Isolate「词典的样式表隔离」</a></li><li class="list-group-item title"><a href="https://www.autoptr.top/gdocr/mutex-performance-difference/" style="border-bottom:none" title="关于GoldenDict++查询性能提升的一点思考,std::recursive_mutex 和 std::mutex 性能差异">关于GoldenDict++查询性能提升的一点思考</a></li><li class="list-group-item title"><a href="https://www.autoptr.top/gdocr/wiki/" data-series="GoldenDict++OCR「划词版」" style="border-bottom:none;color:#428bca">GoldenDict Wiki &amp; Posts「Wik和网络引文」</a></li><li class="list-group-item title"><a href="https://www.autoptr.top/gdocr/cn/" data-series="GoldenDict++OCR「划词版」" style="border-bottom:none;color:#428bca">GoldenDict++ Chinese Docs「箐典·使用说明」</a></li><li class="list-group-item title"><a href="https://www.autoptr.top/gdocr/en/" data-series="GoldenDict++OCR「划词版」" style="border-bottom:none;color:#428bca">GoldenDict++ English Docs「箐典·HOWTO」</a></li></ul>
