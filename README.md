# GRND — 法的文書

iOS アプリ **GRND 生活管理** のプライバシーポリシー・利用規約・サポートページ。

GitHub Pages で配信している。App Store Connect の Privacy Policy URL /
Support URL、およびアプリ内(課金画面・プロフィール画面・ログイン画面)から参照される。

## 日本語(正本)

- プライバシーポリシー: https://createdigging.github.io/grnd-docs/privacy.html
- 利用規約: https://createdigging.github.io/grnd-docs/terms.html
- サポート: https://createdigging.github.io/grnd-docs/support.html

## English(参考訳)

- Privacy Policy: https://createdigging.github.io/grnd-docs/privacy.en.html
- Terms of Use: https://createdigging.github.io/grnd-docs/terms.en.html
- Support: https://createdigging.github.io/grnd-docs/support.en.html

**日本語版が正本**。英語版は参考訳で、その旨を各ページ冒頭に明記している。
内容を変える時は日本語を直してから英語へ反映すること(逆はしない)。

アプリは端末のロケールが `en` の時だけ `.en.html` を開く
(`src/utils/links.ts` の `localized()`)。App Store Connect に登録する URL は
日本語版のまま。ASC に英語ロケールを追加した時に、そちらへ英語版 URL を入れる。

## 更新手順

正本はアプリ本体のリポジトリ(private)の `docs/`。ここはその公開ミラー。
**本体側を直してからここへコピーする。**

> ⚠️ 2026-09-07 時点で、この手順が一度破られていた。2026-09-05 に Apple ログインの
> 記載をミラー側だけに入れて本体 `docs/` に戻していなかったため、両者が乖離していた。
> 同日に本体へ取り込んで解消済み。片側だけ直さないこと。

お問い合わせ: grnd.support@gmail.com
