# Matsu RallyCon v0.5 PDF

KOMAREN-style A4 roadbook PDFを中央に表示する、iPhone Safari / GitHub Pages向け試作です。

## 今回のポイント
- 中央にPDFをcanvas表示
- PDF読込（iPhoneのファイルApp / iCloud Drive等から選択）
- ページ送り、ズーム
- コマ練Classic2026のTOTAL距離索引を内蔵（234コマ）
- TOTALに合わせて「現在のコマ」へ同期
- AUTO NEXT（次TOTALまで30m以内）
- 現在コマのPDFページへ自動移動
- TOTAL / LEG / SPEED / TIME
- ±10m距離補正
- 電子コンパス / CAP 0°セット
- iPhone Safe Area対応、横画面専用
- サンプルPDF同梱

## 注意
- GPS距離はGPS点間の積算で、タイヤ周長補正はまだ入れていません。
- v0.5ではサンプルPDFのコマ索引を内蔵しています。別PDFではPDF表示・手動ページ送りが使えます。
- AUTO NEXTやPDFコマ同期を汎用化するのが次の段階です。
- PDF.jsをCDNから読み込みます。初回表示にはインターネット接続が必要です。

## GitHub Pages
`index.html`をルートに置き、Pagesを `main / (root)` に設定してください。
