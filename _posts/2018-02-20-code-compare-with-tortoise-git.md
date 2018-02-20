---
layout: post
title: "Code Compare를 Tortoise git에서 사용하기"
description: "Code Compare를 Tortoise git에서 사용하기"
categories: [manual]
tags: [code_compare, tortoise_git]
redirect_from:
  - /2018/02/20/
---

* Kramdown table of contents
{:toc .toc}

# Diff Viewer

> "C:\Program Files\Devart\Code Compare\CodeCompare.exe" /SC=Git %base %mine

![diff viewer](/resources/2018-02-20-diff-viewer.png)


# Merge Tool

> "C:\Program Files\Devart\Code Compare\CodeMerge.exe" /TF=%theirs /MF=%mine /RF=%merged /BF=%base /REMOVEFILES

![merge tool](/resources/2018-02-20-merge-tool.png)
