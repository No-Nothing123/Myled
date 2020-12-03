# ロボットシステム学　課題１
第７、８回のmyled.cにオリジナリティの改造をして、Githubに置く。
# 動作環境
    Raspberry Pi 4 x 1
     OS: Ubuntu 20.04.1 LTS
    LED x 1
    抵抗(100Ω) x 1
    ユニバーサル基盤 x 1
    ジャンパー線 x 2
# 改造内容について
    echo 1 > /dev/myled0  //LEDは10回点滅します。
    echo ２ > /dev/myled0　//LEDは"sos"のモールス信号”... --- ...”を表します。
# 実行方法
    make
    sudo insmod myled.ko
    sudo chmod 666 /dev/myled0
    echo 1 > /dev/myled0 or echo ２ > /dev/myled0
  
# 動画
https://youtu.be/cLjZS18CaB4
