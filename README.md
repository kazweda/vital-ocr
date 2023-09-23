# vital-ocr
AppSheetで試作した血圧管理アプリです。
診察券のバーコードをスマホで読み取る想定で作ってみました。
それと血圧計の画面を撮影して
- 血圧上
- 血圧下
- 心拍数
をOCR機能で自動的に登録することができます。

## 機能について
- 患者管理
- 血圧管理
- 血圧チャート
- 心拍チャート

## 注意事項
血圧計の機種の違いなどで読み取りに失敗する場合は再学習(Retrain)させることができます。
照明の映り込みについては反射防止対策が必要かもしれません。

## インストール
> Optical Character Recognition (OCR)
This feature is available to AppSheet Enterprise accounts only.

現在OCR機能がベータ版なのと、Enterpriseアカウントが必要ということで、ひとまずの機能の説明とスクリーンショットの紹介までとします。
