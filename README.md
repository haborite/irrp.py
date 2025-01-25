# irrp.py
Modified irrp.py for compression of long infrared codes.

# About
Raspberry piシリーズのGPIOから赤外線センサで受信したパターンを記録/送信するためにirrp.py(https://abyz.me.uk/rpi/pigpio/examples.html)というスクリプトが一般に使用されます。
しかし、irrp.pyには600エントリーを超える長さのパターンを送信できないという制限があり、多くの日本メーカーのエアコン等のコードが送信できないという問題点がありました。
この改良版irrp.pyは、コードの圧縮を用いて、そのような長い赤外線コードの送信に対応したものです。
より詳しい説明: https://muscula.aa0.netvolante.jp/posts/28

# About
**irrp.py(https://abyz.me.uk/rpi/pigpio/examples.html) is a commonly used script to record/transmit patterns received by the infrared sensor from the GPIO of the Raspberry pi series.
However, irrp.py has a limitation that it cannot send patterns longer than 600 entries, which prevents it from sending codes for Japanese air conditioners.
This improved version of irrp.py uses code compression to support the transmission of such long infrared codes.
More detailed description: https://muscula.aa0.netvolante.jp/posts/28

