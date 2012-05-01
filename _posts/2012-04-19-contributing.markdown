---
layout: default
title: 贡献您原创的教程
permalink: contributing
---

# 贡献您原创的教程

这个教程网站是用 [jekyll](https://github.com/mojombo/jekyll) 生成的静态网页组成的，所有的文档都是用 [markdown](http://daringfireball.net/projects/markdown/) 编辑。如果您有意贡献自己原创的教程，请按照以下步骤进行：

1. Fork [repository on github](https://github.com/railsgirls/railsgirls.github.com) ，点击 “Fork” 键。
2. `git clone` 您刚创建的 fork。
3. 创建一个文件，取名为 `YYYY-MM-DD-guide_name.markdown` （如：`2012-05-01-jiaocheng——gitcafe.markdown`）将它放在您的fork中的 `_posts` 目录下。
4. 在这个文件中添加一些YAML文件头，结果应该看上去像这样：{% highlight yaml %}
---
layout: default
title: 教程的名字
permalink: one-word-summary.html
---
{% endhighlight %}
5. 将这个新教程 commit 到您的 git repository中。
6. 您的 commit 完成后，将它 push 到您的 fork 下.
7. 您现在可以创建一个 pull request ，同时解释一下您这个教程的意义。大功告成！

您可以参考我们 [Rails Girls App Tutorial](https://github.com/railsgirls/railsgirls.github.com/blob/master/_posts/2012-04-18-app.markdown) 的结构。

非常感谢您腾出宝贵的时间帮助 Rails Girls！
