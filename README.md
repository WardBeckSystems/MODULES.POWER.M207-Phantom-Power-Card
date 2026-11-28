# M207 Phantom Power Card · Power

Ward-Beck Systems M207, 1981|14. Wiki page: [M207 on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M207.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 23 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 10 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 5 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 54 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 1 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 1 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 8 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 17 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

**On the WBSps forum (2006|39 - 2014|47):** [3 topics](FORUM.md): what owners and technicians said about it.

## Circuit description

From [1982 - M207 - Phantom Power Card (2).pdf](MANUALS/1982%20-%20M207%20-%20Phantom%20Power%20Card%20(2).pdf) pages 2-7 (read by OCR; check against the pages). As data: [`CircuitDescription.json`](CircuitDescription.json).

<details><summary>Read it</summary>

**M20 7 PHANTOM POWER SUPPLY**

The M207 Phantom Power Supply is 8 24 volt t o 48 vol l de to do; o;or'!ver ler. T h i..; s achieved with a push -pull r&quot;la&quot;al i&quot;&quot; o sci ll a to.and a YOl lag.. dou bl.... c ir-cu l l.

01 through 04 form I h.. push _pu ll r,,18xa tl0l&quot;l o sc ill a to.wh kh operates ala nominal r rrq u e n o;y o r 100 k H:z:. R4 i:l; adjusled tog lye a symmet ri o;al out pul &quot; t t h.. collectors of 01 and 0 3. The peak 10 peak AC YOl18ge on Ihe couec ecr-s o f 01 and 0 3 is in Ihe order o f 20 vol l S.

The vol lag e doubling a e tl o n Is a c.h iev..,j by pre-eharglng C8 10 Ihe 24 Yol l sup ply volt 390 throug l, CR 1, CR2 &quot;nd C R3.. The r&quot;eti fled 20 volt p pAC volt &quot;9&quot;;'1 th&quot;&quot; eoe ee via C6, CR2 &amp; CR3. The net effo&lt;: t Is to o;ha r g e C8 to approx ima tel y!&gt;!&gt; v o ll:l;.

O!&gt; is a series p a:l; s,-.,gu ill tor wl lh Its d o; output yollege set by:z:ener diode CR4. T h&quot; 48 vall d o; output yolt 8g e is addition ally filter e d by C l 0 CFt!&gt; &amp; C li.

**PARTS LIST**

&quot;'201 24 V to 48V CONVERTER

**PART DESCRIPTION**

&quot;'G MF e PART NUMBER

ci Capaci1 0r Ph ilip&quot;, 100 uF / 40 V

2200 p F / 6 30 V

1 u F / 2!!AJ V.

C'.&quot;.1 u F/~ V. 344A81 101

. 3&quot;&quot;A8.1001(

z.2: uF / 63 V

**426ETH22**

CO&gt;.. 2.2 uf /6 3 II

**... J.448 HA 2M2**

cu.. 21 pF

2222 -638 -58219

Diode

Motorola lN4003

CR'.&quot;, Zene r- 'R IN47 57 &quot; CR&gt; &quot; Motorola lNIoOO3

F utle 0.25'&quot; F8 B u ~'S AGe 1/4

Q'. National M o loro l a

**2N2 101**

Q' &quot; NllUofla' 2N4037 Q. &quot; M O lon&gt; l.. 2N2102

R' Resistor 1/2W 51 Phil ip&quot;

R' T,.l m POI Pi her PTlOh 12.5 } SK R5 R e ~I Slor 1/4W S$ '&quot; Phil ip&quot;

R9 Res is tor&quot; 1!2W SI.., Philips

**PART DESCRIPTION**

&quot;'0 &quot;'0,,,.n NUMBER

R.... i.. lor-1!2W Resistor 1/4W

Fuse Holde.. s

Philips

L 'tlelf use toaoee T.. ~ n s l slor Heat Sinks B ir tch&quot;.. lAL116

Fer-eit e Bead.. Pnll1 ps VK21 029/3a

was r..com mend t&quot;&quot; use o f.. ~ I&quot;cem..n t pll rt s made by Lh&quot; specified

manufactu........ for continued optimum eQuip &quot;.. &quot;,t p&quot;..f o r man ce.

**P I CONNECTOR LAYOUT**

104201 24V tu 48V CONVERTER

,.21oV SUPPLY VOLTAGE

a ·48 PHANTOM POWER

3 Ne

s NO

**9 COMMON**

io COMMON

**NOTES:**

I. &quot;LL R.E.S1STOl&lt;.S. M:..E ' / 4 W 5 &quot; A&quot;-JO &quot;L..L C&quot;''''ACIT o~S \t..J..A.&lt;l...f L)\..1LES,S SP EC.IF IE. D OTHE.RW ISe:..

**2. L.....S.T C OMP'O&quot;'-JE..\..1T**

DE:' S.Ic=.k.1&quot;&quot;'TI~~ ~ C I~.C ~ ~.

Ft,QS.R \'2 3. USE PcB 14 · 0 32.

4. \.E D R.,-r E BE&quot;,-=::'

N O.- E &quot;&quot;4.

...., '11.w

Q' \ 1~400&quot;3 C'G. 2&quot;'40 3 '7 ~ RG. -01 33 K CJa. 2 c.2.3

**I N 4 0 0::3 1~400~**

1':4-5 K. 2 +4-8 v

1/ -25 0.., c~ loa~/40..

. 1/2 S 0 v

**C.:'\...5**

21p CIS 2 1 p

...80 ell / 51&lt;. 0 4-2'2/ '''' e &gt;1 210 2 CIO Z2/t.3oJ

**COMMOIJ**

~-----lL----------l ----l_&quot;::::::&quot;'-=&quot;:::&quot;&quot;&quot;&quot;';7&quot;&lt;:::&quot;':::&quot;,_ = ----l --'- ---'-_---'-_ - - ' L_ _--'- ~ 10 C.O.......... O I.J

NOTE &quot;&quot;4.

ENG. G;e 8 24v to 48v CONVERTER

**APP I**

SCALE ISSUE B · 207-02 -001 2

100/40...

- R t 47 '/Z w FI

II t... I,. ~I

&quot;v v &quot; &quot;

~ v V I 2.'.1'403&quot;'7 tl

Jf•. 2,,)..,1&lt;4037&quot;'&quot; 2W '2)O~

~' ii'&quot; ~I ~I if&quot; a i !

**.1 L**

~ Ii. ~ ~ til &quot;u •it ~I'&quot;Oi

**III**

2.... 2 10'2.. &quot;'~ ~I.... ~I ~Ion ~I ~r 2.,.2102 &quot;'~ •

III &gt; J,

·u til &quot;I:1;'! '&quot;

a: III Q tilt: U

tb 0 I

u al

5 1&lt;.,

**ENG. 6£13**

24'1 to 48'1 CONVERlER

COMPONENT l A,YOUT

**SCALE ISSUE**

B 2 0 7 -0 6 -0 o 1 2

</details>

<!-- /module data -->

## Mechanical

_Mechanical drawings: front panels, cover plates, metalwork and hardware (-03- drawings), AutoCAD files, each with its `(EXTRACTED).svg` vectors; `<module> - front panel.svg` is the front panel as vectors._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSWQ4LWo2N01MRW8/view?resourcekey=0-HONMjFQUNiYS3FNM5KZfNw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSWQ4LWo2N01MRW8&resourcekey=0-HONMjFQUNiYS3FNM5KZfNw" width="240" alt="19xx - M207 - DOC - 1202-04-007 - OSCILLATOR CUE-SOLO RE-ENTRY AND AUX LEVEL SCHEMATIC.jpg"></a><br><sub>19xx - M207 - DOC - 1202-04-007 - OSCILLATOR CUE-SOLO RE-ENTRY AND AUX LEVEL SCHEMATIC · <a href="MECHANICAL/19xx%20-%20M207%20-%20DOC%20-%201202-04-007%20-%20OSCILLATOR%20CUE-SOLO%20RE-ENTRY%20AND%20AUX%20LEVEL%20SCHEMATIC%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

Not on Google Drive yet: `1981 - 207-03-001 - COVER PLATE - DRN GEB - ENG GEB - ISS 1.jpg`

## 3-D model

[`MECHANICAL/M207.stl`](MECHANICAL/M207.stl) (GitHub turns it in 3-D) · [view, change and generate it on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/2026/stl.html?m=M207)

- **Size:** 41 × 178 mm panel, 165 mm deep, 3.2 mm plate (assumed: 1.6" x 7" x 6.5", the common module)
- **From the drawing:** 0 holes and cut-outs, 0 knobs (front panel: `MECHANICAL/M207 - front panel.svg`)
- no drawing of the front panel: the panel is blank
- Made by `tools/module_models.py` (→ `MECHANICAL/M207.model.json`) and `tools/stl/make_stl.mjs` in [WBSps.ca](https://github.com/WardBeckSystems/WBSps.ca); the site makes the same STL from the same JSON.

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYnQwLV9iQ1dBUXM/view?resourcekey=0-YDoYbRlseGooGzP-bENGVg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYnQwLV9iQ1dBUXM&resourcekey=0-YDoYbRlseGooGzP-bENGVg" width="240" alt="1982 - M207 - 07-06-001 - CONVERTER COMPONENT LAYOUT.jpg"></a><br><sub>1982|15 · 07-06-001 - CONVERTER COMPONENT LAYOUT · <a href="SCHEMATICS/1982%20-%20M207%20-%2007-06-001%20-%20CONVERTER%20COMPONENT%20LAYOUT%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQVV5dmFuelFnVEk/view?resourcekey=0-THUpqiJeQc-SHnp3UY_IeA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQVV5dmFuelFnVEk&resourcekey=0-THUpqiJeQc-SHnp3UY_IeA" width="240" alt="19xx - M207 - DOC - 1202-02-011 - REDRAWN FOR.jpg"></a><br><sub>19xx - M207 - DOC - 1202-02-011 - REDRAWN FOR · <a href="SCHEMATICS/19xx%20-%20M207%20-%20DOC%20-%201202-02-011%20-%20REDRAWN%20FOR%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

Not on Google Drive yet: `19xx - 207-02-001 - 24v TO 48v CONVERTER SCHEMATIC - DRN GEB - ENG GEB - ISS 2.jpg`, `M207 - P07 - Component Layout.jpg`

## Pinouts

_Pinouts: the RTO-144 edge connector (connection sheets, connector layouts and rear views, strapping), and the pinout / connections drawings made from them. The module root `RTO.json` lists every contact._

Not on Google Drive yet: `M207 - RTO-144 Connections.pdf`

## RTO-144 pinout

RTO-144 edge connector. Every contact, with where it was read: [`RTO.json`](RTO.json).

| Pin | Signal | Kind | Pair | Confidence |
|---|---|---|---|---|

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKV2M2aWp6TUdRNVU/view?resourcekey=0-H1xBl-fCFf8GDILQ2PASig" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKV2M2aWp6TUdRNVU&resourcekey=0-H1xBl-fCFf8GDILQ2PASig" width="240" alt="1982 - M207 - P01 - TOC.jpg"></a><br><sub>1982|15 · P01 - TOC</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNXRGdFRkdVVkc2c/view?resourcekey=0-SI2HUAlO565ZGi-10hvxoQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNXRGdFRkdVVkc2c&resourcekey=0-SI2HUAlO565ZGi-10hvxoQ" width="240" alt="1982 - M207 - P02 - 1-1.jpg"></a><br><sub>1982|15 · P02 - 1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRzVJWUZRUVdyUEk/view?resourcekey=0-0OUvNw9rgaMWb72EsLAnNw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRzVJWUZRUVdyUEk&resourcekey=0-0OUvNw9rgaMWb72EsLAnNw" width="240" alt="1982 - M207 - P03 - 2-1.jpg"></a><br><sub>1982|15 · P03 - 2-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcE1ENUhSQ3gwTU0/view?resourcekey=0-7tGN3peBkGaIwje5HVieCQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcE1ENUhSQ3gwTU0&resourcekey=0-7tGN3peBkGaIwje5HVieCQ" width="240" alt="1982 - M207 - P04 - 2-2.jpg"></a><br><sub>1982|15 · P04 - 2-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRVkxaFh3WDhjR28/view?resourcekey=0-fFbr4WUfN5EYvIG9dsTuPQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRVkxaFh3WDhjR28&resourcekey=0-fFbr4WUfN5EYvIG9dsTuPQ" width="240" alt="1982 - M207 - P05 - 3-1.jpg"></a><br><sub>1982|15 · P05 - 3-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKREFIckZCOUVLQlE/view?resourcekey=0-YLmePHTzjiFrx4RxhEw1Hw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKREFIckZCOUVLQlE&resourcekey=0-YLmePHTzjiFrx4RxhEw1Hw" width="240" alt="1982 - M207 - Phantom Power Card (2).pdf"></a><br><sub>1982|15 · Phantom Power Card (2)</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVHF3VHFUcXl2M0E/view?resourcekey=0-7B1GwoKMuzYkiJK-X30lRQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVHF3VHFUcXl2M0E&resourcekey=0-7B1GwoKMuzYkiJK-X30lRQ" width="240" alt="1982 - M207 - Phantom Power Card.pdf"></a><br><sub>1982|15 · Phantom Power Card</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMi1rcjZwbXMyOUE/view?resourcekey=0-V82wewC7Mz-xGA5v3tieXg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMi1rcjZwbXMyOUE&resourcekey=0-V82wewC7Mz-xGA5v3tieXg" width="240" alt="19xx - M207 - DOC - L1202A - P12 - 1-9.jpg"></a><br><sub>19xx - M207 - DOC - L1202A - P12 - 1-9</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdFFQX2d0d0tvRDA/view?resourcekey=0-fZBJYJyKwM5zYntvBSm4dQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdFFQX2d0d0tvRDA&resourcekey=0-fZBJYJyKwM5zYntvBSm4dQ" width="240" alt="19xx - M207 - DOC - L1202A - P13 - 11-1.jpg"></a><br><sub>19xx - M207 - DOC - L1202A - P13 - 11-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWEh5NUxNdUMtdDQ/view?resourcekey=0-aN8Pm3MtXS5DftM3C-LdBQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWEh5NUxNdUMtdDQ&resourcekey=0-aN8Pm3MtXS5DftM3C-LdBQ" width="240" alt="19xx - M207 - DOC - L1202A - P17 - 11-5.jpg"></a><br><sub>19xx - M207 - DOC - L1202A - P17 - 11-5</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRGVVUmx1MlN1ek0/view?resourcekey=0-vJM2sfewluMBwXhSfCFOAg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRGVVUmx1MlN1ek0&resourcekey=0-vJM2sfewluMBwXhSfCFOAg" width="240" alt="19xx - M207 - DOC - L1202A - P25 - IV-1.jpg"></a><br><sub>19xx - M207 - DOC - L1202A - P25 - IV-1</sub></td></tr>
</table>

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1982 - M207 - 207-02-001 - COMMOU NOTE.kicad_sch](KICAD/1982%20-%20M207%20-%20207-02-001%20-%20COMMOU%20NOTE.kicad_sch)
- [1982 - M207 - Phantom Power Card (2) p6.kicad_sch](KICAD/1982%20-%20M207%20-%20Phantom%20Power%20Card%20(2)%20p6.kicad_sch)
- [1982 - M207 - Phantom Power Card p6.kicad_sch](KICAD/1982%20-%20M207%20-%20Phantom%20Power%20Card%20p6.kicad_sch)
- [19xx - 207-02-001 - 24v TO 48v CONVERTER SCHEMATIC - DRN GEB - ENG GEB - ISS 2.kicad_sch](KICAD/19xx%20-%20207-02-001%20-%2024v%20TO%2048v%20CONVERTER%20SCHEMATIC%20-%20DRN%20GEB%20-%20ENG%20GEB%20-%20ISS%202.kicad_sch)
- [19xx - M207 - DOC - 1202-02-011 - REDRAWN FOR.kicad_sch](KICAD/19xx%20-%20M207%20-%20DOC%20-%201202-02-011%20-%20REDRAWN%20FOR.kicad_sch)
- [M207 - P06 - Schematic.kicad_sch](KICAD/M207%20-%20P06%20-%20Schematic.kicad_sch)
- [M207.kicad_sym](KICAD/M207.kicad_sym)
- [index.html](KICAD/index.html)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
