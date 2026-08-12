# decide-content-topics

一个帮自媒体创作者筛选信息、比较选题并生成选题立项卡的 Skill。

热点太多，不知道该做哪个？把你的账号定位、近期内容和一批信息交给它。它会先淘汰不适合的内容，再给候选选题评分，最后整理成一张可以继续写脚本的选题立项卡。

## 它会生成什么

1. `08-信息筛选表.md`：每条信息是进入候选、继续观察还是淘汰。
2. `09-候选选题比较.md`：最多三个候选，包含评分、风险和反对理由。
3. `10-选题立项卡.md`：记录最终题目、证据边界、观众能带走什么，以及下一步写稿要求。

进入候选和生成立项卡之前，它都会停下来等你确认。AI 负责整理和比较，最后做不做还是由你决定。

## 怎么开始

1. 从 [Releases](https://github.com/Damonhhh/decide-content-topics/releases) 下载 `decide-content-topics-v0.1-skill.zip`。
2. 解压后，确认 `decide-content-topics` 文件夹里直接包含 `SKILL.md`。
3. 按你所用 AI 客户端的方式导入或放进 Skill 目录。
4. 准备账号定位、近期内容和带来源的信息快照。
5. 对它说：`结合我的账号定位和近期内容，先筛选这批信息，不要直接写稿。`

没有真实资料时，可以先用 [`assets/example-project`](skill/decide-content-topics/assets/example-project) 中的虚构案例试跑。空白模板位于 [`assets/templates`](skill/decide-content-topics/assets/templates)。

## 它不负责什么

- 实时抓取热点；
- 从零设计账号定位；
- 直接写完整口播稿；
- 剪辑、渲染或自动发布。

这套 Skill 来自一条已经实际跑通过的自媒体选题流程。v0.1 仍需要你根据自己的账号和行业调整输入资料、评分要求与风险边界。

## 许可证

[MIT](LICENSE) © 2026 Damon
