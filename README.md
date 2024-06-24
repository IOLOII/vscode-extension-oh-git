# Oh! Git
<img src="icons8-git-150.png">

> Here are some extension for git which may give you better experience.

## ? When you install this pack, what you will get for git

* **Visualization operation**
* **More convenient operation**
* **More aesthetically pleasing and intuitive submission**
* **Qucik add or append gitignore  (with Ctrl+Shift+P or F1)**
* **Inline commit message**


# How to set with these extensions?

Here ars some tips: (paste into setting.json)

## mhutchie.git-graph

```json
"git-graph.date.type": "Commit Date",
"git-graph.graph.colours": [
  "#04ff8e",
  "#ce2d35",
  "#2386ff",
  "#ffe609",
  "#ff5100",
  "#6a5bcd",
  "#ff6bb5",
  "#f8f8ff",
  "#9acd32"
],
"git-graph.repository.commits.fetchAvatars": true
```

## rioukkevin.vscode-git-commit

```json
"vscodeGitCommit.template": [
  "{prefix} {message}"
],
"vscodeGitCommit.variables": {
  "prefix": "QuickPickItem",
  "QuickPickItem": [
    {
      "label": "🌟",
      "detail": "增加,开发新的功能【模块组件】"
    },
    {
      "label": "🎨",
      "detail": "开发,增加,拓展新的【功能】或【样式】调整"
    },
    {
      "label": "🩹",
      "detail": "调整,【补丁】,打补丁,对于一些需要【优化】的内容或者【细节调整】,即没有更新,也没有修复,"
    },
    {
      "label": "👷‍♂️",
      "detail": "修复,修复bug👷‍♂️,【发现】项目中的问题"
    },
    {
      "label": "📝",
      "detail": "【改错】"
    },
    {
      "label": "🐛",
      "detail": "修复,修复bug🐛,【线上】产生的bug"
    },
    {
      "label": "✅",
      "detail": "【发布版本】"
    },
    {
      "label": "📝",
      "detail": "备忘录,【计划】事项,todo"
    },
    {
      "label": "🏷️",
      "detail": "发布标签【tag】"
    },
    {
      "label": "⏪",
      "detail": "【回退】"
    },
    {
      "label": "🧪",
      "detail": "【测试】功能，增加测试"
    },
    {
      "label": "📄",
      "detail": "对【文档笔记】更改"
    },
    {
      "label": "⚙️",
      "detail": "对【配置】性文件的修改"
    },
    {
      "label": "💭",
      "detail": "想法,【计划】,dev分之中未来【将要实现】或刚开始写【未完成】的功能"
    },
    {
      "label": "⚠️🪧",
      "detail": "注意⚠️ 【提示】内容"
    },
    {
      "label": "🪦",
      "detail": "【放弃】,功能【无效】,版本功能或release合并后出现【不满意】"
    },
    {
      "label": "👨🏻‍💻",
      "detail": "https://www.emojiall.com/zh-hans/all-emojis"
    }
  ]
}

```

## waderyan.gitblame
```json
"gitblame.statusBarMessageClickAction": "Open git show",
"gitblame.ignoreWhitespace": true,
"gitblame.inlineMessageEnabled": true,
"gitblame.inlineMessageFormat": "👨🏻‍💻${author.name} 🧸${time.ago} ${commit.summary}",
"gitblame.inlineMessageNoCommit": "🏄🏻‍♂️",
"gitblame.statusBarMessageFormat": "${author.name}👨🏻‍💻 ${time.ago}🧸",
"gitblame.statusBarMessageNoCommit": "🏄🏻‍♂️"
```

## donjayamanne.githistory

No need for excessive settings

## arturock.gitstash

No need for excessive settings

## codezombiech.gitignore

No need for excessive settings

# Why not add GitLens ?

It's a bit complicated, I don't need too many features. I want more disposable, simple and convenient to configure, personalized

# License

[MIT License](https://github.com/IOLOII/IOLOII-vscode-theme/blob/master/LICENSE)

**Enjoy!**

<a target="_blank" href="https://icons8.com/icon/38389/git">Git</a> icon by <a target="_blank" href="https://icons8.com">Icons8</a>
