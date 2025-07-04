

---

## 概要
ジョイスティックの X 軸操作でモーターを制御するものです。  
- 左右の傾きでモーターの回転方向を PWM 制御 
---

## デモ動画
モーターをジョイスティックで制御している様子が確認できます
[![Joystick → Motor Control Demo](https://img.youtube.com/vi/7BHZJv9Ya_I/0.jpg)](https://www.youtube.com/watch?v=7BHZJv9Ya_I)

---
## 参考資料
- この装置を作るにあたってコードと回路図は下記の動画を参考にして作りました。
- Raspberry Pi LESSON 20: Controlling Position of a Servo With a Potentiometer[https://www.youtube.com/watch?v=X6ZC-L02aEs&t=2s]

---

##回路図
- 下記の画像はFritzingで作成したブレッドボード図です
![モーター回路図](motor.png)
- ジョイスティックに関しては画像の接続部分の表記と実際に接続しているものがことなります。 
- 左からGND,5v,URX,URY,SWが今回使用したジョイスティックの仕様です
- 以降ジョイスティックを使った電子工作にかんしてはこの並び順のものを使用します
- 画像のraspberryPi本体の上部にあるものがモーターです


