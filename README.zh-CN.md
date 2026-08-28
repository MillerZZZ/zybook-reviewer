[English](README.md) | 简体中文

# ZyBooks Auto

一个 Tampermonkey 用户脚本，自动完成 ZyBooks 上的互动练习。能答多选题、做拖拽题、以 2 倍速播放动画，做完自动翻页。

## 功能

- **多选题** — 逐个点击选项，找到正确答案后跳过已完成的题目。
- **拖拽题** — 通过试错把拖拽对象匹配到对应目标。
- **动画和幻灯片** — 自动点击播放、设置 2 倍速，等播完继续。
- **简答题** — 有"显示答案"按钮的题目会自动填入答案并提交。
- **自动翻页** — 所有 participation 活动完成后自动跳到下一页。

## 安装

1. 浏览器安装 [Tampermonkey](https://www.tampermonkey.net/)。
2. 安装 [Stylus](https://chromewebstore.google.com/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne)（可选，用来自定义样式）。
3. 打开 [Greasy Fork 页面](https://greasyfork.org/en/scripts/488644-zybooks-auto)，点"安装此脚本"。

或者直接把 `ZyBooks_auto.js` 的内容复制到 Tampermonkey 新建脚本里。

## 使用

打开任意 ZyBooks 章节页面，脚本自动运行。按 F12 打开浏览器控制台可以看运行日志。

## 注意

- Challenge 活动会被跳过，脚本只处理 participation 练习。
- 拖拽题不一定一次全对，脚本用的是试错法。
- 保持浏览器标签页打开且可见，后台标签页有些活动可能加载不正常。

## 许可证

[MIT](LICENSE)
