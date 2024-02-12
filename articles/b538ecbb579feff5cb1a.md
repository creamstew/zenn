---
title: "Next.js + TypeScript + TailwindでTodoアプリのテンプレートを作りました"
emoji: "⛳"
type: "tech" # tech: 技術記事 / idea: アイデア
topics: [nextjs, typescript, tailwindcss]
published: true
---

新しい言語やライブラリを試す際に簡単な Todo アプリを作る時があると思います。
自分は最近 Go に興味を持つようになり、Go やフレームワークの Echo,Gin を使って簡単な API を作ろうとしています。

その際にフロントエンドとバックエンド間で通信をしたかったので、それ用に Next.js + TypeScript + Tailwind で Todo アプリのテンプレートを作りました！

下記の通り必要最低限の設定をしていて、Docker を使っているのでコマンド一発で環境構築できます。

- TypeScript
- Tailwind
- ESLint
- Prettier
- husky
- lint-staged
- Docker

これで何か試したい時はこのテンプレートからブランチを切って試せるので便利だと思います！
もし良ければ使ってみてください！

画面（CSS 弱者なので画面はイマイチです...）。
![](/images/b538ecbb579feff5cb1a/todo-nextjs-view.png)

https://github.com/creamstew/todo-nextjs
