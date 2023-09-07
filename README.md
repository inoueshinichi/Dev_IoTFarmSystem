# Dev_IoTFarmSystem
## 農業コミュニティ(サツマイモ)用のIoT/Mobile/Web/インフラ基盤

## '23/09 構想段階

### 機能要件
+ PCブラウザ閲覧
+ モバイル閲覧
+ アカウント機能
+ アラート機能
+ カレンダー機能
+ 作業報告機能
+ 集合知機能
+ レコメンド機能
+ 天気予報閲覧機能
+ ピンポイントな天気予測機能
+ タスクスケジューリング機能
+ 衛星画像データを用いた緑化度合いの可視化機能
+ 活動メンバーのトラッキング機能(ON/OFF)

### IoTセンシング
+ 土壌センシング e.g. アルカリ性/酸性
+ 湿度センシング
+ 風向きセンシング
+ 気温センシング
+ GPS(GNSS)

### インフラ
+ AWSクラウド
+ モバイル
+ PCブラウザ
+ エッジPC(Arduino, RaspberryPi etc.)
+ 各センサ
+ Bigbee(広域無線通信規格) 各エッジ(Node)から集約機(Coordinator)へのデータ転送
+ 

