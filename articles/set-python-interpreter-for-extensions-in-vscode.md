---
title: "VSCodeの python.defaultInterpreterPath は Quarto 等のサードパーティー拡張機能にも適用される"
emoji: "✍️"
type: "tech" # tech: 技術記事 / idea: アイデア
topics: ["vscode", "python", "Quarto"]
published: false
---

VSCodeのQuarto拡張機能を使うときに [`python.defaultInterpreterPath`](https://code.visualstudio.com/docs/python/environments#_manually-specify-an-interpreter) にPython仮想環境内の `python.exe` のフルパスを指定しておくと，`Quarto: Render` 等を実行するときに指定した仮想環境のPythonを使うことができます。