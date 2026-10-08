# 運用の流れ（大和さん向け）

1. Mac側AIが `requests/NNN-*.md` を書いて push（または大和さんがこのファイルを貼る）。
2. Windows側AIにリポジトリの該当ファイルを読ませ、実行させる。
3. Windows側AIが `results/NNN-*.md` に結果を書いて push。
4. Mac側AIがそれを読んで次へ進む。

Windows側AIへの最初の一言（例）:
「リポジトリ BoroleBorole/win-mac- の requests/001-krea-services-and-e2e.md を読み、その指示に従ってください。結果は results/001-... に書いて push してください。」
