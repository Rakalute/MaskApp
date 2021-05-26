# MaskApp
機械学習を用いてマスクの着用有無判別するAndroidスマートフォンアプリケーションで，**オフライン**で使用可能です．


# アプリケーションの処理手順
本アプリケーションの処理手順は以下のようになっています．顔検出にはfirebaseの顔検出APIを，マスク着用有無の判別には，[次のリンク](https://www.pyimagesearch.com/2020/05/04/covid-19-face-mask-detector-with-opencv-keras-tensorflow-and-deep-learning/)で紹介されていた機械学習モデル(tfliteモデル)を使用しました．
こちらでは，スマートフォンでも機械学習による推論を可能にするためTensorFloeLiteを用いて機械学習モデルを最適化しています．

![処理手順2](https://user-images.githubusercontent.com/81143699/114265956-a279da80-9a2e-11eb-8d0e-1fd7dc98795f.PNG)

また本アプリケーションは英語と日本語の両方に対応しており，最初に選択することが可能です．


# アプリケーションのデモ
|マスク着用|マスク未着用|
|---|---|
|　　　![youtube_social_square_red.png](https://user-images.githubusercontent.com/81143699/114266455-73189d00-9a31-11eb-99b3-a2bb44d1f593.gif)　　　|　　　![Twitter_Social_Icon_Square_Colorのコピー.png](https://user-images.githubusercontent.com/81143699/114268074-300ef780-9a3a-11eb-86cb-4d589ef85ae9.gif)　　　|


# 環境
Android Grable Plugin Version: 4.1.3  
Gradle Version: 6.5

