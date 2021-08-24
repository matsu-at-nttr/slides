## スライド置き場

- [marp](https://marp.app/) により、markdownからスライドを作成できるツールを利用
- mainにマージすると、自動で生成してgithub pageにデプロイできるように
  - e.g. https://matsu-at-nttr.github.io/slides/introduction-of-understanding-the-spiral-of-technologies.html

- [`gh-pages`](https://github.com/matsu-at-nttr/slides/tree/gh-pages) ブランチに、pdfも自動生成されているので `speaker deck`などでの共有も可能


## marp cli


```
# mdの変更を検知してコンパイルしてくれるので、編集しながらプレビューできる

npx @marp-team/marp-cli@latest -w  introduction-of-understanding-the-spiral-of-technologies.md
```

## Markdown syntax

https://marpit.marp.app/markdown