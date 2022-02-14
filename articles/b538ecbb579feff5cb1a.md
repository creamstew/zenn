---
title: "Next.js + TypeScript + TailwindでTodoアプリのテンプレートを作りました"
emoji: "⛳"
type: "tech" # tech: 技術記事 / idea: アイデア
topics: [nextjs,typescript,tailwindcss]
published: true
---

新しい言語やライブラリを試す際に簡単なTodoアプリを作る時があると思います。
自分は最近Goに興味を持つようになり、GoやフレームワークのEcho,Ginを使って簡単なAPIを作ろうとしています。

その際にフロントエンドとバックエンド間で通信をしたかったので、それ用にNext.js + TypeScript + TailwindでTodoアプリのテンプレートを作りました！

下記の通り必要最低限の設定をしていて、Dockerを使っているのでコマンド一発で環境構築できます。

- TypeScript
- Tailwind
- ESLint
- Prettier
- husky
- lint-staged
- Docker

これで何か試したい時はこのテンプレートからブランチを切って試せるので便利だと思います！
もし良ければ使ってみてください！

画面（CSS弱者なので画面はイマイチです...）
![](/images/b538ecbb579feff5cb1a/todo-nextjs-view.png)


https://github.com/creamstew/todo-nextjs
