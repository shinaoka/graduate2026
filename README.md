## Lecture for graduate students 2026

ブラウザからは, [https://shinaoka.github.io/graduate2026/](https://shinaoka.github.io/graduate2026/) で確認できる.

このリポジトリの講義資料は, 特記がない限り [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) で公開する.

### ローカルでの確認

- `make serve` - プレビュー
- `make build` - `book/dist` にビルド

原稿は `book/*.qmd` で管理する.

### GitHub Pages

`main` への push で [`.github/workflows/pages.yml`](.github/workflows/pages.yml) が走り, `book/dist` をデプロイする.
リポジトリの Settings -> Pages で GitHub Actions をソースに指定すること.
