# Learn Mindustry Mod

本仓库是Mindustry游戏mod开发教程的Github.io静态页面。

## 编写
使用IDEA/VSCODE直接编辑markdown，使用`pnpm dev`进行预览。

## 栏目
- Java 教程：`docs/java/`（`/java`）
- JavaScript 教程：`docs/Javascript/`（`/Javascript`）
- Json 教程：`docs/json/`（`/json`），包含：
  - 人工前言：`docs/json/index.md`
  - Gemini 版：`docs/json/json_gemini/`
  - GPT 版：`docs/json/json_gpt/`
- 贴图：`docs/sprite/`（`/sprite`）
- 组件沙盒：`docs/sandbox.md`
- 孤页：`docs/多合成工厂库.md`（未加入侧边栏，仅可通过直接链接访问）

## 编写规范
- 每个章节文件的标题使用Markdown的一级标题，章内小节使用二级标题
- 各文件夹的`index.md`中写入该组标题（如`# 前言`、`# Gemini版`）
- 图片使用相对路径引用

## 组件
see [docs/sandbox.md](docs/sandbox.md)
### Tabs
```markdown
:::: tabs 

::: tab apple

::: 

::: tab "banana" id="banana"

::: 

::::
```
### GitHubCard
```markdown
<GitHubCard repo="learn-mindustry-mod/learn-mindustry-mod.github.io"/>
```

用`”[^“”，。、：的与非和而 ]+?“` `“[^“”，。、：的与非和而 ]+?“` `”[^“”，。、：的与非和而 ]+?”`来检查有没有反向的引号
