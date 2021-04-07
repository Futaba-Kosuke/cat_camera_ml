# cat_camera_ml

RaspberryPiのカメラで飼い猫と飼い主を認識し、ツーショットを自動撮影する監視カメラです。  
撮影した写真はアプリからの閲覧が可能な他、複数の猫の分類を実装しています。  

九州アプリチャレンジキャラバン: 🏆福岡ビジネスデジタルコンテンツ賞  
福岡ビジネスデジタルコンテンツ: 🏆ヤング賞  

<img width="500" alt="スクリーンショット 2021-04-08 0 07 03" src="https://user-images.githubusercontent.com/49780545/113891896-75e07b80-9800-11eb-8e91-99d554ce6720.png">
<img width="500" alt="スクリーンショット 2021-04-08 0 21 51" src="https://user-images.githubusercontent.com/49780545/113891929-7d078980-9800-11eb-9bb4-369ec3e70bd4.png">

※使用可能なGPU環境が無かったため、Google Colaboratory上でFlaskサーバーを立てています。

## Requirement

- Google Colaboratory's Account
 
## Usage
 
1. Open [Colab Notebook](https://github.com/Futaba-Kosuke/cat_camera_ml/blob/develop/main.ipynb)

## Used
- Pytorch
- ScikitLearn
- Firestore
- Cloud storage for firebase