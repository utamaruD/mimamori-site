# スマホ見守りくん 紹介サイト

GitHub Pages で公開する、紹介ページ・プライバシーポリシー・サポートページ（カレまるの `site/` と同じ作り）。
このフォルダの中だけで完結しているので、中身をそのまま公開用のリポジトリに入れれば動く。

| ファイル | 内容 |
|---|---|
| `index.html` | 紹介ページ（トップ） |
| `privacy.html` | プライバシーポリシー（VPN アプリは App Store の審査で必須） |
| `support.html` | よくある質問とお問い合わせ先（App Store の「サポート URL」） |
| `page.css` | 見た目（アイコンの青） |
| `icon.png` / `favicon.png` | アイコン（`design/icon_1024.png` から作ったもの） |

## 公開のしかた

`mimamori-kun` を非公開（Private）にしている場合、無料の GitHub ではここから Pages を出せない。

1. GitHub で public の新しいリポジトリを作る（例：`mimamori-site`）
2. このフォルダの中身を、そのリポジトリの一番上に入れて push する
3. そのリポジトリの Settings → Pages → Build and deployment で
   Source を「Deploy from a branch」、Branch を `main` と `/ (root)` にして Save
4. 数分で `https://utamarud.github.io/mimamori-site/` のような URL で見られるようになる

## 公開する前に確かめること

- お問い合わせ先はカレまると同じ utapaso@gmail.com にしてある。別にするなら `privacy.html` と `support.html` を直す
- 公開後は `index.html` の「iPhone 向けに近日公開予定です。」を App Store へのリンクに変える

## 公開したら

App Store Connect の「サポート URL」に `.../support.html`、「プライバシーポリシー URL」に `.../privacy.html` を入れる。
