# Dev_IoTFarmSystem
## 農業コミュニティ用インフラシステム基盤の開発

## 背景
+ 技術で役に立つ
+ 地域の人に恩返し

## 目的
+ 地域コミュニティの活性化
+ 大規模システム(IoT-Web-Mobile-インフラ)の開発実務経験を積む

## ロードマップ
| マイルストン | 内容 | 達成状況 |
| :-- | :-- | :-- |
| 0合目 | 構想案, 要件定義の作成 | 実行中 |
| 1合目 | Dockerによるローカル環境によるブラウザとサーバーの疎通確認 | - |
| 2合目 | フロントエンド: UI設計, React実装 |
| 3合目 | サーバーサイド: Next.js, Djangoによる基幹部の実装 | - |
| 4合目 | サーバーサイド: データフロー, DB設計 | - |
| 5合目 | アカウント機能, 認証機能 | - |
| 6合目 | AWS展開: EC2インスタンス展開 etc. | - |
| 7合目 | サーバーサイド: 衛星画像データを用いた緑化度合いの可視化機能 | - |
| 8合目 | カレンダー機能, 天気予報機能, 日記機能, 作業報告機能 | - |
| 9合目 | エッジPCによる各種センシングデータ取得, サーバーへの転送, 疎通確認 | - |
| 10合目 | 作物の成長度可視化機能 | - |
| 11合目 | モバイルアプリの開発, 疎通確認 | - |
| 12合目 | | |

## 完了条件
+ コミュニティでこのシステムを運用してもらう


## '23/09 (構想段階)

### インターフェース
+ ブラウザ閲覧
+ モバイル閲覧

### 機能要件
+ アカウント機能
+ 認証機能
+ 日記機能
+ アラート機能
+ カレンダー機能
+ 作業報告機能
+ 集合知機能
+ 天気予報閲覧機能
+ ピンポイントな天気予測機能
+ タスクスケジューリング機能
+ 衛星画像データを用いた緑化度合いの可視化機能
+ 作物の成長度可視化機能
+ 活動メンバーのトラッキング機能(ON/OFF)
+ 農地管理状況のDB機能

### 技術要素
+ 衛星画像データ
+ センシング
+ IoT
+ Cloud
+ Mobile
+ Web

### センシング
+ 土壌センシング e.g. アルカリ性/酸性
+ 湿度センシング
+ 風向きセンシング
+ 気温センシング 
+ GPS(GNSS) : 農作業者のロケーション確認
+ 衛星画像データ : 緑化度合い, 農地の状態推定

### IoT
+ エッジPC : Arduino, RaspberryPi etc.)
+ Bigbee(広域無線通信規格) 各エッジ(Node)から集約機(Coordinator)へのデータ転送



