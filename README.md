# taro-autodev-app

Google Play ストアに公開しているアプリのプライバシーポリシーおよび利用規約をホスティングするリポジトリです。

GitHub Pages (`https://rintaro-ko.github.io/taro-autodev-app/`) 経由で公開され、各アプリの Play Store 掲載情報からリンクされます。

## 対象アプリ

| アプリ | プライバシーポリシー | 利用規約 |
|--------|:------------------:|:--------:|
| **RideVoiceNavi** | [privacy-policy.html](docs/privacy-policy.html) | [terms-of-service.html](docs/terms-of-service.html) |
| **TechRing** | [techring-privacy-policy.html](docs/techring-privacy-policy.html) | [techring-terms-of-service.html](docs/techring-terms-of-service.html) |

## ディレクトリ構成

```
docs/
├── privacy-policy.html              # RideVoiceNavi プライバシーポリシー
├── terms-of-service.html            # RideVoiceNavi 利用規約
├── techring-privacy-policy.html     # TechRing プライバシーポリシー
└── techring-terms-of-service.html   # TechRing 利用規約
```

## 公開 URL

GitHub Pages を有効にしている場合、以下の URL でアクセス可能です:

- `https://rintaro-ko.github.io/taro-autodev-app/docs/privacy-policy.html`
- `https://rintaro-ko.github.io/taro-autodev-app/docs/terms-of-service.html`
- `https://rintaro-ko.github.io/taro-autodev-app/docs/techring-privacy-policy.html`
- `https://rintaro-ko.github.io/taro-autodev-app/docs/techring-terms-of-service.html`

## 新しいアプリを追加する場合

1. `docs/` に `<app-name>-privacy-policy.html` と `<app-name>-terms-of-service.html` を作成
2. 本 README の対象アプリ表に追記
3. Play Console のストア掲載情報から該当 URL をリンク
