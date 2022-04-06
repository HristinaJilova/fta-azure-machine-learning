## Azure Machine Learning サービス作成

0. デモ用の Azure Subscription を準備します。<br>
   ※ サービス作成に時間がかかる場合があるので、Backup として構築済みの Azure ML 環境を準備しておくと良い。
1. Azure Portal を開きます。
2. 上部の検索ボックスで "機械学習" と検索し、"機械学習" を選択します。
3. ウィザードで設定値を入力します。
- 基本タブ
    - コンテナーレジストリーも入力する
- ネットワーク
    - パブリックエンドポイント
- 詳細
    - 変更なし
- タグ
    - 入力なし
- 確認および作成
    - 作成ボタンをクリック
4. リソースグループから作成された Azure ML Workspace と関連 Azure サービスを確認します。
5. Azure ML studio にログインします。