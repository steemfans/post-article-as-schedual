# Post Article as Schedual to Steem

1. Open this repo [https://github.com/steemfans/post-article-as-schedual](https://github.com/steemfans/post-article-as-schedual).
2. Click **Use this template** button. Write a name for your repo.
3. Then open the repo **Settings** and click **Actions** -> **General** on the left panel. Then find **Workflow permissions** part. Select **Read and write permissions** and **Save**.
4. On the left panel in the **Settings** page, click **Secrets** -> **Actions** -> **New repository secret**. 
Here, you need set three key-value pairs. 
 * **USERNAME**: This is your steem account name.
 * **POSTING_KEY**: This is your steem account posting key.
 * **TZ**: This is your local timezone. example: Asia/Shanghai. Please refer to this: [https://timezonedb.com/time-zones](https://timezonedb.com/time-zones).
5. Now you can add issue to schedual your posting action. There is an issue template you could reference.

> **Attention! The github action schedual is not precision because of the huge queued jobs on all Github platform.**

# Issue Template

```
---
title: Your article title
tags: Your article tags, example: tag1,tag2,tag3
reward: Detail instruction is here ([https://github.com/steemfans/post-to-steem-action#reward](https://github.com/steemfans/post-to-steem-action#reward))
date: Your schedual posting date. The format MUST be *YYYY-MM-DD hh:mm:ss*, example: 2022-04-01 00:01:10
---
Your article content starts here.
```

# Video Tutorial

[![The tutorial of how to use Post-Article-as-Schedual tool](https://i.ytimg.com/vi/AXPfPiPQVJg/hqdefault.jpg)](https://www.youtube.com/watch?v=AXPfPiPQVJg)

# Other Thing

Any question, please feel free to create an issue on here
=> [https://github.com/steemfans/post-article-as-schedual/issues](https://github.com/steemfans/post-article-as-schedual/issues).

If you think this tool is awesome, please give me a witness vote.
Thank you!

My witness name: **ety001**.

or use direct link to vote:
[https://auth.steem.fans/sign/account_witness_vote?approve=1&witness=ety001](https://auth.steem.fans/sign/account_witness_vote?approve=1&witness=ety001)

---

# 按照计划发文到 Steem

1. 访问这个仓库 [https://github.com/steemfans/post-article-as-schedual](https://github.com/steemfans/post-article-as-schedual).
2. 点击 **Use this template** 按钮. 给你的这个仓库起个名字，然后创建.
3. 打开这个仓库的 **Settings** 页面，在左边栏点击 **Actions** -> **General**，找到 **Workflow permissions** 部分，选择 **Read and write permissions** 并 **Save**.
4. 在 **Settings** 页面左边栏, 依次点击 **Secrets** -> **Actions** -> **New repository secret**. 在这里, 
你需要添加三组 key-value 对. 
 * **USERNAME**: 你的 Steem 用户名.
 * **POSTING_KEY**: 你的 Steem 账户的 Posting Key.
 * **TZ**: 你的当地时区. 例如: Asia/Shanghai. 具体可以参考这里: [https://timezonedb.com/time-zones](https://timezonedb.com/time-zones)
5. 现在你可以添加 issue 来安排你的发文计划了. 在添加新的 issue 的时候，会有一个模板供你参考.

> **注意! Github action 由于使用的人太多, 他的计划任务的时间并不精确.**

# Issue 模板

```
---
title: Your article title
tags: Your article tags, example: tag1,tag2,tag3
reward: Detail instruction is here ([https://github.com/steemfans/post-to-steem-action#reward](https://github.com/steemfans/post-to-steem-action#reward))
date: Your schedual posting date. The format MUST be *YYYY-MM-DD hh:mm:ss*, example: 2022-04-01 00:01:10
---
Your article content starts here.
```

# 视频教程

[![The tutorial of how to use Post-Article-as-Schedual tool](https://i.ytimg.com/vi/AXPfPiPQVJg/hqdefault.jpg)](https://www.bilibili.com/video/BV1zv4y1N7PE?share_source=copy_web)

# 其他

如果有任何问题，请到这里提交 issue
=> [https://github.com/steemfans/post-article-as-schedual/issues](https://github.com/steemfans/post-article-as-schedual/issues).

如果你觉得这个小玩意很赞，欢迎投票，多谢！

我的用户名是: **ety001**.

或者你也可以直接使用下面的链接进行投票:
[https://auth.steem.fans/sign/account_witness_vote?approve=1&witness=ety001](https://auth.steem.fans/sign/account_witness_vote?approve=1&witness=ety001)

