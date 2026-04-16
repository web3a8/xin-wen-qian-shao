# 新闻前哨

一个 AI 驱动的新闻采集站，提供 RSS 订阅源，地址：[https://web3a8.github.io/xin-wen-qian-shao/](新闻前哨)。

目前新闻总结的重点是 AI 领域，后续可能会拓展到更多。

如果想自己做总结，可以使用我的订阅源获取新闻，交给龙虾或Claude code做总结。

## 这个项目能做什么

- 聚合多类新闻源：目前有100+，后面会持续添加更多信源。
- 对外提供统一 RSS 订阅源，适合接入阅读器、自动化工具或个人信息流。
- 提供一个简洁的 Web 页面，按信源浏览最新内容，并展示 AI 生成的总结、事件和洞察。

## 当前概览

- 信源总数：`185`
- 抓取方式：`161` 个直连 RSS，`23` 个 RSSHub，`1` 个 Playwright
- 仓库地址：[https://github.com/web3a8/xin-wen-qian-shao](https://github.com/web3a8/xin-wen-qian-shao)

## 使用方式

- 想直接订阅：使用 `dist/rss.xml`。
- 想快速浏览：打开站点首页，按信源筛选并查看 AI 总结。
- 想接自己的系统：把 RSS 当作公开输入层，再按需做二次处理。

## 信源清单

下面的表格来自项目当前的信源配置，按主题分组展示。

### AI 深读（25）

| 信源 | 订阅地址 |
| --- | --- |
| A List Apart | `https://alistapart.com/main/feed/` |
| abortretry.fail | `https://www.abortretry.fail/feed` |
| aresluna.org | `https://aresluna.org/main.rss` |
| arXiv AI | `https://rss.arxiv.org/rss/cs.AI` |
| daringfireball.net | `https://daringfireball.net/feeds/main` |
| Google AI Blog | `https://blog.google/technology/ai/rss/` |
| Google DeepMind | `https://deepmind.google/blog/rss.xml` |
| Hacker News | `https://news.ycombinator.com/rss` |
| Hacker News AI | `https://hnrss.org/newest?q=AI` |
| Hacker News Ask | `https://hnrss.org/ask` |
| Hacker News LLM | `https://hnrss.org/newest?q=LLM` |
| Hacker News OpenClaw | `https://hnrss.org/newest?q=OpenClaw` |
| Hacker News Show | `https://hnrss.org/show` |
| Hacker News 最佳 | `https://hnrss.org/best` |
| Hacker News 首页 | `https://hnrss.org/frontpage` |
| Hugging Face 博客 | `https://huggingface.co/blog/feed.xml` |
| Kotlin Blog | `https://blog.jetbrains.com/kotlin/feed/` |
| MarkTechPost | `https://www.marktechpost.com/` |
| OpenAI 博客 | `https://openai.com/news/rss.xml` |
| OpenClaw Commits | `https://github.com/openclaw/openclaw/commits/main.atom` |
| philiplaine.com | `https://philiplaine.com/index.xml` |
| Tailwind CSS Blog | `https://tailwindcss.com/feeds/feed.xml` |
| The Hacker News | `https://feeds.feedburner.com/TheHackersNews` |
| 少数派 | `https://sspai.com/feed` |
| 第一财经最新 | - |

### 热榜（26）

| 信源 | 订阅地址 |
| --- | --- |
| geohot.github.io | `https://geohot.github.io/blog/feed.xml` |
| IT之家 24h | - |
| LinuxDo 热门话题 | `https://linux.do/top.rss` |
| Readhub 热门 | - |
| V2EX 最热 | - |
| 今日热榜 - 36氪 | - |
| 今日热榜 - IT之家 | - |
| 今日热榜 - 今日头条 | - |
| 今日热榜 - 哔哩哔哩 | - |
| 今日热榜 - 少数派 | - |
| 今日热榜 - 微博 | - |
| 今日热榜 - 澎湃新闻 | - |
| 今日热榜 - 百度贴吧 | - |
| 今日热榜 - 知乎 | - |
| 今日热榜 - 稀土掘金 | - |
| 今日热榜 - 腾讯新闻 | - |
| 华尔街见闻实时快讯 | - |
| 华尔街见闻最热 | - |
| 少数派 Matrix | - |
| 微博热搜 | - |
| 效率火箭 | `https://rss.aishort.top/?type=xlrocket` |
| 澎湃新闻头条 | - |
| 爱范儿 | `https://rss.aishort.top/?type=AppSolution` |
| 百度热搜 | - |
| 知乎热榜 | - |
| 第一财经头条 | - |

### 综合（133）

| 信源 | 订阅地址 |
| --- | --- |
| anildash.com | `https://anildash.com/feed.xml` |
| antirez.com | `http://antirez.com/rss` |
| Ars Technica | `https://feeds.arstechnica.com/arstechnica/index` |
| arXiv NLP | `https://rss.arxiv.org/rss/cs.CL` |
| arXiv 机器学习 | `https://rss.arxiv.org/rss/cs.LG` |
| arXiv 计算机视觉 | `https://rss.arxiv.org/rss/cs.CV` |
| AWS Blog | `https://aws.amazon.com/blogs/aws/feed/` |
| beej.us | `https://beej.us/blog/rss.xml` |
| bernsteinbear.com | `https://bernsteinbear.com/feed.xml` |
| berthub.eu | `https://berthub.eu/articles/index.xml` |
| blog.jim-nielsen.com | `https://blog.jim-nielsen.com/feed.xml` |
| blog.pixelmelt.dev | `https://blog.pixelmelt.dev/rss/` |
| bogdanthegeek.github.io | `https://bogdanthegeek.github.io/blog/index.xml` |
| borretti.me | `https://borretti.me/feed.xml` |
| brutecat.com | `https://brutecat.com/rss.xml` |
| buttondown.com/hillelwayne | `https://buttondown.com/hillelwayne/rss` |
| ByteByteGo | `https://blog.bytebytego.com/feed` |
| chadnauseam.com | `https://chadnauseam.com/rss.xml` |
| chiark.greenend.org.uk/~sgtatham | `https://www.chiark.greenend.org.uk/~sgtatham/quasiblog/feed.xml` |
| Chrome Developer Blog | `https://developer.chrome.com/blog/feed.xml` |
| Cloudflare Blog | `https://blog.cloudflare.com/rss/` |
| Codrops | `https://tympanus.net/codrops/feed/` |
| computer.rip | `https://computer.rip/rss.xml` |
| construction-physics.com | `https://www.construction-physics.com/feed` |
| CSS-Tricks | `https://css-tricks.com/feed/` |
| danielchasehooper.com | `https://danielchasehooper.com/feed.xml` |
| danieldelaney.net | `https://danieldelaney.net/feed` |
| danielwirtz.com | `https://danielwirtz.com/rss.xml` |
| derekthompson.org | `https://www.theatlantic.com/feed/author/derek-thompson/` |
| Dev.to | `https://dev.to/feed` |
| devblogs.microsoft.com/oldnewthing | `https://devblogs.microsoft.com/oldnewthing/feed` |
| dfarq.homeip.net | `https://dfarq.homeip.net/feed/` |
| downtowndougbrown.com | `https://www.downtowndougbrown.com/feed/` |
| dwarkesh.com | `https://www.dwarkeshpatel.com/feed` |
| dynomight.net | `https://dynomight.net/feed.xml` |
| eli.thegreenplace.net | `https://eli.thegreenplace.net/feeds/all.atom.xml` |
| entropicthoughts.com | `https://entropicthoughts.com/feed.xml` |
| ericmigi.com | `https://ericmigi.com/rss.xml` |
| evanhahn.com | `https://evanhahn.com/feed.xml` |
| experimental-history.com | `https://www.experimental-history.com/feed` |
| fabiensanglard.net | `https://fabiensanglard.net/rss.xml` |
| filfre.net | `https://www.filfre.net/feed/` |
| Fluent Reader Releases | `https://github.com/yang991178/fluent-reader/releases.atom` |
| FreeBuf | `https://www.freebuf.com/feed` |
| FreshRSS Releases | `https://github.com/FreshRSS/FreshRSS/releases.atom` |
| garymarcus.substack.com | `https://garymarcus.substack.com/feed` |
| geoffreylitt.com | `https://www.geoffreylitt.com/feed.xml` |
| gilesthomas.com | `https://gilesthomas.com/feed/rss.xml` |
| GitHub Blog | `https://github.blog/feed/` |
| Go Blog | `https://go.dev/blog/feed.atom` |
| Golang Weekly | `https://golangweekly.com/rss/` |
| grantslatton.com | `https://grantslatton.com/rss.xml` |
| gwern.net | `https://gwern.substack.com/feed` |
| herman.bearblog.dev | `https://herman.bearblog.dev/feed/` |
| hey.paris | `https://hey.paris/index.xml` |
| hugotunius.se | `https://hugotunius.se/feed.xml` |
| idiallo.com | `https://idiallo.com/feed.rss` |
| it-notes.dragas.net | `https://it-notes.dragas.net/feed/` |
| IT之家 | `https://www.ithome.com/rss/` |
| JavaScript Weekly | `https://javascriptweekly.com/rss/` |
| jayd.ml | `https://jayd.ml/feed.xml` |
| jeffgeerling.com | `https://www.jeffgeerling.com/blog.xml` |
| joanwestenberg.com | `https://joanwestenberg.com/rss` |
| johndcook.com | `https://www.johndcook.com/blog/feed/` |
| jyn.dev | `https://jyn.dev/atom.xml` |
| keygen.sh | `https://keygen.sh/blog/feed.xml` |
| Krebs on Security | `https://krebsonsecurity.com/feed/` |
| lcamtuf.substack.com | `https://lcamtuf.substack.com/feed` |
| LinuxDo 最新话题 | `https://linux.do/latest.rss` |
| lucumr.pocoo.org | `https://lucumr.pocoo.org/feed.atom` |
| martinalderson.com | `https://martinalderson.com/feed.xml` |
| matduggan.com | `https://matduggan.com/rss/` |
| matklad.github.io | `https://matklad.github.io/feed.xml` |
| maurycyz.com | `https://maurycyz.com/index.xml` |
| Meta Engineering | `https://engineering.fb.com/feed/` |
| micahflee.com | `https://micahflee.com/feed/` |
| michael.stapelberg.ch | `https://michael.stapelberg.ch/feed.xml` |
| miguelgrinberg.com | `https://blog.miguelgrinberg.com/feed` |
| minimaxir.com | `https://minimaxir.com/index.xml` |
| MIT Technology Review | `https://www.technologyreview.com/feed/` |
| mitchellh.com | `https://mitchellh.com/feed.xml` |
| mjg59.dreamwidth.org | `https://mjg59.dreamwidth.org/data/rss` |
| Mozilla Hacks | `https://hacks.mozilla.org/feed/` |
| Nature | `https://www.nature.com/nature.rss` |
| nesbitt.io | `https://nesbitt.io/feed.xml` |
| NetNewsWire Releases | `https://github.com/Ranchero-Software/NetNewsWire/releases.atom` |
| oldvcr.blogspot.com | `https://oldvcr.blogspot.com/feeds/posts/default` |
| OpenClaw Releases | `https://github.com/openclaw/openclaw/releases.atom` |
| overreacted.io | `https://overreacted.io/rss.xml` |
| paulgraham.com | `http://www.aaronsw.com/2002/feeds/pgessays.rss` |
| pluralistic.net | `https://pluralistic.net/feed/` |
| Product Hunt | `https://www.producthunt.com/feed` |
| Python Blog | `https://blog.python.org/feeds/posts/default` |
| rachelbythebay.com | `https://rachelbythebay.com/w/atom.xml` |
| rakhim.exotext.com | `https://rakhim.exotext.com/rss.xml` |
| React Blog | `https://react.dev/rss.xml` |
| refactoringenglish.com | `https://refactoringenglish.com/index.xml` |
| righto.com | `https://www.righto.com/feeds/posts/default` |
| RSSHub Radar Releases | `https://github.com/DIYgod/RSSHub-Radar/releases.atom` |
| Rust Blog | `https://blog.rust-lang.org/feed.xml` |
| Schneier on Security | `https://www.schneier.com/feed/` |
| seangoedecke.com | `https://www.seangoedecke.com/rss.xml` |
| shkspr.mobi | `https://shkspr.mobi/blog/feed/` |
| Simon Willison's Blog | `https://simonwillison.net/atom/everything/` |
| simone.org | `https://simone.org/feed/` |
| skyfall.dev | `https://skyfall.dev/rss.xml` |
| Smashing Magazine | `https://www.smashingmagazine.com/feed/` |
| Spotify Engineering | `https://engineering.atspotify.com/feed/` |
| steveblank.com | `https://steveblank.com/feed/` |
| Stripe Blog | `https://stripe.com/blog/feed.rss` |
| susam.net | `https://susam.net/feed.xml` |
| Swift Blog | `https://www.swift.org/atom.xml` |
| TechCrunch | `https://techcrunch.com/feed/` |
| tedium.co | `https://feed.tedium.co/` |
| tedunangst.com | `https://www.tedunangst.com/flak/rss` |
| terriblesoftware.org | `https://terriblesoftware.org/feed/` |
| The Verge | `https://www.theverge.com/rss/index.xml` |
| This Week in Rust | `https://this-week-in-rust.org/atom.xml` |
| timsh.org | `https://timsh.org/rss/` |
| tomrenner.com | `https://tomrenner.com/index.xml` |
| troyhunt.com | `https://www.troyhunt.com/rss/` |
| TypeScript Blog | `https://devblogs.microsoft.com/typescript/feed/` |
| utcc.utoronto.ca/~cks | `https://utcc.utoronto.ca/~cks/space/blog/?atom` |
| V2EX 技术 | `https://www.v2ex.com/feed/tab/tech.xml` |
| Vercel Blog | `https://vercel.com/atom` |
| Vue Blog | `https://blog.vuejs.org/feed.rss` |
| wheresyoured.at | `https://www.wheresyoured.at/rss/` |
| Wired | `https://www.wired.com/feed/rss` |
| worksonmymachine.substack.com | `https://worksonmymachine.substack.com/feed` |
| xania.org | `https://xania.org/feed` |
| xeiaso.net | `https://xeiaso.net/blog.rss` |
| 安全客 | `https://api.anquanke.com/data/v1/rss` |
| 阮一峰的网络日志 | `https://www.ruanyifeng.com/blog/atom.xml` |

### 宏观（1）

| 信源 | 订阅地址 |
| --- | --- |
| 华尔街见闻最新资讯 | `https://feed.wallstreetcn.com/wallstreetcn/news/global` |

## 如果您有好的信源，欢迎提交issue
