# Week3: Making the Lab
In this week, we are going to get used to fabrication tools (3D printer, laser cutter, and 3D design software). The purpose of this week is to learn how to make hardware by using fabrication tools.<br/>
I guess this week gonna be a hardest challenge for me who haven’t had any experiences of using either design nor modeling software...<br/>
<br/>

## 1. Install and Test at least 2 different 3D Applications.

## (2) Using 3D modeling software

### Lists of software
I downloaded and tried to use these software shown below. However, I failed to download OpenSCAD and FreeCad due to the security reason of Macbook. About SketchUp, it appeared that it is usable to create something by myself but  cannot be used for installing STL file unless I update (that means I have to resister the paid version). Also, handling Blender was, in my impression, too high-level for amateur like me. I thought it would be necessary more practice for dealing with these softwares well.<br/>
・SketchUp<br/>
・OpenSCAD<br/>
・FreeCAD<br/>
・Blender<br/>
・Fusion360<br/>
<br/>
### Making Spur Gear by Fusion360
For an excercise, I made a spur gear. <br/>
<br/>
**Reference**<br/>
・[【歯車マスターへの道】超入門編・Fusion360での歯車の作り方](https://www.youtube.com/watch?v=fEFBxSfHgyg)<br/>
・[Fusion360で歯車を簡単に作る方法｜噛み合わせて回転させるには？](https://www.fact-cam.co.jp/product/2019/10/fusion360/archives/000447.html)<br/>
・[Fusion360による歯車設計](https://fabble.cc/robotakun/fusion360xxxxxxx)<br/>
<br/>
![Fusion](/photo/Fusion_pic_1.jpeg)<br/>
<br/>
・ This is start screent of Fusion360.<br/>
![Gear2](/photo/Fusion_pic_2.jpeg)<br/>
<br/>
・ Utirity -> Add-in- > Select "SpurGear" from a list -> 「実行」<br/>
![Gear3](/photo/Fusion_pic_3.jpeg)<br/>
<br/>
・ Setting of a spur gear<br/>
![Gear4](/photo/Fusion_pic_4.jpeg)<br/>
![Gear5](/photo/Fusion_pic_5.jpeg)<br/>
<br/>
**Settings**<br/>
| Standard　|　Metric　|
| Pressure Angle　|　20deg　|
| Module　|　1　|
| Number of Teeth　|　24　|
| Backlash　|　0mm　|
| Root Fillet Radius　|　0mm　|
| Gear Thickness　|　2.5mm　|
| Pitch Diameter　|　2.5mm　|
<br/>
<br/>
About items...<br/>
・Standard: Unit of length<br/>
・Pressure Angle: The size of the cutting edge<br/>
・Module: Pitch Diameter/Number of Teeth<br/>
・Number o Teeth: 〃 <br/>
・Backlash: The expansion gap<br/>
・Root Fillet Radius: <br/>
・Gear Thickness: The thickness of gear<br/>
・Hole Diameter: The size of hole<br/>
・Pitch Diameter: 〃  <br/>
<br/>
・A spur gear will be shown.
![Gear6](/photo/Fusion_pic_6.jpeg)<br/>
<br/>
・I added another small spun gear. It can be easily made by changing the number of teeth when setting details.<br/>
![Gear7](/photo/Fusion_pic_7.jpeg)<br/>
<br/>
<br/>
## 2. Hands-on Group Work: Design and Make a CleanBox
Materials<br/>
- Cardboard box<br/>
- Plastic bag<br/>
- Hairdryer<br/>
- Tape<br/>
- Cutter<br/>
<br/>
What is essential for a cleanbox is:<br/>
- Spatial separation between in/outside of the box<br/>
- Air flow (from inside to outside of the cleanbox)<br/>
- The space to insert hands into it.<br/>
<br/>
<br/>
## 3. Fork and Change the BHA Stirrer Repo
## (1) Folking GitHub repositories
"Folking" means to clone a remote repository and save it in your page.<br/>
By folking, you can edit the codes and files of the original.<br/>
<br/>
・Access to the original repository<br/>
This time, I have localized BHA's DIY magnetic stirrer.<br/>
![Local1](/photo/w3_screenshot_1.png)<br/>
<br/>
・To localize, push a "local" button on the upper right of the page.<br/>
![Local2](/photo/w3_screenshot_2.png)<br/>
<br/>
・Then, the page is localized to your own page.<br/>
![Local3](/photo/w3_screenshot_3.png)<br/>
<br/>
・Click your icon and select "Your repositories."<br/>
![Local4](/photo/w3_screenshot_4.png)<br/>
<br/>
・When you select "Your repositories," you can check all your repositories.<br/>
![Local5](/photo/w3_screenshot_5.png)<br/>
<br/>
・Click "Code" and "Open with GitHub Desktop," the GitHub Desktop automatically open, and you can edit the code.<br/>
![Local6](/photo/w3_screenshot_6.png)<br/>
<br/>
<br/>
Reference:[「Blenderでのインポート手順」](https://www.kkaneko.jp/db/cg/blenderimportexport.html#S3)<br/>
<br/>
<br/>
## (2) Find out where to get the parts online in Japan
- [Akitsuki Densho online shop](https://akizukidenshi.com/catalog/)<br/>
- [Aitendo](https://www.aitendo.com)<br/>
- [Marutsu](https://www.marutsu.co.jp)<br/>
- [Sengoku online](https://www.sengoku.co.jp)<br/>
<br/>

## (3) Update the BoM_Japan.md file with more current information.
<br/>
<br/>
<br/>
## 4. Prepare the PocketPCR Case for 3D Printing
<br/>
<br/>
## 5. Akihabara Tour (optional)
## 3/19(Sat)
As an option of BHA, we did Akihabara tour for looking around electric parts shops. Akihabara is well-known as a electric town which has long history..<br/>
![Akihabara1](/photo/Akihabara_1.jpg)<br/>
<br/>
We visited a lot of shops. Georg-san, our local instructor, led the way to an area where old stores were lined up along the street and into an alley. Under the low ceilings with exposed piping and electric lights, there was a cluster of small stores with countless goods and parts crammed into as many as possible. There was a store specializing in radio equipment, an audio store selling used videotapes and cassette tapes, a store selling only electrical buttons, etc.
There were There were also used goods like junk on sale. It was the first time for me to visit such a place, and so to the other female participants. We were curious about everything. <br/>
![Akihabara2](/photo/Akihabara_2.jpg)<br/>
<br/>
Next, we visited to an old building called "Tokyo Radio Department Store(東京ラジオデパート)," which was entirely occupied by parts stores.<br/>
![Akihabara3](/photo/Akihabara_3.jpg)<br/>
![Akihabara4](/photo/Akihabara_4.jpg)<br/>
<br/>
And then went on a short walk to Akitsuki Denshi Tsusho(秋月電気通商) and Sengoku Densho(千石電商), both specialized in electric parts and tools.
![Akihabara5](/photo/Akihabara_5.jpg)<br/>
<br/>
In Akitsuki Denshi Tsusho, the walls of the not-so-spacious store were filled with drawers, and each of the small drawers held various small electronic parts such as resistors, sensors, USB connectors, and so on.
![Akihabara7](/photo/Akihabara_7.jpg)<br/>
<br/>
Georg-san opened the drawers and showed us their contents, but these all looked the same to me. This is an Arduino, Georg-san said, and he found a microcomputer Arduino and showed it to me. Georg-san told us that the Arduino was easy to operate and that we would be able to use it in no time. We opened the drawers at random, and got excited talking to each other about the parts in them and what they were. There were more people than expected, and the store was packed with customers. <br/>
![Akihabara8](/photo/Akihabara_8.jpg)<br/>
![Akihabara9](/photo/Akihabara_9.jpg)<br/>
<br/>
Finally, we went to "Hard-Off" in Akihabara which is a second-hand shop. Hard-Off was a mess of used stereo equipment, used cables, headphones, and tablets. <br/>
![Akihabara10](/photo/Akihabara_10.jpg)<br/>
Around 4p.m., our tour came to an end. It was exciting excursion!<br/>
<br/>
