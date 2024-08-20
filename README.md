# bot_trade_optimize
Bot戦略に関しての私的管理用のタスク管理。
コードに関して法律上、友人のみと情報交換と開発目的に行い公開は原則行わない。(損失が出た場合の責任は負えず、求められても拒否をするものとする。)

バックテストを行い好成績を残したものは`rs`ディレクトリに配置する。

## Tasks
*DONE*
- [x] トレーディング戦略の設計
- [x] 初期コーディング
- [x] バックテスト環境のセットアップ
- [x] ベイズ最適化によるパラメータチューニング
- [x] 戦略の比較
- [x] 並列処理による高速化
- [x] 期間指定によるバックテスト
- [x] 設定パラメータの簡略化

*In Progress*
- [-] 設定用パラメータによる管理
- [-] 使用するテクニカル指標の精査、追加
- [-] ドキュメント作成
- [-] 利益確定による条件付与

*To Do*
- [ ] パラメータ最適化による手法の精査、テスト
- [ ] 引数からの通貨ペアの設定を可能にする
- [ ] 取引回数に応じた重み付け
- [ ] 損失のあるトレードを行った際の重み付け
- [ ] ポジションを持つ際にBad Promptを読み込み近似値である場合breakさせる
- [ ] テクニカル指標の値それぞれに応じた重み付けを行い、合計値から期待値を作りポジション取りを行う
- [ ] 利益・損失パターンを割り出す為のSVM実装
- [ ] バックテストデータのCSV出力、Streamlitでの視覚化を容易とする
- [ ] GUI上での操作(必要ではない・・・)

