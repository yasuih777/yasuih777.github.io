# 目的

このレポジトリでは、「[優月の生物統計学ノート](https://yasuih777.github.io/qmds/)」の運用のためのコードを格納しています。

# 環境

- OS: WSL Ubuntu 20.04.6 LTS
- Quarto: 1.3.450
- R: 4.2.0
  - renv: 1.0.3

# サイトの編集

1. 編集用のブランチを作成
1. Quarto Markdown (.qmd)を編集する
1. [_quarto.yml](./_quarto.yml)を編集
1. WSL上で`quarto render {select .qmd}`を実行
1. リモートブランチにpush
1. `main`ブランチにマージ

# Tips

## Quarto
- [公式リンク](https://quarto.org/)

# Licence

このレポジトリ内のコードでは`MIT Licence`を適応します。