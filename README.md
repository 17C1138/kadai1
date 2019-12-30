# robosys_2019_kadai1

このプログラムはLEDの点滅プログラムである


コマンド手順
   make  
   sudo insmod myled.ko  
   sudo chmod 666 /dev/myled0  
   echo 0 /dev/myled0 →LEDが消灯  
   echo 1 /dev/myled0 →LEDが点灯  
   echo 2 /dev/myled0 →LEDが点滅  


デモ動画：https://youtu.be/Eu0AfvLAoBA


次のページを参考にして作成した
https://ryuichiueda.github.io/robosys2019/lesson7.html

