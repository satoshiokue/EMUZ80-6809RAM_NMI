## ファームウェア
main.cはPTCアクセスによってPICがNMI割り込みを固定値のディレイで発生させるファームウェアです。  

下記ブログのMUTIF09用AplusBASICv5.HEXを整形してmain.cのrom[]に格納することでASSIST9のTRACE機能を作動させることができます。  
MEZ6809RAMではNMI信号が使えないのでMEZ6809RAM_NMIで使用してください。

夢七さんのブログ「SBC6809をつくる」
MUTIF09のASSIST09にTRACE機能を加える  
https://yumeziu.blogspot.com/2019/03/mutif09assist09trace.html

# MEZ6809RAM_NMI
6809 Mezzanine board for EMUZ80

C1 = 0.1uF  
C2 = 0.1uF  
R1 = 10k

RAM U2 = TC551001CP-85L  
オレンジピコショップ  
https://store.shopping.yahoo.co.jp/orangepicoshop/pico-i-009.html

![MEZ6809RAM PCB TOP](https://github.com/satoshiokue/EMUZ80-6809RAM_NMI/blob/main/MEZ6809RAMI_top.jpg)
![MEZ6809RAM PCB BOTTOM](https://github.com/satoshiokue/EMUZ80-6809RAM_NMI/blob/main/MEZ6809RAMI_bottom.jpg)

