## Polyacrylamide bead formation

For each sample:

a) Combine the following reagents in a 2 ml round-bottom safe-lock microtube and vortex gently: 
- 115 µl/120 µl sample material 
- 80 µl 30% BIS/acrylamide (storage temp: 4 °C) 
- 25 µl 10% APS (storage temp: -20 °C)

Samples:
- 5: rhodomonas about 100 000 cells/ml (25µl + 90 µl PCR H20)
- 6: cell-free medium + waste water (25µl + 90µl)
- 7: 100 000 cells/ml + waste water (25µl + 90µl)

Waste water variant samples (to test if the amount of bacteria could be lower), prepared separately: 
- Non-filtered: not been strained through 100 µm sieve (120 µl)
- Variant 30: contains fraction obtained from the top of 30 µm mesh (120 µl)
- Variant 10 contains fraction obtained from the top of 10 µm mesh (120 µl)

b) Shake & mix STT (Span/Tween/Triton) emulsion oil thoroughly before use!  
Add 600 µl STT emulsion oil. (storage temp: RT) 
Vortex at max speed (3 000 rpm) for 30 s.

c) Add 25 µl TEMED.  (storage temp: RT) 
Vortex at max speed (3 000 rpm) for 30 s.

d) Allow tube to sit on the benchtop for polymerization to occur for 1h 30 min

e) Removal of oil:
- Equal volumes of water and diethyl ether (at least 50 % water!) mixed, shaken and opened occasionally to prevent pressure from building up.
- Add 800 µl of diethyl ether to the tube, then immediately close, invert and flick the tube to mix the emulsion with the ether. A visible precipitate ought to form. Draw off the ether/oil mixture around the precipitate and discard.
- Add 1 ml of autoclaved H2O to the top of the tube and mix by flicking and inverting. Centrifuge for 30 s at 12 000rcf. Three layers should form: a bottom layer of beads, a middle cloudy layer of oil/water, and a top milky layer of oil. Draw off the top oil layer as much as possible and discard.
- Repeat the H2O wash steps until there is no remaining oil at the top of the tube and the liquid phase is transparent.

f) Aspirating (not performed for the variant samples:
- Resuspend the beads in 300 µl of water.
- Fill a 50 ml tube with 0,1 % Triton X-100 solution, placing a 20 µm filter on top so the level of liquid is just above the mesh. Add the bead suspension. 
- Place the tube in a shaker (low speed) and let the smallest beads pass through. 

## Fusion PCR
Prepare the PCR master mix (done separately to the variant samples, hence the volumes may vary):
| Reagent | 1X | 5X |
| :---: | :---: | :---: |
| 5xGC buffer | 20 µl | 100 µl
| 50 mM MgCl2 | 2 µl | 10 µl |
| dNTP mix (10 mM each) | 2.5 µl | 12.5 µl |
| 10 µM R2 and F1 primers (3, each) | 10 µl | 50 µl |
| 10 µM R1-F2’ and F2-R1' primers (4, each)  | 1 µl | 5 µl |
| 1e6 cp/µl barcode | 1 µl | 5 µl |
| Phusion DNA polymerase (2 U/µl) | 8 µl | 40 µl |

a)  Combine 33 µl of sample (bead suspension) and 67 µl of master mix. Add 100 µl of fluorinated oil with surfactant.

b)  Emulsify by vortexing briefly and pipetting up and down until the phases have completely mixed.

c)  Aliquot to two PCR tubes and cover with 50 µl of mineral oil. 

Running PCR:
| Step | Temperature (°C) | Time | Number of cycles |
| :---: | :---: | :---: | :---: |
| Beginning temperature | 80 | 10 s | 1 |
| Initial denaturation | 94 | 30 s | 1 |
| Denaturation | 94 | 5 s | 32 |
| Annealing | 55 | 30 s | 
| Extension | 72 | 30 s | 
| Final extension | 72 | 5 min | 1
| Storing temperature | 4 | Inf | 1

d) Immediately after the fusion reaction, pool the emulsion aliquots for each sample into a new 2 ml round-bottom safe-lock tube.

e) Separate the phases (top: mineral oil, middle: emulsion, bottom: surplus fluorinated oil) by spinning and discard the mineral oil. Some fluorinated oil may also be removed, if applicable.

f) Add 50 µl of PFO, mix and spin. The upper aqueous phase is collected / bottom phase discarded

g) Cleanup with Monarch® PCR & DNA Cleanup Kit (5 μg).

## 16S and 18S blocking

Prepare the PCR master mix (done separately to the variant samples, hence the volumes may vary):
| Reagent | 1X | 5X |
| :---: | :---: | :---: |
| PCR H2O | 23.5 µl | 117.5 µl |
| 5xGC buffer | 10 µl | 50 µl |
| dNTP mix (10 mM each) | 1 µl | 5 µl |
| 32 µM BlockF-16S and BlockR-16S primers | 5 µl | 25 µl |
| 32 µM BlockF-18S and BlockR-18S primers | 5 µl | 25 µl |
| Phusion DNA polymerase (2 U/µl) | 0.5 µl | 2.5 µl |

Combine 45 µl mastermix and 5 µl template (purified fusion PCR product)

Running PCR:
| Step | Temperature (°C) | Time | Number of cycles |
| :---: | :---: | :---: | :---: |
| Beginning temperature | 98 | 30 s | 1 |
| Denaturation | 98 | 10 s | 30 |
| Annealing | 55 | 30 s | 
| Extension | 72 | 30 s | 
| Final extension | 72 | 5 min | 1
| Storing temperature | 4 | Inf | 1

Cleanup with Monarch® PCR & DNA Cleanup Kit (5 μg). To make the template DNA concentration as high as possible with good yield, elution volume was 10 µl.

## Nested PCR 

Prepare 2 PCR master mixes (with either 16S and 18S nested primers), (done separately to the variant samples, hence the volumes may vary):
| Reagent | 1X | 5X |
| :---: | :---: | :---: |
| PCR H2O | 14.75 µl | 74 µl |
| 5xGC buffer | 5 µl | 25 µl |
| dNTP mix (10 mM each) | 0.5 µl | 2.5 µl |
| Primer mix * either 16S or 18S | 2.5 µl | 12.5 µl |
| Phusion DNA polymerase (2 U/µl) | 0.5 µl | 2.5 µl |

(*) Primer mixes: 
- 16S: 16S nested primers (3 primers), i5 forward, BlockF, BlockR; (3µM each) 
- 18S: 18S nested primers (3 primers), i5 forward, BlockF, BlockR; (3µM each)

Combine 23 µl mastermix + 2 µl of sample (from blocking PCR) 

Running PCR:
| Step | Temperature (°C) | Time | Number of cycles |
| :---: | :---: | :---: | :---: |
| Beginning temperature | 98 | 30 s | 1 |
| Denaturation | 98 | 10 s | 24 |
| Annealing | 55 | 30 s | 
| Extension | 72 | 30 s | 
| Final extension | 72 | 5 min | 1
| Storing temperature | 4 | Inf | 1

Replicate samples pooled and cleanup with Monarch® PCR & DNA Cleanup Kit (5 μg).

## Indexing

16S and 18S barcoding experiments were further prepared for sequencing using indexing primers.

Primers used:

| | N701 | N702 | N703 |
| :---: | :---: | :---: | :---: |
| **S507** |Sample 5, 16S |Sample 6, 16S |Sample 7, 16S |
| **S508** |Sample 5, 18S |Sample 6, 18S |Sample 7, 18S |

| | N705 | N706 | N707 |
| :---: | :---: | :---: | :---: |
| **S510** |Variant non-filtered, 16S |Variant 30, 16S |Variant 10, 16S |
| **S511** |Variant non-filtered, 18S |Variant 30, 18S |Variant 10, 18S |

 Prepare following PCR mix (4× per sample + 1 extra volume; performed separately to the variant samples):

| Reagent | 1X | 25X |
| :---: | :---: | :---: |
| H2O | 12,4 µl | 310 µl
| 5x HF buffer | 4 µl | 100 µl |
| dNTP mix (10 mM each) | 0,4 µl | 10 µl |
| Phusion DNA polymerase (2 U/µl) | 0,2 µl | 5 µl |
| i5 primer (10 µM) | 1 µl | 
| i7 primer (10 µM) | 1 µl | 
Reaction | 19 µl | 95 µl |

Pipette 17 µl mastermix, 1 µl of appropriate primers each, and 1 µl template (purified nested PCR product) to 4 PCR tubes per sample

b) Run the following cycling program:

| Step | Temperature (°C) | Time | Number of cycles |
| :---: | :---: | :---: | :---: |
| Beginning temperature | 98 | 30 s | 1 |
| Denaturation | 98 | 10 s | 12 |
| Annealing | 55 | 20 s | 
| Extension | 72 | 20 s | 
| Final extension | 72 | 5 min | 1
| Storing temperature | 4 | Inf | 1

Pool replicate samples, purify with Monarch® PCR & DNA Cleanup Kit (5 μg).

DNA concentration was measured by fluorometry (Qubit) and quality evaluated by electrophoresis.

<td valign="top"><img src="../lab_figures/gel1.png" width=400></td>


1. 1 kB MW marker
2. 16S sample 5 (rhodo only)
3. 16S sample 6 (ww only)
4. 16S sample 7 (rhodo + ww)
5. 18S sample 5
6. 18S sample 6
7. 18S sample 7

Bands look quite good. Something seems to be amplified in the 100 - 200 bp range, but it mainly shows in the lane 5.

The concentration in the same order as above, in ng/µl:

2. 3,8
3. 38,0
4. 14,4
5. 15,6
6. 22,2
7. 22,4

## Sample pooling and sequencing

Each of the 12 samples (6 samples, 16S and 18S versions of each -> 12 samples) was added in 0,2 ng/µl final concentration, which would add up to 2,4 ng/µl total nucleic acid concentration

The concentration was measured by Qubit, showing 2,1 ng/µl, which corresponds to 9,708 nM.

Library was then diluted with Qiagen elution buffer to 4 nM.

Samples were denatured and inserted to cassette, and sequenced in the Turku Bioscience facilities.

