# Learn Mindustry Mod
<h1 align="center">
  <a href="https://github.com/DeterMination-Wind/learn-mindustry-mod.github.io/releases/latest"><img src="https://img.shields.io/github/v/release/DeterMination-Wind/learn-mindustry-mod.github.io?display_name=release&label=Latest%20Release&color=green"></a>
  <a href="https://github.com/DeterMination-Wind/learn-mindustry-mod.github.io/releases"><img src="https://img.shields.io/github/downloads/DeterMination-Wind/learn-mindustry-mod.github.io/total?label=Downloads&color=blue"></a>
  <a href="LICENSE"><img src="https://img.shields.io/github/license/DeterMination-Wind/learn-mindustry-mod.github.io?label=License"></a>
  <a href="https://github.com/DeterMination-Wind/learn-mindustry-mod.github.io"><img src="https://img.shields.io/github/stars/DeterMination-Wind/learn-mindustry-mod.github.io?style=flat&label=Star%20this%20mod!&color=yellow"></a>
</h1>

本仓库是Mindustry游戏mod开发教程的Github.io静态页面。

## 编写
使用IDEA/VSCODE直接编辑markdown，使用`pnpm dev`进行预览。
## 编写规范
- 每节标题使用Markdown的一级标题
- 每章标题写在各文件夹`index.md`文件中
- 图片使用相对路径引用

## 组件
see sandbox.md
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