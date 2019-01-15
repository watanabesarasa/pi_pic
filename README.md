# pi_pic
## 概要　
ROSを使って何かを作る課題
-  カメラと顔の距離がいい感じになると写真を撮ってくれる
  -   リアルタイムで顔が認識されてる様子が確認できる
  
## 必要なもの
-  Raspberry Pi 3 Model B V1.2
  -  http://file.ueda.tech/RPIM_BOOK/ubuntu-16.04-raspimouse-ros-book-part1+catkin_ws.img.xz
-  webカメラ
 
## 使用方法
-  コマンド
```
roslaunch pi_pic_ros pic.launch 
rosrun pi_pic_ros face_pic.py  
```
-  ブラウザで　http://[000.00.00.00]:10000/stream?topic=/face（[]の中は自分の IPアドレス）を開いて確認

-  距離感を調節する

## LICENCE
-  MITライセンスに基づく
-  [LICENCE](https://github.com/watanabesarasa/pi_pic/blob/master/LICENSE)

## デモンストレーション
-  URL：
