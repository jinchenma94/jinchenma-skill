# jinchenma-skill

金尘马公开版 AI Agent Skills。

## 最快使用

把下面这句话发给你的 AI Agent，让它帮你安装：

```text
请从 https://github.com/jinchenma94/jinchenma-skill 安装 jinchenma-article-writing skill 到我的 AI Agent skills 目录。
```

## jinchenma-article-writing

这是一个文章写作辅助 skill，主要用来做三件事：

- 写文章前整理素材。
- 基于素材协作文章大纲。
- 按“金尘马式 AI 干货写作”规则检查文章方向和初稿质量。

适合这类需求：

- “我想写一篇文章，先帮我搜资料。”
- “把这些链接整理成写作素材。”
- “基于这些素材，帮我做一版大纲。”
- “这篇文章面向 AI 小白，要讲人话、实用、能照着做。”

## 怎么用

安装后，这个 skill 目录通常长这样：

```text
skills/jinchenma-article-writing/
```

然后直接对你的 AI Agent 说写作需求，例如：

```text
我想写一篇面向小白的 AI 干货文章，主题是如何让 AI 记住自己。先帮我全网搜素材，并整理成素材索引。
```

如果你没有指定保存目录，生成的素材、索引、大纲和初稿会默认放到你当前项目目录下：

```text
./jinchenma-article-writing-workspace/
```

公开版文风规则在这里：

```text
skills/jinchenma-article-writing/references/writing-style.md
```
