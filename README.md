# Knowledge Project Research Site

研究紹介ページを GitHub Pages とオンプレミスサーバの両方で運用できるようにするための静的サイトです。`minima` テーマをベースに、/Users/ryua/Code/Github_pages と同じビジュアルを採用しています。

## ローカルプレビュー

1. Ruby 3.0 以上と Bundler を用意します。
2. 依存関係をインストールします。
   ```bash
   bundle install
   ```
3. 下記コマンドで開発サーバを起動します。
   ```bash
   bundle exec jekyll serve --livereload
   ```
4. ブラウザで `http://localhost:4000/` を開くとプレビューできます。

## デプロイ

- **GitHub Pages**: このリポジトリを `<username>.github.io` または任意のプロジェクトリポジトリに push すれば、自動的にビルドされます。`_config.yml` の `url` と `baseurl` は公開先に合わせて変更してください。
- **任意サーバ**: `bundle exec jekyll build` で `_site` ディレクトリが生成されます。生成された静的ファイルを任意の HTTP サーバに配置すれば運用できます。

## カスタマイズポイント

- トップ画像を差し替えるには `assets/img/placeholder-lab.jpg` を用意してください。
- 研究領域や成果の項目は `index.md` を編集して更新します。
- 追加ページを作る場合は Markdown ファイルを追加し、`_config.yml` の `header_pages` でナビゲーションを制御できます。
