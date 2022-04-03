# Centrifuge DIY

## 3/22(Tue) Prototype 1

どうやったら歯車を垂直方向に噛み合わせることができるんだろうと思い（それができなければ遠心分離機が作れない）、ネットで調べてみる。垂直方向に組み合わさっている歯車は「かさ歯車」というらしい。<br/>
・[https://monozukuri.sqcd-aid.com/日本の国でものづくり、ひとづくりを行いましょ/index-of-basic/28-1-introduction-of-gear/](https://monozukuri.sqcd-aid.com/日本の国でものづくり、ひとづくりを行いましょ/index-of-basic/28-1-introduction-of-gear/)<br/>
￼<br/>
・回転と力の伝わり方<br/>
[https://www.mabuchi-motor.co.jp/motorize/teck/](https://www.mabuchi-motor.co.jp/motorize/teck/)<br/>
<br/>
歯車ABC 入門編 p.17<br/>
[https://www.khkgears.co.jp/gear_technology/pdf/gearabc_a.pdf](https://www.khkgears.co.jp/gear_technology/pdf/gearabc_a.pdf)<br/>
<br/>
歯車の種類と動き<br/>
[https://tutorials.shade3d.jp/歯車の種類と動き/post/2391](https://tutorials.shade3d.jp/歯車の種類と動き/post/2391)<br/>
⇨軸と歯車が組み合わさったものは「ウォームギア」というらしい<br/>
⇨ネットにデータがありそう。探す。<br/>
↓<br/>
[Makebotで検索（Search word: "worm gear"）](https://www.thingiverse.com/search?q=worm+gear&type=things&sort=relevant)<br/>
⇨色々出てきた。<br/>
<br/>
・土台付き手回し歯車<br/>
[https://www.thingiverse.com/thing:2791504](https://www.thingiverse.com/thing:2791504)<br/>
￼<br/>
・ウォームギア<br/>
[https://www.thingiverse.com/thing:2480647](https://www.thingiverse.com/thing:2480647)￼<br/>
￼<br/>
・かなり遠心分離機に近い構造のものも見つかった。回転数はどれほどだろう。￼<br/>
[https://www.thingiverse.com/thing:2170237](https://www.thingiverse.com/thing:2170237)￼<br/>
￼<br/>
・「Centrifuge」で検索をかけたところ、[電動ドリルに取り付けただけの遠心分離機](https://www.thingiverse.com/thing:4583027)を発見した。これはなかなかの代物。<br/>
<br/>
・手回し遠心分離機のデータを発見！これはかなり求めているものに近いのではないか。<br/>
[https://www.thingiverse.com/thing:946640](https://www.thingiverse.com/thing:946640)<br/>
<br/>
・ブンブン駒型<br/>
[https://www.thingiverse.com/thing:1946291](https://www.thingiverse.com/thing:1946291)<br/>
<br/>
わかったこと・・・一から設計するのはかなり骨が折れそうなので、すでに公開されている既存のリソースを有効活用し、できることならそれをアレンジするほうが、よっぽど簡単だと思われる。<br/>
<br/>
### 3/23(Wed)
・動画　かさ歯車<br/>
[https://img.youtube.com/vi/9XQ29WcXvPQ/0.jpg](https://img.youtube.com/vi/9XQ29WcXvPQ/0.jpg)<br/>
![https://img.youtube.com/vi/9XQ29WcXvPQ/0.jpg](https://img.youtube.com/vi/9XQ29WcXvPQ/0.jpg)<br/>
Fusion360ではなく3DCADを使用<br/>
<br/>
・動画　かさ歯車その２<br/>
[https://www.youtube.com/watch?v=4XWLYM0b8FI](https://www.youtube.com/watch?v=4XWLYM0b8FI)<br/>
![https://img.youtube.com/vi/4XWLYM0b8FI/0.jpg](https://www.youtube.com/watch?v=4XWLYM0b8FI)<br/>
こっちはFusion。英語で検索したら出てきた。見よう見まねでなんとか作れるだろうか。<br/>
<br/>
<br/>
### 4/1(Fri)
History of centrifuge<br/>
[https://youtu.be/Q3CSUfjfgus](https://youtu.be/Q3CSUfjfgus)<br/>
[![thumbnail](https://img.youtube.com/vi/Q3CSUfjfgus/0.jpg)](https://www.youtube.com/watch?v=Q3CSUfjfgus)<br/>
The origin of centrifuge that was developed for milk separation.<br/>
A Swedish engineer invented the first centrifuge in 1880s in order to help cattle farmers to separate fresh cream from milk.<br/>
<br/>
"How to work centrifuge basic principe"<br/>
[https://youtu.be/nX0NNfV8nWw](https://youtu.be/nX0NNfV8nWw)<br/>
[![thumbnail](https://img.youtube.com/vi/nX0NNfV8nWw/0.jpg)](https://www.youtube.com/watch?v=nX0NNfV8nWw)<br/>
<br/>
### 4/2(Sat)
To understand and speculate the works of gear, I thought about making prototype by assembling gears.<br/>
とりあえずモデルを作ってみる。それがうまく動けば、3Dモデルソフトでその再現を目指したい。<br/>
<br/>
Therefore, I came back Akihabara!!<br/>
![Akihabara](/photo/Akihabara.jpg)<br/>
<br/>
I visited Sengoku Densho again.<br/>
A variety of gears are soldon the 3rd floor.<br/>
![Proto_1_1](/photo/Proto_1_1.jpg)<br/>
<br/>
**What I bought**
・[Spun gear (50 teeth, 1.0 module)](https://www.sengoku.co.jp/mod/sgk_cart/detail.php?code=8AGA-HGKC) ¥649<br/>
・[Handle(40mm, 3.0module)](https://www.sengoku.co.jp/mod/sgk_cart/detail.php?code=4AZU-JFFG()  ¥682<br/>
・Bevel gear (? teeth, 6.0 module) ¥490<br/>
・[Pinion gear (14 teeth, 1.0 module)](https://www.sengoku.co.jp/mod/sgk_cart/detail.php?code=EEHD-0SDD) ¥363<br/>
・[Screw rod](https://www.sengoku.co.jp/mod/sgk_cart/detail.php?code=4A8D-BJEG) (3mm*29mm) * 2 = ¥594<br/>
・[Stainless shaft (6mm) ¥480 -> (5mm)](https://www.sengoku.co.jp/mod/sgk_cart/detail.php?code=EEHD-4L6A) ¥480<br/>
<br/>
Note: I couldn't find plate-shaped materials in Sengoku Densho that is suitable to fix gears. I should look it for other shops.<br/>
<br/>
**Additional items purchased**<br/>
・[Screw rod (3mm*59mm)](https://www.sengoku.co.jp/mod/sgk_cart/detail.php?code=5A8D-CJEJ)  ¥396<br/>
・Hexagon head nut(3mm) * 6 = ¥60<br/>
・[Mini Glue](https://www.amazon.co.jp/アロンアルフア-EXTRA-ミニ×4-0-5g×4-04611/dp/B000IGRZ2W/ref=asc_df_B000IGRZ2W/?tag=jpgo-22&linkCode=df0&hvadid=222868425990&hvpos=&hvnetw=g&hvrand=13755070881471756200&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=20636&hvtargid=pla-440365886762&psc=1&th=1&psc=1) ¥396<br/>
・Clay（ダイソー）¥110<br/>
・Cork Board（ダイソー） ¥110<br/>
<br/>
Note: I bought clay and cork board, as I thought it could be used as a foundation.<br/>
<br/>
Total amount: ¥4,676<br/>
<br/>
![Proto_1_1_2](photo/Proto_1_1_2.jpg)<br/>
<br/>
Handle<br/>
![Proto_1_2](photo/Proto_1_2.jpg)<br/>
<br/>
![Proto_1_3](photo/Proto_1_3.jpg)<br/>
<br/>
Spun gear<br/>
![Proto_1_4](photo/Proto_1_4.jpg)<br/>
<br/>
Connect handle and spun gear with screw to move together.<br/>
![Proto_1_4_2](photo/Proto_1_4_2.jpg)<br/>
![Proto_1_4_3](photo/Proto_1_4_3.jpg)<br/>
<br/>
Screw rod<br/>
![Proto_1_5](photo/Proto_1_5.jpg)<br/>
<br/>
Pinion gear <br/>
![Proto_1_5_2](photo/Proto_1_5_2.jpg)<br/>
<br/>
Unfortunately, it appears that 6mm shaft is too big to fit after buying it. So, I had to go back the shop to changed it to 5mm. This time, however, it was still not match with the hole of bevel gear. I will have to deal with this problem later (fill a gap with something?).<br/>
![Proto_1_6](photo/Proto_1_6.jpg)<br/>
<br/>
![Proto_1_8](photo/Proto_1_8.jpg)<br/>
![Proto_1_9](photo/Proto_1_9.jpg)<br/>
![Proto_1_10](photo/Proto_1_10.jpg)<br/>
![Proto_1_11](photo/Proto_1_11.jpg)<br/>
![Proto_1_12](photo/Proto_1_12.jpg)<br/>
<br/>
![Proto_1_13](photo/Proto_1_13.jpg)<br/>
![GIF Cent_proto_1](photo/Cent_proto_1.gif)<br/>
My choice that using clay as foundation was entirely mistake, though it helped  to adjust the positions of each parts. It was too soft to fix the gears and polls...<br/>
土台がよわよわすぎた……😭😭<br/>
Therefore, I will make foundation with material which is harder next time.<br/>
<br/>
![Proto_1_14](photo/Proto_1_14.jpg)<br/>
<br/>
Not working version (pinion gear and bevel gear are not meshing well)<br/>
![GIF Cent_proto_2(not working)](photo/Cent_proto_2(not working).gif)<br/>
<br/>
After adjusting the height of the bevel gear, then it worked (just a little bit...).<br/>
![GIF Cent_proto_3(working)](photo/Cent_proto_3(working).gif)<br/>
Anyway, it was good to know that the gears' teeth are meshing and able to move, even though it moved awkward.<br/>
<br/>
こっちを使ったほうがよっぽど早いのでは、という誘惑（3000円くらいだし）……。しかしひとまずは一から作ることに挑戦してみたい。<br/>
![Motor gear box](photo/Motor gear box.jpg)<br/>
<br/>
**Reviews & Tasks**<br/>
・コルクボードで土台を作ってみる。もしそれがうまくいかなければ、別の素材を探す。<br/>
・棒の隙間を埋める<br/>
・今の歯車の数では回転数がかなり遅いと思われる。より速い回転を得たければ、もっと歯車の数を増やす必要がある。<br/>
・ハンドルが小さくて回しにくいので、これも改良したい。<br/>
・歯車の仕組みを理解することや、さまざまな種類があるのが面白くて、歯車にはまってきた。ただ、あまり歯車自体に夢中になると本来の目的を忘れそうなので、程々に。
<br/>
## 3/23(Sun) Prototype 2
Place: FabCafe Material<br/>
![Sample](/photo/93290-2.jpg)<br/>
<br/>
![Moving the handle](/photo/Spinning_2.jpg)<br/>
<br/>
