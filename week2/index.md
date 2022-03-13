# Week2: Deconstruction/Construction of Hardware

## 3/8(Tue) Foldscope, Pocket PCR
#### Participants: Georg, Tsuchiya, Yokogawa, Sakuragi
<br/>
### 1. Making Foldscope
We assmbled Foldscope from the kit, and do observation.<br/>
#### <font color="Olive">- About Foldscope</font>
Foldscope is a small and low-cost microscope made by paper. It was designed by Manu Prakash, a Professor of Oxford University. He developed Foldscope by hoping to make microscope more accessible for children in developing countries such as India. <u>[Foldscope Website](https://www.foldscope.com)</u><br/>

#### <font color="Olive">- Contents</font>
![Parts](/photo/IMG20220308151958-2.jpg)<br/>
<br/>
・Instruction manual<br/>
・Parts of Assembly<br/>
　・Main Parts: Lens stage, Sample stage, Panning guide, Focus ramp<br/>
  ・Sub Parts: Slides, Coupler, Lens, Ring sticker, Covership stickers<br/>
<br/>
#### <font color="Olive">- How to make Foldscope</font>
1. Tear off each parts along perforation.<br/>
![Step1](/photo/IMG20220308152559-2.jpg)<br/>
<br/>
2. Place and insert coupler into center holes.<br/>
![Step2](photo/220308-24-2.jpg)<br/>
3. Flip Lens Stage, put coupler into down holes.<br/>
4. Turn back lens stage. Insert Focus ramp under the lens which is put at Step2.<br/>
5. Assemple Sample stage and Panning guide<br/>
（Causion: If you don't assemble them right, sample stage will not move.)<br/>
6. Assemple 5. and Lens Stage.<br/>
![Step6](/photo/220308-31-2.jpg)<br/>
7. Finish!<br/>
![Foldscope](/photo/IMG20220308160240.jpeg)<br/>
Let's check if you make correctly by sliding Panning guide and Focus ramp. If these are moved smoothly, it's done! Let's look through the microscope.<br/>
<br/>
#### <font color="Olive">- Observation</font>
Foldscope's magnification is 140X. You may able to watch microorganisms and plants tissues. Our local cordinator Georg Tremmel reccomended us to use pond water as a sample for example. He said also that Tardigrade (Kumamushi）is also interest sample to watch by microscope. This time, we saw the cross section of a fern through the Foldscope.</br>
When you want to see something, you put the sample on a slide glass, and set the slide glass above the lens. Then, adjust focus by moving Panning guide and Focus ramp. Panning guide can  adjust X and Y axis, and Focus ramp changes Z axis: the distance between lens and subject. <br/>
<br/>
![Focusing](/photo/FocusingFoldscope.gif)<br/>
<br/>
A light source is important for observation. "To view directly, bring the lens to the eye and view while  holding the Foldscope up to a light source, such as daylight or artificial lighting"(cited from "View methods" of official website). <br/>
![Looking into Foldscope](/photo/220308-39-2.jpg)<br/>
At first, I could see nothing in my view. It was caused because I made a made a mistake that put a slide glass upside down. After fixed it, I coud see clearly each fern's cells and nucleus inside them.<br/>
You can also take a picture by attatching your phone camera with Foldscope lens. <br/>
![Picture by phone camera](/photo/1647131798476.jpg)<br/>
The picture below is the photo micrograph of fern that  I took by my phone.<br/>
<br/>
![Fern Photo](/photo/Foldscope_Fern.jpeg)<br/>
<br/>
***
### 2. Deconstruction of PCR
We have watched PCR machine and learn how it works. We watched together three types of PCR(thermal cyclers): 80's PCR, BentoLab, and PocketPCR.<br/>
<br/>
![80's PCR](/photo/IMG20220308150609.jpeg)<br/>
<div style="text-align: center;">80's PCR machine</div><br/>
These are different in size and price, but main function is almost same.<br/><br/>
We opened up the 80's PCR and learned the basic structure of PCR.<br/>
<br/>
![Inside 80's PCR](/photo/IMG20220308175450.jpg)<br/>
It consists of perche system which control the temprature, fan, and circuit board. I found that basic structure and function of PCR have not been changed dramatically since initial PCR models.<br/>
<br/>
Since I am not a engineering person, I couldn't get what functions each parts on the circuit board have. But some of our team who is familiar with fabrication supeculated and tought the others about each parts on the board. In this experience, I think it would help to analyze hardware with friends who is good with machines.<br/>
<br/>
PCR is used for the amplification of specific DNA sequence. The PCR's function is simple, it repeat the cycle of heating and cooling at certain temprature (95℃→55-60℃→70-74℃→95℃→...).<br/>
・高い製品とポケットPCRのような最低限の機能は備えたPCRとでは何が異なっているのか疑問に感じた。
<br/>
***
### 3. Making PocketPCR
![Pocket PCR](/photo/IMG20220308194338.jpeg)<br/>
<div style="text-align: center;">Pocket PCR</div>
<br/>
#### <font color="Olive">- About PocketPCR</font>
*"The PocketPCR is a low-cost, small size thermocycler capable of activating biological reactions such as polymerase chain reaction (PCR)."*(cited from [here](https://gaudishop.ch/index.php/product/pocketpcr-kit/))<br/>
・Cost: €99<br/>
・PockerPCR is open source device. You can see the designs on GitHub.<br/>
[https://github.com/GaudiLabs/PocketPCR](https://github.com/GaudiLabs/PocketPCR)<br/>
If you interested in or want to buy it, please access to [PocketPCR official website](https://gaudi.ch/PocketPCR/)<br/>
<br/>
Reference:[https://www.hackster.io/news/gaudilabs-releases-pocket-sized-thermocycler-with-the-pocketpcr-5f86674e44be](https://www.hackster.io/news/gaudilabs-releases-pocket-sized-thermocycler-with-the-pocketpcr-5f86674e44be)
<br/>
#### <font color="Olive">- Making PocketPCR</font>
**・Soldering**<br/>
The parts of  PocketPCR is quite simple: a circuit board, small electric fan, and a button.（＋フタ、オプションでケース） A tube hole and a monitor are put on the reverse side of the circuit board.<br/>
<br/>
![Upside](/photo/IMG20220308182911.jpg)<br/>
<br/>
![Downside](/photo/IMG20220308192245.jpg)<br/>
<br/>
You have to solder the button and fan in the ordered place of the circuit board, following instructions. To make it easy, it is better heat  the position which will be soldered, with soldering iron. Be careful not to leave any space in order to bond the parts steadily.<br/>
<br/>
![Soldering](/photo/IMG20220308192104.jpg)<br/>
<br/>
Lastly, put the legs on the four courners of the board. (３Dプリンタで作れるケースもある)<br/>
<br/>
![Put legs](/photo/IMG20220308193848.jpeg)<br/>
<br/>
![Parts](/photo/IMG20220308191525.jpeg)<br/>
<br/>
**・Start PCR**<br/>
When connected to power source with type-C cable, PocketPCR starts to work and the screen on. You can use computer or mobile buttery as power source. <br/>
<br/>
![Connect to PC](/photo/IMG20220308194628.jpg)<br/>
In the setup page, you can set heating/cooling tempratures, time, and cycles of PCR by push or turn the button. The setup manipulation is not difficult. After press the "Run PCR," PCR will start. Don't touch coils around the tubes during heating because it is getting high temprature. <br/>
<br/>
![Setup](/photo/IMG20220308194743.jpg)<br/>
<br/>
I was impressed by how well PocketPCR works even it is so small.
（動くことに感動。意外としっかりとした作りをしている。容量は小さそうだが十分か、やや不安。実際に実験で使ってみない限り性能は評価できない。）
<br/>
<br/>
## 3/10(Thu)
#### Participants: Georg, Haneda, Sakuragi, Hirose

<br/>
## What I learned through Week2?
・History of microscope<br/>
・Basic structure of microscope: lens, light, stability of stage, and XYZ-axis to focus on.<br/>
・and more...<br/>
