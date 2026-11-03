# dsh

这个仓库用来试用 [dsh-superagent-prototype](https://github.com/deepseek-ai/dsh-superagent-prototype)：一个会自己接活、自己开分支、自己提 PR 的智能体。

## 怎么用

1. 在 Issue 或评论里 @ 智能体账号，写清楚你要它做什么。
2. 它会在自己的 DSH Session 里干活，完成后回到原对话回复，需要改代码时推分支并开 PR。
3. 只有白名单里的账号的 @ 才算数。

## 当前内容

- `index.mjs`：一个演示用的最小程序，方便验证"让智能体改一句话"这条链路。
- 想改什么直接开 Issue 就行。
