# M609 Remote Sensitivity Distribution Amplifier · Amplifiers

Ward-Beck Systems M609, 1983|16. Wiki page: [M609 on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M609.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 101 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 2 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 3 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 331 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 1 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 1 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 23 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 55 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

## Specifications

From the technical data sheet: [1983 - M609 - P005 - 1-2.jpg](MANUALS/1983%20-%20M609%20-%20P005%20-%201-2.jpg) page 1 (read by OCR; check against the page). As data: [`Specifications.json`](Specifications.json).

| | |
|---|---|
| **Phasing** | The low terminal number the input pair and the low termina number the output pair are phase. |
| **Power requirement** | 115V AC +/-10%50/60 Hz, 25VA |
| **Ambient temperature** | 50 degrees Celsius. |
| **Dimensions** | wide (86 mm 3.4&quot; high mm 348 mm) deep |
| **Weight** | oz. (1.70 Kg. net |

## Circuit description

From [1983 - M609 - Remote sensitivity and DA (2).pdf](MANUALS/1983%20-%20M609%20-%20Remote%20sensitivity%20and%20DA%20(2).pdf) pages 24-29 (read by OCR; check against the pages). As data: [`CircuitDescription.json`](CircuitDescription.json).

<details><summary>Read it</summary>

SA1i~_I01 AUDIO DiSTRIBUTION AMPLIFIER

Thea u d io input to the SA14_101 Amplifier Assembly &quot;ppe &quot;r,. a t pins t &quot;nd 2 of thea s semb ly conn ec to'. Rl, R2 &quot;nd R3 determine the input impedance of the actively balanced input. CRt through CR4 are limiting diOdes which protect the amplifier input from overloading voltage revets • Integrated circuit Ul and ATTl (M20 8) with their e es ccre re c components ma&quot; e up thea c t i v e l y balanced preamplifi er.

ATTI, the M208 volt age con trolled at tenuator, i, an e n caps u late dun it of WBS propri etory design.

R7 and C6, ·Ihe low frequency and high frequency differential adjust controlS, determine Ih e longitudinal balance b etw ~n the two prea mp l l fie r section s (UI and ATT1). The adJus lment of these components d &quot;l ermines the degree of rejection to common mode signal voltages, typically better than 50 dB overt h &quot; audio frequency band.

Th&quot; precision resistor n&quot;twO&lt;&quot;&quot; R19 t h rough R25 determines the gain range of thea mp l i fie r. Ash u n t 5K ohm conl roil ing el emenl is eco o eer ee 10 pin 7 of Ih e assembly ccnoec rc e • Sh or lin g ou l this control poinl to the amplifier common will result in maximum gain. This maybe trimmed 10 +-30 dB by adj uSl l n g Gain Set control R23.

Selting the remote con lrolling element 10 5K ohm (norm ally fully ccw) r&quot;sults in thea mp l if ie r Slain going to minimum, which. Is _30 dB. If this control line is left open Ihe minimum gain will drop t o are es evalu e, typically by a t lea sl another 20 dB.

The Bias Set control R12;,~ factor y set for optimal performance. Should this control become inadvertently adj u s I&quot; d, II may e e, e t to its optimal point a s follows; Set Ihe amplifi &quot;r gain 10 unity (I.e. +-8 dBm input for +-8 dBm ou tPUI), r &quot;mov&quot; the inputs ig na land term ina t e thea mp l i fie r in 600 ohms. Ma &quot;i n g ana b s o lute output noi, e measure m&quot;n t (over a 20 Hz to 20.. Hz BW) adjust R1 2 for ana bsolu te output noise revet of -72 to _ 74 dBm (corresponding 10 an outp ul noise level o f 80 to 82 dB below +-8 dBm).

The output of ATTl is coupled to the pow &quot;r amp l i fie r output st.. g e

I hroughCl2.

SA14 _101 AUDIO DISTRIBUTION AMPLIFIER

The &quot; c l i v&quot;l y b &quot;l &quot;nced p o..... e,.. outputs t &quot; g e Is made UP oft.....o &quot; mp li f ' e,..s. In teg,..&quot; ted cf r-cult U2 along with Q l Ihr'&quot;Ough a s mak '&quot; up the low &quot;,.. half of the pow e'&quot; oulp ul amp li f le '&quot; wh ll&quot;, U3 along..... 111'1 0 6 th&quot;,ough C l 0 makeup Ih e ucce rhalf.

The output capability 01 I h ls pow e,.. amp l i fie,.. Is in excess o f 2 1/2 W&quot; lI s &quot; n d &quot; p pea,..s a t pins 18 and 19 of I h e assembly coon e CIO,...

The output f,..om this &quot; mpHfle '&quot; d,..lv es the 600 ohm spllue,.. n e l wo,..k s located on the SAI4_066A/B /C assemblies.

Offs el &quot; d j u s l cont,..ols R31 &quot; nd R4 9 &quot;,..e used to Ir'&quot;Im offset voltage err -: o,..s &quot; t thea mp l (f le,.. o ulput toe e r-c • These conn -eta,,&quot;'e set to give a n output DC offs e l vollage o f less than 50 mv when no audios i g ned Isp &quot;'e sent.

The powe '&quot; supply, Int eg,.. alto the SA14_101 assembly, d e,..lv e sIts AC vol l &quot;ge (appe a,.. l n get pins 21 and 22 oft h e assembly conneclor) from the external power transformer T20 1 mounted 00 tte c has sis of the M609.

Bridge rectifier CRS along..... ilh C3 1 and C32 rec ll fl es and fillers the AC vOIl&quot;ge providing a nominal +/_ 32 v o ll DC output. These vo ll &quot;ges drive the power oU lpu t s t&quot; geo f I h e SA14-10 1 d lrecll y, e awe l las app e&quot; rl n g lit connec lo r pins 15 and 16 forth e p u r pose of po.....erlng I h e e Xle rna l SA6_11 7 l rtdtc ato rDriver Assembly.

The +/ -32 volt DC voltages are fur the r decoupi ed and,..e gul a ted by U4 and US along.....I th C35 and C36. This provides p r ec ls o n +/ _18 voll DC &quot;'eg ul&quot; ted supply voltages 10 op e &quot;'ate Ih eIn t eg rated circuit amplifiers and the M206 remote e rt eoo a tcrof the SA14_101 Amplifier Assembly. The +/-16 volts should b e within +/ _0.25 volts of then o min a l value for correct operation oft h e amp l i fie r.

**PARTS LIST**

SA 14_ 101 AUDIO DISTRIBUTION AMPLIFIER

**MFG PART NUMBER**

ct Cap ~dlo&quot; 220 uF / l0 V T390F227M01 0AS ca 220uF /l0V ca 22pF 2222 _638_10229::~~iS T3 90F227M010AS &quot;cs 220 uF /l 0 V 220 uF/ l0 V

C6 2_ 18 pF Philips 2222_ 8 09_ 0 50 0 3 cr 330pF 2222 -630-03331 ce 10 uF/25 V T390C l06M025AS C9 10 uF/25 Vcr 22 uF/35 V

CO, 10 uF/25 V eta 10 uF/25 V eta delete C &quot;p ~ciIO&quot; l OO pF Philips 22 22_638 _58 10 1

cts 12 p F 2222 _638 _10129

ere 4.7p F 2222 -638 -09478 ct z 15 p F 222 2 _638_10 159 ere 22 p F 2222_638_10 2 29 ct s 22 uF/35 V Ke met T39 0£226 M035AS ca 22pF Phillp s 2222_638 _10229

ca 0.0 2 2 u F/l00 V As elco CQ9 2_MC_ l00 _22 3M ca 33 u F/ l 0 V Kem e t T39003 36 M010 AS cal OO p F P h:,lips 2 222_6 38 _581 0 1 cz 12 p F 2222 -638-1012 9 cas 4.7 pF 2222-638-09478

C&quot; 15pF 2222_638 _10 159 C&quot; 47pF 2222-638-34479 C28 22 uF/35 V Kemel T39 0£2 26M035AS C29 22pF Philips 2222_638_10229 CJO 0.0 22 uF / l00 V e setec C09 2_MC_l00_223M

C&quot; 470 u F/40 V Ph,i,li ps

CJ2 470uF/ 40V

C3J 10 u F /25V T39 OC106 M025AS CJ&lt; 10 u F / 25V

C28 22 uF / 25 V 22/~~ 85200

C28 22 uF/ 25 V

5,01, 1....,0, AUDIO DiSTRIBUTION AMPLIFIER

**MFC PART NUMBER**

C&quot;, Diode F a i rch i l d

CR, B.id g eRect if le.

&quot;' Re &quot; ln&quot;IOr&quot; 1/4'11,,5S

.,R' T.-Im Pot 1/4'11 lS 121&lt;1....R2S F

R' Re l l&quot; to/&quot; 1/4'11 I S

**1/4'11 IS**

PTl Oh (2.5)

**MR2S F**

R&quot; 1/4'11 5f. &quot;&quot;

**R&quot; UK**

R&quot; T.- Im POI SK PTlOh 12.5) 51(.&quot; Re&quot; I: I O/&quot; 1/ 4'11..5S sro CR&quot;

**R20 JI(J2**

R2J Trim Pot

41(75 500 P l her PTl Qh (2.5) SOO R&quot; Rel l,~tor 1/ 4 W,,' S 471(5 Philips MR25 F

**R26 1/ 4'11 5%**

Rn delete

R28 R &quot;&quot; I,~t o.-1/4 '11,,5% P h~,1 i ps

**ROO '.7**

5A14-IOl AUDIO DISTRIBUTION AMPLIFIER

DESCRIPTION MFG PART NUMBER

RJ ' Poten tiome ter 50' Plher F'Tl Oh (2.5) 501&lt; R. sl,~tor 1! 4W&quot;.5' F'h~.r iP5

**1! 4W &quot;.5'**

Trim POI P iher F'TlOtl 12.5) 50K

, so Resistor 1! 4W 5' '&quot; Philips CR25

s se

ass 1!2W,,5' 2.2, sc a.z

**SA14_101 AUDIO DISTRIBUTION AMPLIFIER**

ae Re si stor-1/4W 1% JKJ2 Ph!}'P.,

**PN3569**

0' TIP298 0' T1P30B

002' PNJ569

**TN40J6**

0' PNJ569 0' TIP298

**2N3904**

U' Il1 te g,.... I ':',d CircUit Sign etics NE 5534N

National LM20lAN

U' lM J 17LZ U' lMJ37LZ

**DESCRIPTION**

Ul,U2, UJ B Pin Dip Socket Amp

04,05,09,

**A605_03 _022**

was re&lt;:ornm.. n dst he USe of r epl &quot;c ement p e r-ts. made by the specified

manufacturers for continued optimum equipment p ede,.m&quot;nc&quot;.

</details>

<!-- /module data -->

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaWFaVUhScktxeE0/view?resourcekey=0-9lKySxg9CNS1uMf5-vWrbw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaWFaVUhScktxeE0&resourcekey=0-9lKySxg9CNS1uMf5-vWrbw" width="240" alt="1983 - M609 - 14-066-02-002 - ALL RESISTORS ARE.jpg"></a><br><sub>1983|16 · 14-066-02-002 - ALL RESISTORS ARE · <a href="SCHEMATICS/1983%20-%20M609%20-%2014-066-02-002%20-%20ALL%20RESISTORS%20ARE%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQmluMjZJdUYzcEE/view?resourcekey=0-UvbL-VlOzeLKl2Day6Ho0w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQmluMjZJdUYzcEE&resourcekey=0-UvbL-VlOzeLKl2Day6Ho0w" width="240" alt="1983 - M609 - 14-066-06-002 - OUTPUT SPLITTER NETWORKS COMPONENT LAYOUT.jpg"></a><br><sub>1983|16 · 14-066-06-002 - OUTPUT SPLITTER NETWORKS COMPONENT LAYOUT · <a href="SCHEMATICS/1983%20-%20M609%20-%2014-066-06-002%20-%20OUTPUT%20SPLITTER%20NETWORKS%20COMPONENT%20LAYOUT%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUjhHaFBnZEpmU1k/view?resourcekey=0-XsAmr_WHaBSNI3o_epJ6nA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUjhHaFBnZEpmU1k&resourcekey=0-XsAmr_WHaBSNI3o_epJ6nA" width="240" alt="1983 - M609 - 14-066-06-002 - OUTPUT SPLITTER NETWORKS SCHEMATIC.jpg"></a><br><sub>1983|16 · 14-066-06-002 - OUTPUT SPLITTER NETWORKS SCHEMATIC · <a href="SCHEMATICS/1983%20-%20M609%20-%2014-066-06-002%20-%20OUTPUT%20SPLITTER%20NETWORKS%20SCHEMATIC%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKazJ5QlotVXN3OHM/view?resourcekey=0-Dc946N-rWb_-UQpNNhx_pA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKazJ5QlotVXN3OHM&resourcekey=0-Dc946N-rWb_-UQpNNhx_pA" width="240" alt="1983 - M609 - 14-066-06-002.jpg"></a><br><sub>1983|16 · 14-066-06-002 · <a href="SCHEMATICS/1983%20-%20M609%20-%2014-066-06-002%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKX0lSVWxMWnVjcG8/view?resourcekey=0-8dujkH3oWo6AtfskAWWBig" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKX0lSVWxMWnVjcG8&resourcekey=0-8dujkH3oWo6AtfskAWWBig" width="240" alt="1983 - M609 - 14-066-06-003 - OUTPUT SPLITTER NETWORKS COMPONENT LAYOUT.jpg"></a><br><sub>1983|16 · 14-066-06-003 - OUTPUT SPLITTER NETWORKS COMPONENT LAYOUT · <a href="SCHEMATICS/1983%20-%20M609%20-%2014-066-06-003%20-%20OUTPUT%20SPLITTER%20NETWORKS%20COMPONENT%20LAYOUT%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcXNEc3lJSGRQc1U/view?resourcekey=0-J-lZzVQvEUkEFZqJy_ulzw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcXNEc3lJSGRQc1U&resourcekey=0-J-lZzVQvEUkEFZqJy_ulzw" width="240" alt="1983 - M609 - 14-066-06-003.jpg"></a><br><sub>1983|16 · 14-066-06-003 · <a href="SCHEMATICS/1983%20-%20M609%20-%2014-066-06-003%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMHRDQl9pZTdiTXc/view?resourcekey=0-q_D5MAcG09iLY-LRFRZIkg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMHRDQl9pZTdiTXc&resourcekey=0-q_D5MAcG09iLY-LRFRZIkg" width="240" alt="1983 - M609 - 14-066-06-004 - OUTPUT SPLITTER NETWORKS COMPONENT LAYOUT.jpg"></a><br><sub>1983|16 · 14-066-06-004 - OUTPUT SPLITTER NETWORKS COMPONENT LAYOUT · <a href="SCHEMATICS/1983%20-%20M609%20-%2014-066-06-004%20-%20OUTPUT%20SPLITTER%20NETWORKS%20COMPONENT%20LAYOUT%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSUVIa0FqZFJrYnM/view?resourcekey=0-_dMPUBBdzv_8f9Z5IMUWQA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSUVIa0FqZFJrYnM&resourcekey=0-_dMPUBBdzv_8f9Z5IMUWQA" width="240" alt="1983 - M609 - 14-066-06-004.jpg"></a><br><sub>1983|16 · 14-066-06-004 · <a href="SCHEMATICS/1983%20-%20M609%20-%2014-066-06-004%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRWstNjROM2JLbWc/view?resourcekey=0-yJ3rgPZtuafhpUR0oZlq6w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRWstNjROM2JLbWc&resourcekey=0-yJ3rgPZtuafhpUR0oZlq6w" width="240" alt="1983 - M609 - 14-101-02-001 - ALL CAPACITORS UNLESS OTHERWISE.jpg"></a><br><sub>1983|16 · 14-101-02-001 - ALL CAPACITORS UNLESS OTHERWISE · <a href="SCHEMATICS/1983%20-%20M609%20-%2014-101-02-001%20-%20ALL%20CAPACITORS%20UNLESS%20OTHERWISE%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbkxfM1lqWnZ1dU0/view?resourcekey=0-KKKCsToLNwuJ6CFT17xqFw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbkxfM1lqWnZ1dU0&resourcekey=0-KKKCsToLNwuJ6CFT17xqFw" width="240" alt="1983 - M609 - 14-101-02-001 - LAST COMPONENT DESIGNAT IONS ATTI.jpg"></a><br><sub>1983|16 · 14-101-02-001 - LAST COMPONENT DESIGNAT IONS ATTI · <a href="SCHEMATICS/1983%20-%20M609%20-%2014-101-02-001%20-%20LAST%20COMPONENT%20DESIGNAT%20IONS%20ATTI%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWU9wY1NGVFl5aHM/view?resourcekey=0-JqJt8HaAXIGZDxi9kMypLQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWU9wY1NGVFl5aHM&resourcekey=0-JqJt8HaAXIGZDxi9kMypLQ" width="240" alt="1983 - M609 - 14-101-06-001 - AUDIO AMPLIFIER ASSEMBLY COMPONENT LAYOUT.jpg"></a><br><sub>1983|16 · 14-101-06-001 - AUDIO AMPLIFIER ASSEMBLY COMPONENT LAYOUT · <a href="SCHEMATICS/1983%20-%20M609%20-%2014-101-06-001%20-%20AUDIO%20AMPLIFIER%20ASSEMBLY%20COMPONENT%20LAYOUT%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKN2xwRGVtdk9aYm8/view?resourcekey=0-wQdU3oex9hbvL0Gw4yJ7DA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKN2xwRGVtdk9aYm8&resourcekey=0-wQdU3oex9hbvL0Gw4yJ7DA" width="240" alt="1983 - M609 - 14-101-06-001.jpg"></a><br><sub>1983|16 · 14-101-06-001 · <a href="SCHEMATICS/1983%20-%20M609%20-%2014-101-06-001%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKd29sX0dWbUMyQ3M/view?resourcekey=0-4F546Hom4uUYCEzbYE1nYQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKd29sX0dWbUMyQ3M&resourcekey=0-4F546Hom4uUYCEzbYE1nYQ" width="240" alt="1983 - M609 - 609-01-001 - REMOTE SENSITIVITY AUDIO DISTRIBUTION AMPLIFIER FUNCTIONAL.jpg"></a><br><sub>1983|16 · 609-01-001 - REMOTE SENSITIVITY AUDIO DISTRIBUTION AMPLIFIER FUNCTIONAL · <a href="SCHEMATICS/1983%20-%20M609%20-%20609-01-001%20-%20REMOTE%20SENSITIVITY%20AUDIO%20DISTRIBUTION%20AMPLIFIER%20FUNCTIONAL%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKX0FyUWE2dXFjOHM/view?resourcekey=0-RMnm9JMFINteXMB0svyLcg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKX0FyUWE2dXFjOHM&resourcekey=0-RMnm9JMFINteXMB0svyLcg" width="240" alt="1983 - M609 - 609-01-001 - TECTORS OVERLOAD REF NORMAL REF.jpg"></a><br><sub>1983|16 · 609-01-001 - TECTORS OVERLOAD REF NORMAL REF · <a href="SCHEMATICS/1983%20-%20M609%20-%20609-01-001%20-%20TECTORS%20OVERLOAD%20REF%20NORMAL%20REF%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKX2ZucF9ya2tsSTQ/view?resourcekey=0--B8uk1c_6nWhEqAv5J0WIQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKX2ZucF9ya2tsSTQ&resourcekey=0--B8uk1c_6nWhEqAv5J0WIQ" width="240" alt="1983 - M609 - 609-02-001 - INDICATOR DRIVER.jpg"></a><br><sub>1983|16 · 609-02-001 - INDICATOR DRIVER · <a href="SCHEMATICS/1983%20-%20M609%20-%20609-02-001%20-%20INDICATOR%20DRIVER%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVjBLc0Y1STFpb3M/view?resourcekey=0-Nm96j1y6Pfxg0KG2i2GL2w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVjBLc0Y1STFpb3M&resourcekey=0-Nm96j1y6Pfxg0KG2i2GL2w" width="240" alt="1983 - M609 - 609-02-001 - REMOTE SENSITIVITY AUDIO DISTRIBUTION AMPLIFIER SCHEMATIC.jpg"></a><br><sub>1983|16 · 609-02-001 - REMOTE SENSITIVITY AUDIO DISTRIBUTION AMPLIFIER SCHEMATIC · <a href="SCHEMATICS/1983%20-%20M609%20-%20609-02-001%20-%20REMOTE%20SENSITIVITY%20AUDIO%20DISTRIBUTION%20AMPLIFIER%20SCHEMATIC%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbDl6bWVFMlUtMFU/view?resourcekey=0-qTt0ds8MODtm6aEXiYtj5A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbDl6bWVFMlUtMFU&resourcekey=0-qTt0ds8MODtm6aEXiYtj5A" width="240" alt="1983 - M609 - 609-02-002 - STATION TECHNICAL INSULATED GROUND GROUND BAR MULTIPLE UNIT.jpg"></a><br><sub>1983|16 · 609-02-002 - STATION TECHNICAL INSULATED GROUND GROUND BAR MULTIPLE UNIT · <a href="SCHEMATICS/1983%20-%20M609%20-%20609-02-002%20-%20STATION%20TECHNICAL%20INSULATED%20GROUND%20GROUND%20BAR%20MULTIPLE%20UNIT%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcTgxZTdTdzRadzg/view?resourcekey=0-892rVdh4TgDORPMQmF9YGA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcTgxZTdTdzRadzg&resourcekey=0-892rVdh4TgDORPMQmF9YGA" width="240" alt="1983 - M609 - 609-02-002 - TECHNICAL REMOTE SENSITIVITY GROUND AUDIO DISTRIBUTION AMPLIFIER.jpg"></a><br><sub>1983|16 · 609-02-002 - TECHNICAL REMOTE SENSITIVITY GROUND AUDIO DISTRIBUTION AMPLIFIER · <a href="SCHEMATICS/1983%20-%20M609%20-%20609-02-002%20-%20TECHNICAL%20REMOTE%20SENSITIVITY%20GROUND%20AUDIO%20DISTRIBUTION%20AMPLIFIER%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdVVZZTg4ckVwNFU/view?resourcekey=0-GM0jWMDmpVxKvxAZeItY6A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdVVZZTg4ckVwNFU&resourcekey=0-GM0jWMDmpVxKvxAZeItY6A" width="240" alt="1983 - M609 - 609-06-002 - AUDIO DISTRIBUTION AMPLIFIER PERSPECTIVE LAYOUT.jpg"></a><br><sub>1983|16 · 609-06-002 - AUDIO DISTRIBUTION AMPLIFIER PERSPECTIVE LAYOUT · <a href="SCHEMATICS/1983%20-%20M609%20-%20609-06-002%20-%20AUDIO%20DISTRIBUTION%20AMPLIFIER%20PERSPECTIVE%20LAYOUT%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKd2tONkttVlBfRWM/view?resourcekey=0-qodUd5B0w2RMNJJ0XF4b0Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKd2tONkttVlBfRWM&resourcekey=0-qodUd5B0w2RMNJJ0XF4b0Q" width="240" alt="1983 - M609 - 609-06-002 - LOC-R NORM.jpg"></a><br><sub>1983|16 · 609-06-002 - LOC-R NORM · <a href="SCHEMATICS/1983%20-%20M609%20-%20609-06-002%20-%20LOC-R%20NORM%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWFZDWEZCUDdFX3c/view?resourcekey=0-F-W-1xqNP-5g9f2t5A_wYA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWFZDWEZCUDdFX3c&resourcekey=0-F-W-1xqNP-5g9f2t5A_wYA" width="240" alt="1983 - M609 - 8-117-02-001 - INDICATOR DRIVER ASSEMBLY SCHEMATIC.jpg"></a><br><sub>1983|16 · 8-117-02-001 - INDICATOR DRIVER ASSEMBLY SCHEMATIC · <a href="SCHEMATICS/1983%20-%20M609%20-%208-117-02-001%20-%20INDICATOR%20DRIVER%20ASSEMBLY%20SCHEMATIC%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKX2NFYi11VjI2REE/view?resourcekey=0-Vi9xjx4F4A4bf773T6wWRQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKX2NFYi11VjI2REE&resourcekey=0-Vi9xjx4F4A4bf773T6wWRQ" width="240" alt="1983 - M609 - 8-117-02-001.jpg"></a><br><sub>1983|16 · 8-117-02-001 · <a href="SCHEMATICS/1983%20-%20M609%20-%208-117-02-001%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdXlqNVRqVmVQdXM/view?resourcekey=0-7_B-txNNEHIZdjiC5daBNA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdXlqNVRqVmVQdXM&resourcekey=0-7_B-txNNEHIZdjiC5daBNA" width="240" alt="1983 - M609 - 8-117-06-001 - INDICATOR DRIVER ASSEMBLY COMPONENT LAYOUT.jpg"></a><br><sub>1983|16 · 8-117-06-001 - INDICATOR DRIVER ASSEMBLY COMPONENT LAYOUT · <a href="SCHEMATICS/1983%20-%20M609%20-%208-117-06-001%20-%20INDICATOR%20DRIVER%20ASSEMBLY%20COMPONENT%20LAYOUT%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYy16QnpwbkxHUGs/view?resourcekey=0-yhelx1V9L3ifEBZ9PYHjXw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYy16QnpwbkxHUGs&resourcekey=0-yhelx1V9L3ifEBZ9PYHjXw" width="240" alt="1983 - M609 - 8-117-06-001 - NOTES TRANSISTORS.jpg"></a><br><sub>1983|16 · 8-117-06-001 - NOTES TRANSISTORS · <a href="SCHEMATICS/1983%20-%20M609%20-%208-117-06-001%20-%20NOTES%20TRANSISTORS%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

Not on Google Drive yet: `19xx - 609-02-001 - REMOTE SENSITIVITY AUDIO DISTRIBUTION AMPLIFIER SCHEMATIC - ISS 1.jpg`

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUjc3eUFuNnhHbEE/view?resourcekey=0-C5o09ZZO3G5pz4gfWMU7aw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUjc3eUFuNnhHbEE&resourcekey=0-C5o09ZZO3G5pz4gfWMU7aw" width="240" alt="1983 - M609 - P003.jpg"></a><br><sub>1983|16 · P003</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaHVoR2dBUF9FaGs/view?resourcekey=0-XY5urYqBZ4Bo-A2wX6i4qA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaHVoR2dBUF9FaGs&resourcekey=0-XY5urYqBZ4Bo-A2wX6i4qA" width="240" alt="1983 - M609 - P004 - 1-1.jpg"></a><br><sub>1983|16 · P004 - 1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNDhzd3pZVnlmTHM/view?resourcekey=0-VIZf7XBzu4GVFBK8aYWLBA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNDhzd3pZVnlmTHM&resourcekey=0-VIZf7XBzu4GVFBK8aYWLBA" width="240" alt="1983 - M609 - P005 - 1-2.jpg"></a><br><sub>1983|16 · P005 - 1-2</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQUM2VUh3MFlYVDA/view?resourcekey=0-XBOpPvgqbXBqtQxpuIm4vw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQUM2VUh3MFlYVDA&resourcekey=0-XBOpPvgqbXBqtQxpuIm4vw" width="240" alt="1983 - M609 - P006 - 2-1.jpg"></a><br><sub>1983|16 · P006 - 2-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZDlGOE1aQzg2MHc/view?resourcekey=0-0RKtFl6TAplceONiihXuxA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZDlGOE1aQzg2MHc&resourcekey=0-0RKtFl6TAplceONiihXuxA" width="240" alt="1983 - M609 - P007 - 2-2.jpg"></a><br><sub>1983|16 · P007 - 2-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOXh6TjkzWTZiTzg/view?resourcekey=0-7hrOyVYkm4ThKH4CeuhWTQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOXh6TjkzWTZiTzg&resourcekey=0-7hrOyVYkm4ThKH4CeuhWTQ" width="240" alt="1983 - M609 - P008 - 3-1.jpg"></a><br><sub>1983|16 · P008 - 3-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKT25HOFhTYzE2b1k/view?resourcekey=0-xpZyNcbiBgXu2KFg-Ris6g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKT25HOFhTYzE2b1k&resourcekey=0-xpZyNcbiBgXu2KFg-Ris6g" width="240" alt="1983 - M609 - P009 - 3-2.jpg"></a><br><sub>1983|16 · P009 - 3-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVzZRVi1sSnVNTnc/view?resourcekey=0-ncmL4nQW7a3LyityQFKvNQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVzZRVi1sSnVNTnc&resourcekey=0-ncmL4nQW7a3LyityQFKvNQ" width="240" alt="1983 - M609 - P010 - 3-3.jpg"></a><br><sub>1983|16 · P010 - 3-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOUd5WlI0ZEJhVXM/view?resourcekey=0-fLp5Bk6V9Jl9-pY4gmTd6w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOUd5WlI0ZEJhVXM&resourcekey=0-fLp5Bk6V9Jl9-pY4gmTd6w" width="240" alt="1983 - M609 - P011 - 4-1.jpg"></a><br><sub>1983|16 · P011 - 4-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTlVqYTJxY2lnTDA/view?resourcekey=0-iZQh6yr6-Q_09QDb1RoTYA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTlVqYTJxY2lnTDA&resourcekey=0-iZQh6yr6-Q_09QDb1RoTYA" width="240" alt="1983 - M609 - P012 - 4-2.jpg"></a><br><sub>1983|16 · P012 - 4-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNG5IM2hCNG5KQ00/view?resourcekey=0-Ki5sDtTD5myNMMvdTB2_Lw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNG5IM2hCNG5KQ00&resourcekey=0-Ki5sDtTD5myNMMvdTB2_Lw" width="240" alt="1983 - M609 - P018.jpg"></a><br><sub>1983|16 · P018</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKN2RmaU1wU2dtSUU/view?resourcekey=0-svB-S_BRA04v-rBWcuQEzg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKN2RmaU1wU2dtSUU&resourcekey=0-svB-S_BRA04v-rBWcuQEzg" width="240" alt="1983 - M609 - P020 - SA14-101 - 1-1.jpg"></a><br><sub>1983|16 · P020 - SA14-101 - 1-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKb1VvSDJUUTNaYnM/view?resourcekey=0-JqOGO2CqIw3_WMQclwboKQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKb1VvSDJUUTNaYnM&resourcekey=0-JqOGO2CqIw3_WMQclwboKQ" width="240" alt="1983 - M609 - P021 - SA14-101 - 1-2.jpg"></a><br><sub>1983|16 · P021 - SA14-101 - 1-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcHlESVFTVExfRms/view?resourcekey=0-MWKXAFadUQKPJtgsUNhQaw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcHlESVFTVExfRms&resourcekey=0-MWKXAFadUQKPJtgsUNhQaw" width="240" alt="1983 - M609 - P022 - SA14-101 - 2-1.jpg"></a><br><sub>1983|16 · P022 - SA14-101 - 2-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWEIyS08wdWNSdVU/view?resourcekey=0-WSfOZt7RJpYnP0XJG1HWnw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWEIyS08wdWNSdVU&resourcekey=0-WSfOZt7RJpYnP0XJG1HWnw" width="240" alt="1983 - M609 - P023 - SA14-101 - 2-2.jpg"></a><br><sub>1983|16 · P023 - SA14-101 - 2-2</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVmp3OThRSkxTZ2c/view?resourcekey=0-YkgFi5ODaeq0e7JXEm-NEQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVmp3OThRSkxTZ2c&resourcekey=0-YkgFi5ODaeq0e7JXEm-NEQ" width="240" alt="1983 - M609 - P024 - SA14-101 - 2-3.jpg"></a><br><sub>1983|16 · P024 - SA14-101 - 2-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKeUVkXzBiYmxZRWM/view?resourcekey=0-qzWZXWyh5KdpyZHXLZp_XQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKeUVkXzBiYmxZRWM&resourcekey=0-qzWZXWyh5KdpyZHXLZp_XQ" width="240" alt="1983 - M609 - P025 - SA14-101 - 2-4.jpg"></a><br><sub>1983|16 · P025 - SA14-101 - 2-4</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVEZleC13TnM3Rlk/view?resourcekey=0-3J3PyHbs-oMFx9WYYNh9HQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVEZleC13TnM3Rlk&resourcekey=0-3J3PyHbs-oMFx9WYYNh9HQ" width="240" alt="1983 - M609 - P028 - SA8-117.jpg"></a><br><sub>1983|16 · P028 - SA8-117</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNjg1UkdocVdHZzg/view?resourcekey=0-DIQz4uEvEn_T3JO4ugkJNA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNjg1UkdocVdHZzg&resourcekey=0-DIQz4uEvEn_T3JO4ugkJNA" width="240" alt="1983 - M609 - P029 - SA8-117 - 1-1.jpg"></a><br><sub>1983|16 · P029 - SA8-117 - 1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdkFtT1JWUllqVEE/view?resourcekey=0-D60xBRLWoWxp4TN51YnGog" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdkFtT1JWUllqVEE&resourcekey=0-D60xBRLWoWxp4TN51YnGog" width="240" alt="1983 - M609 - P030 - SA8-117 - 2-1.jpg"></a><br><sub>1983|16 · P030 - SA8-117 - 2-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMFJBUF95WE5qMWc/view?resourcekey=0-kxTg-Lne2L7jw18_IMoXWA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMFJBUF95WE5qMWc&resourcekey=0-kxTg-Lne2L7jw18_IMoXWA" width="240" alt="1983 - M609 - P034 - SA14-066A-B-C - 1-1.jpg"></a><br><sub>1983|16 · P034 - SA14-066A-B-C - 1-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWnZmdHpObEQ2VVU/view?resourcekey=0-g4CPZaW1-Xx33wvo6wx8yg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWnZmdHpObEQ2VVU&resourcekey=0-g4CPZaW1-Xx33wvo6wx8yg" width="240" alt="1983 - M609 - Remote sensitivity and DA (2).pdf"></a><br><sub>1983|16 · Remote sensitivity and DA (2)</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKT0ZhRHFjVUtxUUk/view?resourcekey=0-TEiQ9z-VoIsl6Y8q4rRFGw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKT0ZhRHFjVUtxUUk&resourcekey=0-TEiQ9z-VoIsl6Y8q4rRFGw" width="240" alt="1983 - M609 - Remote sensitivity and DA.pdf"></a><br><sub>1983|16 · Remote sensitivity and DA</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKckpuVVRiRjZBNDA/view?resourcekey=0-F7CHmY3E6YoLbm4YWKvQCA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKckpuVVRiRjZBNDA&resourcekey=0-F7CHmY3E6YoLbm4YWKvQCA" width="240" alt="1985 - M609 - P001 - Title Page.jpg"></a><br><sub>1985|18 · P001 - Title Page</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQ0ZuTVV3dzNraGs/view?resourcekey=0-U92eRsIyC8jnNuNEI1PYGA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQ0ZuTVV3dzNraGs&resourcekey=0-U92eRsIyC8jnNuNEI1PYGA" width="240" alt="1985 - M609 - P033 - SA14-066A-B-C.jpg"></a><br><sub>1985|18 · P033 - SA14-066A-B-C</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdjl5MDMydjdnakk/view?resourcekey=0-vmycsIKavjxdKYs2KPcXuA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdjl5MDMydjdnakk&resourcekey=0-vmycsIKavjxdKYs2KPcXuA" width="240" alt="1986 - M609 - P019 - SA14-101.jpg"></a><br><sub>1986|19 · P019 - SA14-101</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTi1QQlhyRGw2XzA/view?resourcekey=0-urNxOrgjwQFRDjpVU-OGPg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTi1QQlhyRGw2XzA&resourcekey=0-urNxOrgjwQFRDjpVU-OGPg" width="240" alt="19xx - M609 - AD - WBSPS - AD - for the engineer who has everything.jpg"></a><br><sub>19xx - M609 - AD - WBSPS - AD - for the engineer who has everything</sub></td></tr>
</table>

Shared privately on Google Drive (opens after sign-in): [19xx - M609 - DOC - WBSPS - AD - for the engineer who has everything](https://drive.google.com/file/d/0B0yR0b5T78SKbGlUcFh6b0hqcVE/view?resourcekey=0-ciA_tsM-sD9I8DGfjlKSwA)

Not on Google Drive yet: `M609 - P002.jpg`, `M609 - P013 - 5-1.jpg`

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1983 - M609 - 14-066-02-002 - ALL RESISTORS ARE.kicad_sch](KICAD/1983%20-%20M609%20-%2014-066-02-002%20-%20ALL%20RESISTORS%20ARE.kicad_sch)
- [1983 - M609 - 14-101-02-001 - ALL CAPACITORS UNLESS OTHERWISE.kicad_sch](KICAD/1983%20-%20M609%20-%2014-101-02-001%20-%20ALL%20CAPACITORS%20UNLESS%20OTHERWISE.kicad_sch)
- [1983 - M609 - 14-101-02-001 - LAST COMPONENT DESIGNAT IONS ATTI.kicad_sch](KICAD/1983%20-%20M609%20-%2014-101-02-001%20-%20LAST%20COMPONENT%20DESIGNAT%20IONS%20ATTI.kicad_sch)
- [1983 - M609 - 609-01-001 - REMOTE SENSITIVITY AUDIO DISTRIBUTION AMPLIFIER FUNCTIONAL.kicad_sch](KICAD/1983%20-%20M609%20-%20609-01-001%20-%20REMOTE%20SENSITIVITY%20AUDIO%20DISTRIBUTION%20AMPLIFIER%20FUNCTIONAL.kicad_sch)
- [1983 - M609 - 609-01-001 - TECTORS OVERLOAD REF NORMAL REF.kicad_sch](KICAD/1983%20-%20M609%20-%20609-01-001%20-%20TECTORS%20OVERLOAD%20REF%20NORMAL%20REF.kicad_sch)
- [1983 - M609 - 609-02-001 - INDICATOR DRIVER.kicad_sch](KICAD/1983%20-%20M609%20-%20609-02-001%20-%20INDICATOR%20DRIVER.kicad_sch)
- [1983 - M609 - 609-02-001 - REMOTE SENSITIVITY AUDIO DISTRIBUTION AMPLIFIER SCHEMATIC.kicad_sch](KICAD/1983%20-%20M609%20-%20609-02-001%20-%20REMOTE%20SENSITIVITY%20AUDIO%20DISTRIBUTION%20AMPLIFIER%20SCHEMATIC.kicad_sch)
- [1983 - M609 - 609-02-002 - STATION TECHNICAL INSULATED GROUND GROUND BAR MULTIPLE UNIT.kicad_sch](KICAD/1983%20-%20M609%20-%20609-02-002%20-%20STATION%20TECHNICAL%20INSULATED%20GROUND%20GROUND%20BAR%20MULTIPLE%20UNIT.kicad_sch)
- [1983 - M609 - 609-02-002 - TECHNICAL REMOTE SENSITIVITY GROUND AUDIO DISTRIBUTION AMPLIFIER.kicad_sch](KICAD/1983%20-%20M609%20-%20609-02-002%20-%20TECHNICAL%20REMOTE%20SENSITIVITY%20GROUND%20AUDIO%20DISTRIBUTION%20AMPLIFIER.kicad_sch)
- [1983 - M609 - 8-117-02-001 - INDICATOR DRIVER ASSEMBLY SCHEMATIC.kicad_sch](KICAD/1983%20-%20M609%20-%208-117-02-001%20-%20INDICATOR%20DRIVER%20ASSEMBLY%20SCHEMATIC.kicad_sch)
- [1983 - M609 - 8-117-02-001.kicad_sch](KICAD/1983%20-%20M609%20-%208-117-02-001.kicad_sch)
- [1983 - M609 - Remote sensitivity and DA (2) p15.kicad_sch](KICAD/1983%20-%20M609%20-%20Remote%20sensitivity%20and%20DA%20(2)%20p15.kicad_sch)
- [1983 - M609 - Remote sensitivity and DA (2) p17.kicad_sch](KICAD/1983%20-%20M609%20-%20Remote%20sensitivity%20and%20DA%20(2)%20p17.kicad_sch)
- [1983 - M609 - Remote sensitivity and DA (2) p31.kicad_sch](KICAD/1983%20-%20M609%20-%20Remote%20sensitivity%20and%20DA%20(2)%20p31.kicad_sch)
- [1983 - M609 - Remote sensitivity and DA (2) p38.kicad_sch](KICAD/1983%20-%20M609%20-%20Remote%20sensitivity%20and%20DA%20(2)%20p38.kicad_sch)
- [1983 - M609 - Remote sensitivity and DA p15.kicad_sch](KICAD/1983%20-%20M609%20-%20Remote%20sensitivity%20and%20DA%20p15.kicad_sch)
- [1983 - M609 - Remote sensitivity and DA p17.kicad_sch](KICAD/1983%20-%20M609%20-%20Remote%20sensitivity%20and%20DA%20p17.kicad_sch)
- [1983 - M609 - Remote sensitivity and DA p21.kicad_sch](KICAD/1983%20-%20M609%20-%20Remote%20sensitivity%20and%20DA%20p21.kicad_sch)
- [1983 - M609 - Remote sensitivity and DA p31.kicad_sch](KICAD/1983%20-%20M609%20-%20Remote%20sensitivity%20and%20DA%20p31.kicad_sch)
- [1983 - M609 - Remote sensitivity and DA p38.kicad_sch](KICAD/1983%20-%20M609%20-%20Remote%20sensitivity%20and%20DA%20p38.kicad_sch)
- [19xx - 609-02-001 - REMOTE SENSITIVITY AUDIO DISTRIBUTION AMPLIFIER SCHEMATIC - ISS 1.kicad_sch](KICAD/19xx%20-%20609-02-001%20-%20REMOTE%20SENSITIVITY%20AUDIO%20DISTRIBUTION%20AMPLIFIER%20SCHEMATIC%20-%20ISS%201.kicad_sch)
- [M609.kicad_sym](KICAD/M609.kicad_sym)
- [index.html](KICAD/index.html)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
