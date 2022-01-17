# GitBook 绑定域名

让你的书使用上属于你自己的域名，而不是 XXX.gitbook。io，可以使你的电子书更容易被触达，GitBook 能够方便地让你把自己的电子书和自己的域名进行绑定。

无论你从阿里云还是腾讯云买来属于你自己的域名，都可以很方便地把它和 GitBook 进行绑定。

在GitBook 的 `Public`界面，点击下面的「Link an d domain settings」

[![link a domain](https://cdn.ljk.cool/202201142132253.png)](https://cdn.ljk.cool/202201142132253.png)link a domain

然后选择「Connect a domain」，意思是绑定个域名

[![绑定域名](https://cdn.ljk.cool/202201142141551.png)](https://cdn.ljk.cool/202201142141551.png)绑定域名

点击之后，在下面这个框里输入你要绑定的域名，一般来说是这样的：

| <pre><code>1234567891011</code></pre> | <pre><code>举个例子：比如你买的域名是 baidu.com但其实你也同时拥有了所有 xxx.baidu.com 的域名。所以你看，如果你不绑定自己的，GitBook 给你配置的是 你的 id.gitbook.io。你要做的就是把上面提到的 「XXX」换成其它英语单词或者字母，啥都行，一般用小写单词，比如说：* books.baidu.com* docs.baidu.com* info.baidu.com不胜枚举。</code></pre> |
| ------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |

确认了自己的域名之后，填进去，比如我填的是`books.ljk.cool`，点击 `continue`

[![输入](https://cdn.ljk.cool/202201142143255.png)](https://cdn.ljk.cool/202201142143255.png)输入

[![提示配置 CNAME](https://cdn.ljk.cool/202201142149133.png)](https://cdn.ljk.cool/202201142149133.png)提示配置 CNAME

现在你就需要去做一个事情了，就是在你域名里做一些配置，看下图，点击`解析`，这里其实是把你的电子书的网址与你的域名进行绑定

[![域名解析](https://cdn.ljk.cool/202201142139135.png)](https://cdn.ljk.cool/202201142139135.png)域名解析

配置解析点击「添加记录」，有几处要填

[![添加记录](https://cdn.ljk.cool/202201142150206.png)](https://cdn.ljk.cool/202201142150206.png)添加记录

主机记录填 ：填写你自己定义的「XXX」内容，上面我说了，我写的是 books，所以我这里就填 books；

记录类型填 CNAME；

记录值把 hosting.gitbook.io 填进去，保存。这个值就出现在刚才截图里。

这些填好并保存之后，你要回来点一下 「Retry」

[![retry](https://cdn.ljk.cool/202201142153350.png)](https://cdn.ljk.cool/202201142153350.png)retry

然后等会儿你点 `Continue` 就好了。

等五分钟，你再浏览器上输入你自己定义的域名，看看有没有绑定成功吧。

\
\
