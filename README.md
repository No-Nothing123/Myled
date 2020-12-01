# ロボットシステム学　課題１
第７、８回のmyled.cにオリジナリティの改造をして、Githubに置く。
# 改造内容について
echo 1 > /dev/myled0 の時LEDは10回点滅します。
echo ２ > /dev/myled0　の時LEDは"sos"のモールス信号”... --- ...”を表します。
# 実行方法
  make
  sudo insmod /dev/myled0
  
# 動画
