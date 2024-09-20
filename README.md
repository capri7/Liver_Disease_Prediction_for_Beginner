# 第50回_Beginner限定コンペ_肝疾患の確率を予測-

## 【プロジェクトの概要】
このプロジェクトでは、肝臓疾患の予測モデルを構築し、患者が肝疾患である確率を予測します。
今回使用された評価方法はAUCです。

## 【使用したデータ】
Signateから提供されたデータセットを使用し、患者の年齢、性別、血液検査の結果を特徴量としました。
データセットを確認したい方は[こちら](https://signate.jp/competitions/1387#evaluation/)からお願いします。（ログインが必要です。）

## 【アプローチ】 
データの前処理ではそれぞれの特徴量に対数変換を適用しています。
アリゴリズムは、Random Forest、GradientBoost、XGBoost、CatBoost、LightGBM、SVM、Logistic Regressionを使用しました。
アンサンブルモデルを作成してみましたが、GradientBoostが一番精度が高いという結果になりました。

## [結果] 
モデルの評価結果や精度に関する説明。
暫定スコアは以下の通りです。
![暫定スコア](https://github.com/capri7/Liver_Disease_Prediction_for_Beginner/images/score.png)

