# Post Article as Schedual to Steem

1. Fork this repo [https://github.com/steemfans/post-article-as-schedual](https://github.com/steemfans/post-article-as-schedual).
2. After forked, go to your forked repo's **Settings** panel.
3. In the **General** settings, enable **Issues** in **Features**.
4. Then on the left side, click **Secrets** -> **Actions** -> **New repository secret**. Here, you need set three key-value pairs.
* **USERNAME**: This is your steem account name.
* **POSTING_KEY**: This is your steem account posting key.
* **TZ**: This is your local timezone. example: Asia/Shanghai. Please refer to this: [https://timezonedb.com/time-zones](https://timezonedb.com/time-zones).
5. Go to **Actions** panel. Click **I understand my workflows, go ahead and enable them**.
6. In the next page, click **Post to Steem Schedual**, you will see **This scheduled workflow is disabled because scheduled workflows are disabled by default in forks**. Click **Enable workflow**.
7. Now you can add issue to schedual your posting action. There is an issue template you could reference.

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

1. 克隆这个仓库 [https://github.com/steemfans/post-article-as-schedual](https://github.com/steemfans/post-article-as-schedual).
2. 克隆完成后, 进入你克隆的仓库的 **Settings** 面板.
3. 在 **General** 中, 找到 **Features**, 启用 **Issues**.
4. 在左边栏, 依次点击 **Secrets** -> **Actions** -> **New repository secret**. 在这里, 你需要添加三组 key-value 对.
* **USERNAME**: 你的 Steem 用户名.
* **POSTING_KEY**: 你的 Steem 账户的 Posting Key.
* **TZ**: 你的当地时区. 例如: Asia/Shanghai. 具体可以参考这里: [https://timezonedb.com/time-zones](https://timezonedb.com/time-zones)
5. 点击 **Actions** 面板，再点击 **I understand my workflows, go ahead and enable them**.
6. 在下个页面, 点击 **Post to Steem Schedual** 后你会看到 **This scheduled workflow is disabled because scheduled workflows are disabled by default in forks**, 点击 **Enable workflow**.
7. 现在你可以添加 issue 来安排你的发文计划了. 在添加新的 issue 的时候，会有一个模板供你参考.

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

# 其他

如果有任何问题，请到这里提交 issue
=> [https://github.com/steemfans/post-article-as-schedual/issues](https://github.com/steemfans/post-article-as-schedual/issues).

如果你觉得这个小玩意很赞，欢迎投票，多谢！

我的用户名是: **ety001**.

或者你也可以直接使用下面的链接进行投票:
[https://auth.steem.fans/sign/account_witness_vote?approve=1&witness=ety001](https://auth.steem.fans/sign/account_witness_vote?approve=1&witness=ety001)
