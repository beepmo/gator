# The gator project
Process of a physics publication, from data to tickets.  

Abstract shall go here.

  **@Quantum Matter Institute, University of British Columbia**
  
  **Credit: our amazing team of physicists & chemical engineers : )**

# Original markdown renderer
https://hackmd.io/qxGc4w1NTW-AmqHoWDLpaQ

# Gallery
https://hackmd.io/lQTeOCpqQRuWHCunBt5zLA


# Overview

### Active tickets

- [LiTaO3](#LiTaO3) gating with deposited gold
- Li-H gating on [La2/3TiO3](#La2/3TiO3)


**Standby:**

- [XRD](#XRD): Bruce did this for us... sigh, we'll wait to hear about it.

### Completed tickets:  victories!
- [PCB assembly](#PCB-assembly)
- [Measuring reaction-less ionic conductivity](#Measuring-reaction-less-ionic-conductivity)
- [Detecting water electrolysis in ionic liquid](#Detecting-water-electrolysis-in-ionic-liquid)
- [Gold deposition](#Gold-deposition)
    - masks work; repeated as needed in future
- [Nature of HMIM TFSI](#Nature-of-HMIM-TFSI)
- [LiTaO3 gating](#LiTaO3-gating)
    - EIS fit for gated LiTaO3!
- H gating on control sample
- [Electrochemical Impedance Spectroscopy](#Electrochemical-Impedance-Spectroscopy)
    - stoichiometric polarization much understanding sheeesh
- DC stoichiometric polarization measurement!
- [LiTaO3 Paper](#LiTaO3-Paper) literature search
- DC measurement on all remaining La2/3 samples: report electrical conductivity.

### Paused tickets
- [Lithium electrode fabrication](#Lithium-electrode-fabrication)
- H gating on La2/3TiO3
- [Things for fresh films](#Things-for-fresh-films) 


# Theory
Our analysis of DC and AC measurements are built upon work by Joachim Maier & co.
- [Physical chemistry of ionic materials](https://tech.chemistrydocs.com/Books/Physical/Physical-Chemistry-of-Ionic-Materials-by-Joachim-Maier.pdf)
    - p405. Chemical potentials add in an equilibrium (Eq 7.8)
    - p406. Open circuit voltage: Nernst (Eq. 7.10)
- [Generalised equivalent circuits for mass and charge transport: chemical capacitance and its implications](https://pubs.rsc.org/en/content/articlelanding/2001/cp/b100180i)
- [A powerful electrical network model for the impedance of mixed conductors](https://www.sciencedirect.com/science/article/abs/pii/S0013468699001280)

# LiTaO3 Paper

## Literature search

### Synopses
On [our external note](https://hackmd.io/TvcIJVF2SZeTjOIqNTlJpA).

### Required constants:
- dielectric constants
	- $\ce{ LiTaO_{3} }$
	- [The dielectric constant of lithium tantalate (LiTaO3) is approximately 43 at room temperature](https://pubs.aip.org/aip/jap/article-abstract/61/12/5386/172942/The-electrical-properties-of-ferroelectric-LiTaO3)
	- lanthanum titanates (everything under formula $\ce{ Li_{y}La_{x}TiO_{3-\delta} }$)
	- [ Room temperature A-site doped LaTiO3-d perovskite : dielectric constant of 1500 at 100 Hz. B-site doped LaTiO3-d perovskite : a dielectric constant of 900 at 100 Hz.](https://link.springer.com/article/10.1007/s10971-014-3486-2)
- temperature-dependent diffusion coefficients $D$


	- $\ce{ LiTaO_{3} }$ 
	- [550°C: $D$ = 57 nm²/s.
800°C: $D$ = 393 nm²/s ](https://www.sciencedirect.com/science/article/pii/S1878029616300081)
	- lanthanum titanates (everything under formula $\ce{ Li_{y}La_{x}TiO_{3-\delta} }$)
    - [Diffusion coefficient for LaTiO3](https://link.springer.com/article/10.1007/s11581-014-1216-y)
    ![截屏2024-07-15 下午4.26.43](https://hackmd.io/_uploads/r1BwgVmuC.png)
    - [Diffusion coefficient for perovskite](https://pubs.acs.org/doi/10.1021/acsenergylett.1c00871)
    $D$=1e-6 m²/s to 4e-4 m²/s (room temperature) => diffusion of electrons, but talk about the warburg coefficient
    
    
  - [Diffusion coefficients of perovskites](https://pubs.acs.org/doi/10.1021/acs.chemmater.2c03340) : $D$=10e-11 m²/s (at room temperature, Li0.34La0.5TiO2.94 LLTO) 

![Capture d'écran 2024-07-24 113424](https://hackmd.io/_uploads/rkv0FaAOC.png)

$D$=10e-11 m²/s at 900K  ([for La(1-X)/3LixNbO3](https://www.sciencedirect.com/science/article/pii/S0167273821001156))


![image](https://hackmd.io/_uploads/SyTn36R_C.png)


- temperature-dependent ionic conductivities $\sigma$
	- $\ce{ LiTaO_{3} }$ 
	- [ 300°C：ionic conductivity of LiTaO~3~ is 3 × 10^-8^ S/cm](https://pubs.aip.org/aip/jap/article-abstract/61/12/5386/172942/The-electrical-properties-of-ferroelectric-LiTaO3)
	- lanthanum titanates (everything under formula $\ce{ Li_{y}La_{x}TiO_{3-\delta} }$)
	- [Ca doped LaTiO3_650°C: 1.22 × 10^-2^ S/cm](https://www.sciencedirect.com/science/article/pii/S0925838814028928)
	- [Undoped LatiO3_650°C:  1.22 × 10^-2^ S/cm](https://www.sciencedirect.com/science/article/pii/S0167273808007315)
## Figures to make the paper!
- pristine substrates
	- DC: pure electronic
	- EIS: capacitive
- gated samples
	- DC: diffusion coefficient
	- EIS: diffusion coefficient and ionic conductivity
	- RHEED? LiTaO3 ion conduction mechanism unclear
- reduced samples 
	- DC: pure electronic
	- EIS: half parabola (results now interpretable! to be interpreted)
- reduction process: brian rheed
- gating process: drain-src current | gate-drain current | gate-drain voltage vs time
- let's see if anything shows up in XRD!

## Further experiments
- Gating has been done on x-cuts of LiTaO3 thus far. Corroborate with y-cuts and z-cuts.

![image](https://hackmd.io/_uploads/SJPGhpr_R.png)



# Inventory
Links to MSDS.

- [60wt% PTFE | H2O](https://www.sigmaaldrich.com/CA/en/sds/aldrich/665800?userType=anonymous)
    - hazards: serious eye damage. But releases toxic gases (CO, NO, HF) in fire.
- [TMAF](https://www.sigmaaldrich.com/CA/en/sds/aldrich/107212?userType=anonymous)
    - hazards: skin, eye irritation. Flash point 113˚C: ±15˚C critical.
- [HMIM-TFSI](https://www.sigmaaldrich.com/CA/en/sds/aldrich/727954?userType=anonymous)
    - hazards: None. But also releases toxic gases (CO, NO, HF) in fire.
- [LiFePO4](https://www.sigmaaldrich.com/CA/en/sds/aldrich/759546?userType=anonymous)
    - hazards: None. Handle powder under ventilation, ie fumehood. 
- [MPP-TFSI from Fisher](https://www.fishersci.ca/shop/products/1-methyl-1-propylpyrrolidinium-bis-trifluoromethanesulfonyl-imide-tci-america-2/m20985g) 
    - MSDS from external job
- [ketjenblack](https://www.fuelcellstore.com/ketjenblack-carbon-black-ec600jd) received.

## La2/3

- B130a
	- diagonal dropped on kapton
	- out-of-its-way beautiful
	- wired
- B130b
	- dropped on kapton
	- fingers covered
	- looks quite nice, i think dropping on kapton without sticking might be completely fine
	- on thesis device
- B132a
	- carbon cleaned; OL
	- B132b stowed because it dropped on kapton and actually stuck
	- deposition beautiful
- B131a
	- fingers covered
	- gated 07-08. seemed to have been gated on this pair of electrodes befpre.
- B131b
	- fingered deposition beautiful

# Tickets

## LiTaO3

### Data analysis

Let's do a Warburg study group!

Last week saw magic LiTaO3 samples with resistance on $\cdot 10^{-7}\Omega$. Constant current polarizations were done. One of them is documented in [this notebook](https://github.com/beepmo/gator/blob/main/data/07-26/YcutDC.ipynb). Miracle2 was also tested, but reached breakdown voltage (is this what we do to our samples?): voltage jumped from 42V to 0.7V after a while. Data to be retrieved.

### More experiments!

#### Finish characterizing last week's samples!
Three more EIS; one more constant current. We should also give names to samples.

#### More gating!
Our X- and Z- cut orders have arrived. As Bruce suggested, let's gate more X- and Y- cut samples with gold electrodes deposited on them. Will update when Saied gives us the go-ahead for gold dep!

## La2/3TiO3

Last week saw a recipe for periodicity in La2/3 gating! 
> The shield box doesn't work; we need to wait for a peaceful time sans interference, and then set 4V Vpp!

### Data analysis

Observe decay after spike. Do they reset to same level before each spike? Exponential decay constant? Follow much the same analysis as thesis.


### More experiments!

#### 1. Gate voltage
Test gate voltage settings 3Vpp, 2Vpp. Determine threshold for the periodicity recipe.

#### 2. Which ions
Repeat with graphite top electrode and pure HMIM-TFSI without lithium salt. We are operating above hydrolysis voltage.




## Lithium electrode fabrication



#### Commercial LMN electrode
Gift from Bahar: https://www.mtixtl.com/Li-IonBatteryCathode-bc-af-241mn-ds.aspx

- [x] check specs & reactions

## Gold deposition
Sputtering physical vapour deposition. 3h session at Center for Flexible Electronics and Textiles, time pending.

**Get old LTO!**

Consider a LiTaO3 cut that exhibits in-plane anisotropy in ionic conduction. 

![image](https://hackmd.io/_uploads/r1d6VlRHA.png)


Invent aluminium masks for LiTaO3 and LSAT. Mask criteria:
- 2 sets of electrodes to allow ionic conductivity measurement in different directions
- Super home-made: permissible materials are UHV foil and kapton tape. Must assemble onto ceiling of PVD sample holder.

Valid mask design important for future use, esp La2/3 films.

![](https://cdn.discordapp.com/attachments/678390654211981312/1252108812840865943/20240131_143246.jpg?ex=667104b4&is=666fb334&hm=2e3939470e07fa4b31be0a0161731a98bff643eb0d1ef3475208cebe09490643&)

## Electrochemical Impedance Spectroscopy


### Hands on
Construct a hole-less polymer cell like we did for [Measuring reaction-less ionic conductivity](#Measuring-reaction-less-ionic-conductivity). Perform EIS at third floor lab.

We expct the spectra to be characteristic of a [debye circuit](https://lithiuminventory.com/experimental-electrochemistry/eis/debye-circuit/) and can compare our results directly with [HMIMTFSI | Celgard membrane](https://onlinelibrary.wiley.com/doi/full/10.1002/adfm.202306633), as well as our LCR meter results. 

**Status: sanity check our data!**

### EIS for La2/3TiO3

Theory to discuss with Joan:
- Non-blocking electrodes show up as a perfect [RC circuit](https://lithiuminventory.com/experimental-electrochemistry/eis/rc-circuits/).
- Blocking electrodes show up as a [Randles circuit](https://lithiuminventory.com/experimental-electrochemistry/eis/randles-circuit/).


![400](https://i.imgur.com/V5bzJQ4.png)

### EIS for LiTaO3

Contingencies:
- gold deposition

Cold solder padded bare substrate onto puck as control. Then we're ready to perform EIS.


Give Brian a tutorial on all the EIS stuff.
Be prepared to discuss anisotropy. 

**Status: withold Brian discussion till after results; next wire to PCB, our modified puck.**





## Nature of HMIM-TFSI
O organic chemist Yibing, please grant us one question: 
> Among the [acidic ionic liquids](https://pubs.acs.org/doi/10.1021/acs.chemrev.5b00763#:~:text=An%20acidic%20ionic%20liquid%20can,cation%2C%20anion%2C%20or%20both.), does HMIM-TFSI bear any characteristic of a Lewis acid or a Bronsted acid?

![截屏2024-06-24 上午11.04.23](https://hackmd.io/_uploads/SJirSVvU0.png)


- ~~Lewis acid~~ : a substance that accepts electron pairs.
   -  Electron acceptor capacity：usually located in the anion
     - Why anion
         - Cations in Lewis acidic ionic liquids are usually **designed** to have relatively high stability to avoid side reactions. Cations designed in this way keep the entire ionic liquid system stable, while anions are more likely to adjust their electronic structure to accept electron pairs.
         - Imidazole cations (e.g., HMIM⁺) typically have a full π-electron system and high resonance stability and are less likely to accept additional electron pairs.
   - Charge & Electron Density
     -  Overall charge : the total amount of electric charge in a molecule or ion
     -  Local electron density : the distribution of electrons in specific regions within a molecule or ion
     -  Although an anion carries a net negative charge, certain regions within itcan exhibit characteristics of electron deficiency, thereby displaying Lewis acidity.
     
   -  TFSI : The electronegative atoms (F O) are highly saturated and stable, and they do not readily accept additional electron pairs. 
  
- ~~Brønsted acid~~: a substance that releases protons (H+)
   - HMIM：the H on the imidazole ring are not attached to atoms with high electronegativity (e.g., O N S)C-H is not so acidic.
   - TFSI: no H
- Ionic Conductivity of HMIM TFSI
   - HMIM: 
       - Conjugation effect: the phenomenon of π-electron delocalisation in molecules (Significant in imidazole cations)
       - Conjugated system → more stable charge distribution → reduces internal electron rearrangements during the movement of the cation → smoother movement.
    - TFSI：
        - Low polarity: polar groups are evenly distributed
        - lower polarity →  lower interaction forces between HMIM and TFSI → ions to move more freely → increasing the ionic conductivity.
## Gating on $H^+$




## Detecting water electrolysis in ionic liquid 

- [x] **Go through cyclic voltammetry with Joan.**

We still have a lot to learn from round-robin studies of HMIM-TFSI:
- [Part 1: experimental methods and results](https://www.nist.gov/publications/thermodynamic-and-thermophysical-properties-reference-ionic-liquid-1-hexyl-3)
    - track changes in $w(H_2O)$ throughout various experiments
- [Part 2: critical evaluation](https://www.degruyter.com/document/doi/10.1351/PAC-REP-08-09-22/html?_llca=transfer%3A7772f5cf4e88d21caa9740949ee6e50d&_llch=be54cf61ae786d68bd48b5cc5bc50f30fd1c69baf8f171dbff7ac4594b409b46)
    - note results on electrolytic conductivity vs water mole fraction
    - pursue references on the measurement of electrolytic conductivity: how were the experiments set up?


#### Two experiments
Set sweep on Keithley: Linear dual sweep, start 0V, stop 2V, 200 points per cycle, 1 cycle.

Drop PCB in tall flask and immerse in HMIM-TFSI up to src-drn contact pads. First use exposed PCB electrodes as-is. Expect a peak in current at copper (0.34V) or aluminium (-1.66V): this would tell us the composition of the pads. Maybe we'll see a peak around 1.23V due to water! 

Then use carbon-coated electrodes on the PCB. Check whether metal oxidation is eliminated.

#### Worked! Next:
- carbon-coated: Since the carbon paste can dissolve in the ionic liquid, a carbon block is used instead.

##### Testing Carbon Block Electrodes
Place two opposing carbon block electrodes into the setup.Drop the assembly into a flask and immerse in HMIM-TFSI. Perform the sweep and observe the behavior of the carbon block electrodes. Record any current peaks.

#####  Replacing Carbon Paste with Carbon Block in Original Setup
Replace the carbon paste electrodes on the PCB with carbon block electrodes. Use a small amount of carbon paste to fix the carbon blocks in place, ensuring that this paste does not contact the ionic liquid.


## Measuring reaction-less ionic conductivity

We assemble our own conduction cells with separator, washers, and ionic liquid.

Conducted HMIM-TFSI ionic conductivity tests with 10kHz 1Vrms LCR meter, Display A set to resistance. Compare with literature: 0.07 S/m at RT.

| test description                                                                                          | resistance (Ω) | conductivity (S/m)        |
| --------------------------------------------------------------------------------------------------------- | -------------- | ------------------------- |
| droplet on LSAT with interdigitated electrodes                                                            | 1356           | ambiguous due to geometry |
| 35µm polymer sandwiched between 1.6cm diameter washers and wet with IL                                    | 71.66          | 0.0024                    |
| 35µm polymer with 8mm, 12mm diameters oval hole sandwiched between 1.6cm diameter washers and wet with IL | 12.79          | 0.017                     |


### Comparison with literature

[One of the HMIM-TFSI round robin studies](https://pubs.acs.org/doi/10.1021/je7003484) report **0.077 S/m** with 10kHz 1Vrms LCR meter. The ionic conductivity we measured is 4x lower.

[HMIMTFSI | Celgard membrane](https://onlinelibrary.wiley.com/doi/full/10.1002/adfm.202306633) reports **0.05 S/m** at RT with the following set-up:
- eis 10 kHz to 1 MHz; voltage amplitude of 10 mV
- HMIM-TFSI soaked in Celgard 2320 separator (polypropylene/polyethylene/polypropylene [PP/PE/PP] trilayer, 20 µm in thickness)

The ionic conductivity we measured is 5x lower, attributable to two causes.

Since the EIS signature of IL-soaked membrane resembles a CPE and resistor in series, measurements at higher $\omega$ would give lower readings of $Z'$. This makes a 1.5x difference.

![](https://onlinelibrary.wiley.com/cms/asset/889a831d-bec4-4036-b64b-d5845e0fc710/adfm202306633-fig-0006-m.png)


Difference in membranes: higher porosity increases ionic conductivity (same ref as above).
- [ ] what is our celgard model?


### Conclusion

What we measure in EIS and in the LCR meter is a mixture of the ionic conductivity and the electrolytic conductivity.   

Eg. [Round-robin study](https://www.degruyter.com/document/doi/10.1351/PAC-REP-08-09-22/html?_llca=transfer%3A7772f5cf4e88d21caa9740949ee6e50d&_llch=be54cf61ae786d68bd48b5cc5bc50f30fd1c69baf8f171dbff7ac4594b409b46) showed us a conductivity that increases as a function of water content due to hydrolysis. [Ref 4](https://pubs.acs.org/doi/10.1021/je700329a) measured this with the real intercept of EIS, which is the same thing i32a did to report ionic conductivity.
![](https://i.imgur.com/bf80xD8.png)




## LiTaO3 gating
We will perform the complete gating experiment on LiTaO3. 

## La2/3 gating 

2 gated samples from the old samples
1. B131a -> found only electronic conduction
2. B132a -> Weird results, need to run again




    

## PCB assembly
This is an experimental thing all of us need to do. 
1. Solder header pins onto PCB.
2. Attach sample to PCB with two painted electrodes.




## XRD 

### Domains: La2/3TiO3 & 
A cross-polarizer viewer was made. 
Streak patterns were visible on STO substrate, suggesting stress/domains.

Could we use a kind of full film XRD to observe domains and support "streaks" observed on STO through crossed polarizers?

When fresh La2/3 comes out, we have to try both too.


### Structural change: gated LiTaO3
Ionic conductivity was induced.


## Things for fresh films
- ipa rinse, XRD before after
- microscope cross polarizer

# Appendix

## Unix vs Windows
https://gfranzini.gitbooks.io/tracer/content/support/command-line-mac-vs.-windows.html

## Creating a new folder for github:
```shell
(base) beep@dhcp-206-87-220-254 data % ls
05-22		05-23 di water	06-03		06-11
(base) beep@dhcp-206-87-220-254 data % mkdir 06-12
(base) beep@dhcp-206-87-220-254 data % cd 06-12
(base) beep@dhcp-206-87-220-254 06-12 % touch pcb_cv.ipynb
(base) beep@dhcp-206-87-220-254 06-12 % git add -A   
(base) beep@dhcp-206-87-220-254 06-12 % git commit -m "new folder"
[main cd267b9] new folder
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 data/06-12/pcb_cv.ipynb
(base) beep@dhcp-206-87-220-254 06-12 % git push
To https://github.com/beepmo/gator/
```

## EIS fitting
https://impedancepy.readthedocs.io/en/latest/getting-started.html


### New Ionic Liquid (Pb with gating with the old one)

Mass of Lithium Salt : 0.1208g instead of 0.09g
Stiring over night 

