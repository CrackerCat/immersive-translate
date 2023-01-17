# 沉浸式双语网页翻译扩展

## 主要特性

- 智能识别网页主内容区，区别于同类插件翻译整个网页所有的区域，这极大的增强了翻译后的网页阅读体验。类似浏览器的沉浸式阅读模式，所以该扩展被命名为“沉浸式翻译”
- 双语显示，中文/英文对照着看（按照段落分割，或者自定义段落长度，自动为长段落按照每句话换行）
- 为常用网站做了定制优化，比如 Twitter，Reddit，Discord, Gmail, Telegram, Youtube, Hacker News 等，这些网站并不是常规的内容网站，所以定制优化后，翻译的区域非常智能。
- 支持 10+种常见的翻译服务，包括 Deepl, 谷歌, 腾讯翻译君,火山翻译，彩云小译等等.
- PDF 文件双语翻译支持
- 配合 epub 在线阅读网站<https://1paragraph.app/> 或 <https://readwise.io/read> 即可实现双语阅读国外电子书
- 多种译文样式可选择，个性化你的翻译体验。

该扩展完全免费使用，[点击查看视频介绍](https://www.youtube.com/watch?v=sQevumpUprc)，希望我们都能平等的获取互联网上巨大的外语信息，不要让语言成为障碍 ❤️

感谢这些[赞助者](https://immersive-translate.owenyoung.com/thanks), 由于他/她们的支持，更多的人可以免费使用这个工具。如果有余力，你可以[点击这里](https://immersive-translate.owenyoung.com/donate) 赞助我的工作，你也可以关注我的[推特](https://twitter.com/OwenYoungZh)获取最新更新。

## 目录

- [安装](https://immersive-translate.owenyoung.com/installation.html)
- [如何使用](https://immersive-translate.owenyoung.com/usage.html)
- [高级自定义配置](https://immersive-translate.owenyoung.com/advanced.html)
- [更新日志](https://immersive-translate.owenyoung.com/CHANGELOG.html)
- [反馈问题](https://github.com/immersive-translate/next-immersive-translate/issues)
- [☕️ 请开发者喝杯咖啡](https://immersive-translate.owenyoung.com/donate.html)
- [加入 Telegram 群组](https://t.me/+rq848Z09nehlOTgx) 参与功能的讨论。
- [在线文档](https://immersive-translate.owenyoung.com/)

## 安装

### Chrome/类 Chrome 浏览器

已提交商店审核，应该马上会通过。 当前请参考下方`手动安装`的说明进行安装。

### Edge

已上架 Edge 扩展商店，请点击[这里](https://microsoftedge.microsoft.com/addons/detail/%E6%B2%89%E6%B5%B8%E5%BC%8F%E7%BF%BB%E8%AF%91/amkbmndfnliijdhojkpoglbnaaahippg?hl=zh-CN&gl=CN)安装即可。

### Firefox

已上架 Firefox Addon 商店，点击[这里](https://addons.mozilla.org/zh-CN/firefox/addon/immersive-translate/) 安装。

### Safari

桌面版和移动版都支持，需要配合油猴插件安装,以[Userscripts](https://itunes.apple.com/us/app/userscripts/id1463298887)为例:

1. 安装[Userscripts safari 插件](https://itunes.apple.com/us/app/userscripts/id1463298887)，并且授予其始终允许访问任何网站的权限。
2. 安装本扩展的[油猴脚本](https://immersive-translate.owenyoung.com/immersive-translate.user.js)

安装后，打开任意网页，刷新一下之后，会有沉浸式翻译扩展的浮动窗口在浮动在右侧。(safari 扩展首次安装之后，如果遇到没有出现浮窗的问题，建议多刷新一下网页，或者强制重启一下 Safari，以使其生效)

如果你以前没有使用过油猴脚本，可以点击参考[视频教程](https://youtu.be/vOaCFjYmQNM)

### Android 安卓

1. 下载[Firefox Nightly](https://play.google.com/store/apps/details?id=org.mozilla.fenix&hl=en_US&gl=US)版本
2. 在 Firefox 的附加组件推荐里找到[Tamper Monkey](https://www.tampermonkey.net/),安装
3. 安装本扩展的[油猴脚本](https://immersive-translate.owenyoung.com/immersive-translate.user.js)

安装后，打开任意网页，会有该扩展的浮动窗口在右侧。

### 其他移动浏览器

比如 Kiwi 浏览器等等，只要支持油猴脚本的浏览器，都可以通过油猴脚本安装本扩展。

### 油猴脚本 GreasyFork 地址

你也可以通过[Greasy Fork](https://greasyfork.org/zh-CN/scripts/457196-immersive-translate) 商店安装油猴脚本，但是缺点是 [Userscripts](https://itunes.apple.com/us/app/userscripts/id1463298887) 似乎不支持 Greasyfork 托管的脚本的自动更新，因为 GreasyFork 不允许填写 `updateURL` 属性。

### 手动安装

> 手动安装的话，无需等待商店审核，立即体验最新开发版本的功能。

所有代码已经打包上传到 Github 仓库了, 使用以下命令加载到本地：

```
git clone https://github.com/immersive-translate/next-immersive-translate.git
```

扩展位于`dist/chrome`, `dist/firefox`, `dist/userscript` 中。

**Chrome 手动安装**

1. 打开扩展管理窗口，`chrome://extensions`
2. 激活开发者模式
3. 载入`dist/chrome`

**Firefox 手动安装**

1. 打开`about:debugging#/runtime/this-firefox`
2. 临时载入附加组件
3. 选择`dist/firefox/manifest.json`即可

## 截图

![screenshot](https://immersive-translate.owenyoung.com/assets/twitter.png)

[点这里](https://immersive-translate.owenyoung.com/usecase.html)查看更多截图

## 赞助我的工作

我喜欢为“穷人”创造工具，因为我在免费的互联网工具和内容中学到了很多，我从心底里相信平等地获取知识是每个人最应拥有的权利。

前几天看到阿玛蒂亚·森的一句话：“考察一个人的判断力，主要考察他信息来源的多样性。有无数的可怜人，长期活在单一的信息里，而且是一种被扭曲，颠倒的信息，这是导致人们愚昧且自信的最大原因。” 鉴于中文互联网显而易见的信息审查，污染和控制，我们更应该让自己尽可能多的获取不同的信息源，所以我创建了一些免费的双语工具来帮助人们更有效的获取互联网上巨大的英文信息源。

我创建了 <https://www.buzzing.cc/> ，这是一款聚合外网可信度高的权威媒体以及社交媒体里的热门讨论，我使用 Deepl 将标题翻译为中文，以便母语使用者可以快速浏览以获得自己感兴趣的内容。没有废话，没有登录，有良好的 RSS 支持，以及最大化页面的信息密度。同时也支持无图模式，以减少分心。

我还创建了 [沉浸式双语翻译扩展](https://immersive-translate.owenyoung.com/) , 这是一款浏览器网页双语翻译扩展，智能识别绝大多数网页的主内容，自动按照每一个段落双语翻译，支持 10 多个翻译引擎，以及几乎所有浏览器平台，甚至包括 Safari 移动版，Firefox nightly 安卓版等等。我希望中文用户能够通过此扩展获取更多，更高质量的信息源。

我还创建了一些其他的免费工具，你可以[点击这里](https://www.owenyoung.com/projects/)了解我所有的项目。

非常感谢你的支持，由于你的支持，可以让更多的人平等的获取这些宝贵的知识。

> PS. 我比预想中花了巨大的时间和精力开发[沉浸式双语翻译扩展](https://immersive-translate.owenyoung.com/)，你的支持对我的工作非常重要，谢谢！

### 月度赞助链接

我已开通了 [Github Sponsor 主页](https://github.com/sponsors/theowenyoung?frequency=recurring), 点击[这里](https://github.com/sponsors/theowenyoung?frequency=recurring)可以进行月度赞助，$1 起即可小额支持，支持 Paypal，以及 Stripe 支付（貌似 Stripe 需要外币信用卡，比如 Visa/万事达）

> 你也可以选择[Patreon 平台](https://www.patreon.com/theowenyoung) 进行赞助，$1 起即可小额支持，同样支持 Paypal，以及信用卡。

### 一次性赞助

点击[我的 Github Sponsor 主页](https://github.com/sponsors/theowenyoung?frequency=one-time) ，$2 起即可小额支持，支持 Paypal，以及信用卡支付。

### 加密货币一次性赞助

1. USDT 或 USDC 或 ETH (ERC20): `0xA9e3dE8C304D907F92E6C73E21D07Cd3f2f2D708`

<details>
<summary>点击展开二维码</summary>
<img src="https://immersive-translate.owenyoung.com/usdt-erc20-immersive-translate-400.jpg" alt="qrcode"></img>
</details>

2. USDT 或 USDC (TRC20): `TRWaYy8Z3Gnydm1mpKetX7ahwCbFqRszv6`

<details>
<summary>点击展开二维码</summary>
<img src="https://immersive-translate.owenyoung.com/usdt-trc20-immersive-translate-400.jpg" alt="qrcode"></img>
</details>

### 其他

你还可以通过帮忙翻译[界面语言](https://crowdin.com/project/immersive-translate)来帮助这个项目

或者加入[Telegram 群组](https://t.me/+rq848Z09nehlOTgx) 参与功能的讨论。

## Links

- [Github](https://github.com/immersive-translate/immersive-translate/)
- [在线文档](https://immersive-translate.owenyoung.com/)
