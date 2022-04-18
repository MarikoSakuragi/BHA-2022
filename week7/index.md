# Week 7: CRISPR Week
## BioHack Academy: Fabio Ferreira - Digital DNA Design
<br/>
This is the lecture about methodology of designing genes and how to get them.<br/>
<br/>
#### Coding<br/>
（DNA配列に対して）Mutagenic event ->deletion -> insertion -> Substitution（置換）<br/>

#### CRISPR<br/>
Q. What is Linker loop?<br/>
<br/>
細胞が壊れたとき（皮膚の怪我など）・・・DNAは自力で修復しようとする<br/>
→CRISPRはその仕組みを利用して、壊したDNAの配列の隙間に新たなDNA配列を挿入する<br/>

#### Design sgRNA: Tools and parakeets<br/>
・Target (coding and non-coding sequences)<br/>
・PAM(s)<br/>
・On-target efficiency<br/>
・Off-targets<br/>
<br/>
There are online tools for the design.<br/>
・Species-specific (mice, zebra fishes, etc…)<br/>
・Coding vs non-coding sequences (Coding: place and write name of the genes.)<br/>
（既に用意されているものがあるということらしい。どっちがどっち？）<br/>
・integration of multiple parameters<br/>
<br/>
#### Some online tools to select sgRNA<br/>
Fabio’s recommendation is “Benching”<br/>
<br/>
#### Where to get the vectors (and sgRNAs)<br/>
A lot of companies sell the prasmids<br/>
- Addgene (Non-profit) 60€(?)<br/>
[https://www.addgene.org/guides/crispr/](https://www.addgene.org/guides/crispr/)<br/>
↑There are also protocols for CRISPR.<br/>

#### How to use Benching
Pick your gene. For example, ENSG0000254647<br/>
↓<br/>
On Benching click “+”<br/>
-> DNA sequence<br/>
-> New DNA sequence<br/>
-> Search External Databases<br/>
-> Search for “ENSG0000254647”<br/>
-> Import<br/>
<br/>
![Benchling_1](/photo/Benchling_1.jpg)<br/>
<br/>
![Benchling_2](/photo/Benchling_2.jpg)<br/>
<br/>
![Benchling_3](/photo/Benchling_3.jpg)<br/>
<br/>
![Benchling_4](/photo/Benchling_4.jpg)<br/>
<br/>

## Homework
- Explain, draw/sketch and understand the CRISPR/Cas9 mechanism. Name the involved parts, expand and learn the acronym, explain why this technology is a break-through, explain how it can be programmed.<br/>
<br/>
- Explain, draw/sketch and understand the DNA Repair mechanisms: HDR and NHEH<br/>
<br/>
- Make an account at [benchling.com](http://benchling.com/) and follow the CRISPR tutorial from Fabio Ferreira on Digital DNA Design.<br/>
<br/>
- *Extra Credit: Compare with other Genome Editing technologies like Restriction Enzymes, TALENs and ZFNs.*<br/>
<br/>

## CRISPR Basic
#### What is CRISPR?
CRISPR: Clustered Regularly Interspaced Short Palindromic Repeats<br/>
<br/>
（・・・・）<br/>
<br/>
[CRISPR Cas9 - A Brief Introduction(YouTube)](https://youtu.be/1aJxXWkE3Ek)
<br/>
### Guiding, Cutting, Checking
#### <font color="Olive">Guiding</font>
Making guide RNA to instruct CAS9 where to cut<br/>
1. setting the stage for sgRNA production<br/>
2. 60m Making sgRNA<br/>
3. 30m Destroying unnecessary DNA<br/>
4. cleaning sgRNA<br/>

#### <font color="Olive">Cutting</font>
CAS9 precisely cuts DNA<br/>
1. Setting the stage for CAS9 cutting<br/>
2. Combining sgRNA + CAS9+targetDNA<br/>
3. 60-90m cutting targetDNA<br/>

#### <font color="Olive">Checking</font>
Separate DNA fragment<br/>
1. Preparing the GEL<br/>
2. Running the GEL<br/>
3. Checking the GEL (UV light)<br/>

<br/>
Heat shock? (PCR?)<br/>
<br/>
### Make sure you know definitions of:
- sgRNA<br/>
sgRNA(segment RNA)=gRNA(guide RNA)<br/>
"CRISPR/Cas9 gene targeting requires a custom single guide RNA (sgRNA) that contains a targeting sequence (crRNA sequence) and a Cas9 nuclease-recruiting sequence (tracrRNA)."<br/>
<br/>
sgRNA is consists by 2 regions: crRNA sequences and tracrRNA.<br/>
<br/>
![seRNA](/photo/CRISPR_1.jpg)<br/>
Citation above and image from [How to design sgRNA sequences - Takara Bio](https://www.takarabio.com/learning-centers/gene-function/gene-editing/gene-editing-tools-and-information/how-to-design-sgrna-sequences)<br/>
<br/>
- PAM sequence<br/>
PAM: "Protospacer Adjacent Motif" (プロトスペーサー隣接配列)<br/>
Specific sequence of nucleotides, around 2-6 base pairs, that follow the protospacer sequence in a viral genome<br/>
<br/>
CRISPR cut target sequences only when PAM follows just behind that sequences. It is thought that PAM is the system that microbes distinguish themselves from viruses.<br/>
<br/>
![CRISPR Cas9 - A Brief Introduction](/photo/CRISPR_2.jpg)<br/>
Image from [CRISPR Cas9 - A Brief Introduction(YouTube)](https://youtu.be/1aJxXWkE3Ek)<br/>
<br/>
![CRISPR_memo](/photo/CRISPR_memo.jpg)<br/>
<br/>
- Promoter<br/>
<br/>
<br/>
- Plasmid<br/>
<br/>
<br/>
- 5' to 3' Directionality (“5 prime to 3 prime)<br/>
"5' and "3'" indicate the carbon numbers in the DNA's sugar backbone.
DNA sequences always extend to 5'(five prime) -> 3'(3 prime) direction.<br/>
<br/>
![5' to 3' Direction](/photo/CRISPR_3.jpg)<br/>
Image from [Wikipedia](https://en.wikipedia.org/wiki/Directionality_(molecular_biology))<br/>
<br/>
- Enzyme<br/>
"Enzymes are built of proteins folded into complicated shapes; they are present throughout the body.The chemical reactions that keep us alive – our metabolism – rely on the work that enzymes carry out."<br/>
[Enzymes: How they work and what they do - *Medical News Today*](https://www.medicalnewstoday.com/articles/319704#the-basics)<br/>
<br/>
**Cas9** is also the enzyme which cut genome:a dual RNA-guided DNA endonuclease enzyme.<br/>
<br/>
<br/>

#### References<br/>
- CRISPR Cas9 - A Brief Introduction<br/>
[https://youtu.be/1aJxXWkE3Ek](https://youtu.be/1aJxXWkE3Ek)<br/>
<br/>
- What is the PAM? - A CRISPR Whiteboard Lesson<br/>
[https://www.youtube.com/watch?v=iSEEw4Vs_B4](https://www.youtube.com/watch?v=iSEEw4Vs_B4)<br/>
<br/>
- CRISPR-Cas9 基本の「き」コスモ・バイオ株式会社<br/>
[https://www.cosmobio.co.jp/product/detail/crispr-cas9-introduction-apb.asp?entry_id=15520](https://www.cosmobio.co.jp/product/detail/crispr-cas9-introduction-apb.asp?entry_id=15520)<br/>
<br/>
- Wikipedia, "Directionality (molecular biology)"<br/>
[https://en.wikipedia.org/wiki/Directionality_(molecular_biology)](https://en.wikipedia.org/wiki/Directionality_(molecular_biology))<br/>
<br/>
- Wikipedia, "Phosphodiester bond"<br/>
[https://en.wikipedia.org/wiki/Phosphodiester_bond](https://en.wikipedia.org/wiki/Phosphodiester_bond)<br/>
<br/>
- CRISPR　そしてゲノム編集へ… RNA Japan<br/>
[https://www.rnaj.org/newsletters/item/844-nishimasu-1](https://www.rnaj.org/newsletters/item/844-nishimasu-1)<br/>
<br/>
- 国内初！ゲノム編集トマト 「シシリアンルージュハイギャバ」<br/>
(Genetical modified tomato by CRISPR-Cas9 was developed in 2020)<br/>
[https://p-e-s.co.jp/higabatomato_column/genome-editing-for-sicilian-rouge/](https://p-e-s.co.jp/higabatomato_column/genome-editing-for-sicilian-rouge/)<br/>
<br/>
- Benchiling
[https://www.benchling.com](https://www.benchling.com)<br/>
