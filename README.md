# Unity-Oscilloscope
<<<<<<< HEAD
Windowsで動作させるためにArduinoのプログラムにDelay(20)を追加

Mac上ではArduinoから送信されるPacket(115200bps)を処理することが可能だが、Windowsでは1secあたり120byteの処理が限界のため、ArduinoのプログラムにDelay(20)を追加した。
=======
Windowsのパケット処理速度(960bps)に合わせ、ArduinoにDelay(20)を追加した。

MacではArduinoからの115200bpsのシリアル通信を処理することが可能だが、Windowsでは960bpsしか処理できないため、Graph上に信号が正しく反映されない。
>>>>>>> origin/master
