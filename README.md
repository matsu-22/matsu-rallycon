# Matsu RallyCon v0.3 SAFE

iPhone Safari / Home Screen向けのラリーコンピューター試作版です。

## v0.3 SAFE 変更点
- TOTAL表示を `0.00 km` の2桁表示に統一
- LEG表示を `0.00 km` の2桁表示に統一
- ROADBOOK目標距離・NEXTまで表示も2桁に統一
- LEG計算を「最後にNEXTした時点のTOTALとの差」で明確化
- 手動NEXT・自動NEXTのどちらでもLEGを0.00から再スタート
- iPhone Safe Area対応を継承
- 電子コンパスCAP対応を継承
- CAP 0°補正を継承
- GPS距離、速度、GPS精度、±10m補正、タイマー、Wake Lockを継承

## LEGの動作
例：
- START：TOTAL 0.00 / LEG 0.00
- 100m走行：TOTAL 0.10 / LEG 0.10
- NEXT：TOTAL 0.10 / LEG 0.00
- 300m走行：TOTAL 0.40 / LEG 0.30

## 注意
- 距離はGPS座標間の積算値です。タイヤ外周補正はまだ入れていません。
- 電子コンパスはiPhone側のセンサー許可とキャリブレーションが必要です。
- 実際のラリー使用前に十分な走行テストをしてください。
