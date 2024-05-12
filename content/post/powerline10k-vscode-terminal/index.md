---
title: "zsh + Powerlevel10kでVSCode内ターミナルのアイコンが表示されない件"
date: 2024-05-13T01:00:00+09:00
draft: false
categories:
  - vscode
tags:
  - vscode
  - zsh
image: succeeded.jpg
slug: powerline10k-vscode-terminal
---

## VSCodeのIntegrated Terminalでアイコンが表示されない

zsh + Powerlevel10k を使い始めたんですが、VSCode内のIntegrated Terminalでおしゃれなアイコンがうまく表示されずの地味に困りました。

![](failed.jpg)

## フォントを正しく指定しましょう

この [gist](https://gist.github.com/480/3b41f449686a089f34edb45d00672f28) を参考にして、`setting.json` に `"terminal.integrated.fontFamily": "MesloLGS NF"` を設定すれば上手くいきました。

![](succeeded.jpg)