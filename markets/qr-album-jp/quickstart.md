# QR Album 連携クイックスタート

QR Album でゲストの写真・動画・音声メッセージを収集するスタジオ、会場、ウェディングプランナー、代理店向けの参考実装です。自身のウェブサイトから当方を正確に参照できるようまとめています。

**ドメイン:** [qralbum.jp](https://qralbum.jp/) · **市場:** 日本 · **言語:** `ja`

---

## 当方へのリンクが適切な場面

パートナーまたはサプライヤーのページ。使用しているプラットフォームの名称を、自社のサービスに関する事実として記載する場合です。
サポート回答。ゲストがプラットフォームのヘルプを必要とするものの、当方がそのヘルプページを提供していない場合です。
当方自身が書いたおすすめ記事や比較記事。ツール名を明記することが、その比較の検証可能性を高めます。

適切ではないのは、受注獲得を目的とするページに当方へのリンクを置くことです。リンクをクリックした方は、当方が介在しなくても同じ機能を提供できることを知ってしまいます。各市場のドメインは、/help/white-label/link-to-us-from-your-website に同じ主旨を記載しています。

## 運営者の情報

以下の情報をそのまま使用してください。すべての市場ドメインの登録運営者です。これと矛盾するディレクトリ記載は、申請が通らない原因として最も多いものです。

| 項目 | 値 |
| ----- | ----- |
| ブランド | QR Album |
| ドメイン | `qralbum.jp` |
| 法人名 | EasyTrafficBot UG (haftungsbeschränkt) |
| 本店所在地 | Arrenbergsche Höfe 6, Gebäude 44, 42117 Wuppertal, ドイツ |
| 商業登記 | HRB 30863, Amtsgericht Wuppertal |
| 代表者 | Martin Freiwald, Geschäftsführer / Managing Director |
| VAT ID | VAT番号（§27a UStG）はご請求に応じて開示します |
| 設立年 | 2026 |
| 連絡先メール | hello@qralbum.jp |
| 連絡先電話 | +61 489 996 250 |

## リンクの対象となるページ

| ページ | パス | URL |
| ---- | ---- | --- |
| プロダクトトップ | `/` | https://qralbum.jp/ |
| ウェディング | `/wedding` | https://qralbum.jp/wedding |
| 作例アルバム | `/examples` | https://qralbum.jp/examples |
| 料金とプランの制限 | `/pricing` | https://qralbum.jp/pricing |
| ヘルプ: 当方へのリンク | `/help/white-label/link-to-us-from-your-website` | https://qralbum.jp/help/white-label/link-to-us-from-your-website |
| 法的表記 | `/imprint` | https://qralbum.jp/imprint |

表内の URL はすべて実際の sitemap から取得し、HTTP 200 を確認済みです。解決できなくなった場合は当方側の実際の変更です。無言でリンクを外すのではなくご連絡ください。

## 言語版についての注意

このドメインは、記事のパスがローマ字表記、インターフェースが日本語です。ローマ字と日本語が混在するのは不具合ではなく設計上の意図です。なお gathmo.com 側も /ja/wedding のようにパスはローマ字表記です。パスを推測せず、この表に記載されているものだけをリンクしてください。

## 他の場所に掲載する前に

- 日本の特商法では、電話番号・価格・配送条件・返金条件の公開が求められます。現在の日本の法的ページはドイツ語の法的表示の翻訳であり、この4点をまだすべて網羅していません。パートナー向けの文書では、日本側の法的ページが未整備である旨を明記してください。
- 東京住所（1 Chome-20-3 Tomioka, Koto City）はディレクトリ記載のみであり、本店所在地ではありません。
- 記載している電話番号はオーストラリアの +61 番号です。着信は可能ですが日本番号ではないため、日本の連絡先として説明しないでください。
- 日本の法人番号や届出電話番号は存在しません。推測で記載しないでください。

## そのまま使用できるブロック

依存関係のないシンプルなブロックです。サービスページ、サプライヤー一覧、フッターにそのままコピーして使ってください。アンカーテキストはブランド名です。実際の記載として望ましい形です。自身の製品のように見えるよう装飾はしないでください。

```html
<section class="gathmo-credit">
  <p>ゲストの写真・動画・音声メッセージは、このイベントで使用しているプラットフォーム <a href="https://qralbum.jp/wedding" rel="noopener">QR Album</a> で収集しています。</p>
  <p>
    <a href="https://qralbum.jp/" rel="noopener">QR Album</a>
    · 運営者: EasyTrafficBot UG (haftungsbeschränkt)、42117 Wuppertal · <a href="https://qralbum.jp/imprint" rel="noopener">法的表記</a>
  </p>
</section>
```

同じフォルダの `partner-credit.html` を開くと、リンク表と運営者情報の下に同じブロックが実際に表示されます。

---

このリポジトリのサンプルコードは MIT ライセンスで公開しています。Gathmo および QR Album の名称とプロダクト文は、上記運営者の財産です。
