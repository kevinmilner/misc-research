# Random Field Loss Debug

Random field dubugging with the following parameters:

* 10 randomly chosen ruptures
* 5 randomly chosen assets
* 100 random fields
* 100 randomly sampled (from a normal distribution) between-event values

The mean of all 100 between-event values is -0.03953218

## Table Of Contents
* [Rupture 135839, M7.2476196](#rupture-135839-m72476196)
  * [Rupture 135839, Asset0](#rupture-135839-asset0)
  * [Rupture 135839, Asset1](#rupture-135839-asset1)
  * [Rupture 135839, Asset2](#rupture-135839-asset2)
  * [Rupture 135839, Asset3](#rupture-135839-asset3)
  * [Rupture 135839, Asset4](#rupture-135839-asset4)
* [Rupture 205629, M7.104012](#rupture-205629-m7104012)
  * [Rupture 205629, Asset0](#rupture-205629-asset0)
  * [Rupture 205629, Asset1](#rupture-205629-asset1)
  * [Rupture 205629, Asset2](#rupture-205629-asset2)
  * [Rupture 205629, Asset3](#rupture-205629-asset3)
  * [Rupture 205629, Asset4](#rupture-205629-asset4)
* [Rupture 81057, M7.0598035](#rupture-81057-m70598035)
  * [Rupture 81057, Asset0](#rupture-81057-asset0)
  * [Rupture 81057, Asset1](#rupture-81057-asset1)
  * [Rupture 81057, Asset2](#rupture-81057-asset2)
  * [Rupture 81057, Asset3](#rupture-81057-asset3)
  * [Rupture 81057, Asset4](#rupture-81057-asset4)
* [Rupture 215437, M7.700723](#rupture-215437-m7700723)
  * [Rupture 215437, Asset0](#rupture-215437-asset0)
  * [Rupture 215437, Asset1](#rupture-215437-asset1)
  * [Rupture 215437, Asset2](#rupture-215437-asset2)
  * [Rupture 215437, Asset3](#rupture-215437-asset3)
  * [Rupture 215437, Asset4](#rupture-215437-asset4)
* [Rupture 187237, M7.2455945](#rupture-187237-m72455945)
  * [Rupture 187237, Asset0](#rupture-187237-asset0)
  * [Rupture 187237, Asset1](#rupture-187237-asset1)
  * [Rupture 187237, Asset2](#rupture-187237-asset2)
  * [Rupture 187237, Asset3](#rupture-187237-asset3)
  * [Rupture 187237, Asset4](#rupture-187237-asset4)
* [Rupture 103472, M7.0620694](#rupture-103472-m70620694)
  * [Rupture 103472, Asset0](#rupture-103472-asset0)
  * [Rupture 103472, Asset1](#rupture-103472-asset1)
  * [Rupture 103472, Asset2](#rupture-103472-asset2)
  * [Rupture 103472, Asset3](#rupture-103472-asset3)
  * [Rupture 103472, Asset4](#rupture-103472-asset4)
* [Rupture 169293, M7.9014773](#rupture-169293-m79014773)
  * [Rupture 169293, Asset0](#rupture-169293-asset0)
  * [Rupture 169293, Asset1](#rupture-169293-asset1)
  * [Rupture 169293, Asset2](#rupture-169293-asset2)
  * [Rupture 169293, Asset3](#rupture-169293-asset3)
  * [Rupture 169293, Asset4](#rupture-169293-asset4)
* [Rupture 208188, M8.023331](#rupture-208188-m8023331)
  * [Rupture 208188, Asset0](#rupture-208188-asset0)
  * [Rupture 208188, Asset1](#rupture-208188-asset1)
  * [Rupture 208188, Asset2](#rupture-208188-asset2)
  * [Rupture 208188, Asset3](#rupture-208188-asset3)
  * [Rupture 208188, Asset4](#rupture-208188-asset4)
* [Rupture 68673, M8.155491](#rupture-68673-m8155491)
  * [Rupture 68673, Asset0](#rupture-68673-asset0)
  * [Rupture 68673, Asset1](#rupture-68673-asset1)
  * [Rupture 68673, Asset2](#rupture-68673-asset2)
  * [Rupture 68673, Asset3](#rupture-68673-asset3)
  * [Rupture 68673, Asset4](#rupture-68673-asset4)
* [Rupture 42699, M7.9970284](#rupture-42699-m79970284)
  * [Rupture 42699, Asset0](#rupture-42699-asset0)
  * [Rupture 42699, Asset1](#rupture-42699-asset1)
  * [Rupture 42699, Asset2](#rupture-42699-asset2)
  * [Rupture 42699, Asset3](#rupture-42699-asset3)
  * [Rupture 42699, Asset4](#rupture-42699-asset4)
## Rupture 135839, M7.2476196
*[(top)](#table-of-contents)*

### Rupture 135839, Asset0
*[(top)](#table-of-contents)*

Asset parameters:

* value: 28152.0
* J-B distance to rupture: 694.690385092882
* Vulnerability function: W1-h-RES1-DF
* GMPE ln mean: -5.4811554
* GMPE phi/tau/total std devs: 0.63	0.36	0.7256032

**Loss Values**

| Description | Loss Value |
|-----|-----|
| Mean Loss (GMPE) | 0.0073295822 |
| Mean Loss (10000 random fields) | 0.01492056 |
| Mean Loss using rand-field exceed probs | 0.022761 |

| ![plot](resources/rup0_asset0_gmpe_dists.png) | ![plot](resources/rup0_asset0_field_losses.png) |
|-----|-----|
| ![plot](resources/rup0_asset0_gmpe_dists_log.png) | ![plot](resources/rup0_asset0_field_losses_log.png) |
| ![plot](resources/rup0_asset0_betweens.png) | ![plot](resources/rup0_asset0_withins.png) |
| ![plot](resources/rup0_asset0_gmpe_exceeds.png) | ![plot](resources/rup0_asset0_cumulative_losses.png) |

### Rupture 135839, Asset1
*[(top)](#table-of-contents)*

Asset parameters:

* value: 173.0
* J-B distance to rupture: 14.043580684469827
* Vulnerability function: RM1L-m-RES1-DF
* GMPE ln mean: -1.169849
* GMPE phi/tau/total std devs: 0.62504166	0.35524026	0.7189386

**Loss Values**

| Description | Loss Value |
|-----|-----|
| Mean Loss (GMPE) | 15.782214 |
| Mean Loss (10000 random fields) | 10.930483 |
| Mean Loss using rand-field exceed probs | 13.233748 |

| ![plot](resources/rup0_asset1_gmpe_dists.png) | ![plot](resources/rup0_asset1_field_losses.png) |
|-----|-----|
| ![plot](resources/rup0_asset1_gmpe_dists_log.png) | ![plot](resources/rup0_asset1_field_losses_log.png) |
| ![plot](resources/rup0_asset1_betweens.png) | ![plot](resources/rup0_asset1_withins.png) |
| ![plot](resources/rup0_asset1_gmpe_exceeds.png) | ![plot](resources/rup0_asset1_cumulative_losses.png) |

### Rupture 135839, Asset2
*[(top)](#table-of-contents)*

Asset parameters:

* value: 127.0
* J-B distance to rupture: 273.5062053170421
* Vulnerability function: RM1L-l-RES1-DF
* GMPE ln mean: -3.8194346
* GMPE phi/tau/total std devs: 0.63	0.36	0.7256032

**Loss Values**

| Description | Loss Value |
|-----|-----|
| Mean Loss (GMPE) | 0.08566205 |
| Mean Loss (10000 random fields) | 0.05307457 |
| Mean Loss using rand-field exceed probs | 0.07050732 |

| ![plot](resources/rup0_asset2_gmpe_dists.png) | ![plot](resources/rup0_asset2_field_losses.png) |
|-----|-----|
| ![plot](resources/rup0_asset2_gmpe_dists_log.png) | ![plot](resources/rup0_asset2_field_losses_log.png) |
| ![plot](resources/rup0_asset2_betweens.png) | ![plot](resources/rup0_asset2_withins.png) |
| ![plot](resources/rup0_asset2_gmpe_exceeds.png) | ![plot](resources/rup0_asset2_cumulative_losses.png) |

### Rupture 135839, Asset3
*[(top)](#table-of-contents)*

Asset parameters:

* value: 8363.0
* J-B distance to rupture: 447.8401003616335
* Vulnerability function: W1-h-RES1-DF
* GMPE ln mean: -4.0803275
* GMPE phi/tau/total std devs: 0.62855977	0.3586201	0.7236683

**Loss Values**

| Description | Loss Value |
|-----|-----|
| Mean Loss (GMPE) | 0.46222234 |
| Mean Loss (10000 random fields) | 0.28902528 |
| Mean Loss using rand-field exceed probs | 0.421706 |

| ![plot](resources/rup0_asset3_gmpe_dists.png) | ![plot](resources/rup0_asset3_field_losses.png) |
|-----|-----|
| ![plot](resources/rup0_asset3_gmpe_dists_log.png) | ![plot](resources/rup0_asset3_field_losses_log.png) |
| ![plot](resources/rup0_asset3_betweens.png) | ![plot](resources/rup0_asset3_withins.png) |
| ![plot](resources/rup0_asset3_gmpe_exceeds.png) | ![plot](resources/rup0_asset3_cumulative_losses.png) |

### Rupture 135839, Asset4
*[(top)](#table-of-contents)*

Asset parameters:

* value: 26997.0
* J-B distance to rupture: 34.65936164836105
* Vulnerability function: W1-m-RES1-DF
* GMPE ln mean: -1.4465866
* GMPE phi/tau/total std devs: 0.61022574	0.3408569	0.69896984

**Loss Values**

| Description | Loss Value |
|-----|-----|
| Mean Loss (GMPE) | 804.4842 |
| Mean Loss (10000 random fields) | 584.70154 |
| Mean Loss using rand-field exceed probs | 709.2692 |

| ![plot](resources/rup0_asset4_gmpe_dists.png) | ![plot](resources/rup0_asset4_field_losses.png) |
|-----|-----|
| ![plot](resources/rup0_asset4_gmpe_dists_log.png) | ![plot](resources/rup0_asset4_field_losses_log.png) |
| ![plot](resources/rup0_asset4_betweens.png) | ![plot](resources/rup0_asset4_withins.png) |
| ![plot](resources/rup0_asset4_gmpe_exceeds.png) | ![plot](resources/rup0_asset4_cumulative_losses.png) |

## Rupture 205629, M7.104012
*[(top)](#table-of-contents)*

### Rupture 205629, Asset0
*[(top)](#table-of-contents)*

Asset parameters:

* value: 28152.0
* J-B distance to rupture: 455.31765368287483
* Vulnerability function: W1-h-RES1-DF
* GMPE ln mean: -4.816326
* GMPE phi/tau/total std devs: 0.63	0.36	0.7256032

**Loss Values**

| Description | Loss Value |
|-----|-----|
| Mean Loss (GMPE) | 0.124110706 |
| Mean Loss (10000 random fields) | 0.06418656 |
| Mean Loss using rand-field exceed probs | 0.10406381 |

| ![plot](resources/rup1_asset0_gmpe_dists.png) | ![plot](resources/rup1_asset0_field_losses.png) |
|-----|-----|
| ![plot](resources/rup1_asset0_gmpe_dists_log.png) | ![plot](resources/rup1_asset0_field_losses_log.png) |
| ![plot](resources/rup1_asset0_betweens.png) | ![plot](resources/rup1_asset0_withins.png) |
| ![plot](resources/rup1_asset0_gmpe_exceeds.png) | ![plot](resources/rup1_asset0_cumulative_losses.png) |

### Rupture 205629, Asset1
*[(top)](#table-of-contents)*

Asset parameters:

* value: 173.0
* J-B distance to rupture: 221.97881822486164
* Vulnerability function: RM1L-m-RES1-DF
* GMPE ln mean: -3.5210862
* GMPE phi/tau/total std devs: 0.6294992	0.3595204	0.7249304

**Loss Values**

| Description | Loss Value |
|-----|-----|
| Mean Loss (GMPE) | 0.12440571 |
| Mean Loss (10000 random fields) | 0.10107006 |
| Mean Loss using rand-field exceed probs | 0.13155662 |

| ![plot](resources/rup1_asset1_gmpe_dists.png) | ![plot](resources/rup1_asset1_field_losses.png) |
|-----|-----|
| ![plot](resources/rup1_asset1_gmpe_dists_log.png) | ![plot](resources/rup1_asset1_field_losses_log.png) |
| ![plot](resources/rup1_asset1_betweens.png) | ![plot](resources/rup1_asset1_withins.png) |
| ![plot](resources/rup1_asset1_gmpe_exceeds.png) | ![plot](resources/rup1_asset1_cumulative_losses.png) |

### Rupture 205629, Asset2
*[(top)](#table-of-contents)*

Asset parameters:

* value: 127.0
* J-B distance to rupture: 518.5566534689463
* Vulnerability function: RM1L-l-RES1-DF
* GMPE ln mean: -5.0649376
* GMPE phi/tau/total std devs: 0.63	0.36	0.7256032

**Loss Values**

| Description | Loss Value |
|-----|-----|
| Mean Loss (GMPE) | 0.0025063262 |
| Mean Loss (10000 random fields) | 0.00133858 |
| Mean Loss using rand-field exceed probs | 0.0020134381 |

| ![plot](resources/rup1_asset2_gmpe_dists.png) | ![plot](resources/rup1_asset2_field_losses.png) |
|-----|-----|
| ![plot](resources/rup1_asset2_gmpe_dists_log.png) | ![plot](resources/rup1_asset2_field_losses_log.png) |
| ![plot](resources/rup1_asset2_betweens.png) | ![plot](resources/rup1_asset2_withins.png) |
| ![plot](resources/rup1_asset2_gmpe_exceeds.png) | ![plot](resources/rup1_asset2_cumulative_losses.png) |

### Rupture 205629, Asset3
*[(top)](#table-of-contents)*

Asset parameters:

* value: 8363.0
* J-B distance to rupture: 206.3980025623005
* Vulnerability function: W1-h-RES1-DF
* GMPE ln mean: -3.1550865
* GMPE phi/tau/total std devs: 0.62637275	0.35652056	0.72072864

**Loss Values**

| Description | Loss Value |
|-----|-----|
| Mean Loss (GMPE) | 6.2615194 |
| Mean Loss (10000 random fields) | 2.7020016 |
| Mean Loss using rand-field exceed probs | 3.7963848 |

| ![plot](resources/rup1_asset3_gmpe_dists.png) | ![plot](resources/rup1_asset3_field_losses.png) |
|-----|-----|
| ![plot](resources/rup1_asset3_gmpe_dists_log.png) | ![plot](resources/rup1_asset3_field_losses_log.png) |
| ![plot](resources/rup1_asset3_betweens.png) | ![plot](resources/rup1_asset3_withins.png) |
| ![plot](resources/rup1_asset3_gmpe_exceeds.png) | ![plot](resources/rup1_asset3_cumulative_losses.png) |

### Rupture 205629, Asset4
*[(top)](#table-of-contents)*

Asset parameters:

* value: 26997.0
* J-B distance to rupture: 154.41544744535676
* Vulnerability function: W1-m-RES1-DF
* GMPE ln mean: -2.8310452
* GMPE phi/tau/total std devs: 0.62498957	0.35519016	0.71886855

**Loss Values**

| Description | Loss Value |
|-----|-----|
| Mean Loss (GMPE) | 58.49787 |
| Mean Loss (10000 random fields) | 39.487164 |
| Mean Loss using rand-field exceed probs | 51.564423 |

| ![plot](resources/rup1_asset4_gmpe_dists.png) | ![plot](resources/rup1_asset4_field_losses.png) |
|-----|-----|
| ![plot](resources/rup1_asset4_gmpe_dists_log.png) | ![plot](resources/rup1_asset4_field_losses_log.png) |
| ![plot](resources/rup1_asset4_betweens.png) | ![plot](resources/rup1_asset4_withins.png) |
| ![plot](resources/rup1_asset4_gmpe_exceeds.png) | ![plot](resources/rup1_asset4_cumulative_losses.png) |

## Rupture 81057, M7.0598035
*[(top)](#table-of-contents)*

### Rupture 81057, Asset0
*[(top)](#table-of-contents)*

Asset parameters:

* value: 28152.0
* J-B distance to rupture: 620.5196004039326
* Vulnerability function: W1-h-RES1-DF
* GMPE ln mean: -5.5057936
* GMPE phi/tau/total std devs: 0.63	0.36	0.7256032

**Loss Values**

| Description | Loss Value |
|-----|-----|
| Mean Loss (GMPE) | 0.006521991 |
| Mean Loss (10000 random fields) | 0.0 |
| Mean Loss using rand-field exceed probs | 0.0 |

| ![plot](resources/rup2_asset0_gmpe_dists.png) | ![plot](resources/rup2_asset0_field_losses.png) |
|-----|-----|
| ![plot](resources/rup2_asset0_gmpe_dists_log.png) | ![plot](resources/rup2_asset0_field_losses_log.png) |
| ![plot](resources/rup2_asset0_betweens.png) | ![plot](resources/rup2_asset0_withins.png) |
| ![plot](resources/rup2_asset0_gmpe_exceeds.png) | ![plot](resources/rup2_asset0_cumulative_losses.png) |

### Rupture 81057, Asset1
*[(top)](#table-of-contents)*

Asset parameters:

* value: 173.0
* J-B distance to rupture: 56.80155166346245
* Vulnerability function: RM1L-m-RES1-DF
* GMPE ln mean: -2.219313
* GMPE phi/tau/total std devs: 0.62818927	0.3582648	0.7231704

**Loss Values**

| Description | Loss Value |
|-----|-----|
| Mean Loss (GMPE) | 2.2515242 |
| Mean Loss (10000 random fields) | 1.2803384 |
| Mean Loss using rand-field exceed probs | 1.6347779 |

| ![plot](resources/rup2_asset1_gmpe_dists.png) | ![plot](resources/rup2_asset1_field_losses.png) |
|-----|-----|
| ![plot](resources/rup2_asset1_gmpe_dists_log.png) | ![plot](resources/rup2_asset1_field_losses_log.png) |
| ![plot](resources/rup2_asset1_betweens.png) | ![plot](resources/rup2_asset1_withins.png) |
| ![plot](resources/rup2_asset1_gmpe_exceeds.png) | ![plot](resources/rup2_asset1_cumulative_losses.png) |

### Rupture 81057, Asset2
*[(top)](#table-of-contents)*

Asset parameters:

* value: 127.0
* J-B distance to rupture: 361.62884408989186
* Vulnerability function: RM1L-l-RES1-DF
* GMPE ln mean: -4.4785953
* GMPE phi/tau/total std devs: 0.63	0.36	0.7256032

**Loss Values**

| Description | Loss Value |
|-----|-----|
| Mean Loss (GMPE) | 0.015296124 |
| Mean Loss (10000 random fields) | 0.00536702 |
| Mean Loss using rand-field exceed probs | 0.007807671 |

| ![plot](resources/rup2_asset2_gmpe_dists.png) | ![plot](resources/rup2_asset2_field_losses.png) |
|-----|-----|
| ![plot](resources/rup2_asset2_gmpe_dists_log.png) | ![plot](resources/rup2_asset2_field_losses_log.png) |
| ![plot](resources/rup2_asset2_betweens.png) | ![plot](resources/rup2_asset2_withins.png) |
| ![plot](resources/rup2_asset2_gmpe_exceeds.png) | ![plot](resources/rup2_asset2_cumulative_losses.png) |

### Rupture 81057, Asset3
*[(top)](#table-of-contents)*

Asset parameters:

* value: 8363.0
* J-B distance to rupture: 374.71615824900556
* Vulnerability function: W1-h-RES1-DF
* GMPE ln mean: -4.0393543
* GMPE phi/tau/total std devs: 0.6284996	0.3585624	0.72358745

**Loss Values**

| Description | Loss Value |
|-----|-----|
| Mean Loss (GMPE) | 0.5250391 |
| Mean Loss (10000 random fields) | 0.12945925 |
| Mean Loss using rand-field exceed probs | 0.19938752 |

| ![plot](resources/rup2_asset3_gmpe_dists.png) | ![plot](resources/rup2_asset3_field_losses.png) |
|-----|-----|
| ![plot](resources/rup2_asset3_gmpe_dists_log.png) | ![plot](resources/rup2_asset3_field_losses_log.png) |
| ![plot](resources/rup2_asset3_betweens.png) | ![plot](resources/rup2_asset3_withins.png) |
| ![plot](resources/rup2_asset3_gmpe_exceeds.png) | ![plot](resources/rup2_asset3_cumulative_losses.png) |

### Rupture 81057, Asset4
*[(top)](#table-of-contents)*

Asset parameters:

* value: 26997.0
* J-B distance to rupture: 18.314450029417543
* Vulnerability function: W1-m-RES1-DF
* GMPE ln mean: -1.155249
* GMPE phi/tau/total std devs: 0.6036888	0.3344283	0.69013214

**Loss Values**

| Description | Loss Value |
|-----|-----|
| Mean Loss (GMPE) | 1268.956 |
| Mean Loss (10000 random fields) | 969.3386 |
| Mean Loss using rand-field exceed probs | 1161.955 |

| ![plot](resources/rup2_asset4_gmpe_dists.png) | ![plot](resources/rup2_asset4_field_losses.png) |
|-----|-----|
| ![plot](resources/rup2_asset4_gmpe_dists_log.png) | ![plot](resources/rup2_asset4_field_losses_log.png) |
| ![plot](resources/rup2_asset4_betweens.png) | ![plot](resources/rup2_asset4_withins.png) |
| ![plot](resources/rup2_asset4_gmpe_exceeds.png) | ![plot](resources/rup2_asset4_cumulative_losses.png) |

## Rupture 215437, M7.700723
*[(top)](#table-of-contents)*

### Rupture 215437, Asset0
*[(top)](#table-of-contents)*

Asset parameters:

* value: 28152.0
* J-B distance to rupture: 71.05894884501028
* Vulnerability function: W1-h-RES1-DF
* GMPE ln mean: -1.9264812
* GMPE phi/tau/total std devs: 0.63	0.36	0.7256032

**Loss Values**

| Description | Loss Value |
|-----|-----|
| Mean Loss (GMPE) | 301.51617 |
| Mean Loss (10000 random fields) | 221.89885 |
| Mean Loss using rand-field exceed probs | 273.17523 |

| ![plot](resources/rup3_asset0_gmpe_dists.png) | ![plot](resources/rup3_asset0_field_losses.png) |
|-----|-----|
| ![plot](resources/rup3_asset0_gmpe_dists_log.png) | ![plot](resources/rup3_asset0_field_losses_log.png) |
| ![plot](resources/rup3_asset0_betweens.png) | ![plot](resources/rup3_asset0_withins.png) |
| ![plot](resources/rup3_asset0_gmpe_exceeds.png) | ![plot](resources/rup3_asset0_cumulative_losses.png) |

### Rupture 215437, Asset1
*[(top)](#table-of-contents)*

Asset parameters:

* value: 173.0
* J-B distance to rupture: 534.3368058887747
* Vulnerability function: RM1L-m-RES1-DF
* GMPE ln mean: -3.9336748
* GMPE phi/tau/total std devs: 0.62966776	0.3596819	0.72515696

**Loss Values**

| Description | Loss Value |
|-----|-----|
| Mean Loss (GMPE) | 0.044866554 |
| Mean Loss (10000 random fields) | 0.03479376 |
| Mean Loss using rand-field exceed probs | 0.046590593 |

| ![plot](resources/rup3_asset1_gmpe_dists.png) | ![plot](resources/rup3_asset1_field_losses.png) |
|-----|-----|
| ![plot](resources/rup3_asset1_gmpe_dists_log.png) | ![plot](resources/rup3_asset1_field_losses_log.png) |
| ![plot](resources/rup3_asset1_betweens.png) | ![plot](resources/rup3_asset1_withins.png) |
| ![plot](resources/rup3_asset1_gmpe_exceeds.png) | ![plot](resources/rup3_asset1_cumulative_losses.png) |

### Rupture 215437, Asset2
*[(top)](#table-of-contents)*

Asset parameters:

* value: 127.0
* J-B distance to rupture: 791.8061611004053
* Vulnerability function: RM1L-l-RES1-DF
* GMPE ln mean: -5.00141
* GMPE phi/tau/total std devs: 0.63	0.36	0.7256032

**Loss Values**

| Description | Loss Value |
|-----|-----|
| Mean Loss (GMPE) | 0.0031012553 |
| Mean Loss (10000 random fields) | 9.3472E-4 |
| Mean Loss using rand-field exceed probs | 0.0014266546 |

| ![plot](resources/rup3_asset2_gmpe_dists.png) | ![plot](resources/rup3_asset2_field_losses.png) |
|-----|-----|
| ![plot](resources/rup3_asset2_gmpe_dists_log.png) | ![plot](resources/rup3_asset2_field_losses_log.png) |
| ![plot](resources/rup3_asset2_betweens.png) | ![plot](resources/rup3_asset2_withins.png) |
| ![plot](resources/rup3_asset2_gmpe_exceeds.png) | ![plot](resources/rup3_asset2_cumulative_losses.png) |

### Rupture 215437, Asset3
*[(top)](#table-of-contents)*

Asset parameters:

* value: 8363.0
* J-B distance to rupture: 45.2838460115642
* Vulnerability function: W1-h-RES1-DF
* GMPE ln mean: -1.2025274
* GMPE phi/tau/total std devs: 0.6048769	0.33560073	0.6917398

**Loss Values**

| Description | Loss Value |
|-----|-----|
| Mean Loss (GMPE) | 273.9915 |
| Mean Loss (10000 random fields) | 200.73106 |
| Mean Loss using rand-field exceed probs | 238.69286 |

| ![plot](resources/rup3_asset3_gmpe_dists.png) | ![plot](resources/rup3_asset3_field_losses.png) |
|-----|-----|
| ![plot](resources/rup3_asset3_gmpe_dists_log.png) | ![plot](resources/rup3_asset3_field_losses_log.png) |
| ![plot](resources/rup3_asset3_betweens.png) | ![plot](resources/rup3_asset3_withins.png) |
| ![plot](resources/rup3_asset3_gmpe_exceeds.png) | ![plot](resources/rup3_asset3_cumulative_losses.png) |

### Rupture 215437, Asset4
*[(top)](#table-of-contents)*

Asset parameters:

* value: 26997.0
* J-B distance to rupture: 459.82072382638347
* Vulnerability function: W1-m-RES1-DF
* GMPE ln mean: -3.3911812
* GMPE phi/tau/total std devs: 0.62713397	0.3572519	0.721752

**Loss Values**

| Description | Loss Value |
|-----|-----|
| Mean Loss (GMPE) | 15.539383 |
| Mean Loss (10000 random fields) | 13.277664 |
| Mean Loss using rand-field exceed probs | 17.80588 |

| ![plot](resources/rup3_asset4_gmpe_dists.png) | ![plot](resources/rup3_asset4_field_losses.png) |
|-----|-----|
| ![plot](resources/rup3_asset4_gmpe_dists_log.png) | ![plot](resources/rup3_asset4_field_losses_log.png) |
| ![plot](resources/rup3_asset4_betweens.png) | ![plot](resources/rup3_asset4_withins.png) |
| ![plot](resources/rup3_asset4_gmpe_exceeds.png) | ![plot](resources/rup3_asset4_cumulative_losses.png) |

## Rupture 187237, M7.2455945
*[(top)](#table-of-contents)*

### Rupture 187237, Asset0
*[(top)](#table-of-contents)*

Asset parameters:

* value: 28152.0
* J-B distance to rupture: 220.42899827010416
* Vulnerability function: W1-h-RES1-DF
* GMPE ln mean: -3.4888635
* GMPE phi/tau/total std devs: 0.63	0.36	0.7256032

**Loss Values**

| Description | Loss Value |
|-----|-----|
| Mean Loss (GMPE) | 8.919588 |
| Mean Loss (10000 random fields) | 3.2194626 |
| Mean Loss using rand-field exceed probs | 4.6293383 |

| ![plot](resources/rup4_asset0_gmpe_dists.png) | ![plot](resources/rup4_asset0_field_losses.png) |
|-----|-----|
| ![plot](resources/rup4_asset0_gmpe_dists_log.png) | ![plot](resources/rup4_asset0_field_losses_log.png) |
| ![plot](resources/rup4_asset0_betweens.png) | ![plot](resources/rup4_asset0_withins.png) |
| ![plot](resources/rup4_asset0_gmpe_exceeds.png) | ![plot](resources/rup4_asset0_cumulative_losses.png) |

### Rupture 187237, Asset1
*[(top)](#table-of-contents)*

Asset parameters:

* value: 173.0
* J-B distance to rupture: 459.6791921461773
* Vulnerability function: RM1L-m-RES1-DF
* GMPE ln mean: -4.348357
* GMPE phi/tau/total std devs: 0.62978023	0.3597896	0.725308

**Loss Values**

| Description | Loss Value |
|-----|-----|
| Mean Loss (GMPE) | 0.015267798 |
| Mean Loss (10000 random fields) | 0.0088922 |
| Mean Loss using rand-field exceed probs | 0.01214337 |

| ![plot](resources/rup4_asset1_gmpe_dists.png) | ![plot](resources/rup4_asset1_field_losses.png) |
|-----|-----|
| ![plot](resources/rup4_asset1_gmpe_dists_log.png) | ![plot](resources/rup4_asset1_field_losses_log.png) |
| ![plot](resources/rup4_asset1_betweens.png) | ![plot](resources/rup4_asset1_withins.png) |
| ![plot](resources/rup4_asset1_gmpe_exceeds.png) | ![plot](resources/rup4_asset1_cumulative_losses.png) |

### Rupture 187237, Asset2
*[(top)](#table-of-contents)*

Asset parameters:

* value: 127.0
* J-B distance to rupture: 718.6404783019321
* Vulnerability function: RM1L-l-RES1-DF
* GMPE ln mean: -5.5039325
* GMPE phi/tau/total std devs: 0.63	0.36	0.7256032

**Loss Values**

| Description | Loss Value |
|-----|-----|
| Mean Loss (GMPE) | 5.0171156E-4 |
| Mean Loss (10000 random fields) | 4.445E-5 |
| Mean Loss using rand-field exceed probs | 9.229067E-5 |

| ![plot](resources/rup4_asset2_gmpe_dists.png) | ![plot](resources/rup4_asset2_field_losses.png) |
|-----|-----|
| ![plot](resources/rup4_asset2_gmpe_dists_log.png) | ![plot](resources/rup4_asset2_field_losses_log.png) |
| ![plot](resources/rup4_asset2_betweens.png) | ![plot](resources/rup4_asset2_withins.png) |
| ![plot](resources/rup4_asset2_gmpe_exceeds.png) | ![plot](resources/rup4_asset2_cumulative_losses.png) |

### Rupture 187237, Asset3
*[(top)](#table-of-contents)*

Asset parameters:

* value: 8363.0
* J-B distance to rupture: 25.110251940672537
* Vulnerability function: W1-h-RES1-DF
* GMPE ln mean: -1.1612767
* GMPE phi/tau/total std devs: 0.6038432	0.3345808	0.6903412

**Loss Values**

| Description | Loss Value |
|-----|-----|
| Mean Loss (GMPE) | 290.59494 |
| Mean Loss (10000 random fields) | 275.554 |
| Mean Loss using rand-field exceed probs | 325.67072 |

| ![plot](resources/rup4_asset3_gmpe_dists.png) | ![plot](resources/rup4_asset3_field_losses.png) |
|-----|-----|
| ![plot](resources/rup4_asset3_gmpe_dists_log.png) | ![plot](resources/rup4_asset3_field_losses_log.png) |
| ![plot](resources/rup4_asset3_betweens.png) | ![plot](resources/rup4_asset3_withins.png) |
| ![plot](resources/rup4_asset3_gmpe_exceeds.png) | ![plot](resources/rup4_asset3_cumulative_losses.png) |

### Rupture 187237, Asset4
*[(top)](#table-of-contents)*

Asset parameters:

* value: 26997.0
* J-B distance to rupture: 385.1454560877946
* Vulnerability function: W1-m-RES1-DF
* GMPE ln mean: -3.7677114
* GMPE phi/tau/total std devs: 0.62803197	0.35811388	0.722959

**Loss Values**

| Description | Loss Value |
|-----|-----|
| Mean Loss (GMPE) | 5.9639564 |
| Mean Loss (10000 random fields) | 4.616757 |
| Mean Loss using rand-field exceed probs | 6.1253605 |

| ![plot](resources/rup4_asset4_gmpe_dists.png) | ![plot](resources/rup4_asset4_field_losses.png) |
|-----|-----|
| ![plot](resources/rup4_asset4_gmpe_dists_log.png) | ![plot](resources/rup4_asset4_field_losses_log.png) |
| ![plot](resources/rup4_asset4_betweens.png) | ![plot](resources/rup4_asset4_withins.png) |
| ![plot](resources/rup4_asset4_gmpe_exceeds.png) | ![plot](resources/rup4_asset4_cumulative_losses.png) |

## Rupture 103472, M7.0620694
*[(top)](#table-of-contents)*

### Rupture 103472, Asset0
*[(top)](#table-of-contents)*

Asset parameters:

* value: 28152.0
* J-B distance to rupture: 664.6072172908746
* Vulnerability function: W1-h-RES1-DF
* GMPE ln mean: -5.643721
* GMPE phi/tau/total std devs: 0.63	0.36	0.7256032

**Loss Values**

| Description | Loss Value |
|-----|-----|
| Mean Loss (GMPE) | 0.003335919 |
| Mean Loss (10000 random fields) | 0.0098532 |
| Mean Loss using rand-field exceed probs | 0.0154980915 |

| ![plot](resources/rup5_asset0_gmpe_dists.png) | ![plot](resources/rup5_asset0_field_losses.png) |
|-----|-----|
| ![plot](resources/rup5_asset0_gmpe_dists_log.png) | ![plot](resources/rup5_asset0_field_losses_log.png) |
| ![plot](resources/rup5_asset0_betweens.png) | ![plot](resources/rup5_asset0_withins.png) |
| ![plot](resources/rup5_asset0_gmpe_exceeds.png) | ![plot](resources/rup5_asset0_cumulative_losses.png) |

### Rupture 103472, Asset1
*[(top)](#table-of-contents)*

Asset parameters:

* value: 173.0
* J-B distance to rupture: 17.032477551146595
* Vulnerability function: RM1L-m-RES1-DF
* GMPE ln mean: -1.2694901
* GMPE phi/tau/total std devs: 0.6254843	0.3556662	0.71953386

**Loss Values**

| Description | Loss Value |
|-----|-----|
| Mean Loss (GMPE) | 13.397572 |
| Mean Loss (10000 random fields) | 8.565567 |
| Mean Loss using rand-field exceed probs | 10.657194 |

| ![plot](resources/rup5_asset1_gmpe_dists.png) | ![plot](resources/rup5_asset1_field_losses.png) |
|-----|-----|
| ![plot](resources/rup5_asset1_gmpe_dists_log.png) | ![plot](resources/rup5_asset1_field_losses_log.png) |
| ![plot](resources/rup5_asset1_betweens.png) | ![plot](resources/rup5_asset1_withins.png) |
| ![plot](resources/rup5_asset1_gmpe_exceeds.png) | ![plot](resources/rup5_asset1_cumulative_losses.png) |

### Rupture 103472, Asset2
*[(top)](#table-of-contents)*

Asset parameters:

* value: 127.0
* J-B distance to rupture: 289.6538168599644
* Vulnerability function: RM1L-l-RES1-DF
* GMPE ln mean: -4.1225557
* GMPE phi/tau/total std devs: 0.63	0.36	0.7256032

**Loss Values**

| Description | Loss Value |
|-----|-----|
| Mean Loss (GMPE) | 0.03995349 |
| Mean Loss (10000 random fields) | 0.01744345 |
| Mean Loss using rand-field exceed probs | 0.024071733 |

| ![plot](resources/rup5_asset2_gmpe_dists.png) | ![plot](resources/rup5_asset2_field_losses.png) |
|-----|-----|
| ![plot](resources/rup5_asset2_gmpe_dists_log.png) | ![plot](resources/rup5_asset2_field_losses_log.png) |
| ![plot](resources/rup5_asset2_betweens.png) | ![plot](resources/rup5_asset2_withins.png) |
| ![plot](resources/rup5_asset2_gmpe_exceeds.png) | ![plot](resources/rup5_asset2_cumulative_losses.png) |

### Rupture 103472, Asset3
*[(top)](#table-of-contents)*

Asset parameters:

* value: 8363.0
* J-B distance to rupture: 420.35845775898594
* Vulnerability function: W1-h-RES1-DF
* GMPE ln mean: -4.2131553
* GMPE phi/tau/total std devs: 0.62873876	0.3587917	0.7239088

**Loss Values**

| Description | Loss Value |
|-----|-----|
| Mean Loss (GMPE) | 0.3031265 |
| Mean Loss (10000 random fields) | 0.21250384 |
| Mean Loss using rand-field exceed probs | 0.312053 |

| ![plot](resources/rup5_asset3_gmpe_dists.png) | ![plot](resources/rup5_asset3_field_losses.png) |
|-----|-----|
| ![plot](resources/rup5_asset3_gmpe_dists_log.png) | ![plot](resources/rup5_asset3_field_losses_log.png) |
| ![plot](resources/rup5_asset3_betweens.png) | ![plot](resources/rup5_asset3_withins.png) |
| ![plot](resources/rup5_asset3_gmpe_exceeds.png) | ![plot](resources/rup5_asset3_cumulative_losses.png) |

### Rupture 103472, Asset4
*[(top)](#table-of-contents)*

Asset parameters:

* value: 26997.0
* J-B distance to rupture: 9.884195532220756
* Vulnerability function: W1-m-RES1-DF
* GMPE ln mean: -0.73613816
* GMPE phi/tau/total std devs: 0.5905011	0.32128924	0.6722487

**Loss Values**

| Description | Loss Value |
|-----|-----|
| Mean Loss (GMPE) | 2354.3843 |
| Mean Loss (10000 random fields) | 1724.6952 |
| Mean Loss using rand-field exceed probs | 2060.095 |

| ![plot](resources/rup5_asset4_gmpe_dists.png) | ![plot](resources/rup5_asset4_field_losses.png) |
|-----|-----|
| ![plot](resources/rup5_asset4_gmpe_dists_log.png) | ![plot](resources/rup5_asset4_field_losses_log.png) |
| ![plot](resources/rup5_asset4_betweens.png) | ![plot](resources/rup5_asset4_withins.png) |
| ![plot](resources/rup5_asset4_gmpe_exceeds.png) | ![plot](resources/rup5_asset4_cumulative_losses.png) |

## Rupture 169293, M7.9014773
*[(top)](#table-of-contents)*

### Rupture 169293, Asset0
*[(top)](#table-of-contents)*

Asset parameters:

* value: 28152.0
* J-B distance to rupture: 648.2448111411015
* Vulnerability function: W1-h-RES1-DF
* GMPE ln mean: -4.294038
* GMPE phi/tau/total std devs: 0.63	0.36	0.7256032

**Loss Values**

| Description | Loss Value |
|-----|-----|
| Mean Loss (GMPE) | 0.79277617 |
| Mean Loss (10000 random fields) | 0.30629376 |
| Mean Loss using rand-field exceed probs | 0.4633882 |

| ![plot](resources/rup6_asset0_gmpe_dists.png) | ![plot](resources/rup6_asset0_field_losses.png) |
|-----|-----|
| ![plot](resources/rup6_asset0_gmpe_dists_log.png) | ![plot](resources/rup6_asset0_field_losses_log.png) |
| ![plot](resources/rup6_asset0_betweens.png) | ![plot](resources/rup6_asset0_withins.png) |
| ![plot](resources/rup6_asset0_gmpe_exceeds.png) | ![plot](resources/rup6_asset0_cumulative_losses.png) |

### Rupture 169293, Asset1
*[(top)](#table-of-contents)*

Asset parameters:

* value: 173.0
* J-B distance to rupture: 14.01186694590594
* Vulnerability function: RM1L-m-RES1-DF
* GMPE ln mean: -0.72076213
* GMPE phi/tau/total std devs: 0.6225097	0.35279965	0.7155319

**Loss Values**

| Description | Loss Value |
|-----|-----|
| Mean Loss (GMPE) | 30.584162 |
| Mean Loss (10000 random fields) | 24.186916 |
| Mean Loss using rand-field exceed probs | 28.538744 |

| ![plot](resources/rup6_asset1_gmpe_dists.png) | ![plot](resources/rup6_asset1_field_losses.png) |
|-----|-----|
| ![plot](resources/rup6_asset1_gmpe_dists_log.png) | ![plot](resources/rup6_asset1_field_losses_log.png) |
| ![plot](resources/rup6_asset1_betweens.png) | ![plot](resources/rup6_asset1_withins.png) |
| ![plot](resources/rup6_asset1_gmpe_exceeds.png) | ![plot](resources/rup6_asset1_cumulative_losses.png) |

### Rupture 169293, Asset2
*[(top)](#table-of-contents)*

Asset parameters:

* value: 127.0
* J-B distance to rupture: 159.32030510236777
* Vulnerability function: RM1L-l-RES1-DF
* GMPE ln mean: -2.407653
* GMPE phi/tau/total std devs: 0.63	0.36	0.7256032

**Loss Values**

| Description | Loss Value |
|-----|-----|
| Mean Loss (GMPE) | 2.2303557 |
| Mean Loss (10000 random fields) | 1.4298079 |
| Mean Loss using rand-field exceed probs | 1.8411473 |

| ![plot](resources/rup6_asset2_gmpe_dists.png) | ![plot](resources/rup6_asset2_field_losses.png) |
|-----|-----|
| ![plot](resources/rup6_asset2_gmpe_dists_log.png) | ![plot](resources/rup6_asset2_field_losses_log.png) |
| ![plot](resources/rup6_asset2_betweens.png) | ![plot](resources/rup6_asset2_withins.png) |
| ![plot](resources/rup6_asset2_gmpe_exceeds.png) | ![plot](resources/rup6_asset2_cumulative_losses.png) |

### Rupture 169293, Asset3
*[(top)](#table-of-contents)*

Asset parameters:

* value: 8363.0
* J-B distance to rupture: 401.91212262700554
* Vulnerability function: W1-h-RES1-DF
* GMPE ln mean: -2.9629278
* GMPE phi/tau/total std devs: 0.6256067	0.35578397	0.71969855

**Loss Values**

| Description | Loss Value |
|-----|-----|
| Mean Loss (GMPE) | 10.055348 |
| Mean Loss (10000 random fields) | 7.8979335 |
| Mean Loss using rand-field exceed probs | 10.539781 |

| ![plot](resources/rup6_asset3_gmpe_dists.png) | ![plot](resources/rup6_asset3_field_losses.png) |
|-----|-----|
| ![plot](resources/rup6_asset3_gmpe_dists_log.png) | ![plot](resources/rup6_asset3_field_losses_log.png) |
| ![plot](resources/rup6_asset3_betweens.png) | ![plot](resources/rup6_asset3_withins.png) |
| ![plot](resources/rup6_asset3_gmpe_exceeds.png) | ![plot](resources/rup6_asset3_cumulative_losses.png) |

### Rupture 169293, Asset4
*[(top)](#table-of-contents)*

Asset parameters:

* value: 26997.0
* J-B distance to rupture: 19.491645292353013
* Vulnerability function: W1-m-RES1-DF
* GMPE ln mean: -0.69447255
* GMPE phi/tau/total std devs: 0.58889043	0.31966794	0.6700594

**Loss Values**

| Description | Loss Value |
|-----|-----|
| Mean Loss (GMPE) | 2497.9104 |
| Mean Loss (10000 random fields) | 1971.3838 |
| Mean Loss using rand-field exceed probs | 2348.4858 |

| ![plot](resources/rup6_asset4_gmpe_dists.png) | ![plot](resources/rup6_asset4_field_losses.png) |
|-----|-----|
| ![plot](resources/rup6_asset4_gmpe_dists_log.png) | ![plot](resources/rup6_asset4_field_losses_log.png) |
| ![plot](resources/rup6_asset4_betweens.png) | ![plot](resources/rup6_asset4_withins.png) |
| ![plot](resources/rup6_asset4_gmpe_exceeds.png) | ![plot](resources/rup6_asset4_cumulative_losses.png) |

## Rupture 208188, M8.023331
*[(top)](#table-of-contents)*

### Rupture 208188, Asset0
*[(top)](#table-of-contents)*

Asset parameters:

* value: 28152.0
* J-B distance to rupture: 588.4067333863293
* Vulnerability function: W1-h-RES1-DF
* GMPE ln mean: -3.9149275
* GMPE phi/tau/total std devs: 0.63	0.36	0.7256032

**Loss Values**

| Description | Loss Value |
|-----|-----|
| Mean Loss (GMPE) | 2.619622 |
| Mean Loss (10000 random fields) | 0.9022716 |
| Mean Loss using rand-field exceed probs | 1.3445386 |

| ![plot](resources/rup7_asset0_gmpe_dists.png) | ![plot](resources/rup7_asset0_field_losses.png) |
|-----|-----|
| ![plot](resources/rup7_asset0_gmpe_dists_log.png) | ![plot](resources/rup7_asset0_field_losses_log.png) |
| ![plot](resources/rup7_asset0_betweens.png) | ![plot](resources/rup7_asset0_withins.png) |
| ![plot](resources/rup7_asset0_gmpe_exceeds.png) | ![plot](resources/rup7_asset0_cumulative_losses.png) |

### Rupture 208188, Asset1
*[(top)](#table-of-contents)*

Asset parameters:

* value: 173.0
* J-B distance to rupture: 18.002001580033287
* Vulnerability function: RM1L-m-RES1-DF
* GMPE ln mean: -0.7712426
* GMPE phi/tau/total std devs: 0.62284297	0.3531213	0.71598047

**Loss Values**

| Description | Loss Value |
|-----|-----|
| Mean Loss (GMPE) | 28.58227 |
| Mean Loss (10000 random fields) | 23.961042 |
| Mean Loss using rand-field exceed probs | 28.175797 |

| ![plot](resources/rup7_asset1_gmpe_dists.png) | ![plot](resources/rup7_asset1_field_losses.png) |
|-----|-----|
| ![plot](resources/rup7_asset1_gmpe_dists_log.png) | ![plot](resources/rup7_asset1_field_losses_log.png) |
| ![plot](resources/rup7_asset1_betweens.png) | ![plot](resources/rup7_asset1_withins.png) |
| ![plot](resources/rup7_asset1_gmpe_exceeds.png) | ![plot](resources/rup7_asset1_cumulative_losses.png) |

### Rupture 208188, Asset2
*[(top)](#table-of-contents)*

Asset parameters:

* value: 127.0
* J-B distance to rupture: 159.32030510236777
* Vulnerability function: RM1L-l-RES1-DF
* GMPE ln mean: -2.2673786
* GMPE phi/tau/total std devs: 0.63	0.36	0.7256032

**Loss Values**

| Description | Loss Value |
|-----|-----|
| Mean Loss (GMPE) | 3.008714 |
| Mean Loss (10000 random fields) | 1.8121287 |
| Mean Loss using rand-field exceed probs | 2.3613558 |

| ![plot](resources/rup7_asset2_gmpe_dists.png) | ![plot](resources/rup7_asset2_field_losses.png) |
|-----|-----|
| ![plot](resources/rup7_asset2_gmpe_dists_log.png) | ![plot](resources/rup7_asset2_field_losses_log.png) |
| ![plot](resources/rup7_asset2_betweens.png) | ![plot](resources/rup7_asset2_withins.png) |
| ![plot](resources/rup7_asset2_gmpe_exceeds.png) | ![plot](resources/rup7_asset2_cumulative_losses.png) |

### Rupture 208188, Asset3
*[(top)](#table-of-contents)*

Asset parameters:

* value: 8363.0
* J-B distance to rupture: 339.4894788682204
* Vulnerability function: W1-h-RES1-DF
* GMPE ln mean: -2.567874
* GMPE phi/tau/total std devs: 0.62348837	0.35374385	0.71684897

**Loss Values**

| Description | Loss Value |
|-----|-----|
| Mean Loss (GMPE) | 24.741194 |
| Mean Loss (10000 random fields) | 14.997117 |
| Mean Loss using rand-field exceed probs | 19.933731 |

| ![plot](resources/rup7_asset3_gmpe_dists.png) | ![plot](resources/rup7_asset3_field_losses.png) |
|-----|-----|
| ![plot](resources/rup7_asset3_gmpe_dists_log.png) | ![plot](resources/rup7_asset3_field_losses_log.png) |
| ![plot](resources/rup7_asset3_betweens.png) | ![plot](resources/rup7_asset3_withins.png) |
| ![plot](resources/rup7_asset3_gmpe_exceeds.png) | ![plot](resources/rup7_asset3_cumulative_losses.png) |

### Rupture 208188, Asset4
*[(top)](#table-of-contents)*

Asset parameters:

* value: 26997.0
* J-B distance to rupture: 44.011872161271796
* Vulnerability function: W1-m-RES1-DF
* GMPE ln mean: -1.0012978
* GMPE phi/tau/total std devs: 0.59943056	0.33021143	0.6843658

**Loss Values**

| Description | Loss Value |
|-----|-----|
| Mean Loss (GMPE) | 1600.1274 |
| Mean Loss (10000 random fields) | 1276.2166 |
| Mean Loss using rand-field exceed probs | 1526.6885 |

| ![plot](resources/rup7_asset4_gmpe_dists.png) | ![plot](resources/rup7_asset4_field_losses.png) |
|-----|-----|
| ![plot](resources/rup7_asset4_gmpe_dists_log.png) | ![plot](resources/rup7_asset4_field_losses_log.png) |
| ![plot](resources/rup7_asset4_betweens.png) | ![plot](resources/rup7_asset4_withins.png) |
| ![plot](resources/rup7_asset4_gmpe_exceeds.png) | ![plot](resources/rup7_asset4_cumulative_losses.png) |

## Rupture 68673, M8.155491
*[(top)](#table-of-contents)*

### Rupture 68673, Asset0
*[(top)](#table-of-contents)*

Asset parameters:

* value: 28152.0
* J-B distance to rupture: 104.41240790207684
* Vulnerability function: W1-h-RES1-DF
* GMPE ln mean: -1.8111215
* GMPE phi/tau/total std devs: 0.63	0.36	0.7256032

**Loss Values**

| Description | Loss Value |
|-----|-----|
| Mean Loss (GMPE) | 368.84094 |
| Mean Loss (10000 random fields) | 260.4626 |
| Mean Loss using rand-field exceed probs | 321.75323 |

| ![plot](resources/rup8_asset0_gmpe_dists.png) | ![plot](resources/rup8_asset0_field_losses.png) |
|-----|-----|
| ![plot](resources/rup8_asset0_gmpe_dists_log.png) | ![plot](resources/rup8_asset0_field_losses_log.png) |
| ![plot](resources/rup8_asset0_betweens.png) | ![plot](resources/rup8_asset0_withins.png) |
| ![plot](resources/rup8_asset0_gmpe_exceeds.png) | ![plot](resources/rup8_asset0_cumulative_losses.png) |

### Rupture 68673, Asset1
*[(top)](#table-of-contents)*

Asset parameters:

* value: 173.0
* J-B distance to rupture: 91.13746388295239
* Vulnerability function: RM1L-m-RES1-DF
* GMPE ln mean: -1.5158098
* GMPE phi/tau/total std devs: 0.62642473	0.35657054	0.7207985

**Loss Values**

| Description | Loss Value |
|-----|-----|
| Mean Loss (GMPE) | 8.7348995 |
| Mean Loss (10000 random fields) | 5.273808 |
| Mean Loss using rand-field exceed probs | 6.635301 |

| ![plot](resources/rup8_asset1_gmpe_dists.png) | ![plot](resources/rup8_asset1_field_losses.png) |
|-----|-----|
| ![plot](resources/rup8_asset1_gmpe_dists_log.png) | ![plot](resources/rup8_asset1_field_losses_log.png) |
| ![plot](resources/rup8_asset1_betweens.png) | ![plot](resources/rup8_asset1_withins.png) |
| ![plot](resources/rup8_asset1_gmpe_exceeds.png) | ![plot](resources/rup8_asset1_cumulative_losses.png) |

### Rupture 68673, Asset2
*[(top)](#table-of-contents)*

Asset parameters:

* value: 127.0
* J-B distance to rupture: 387.0487389473328
* Vulnerability function: RM1L-l-RES1-DF
* GMPE ln mean: -3.0460186
* GMPE phi/tau/total std devs: 0.63	0.36	0.7256032

**Loss Values**

| Description | Loss Value |
|-----|-----|
| Mean Loss (GMPE) | 0.5317186 |
| Mean Loss (10000 random fields) | 0.5081029 |
| Mean Loss using rand-field exceed probs | 0.669143 |

| ![plot](resources/rup8_asset2_gmpe_dists.png) | ![plot](resources/rup8_asset2_field_losses.png) |
|-----|-----|
| ![plot](resources/rup8_asset2_gmpe_dists_log.png) | ![plot](resources/rup8_asset2_field_losses_log.png) |
| ![plot](resources/rup8_asset2_betweens.png) | ![plot](resources/rup8_asset2_withins.png) |
| ![plot](resources/rup8_asset2_gmpe_exceeds.png) | ![plot](resources/rup8_asset2_cumulative_losses.png) |

### Rupture 68673, Asset3
*[(top)](#table-of-contents)*

Asset parameters:

* value: 8363.0
* J-B distance to rupture: 67.7434958702235
* Vulnerability function: W1-h-RES1-DF
* GMPE ln mean: -1.12117
* GMPE phi/tau/total std devs: 0.6027987	0.3335488	0.6889275

**Loss Values**

| Description | Loss Value |
|-----|-----|
| Mean Loss (GMPE) | 307.53253 |
| Mean Loss (10000 random fields) | 263.6408 |
| Mean Loss using rand-field exceed probs | 311.04025 |

| ![plot](resources/rup8_asset3_gmpe_dists.png) | ![plot](resources/rup8_asset3_field_losses.png) |
|-----|-----|
| ![plot](resources/rup8_asset3_gmpe_dists_log.png) | ![plot](resources/rup8_asset3_field_losses_log.png) |
| ![plot](resources/rup8_asset3_betweens.png) | ![plot](resources/rup8_asset3_withins.png) |
| ![plot](resources/rup8_asset3_gmpe_exceeds.png) | ![plot](resources/rup8_asset3_cumulative_losses.png) |

### Rupture 68673, Asset4
*[(top)](#table-of-contents)*

Asset parameters:

* value: 26997.0
* J-B distance to rupture: 23.249264023399178
* Vulnerability function: W1-m-RES1-DF
* GMPE ln mean: -0.63563156
* GMPE phi/tau/total std devs: 0.58651066	0.31726542	0.66682243

**Loss Values**

| Description | Loss Value |
|-----|-----|
| Mean Loss (GMPE) | 2713.6802 |
| Mean Loss (10000 random fields) | 2186.4678 |
| Mean Loss using rand-field exceed probs | 2598.0842 |

| ![plot](resources/rup8_asset4_gmpe_dists.png) | ![plot](resources/rup8_asset4_field_losses.png) |
|-----|-----|
| ![plot](resources/rup8_asset4_gmpe_dists_log.png) | ![plot](resources/rup8_asset4_field_losses_log.png) |
| ![plot](resources/rup8_asset4_betweens.png) | ![plot](resources/rup8_asset4_withins.png) |
| ![plot](resources/rup8_asset4_gmpe_exceeds.png) | ![plot](resources/rup8_asset4_cumulative_losses.png) |

## Rupture 42699, M7.9970284
*[(top)](#table-of-contents)*

### Rupture 42699, Asset0
*[(top)](#table-of-contents)*

Asset parameters:

* value: 28152.0
* J-B distance to rupture: 498.8670034348614
* Vulnerability function: W1-h-RES1-DF
* GMPE ln mean: -3.6463103
* GMPE phi/tau/total std devs: 0.63	0.36	0.7256032

**Loss Values**

| Description | Loss Value |
|-----|-----|
| Mean Loss (GMPE) | 5.7483997 |
| Mean Loss (10000 random fields) | 3.0502691 |
| Mean Loss using rand-field exceed probs | 4.3745856 |

| ![plot](resources/rup9_asset0_gmpe_dists.png) | ![plot](resources/rup9_asset0_field_losses.png) |
|-----|-----|
| ![plot](resources/rup9_asset0_gmpe_dists_log.png) | ![plot](resources/rup9_asset0_field_losses_log.png) |
| ![plot](resources/rup9_asset0_betweens.png) | ![plot](resources/rup9_asset0_withins.png) |
| ![plot](resources/rup9_asset0_gmpe_exceeds.png) | ![plot](resources/rup9_asset0_cumulative_losses.png) |

### Rupture 42699, Asset1
*[(top)](#table-of-contents)*

Asset parameters:

* value: 173.0
* J-B distance to rupture: 18.002001580033287
* Vulnerability function: RM1L-m-RES1-DF
* GMPE ln mean: -0.77516687
* GMPE phi/tau/total std devs: 0.62286836	0.35314578	0.7160146

**Loss Values**

| Description | Loss Value |
|-----|-----|
| Mean Loss (GMPE) | 28.430164 |
| Mean Loss (10000 random fields) | 22.265873 |
| Mean Loss using rand-field exceed probs | 26.322815 |

| ![plot](resources/rup9_asset1_gmpe_dists.png) | ![plot](resources/rup9_asset1_field_losses.png) |
|-----|-----|
| ![plot](resources/rup9_asset1_gmpe_dists_log.png) | ![plot](resources/rup9_asset1_field_losses_log.png) |
| ![plot](resources/rup9_asset1_betweens.png) | ![plot](resources/rup9_asset1_withins.png) |
| ![plot](resources/rup9_asset1_gmpe_exceeds.png) | ![plot](resources/rup9_asset1_cumulative_losses.png) |

### Rupture 42699, Asset2
*[(top)](#table-of-contents)*

Asset parameters:

* value: 127.0
* J-B distance to rupture: 159.32030510236777
* Vulnerability function: RM1L-l-RES1-DF
* GMPE ln mean: -2.2869341
* GMPE phi/tau/total std devs: 0.63	0.36	0.7256032

**Loss Values**

| Description | Loss Value |
|-----|-----|
| Mean Loss (GMPE) | 2.8872013 |
| Mean Loss (10000 random fields) | 1.7341951 |
| Mean Loss using rand-field exceed probs | 2.269448 |

| ![plot](resources/rup9_asset2_gmpe_dists.png) | ![plot](resources/rup9_asset2_field_losses.png) |
|-----|-----|
| ![plot](resources/rup9_asset2_gmpe_dists_log.png) | ![plot](resources/rup9_asset2_field_losses_log.png) |
| ![plot](resources/rup9_asset2_betweens.png) | ![plot](resources/rup9_asset2_withins.png) |
| ![plot](resources/rup9_asset2_gmpe_exceeds.png) | ![plot](resources/rup9_asset2_cumulative_losses.png) |

### Rupture 42699, Asset3
*[(top)](#table-of-contents)*

Asset parameters:

* value: 8363.0
* J-B distance to rupture: 253.60115106692265
* Vulnerability function: W1-h-RES1-DF
* GMPE ln mean: -2.2545636
* GMPE phi/tau/total std devs: 0.6211083	0.35144582	0.71364534

**Loss Values**

| Description | Loss Value |
|-----|-----|
| Mean Loss (GMPE) | 47.11329 |
| Mean Loss (10000 random fields) | 39.952812 |
| Mean Loss using rand-field exceed probs | 50.80125 |

| ![plot](resources/rup9_asset3_gmpe_dists.png) | ![plot](resources/rup9_asset3_field_losses.png) |
|-----|-----|
| ![plot](resources/rup9_asset3_gmpe_dists_log.png) | ![plot](resources/rup9_asset3_field_losses_log.png) |
| ![plot](resources/rup9_asset3_betweens.png) | ![plot](resources/rup9_asset3_withins.png) |
| ![plot](resources/rup9_asset3_gmpe_exceeds.png) | ![plot](resources/rup9_asset3_cumulative_losses.png) |

### Rupture 42699, Asset4
*[(top)](#table-of-contents)*

Asset parameters:

* value: 26997.0
* J-B distance to rupture: 19.491645292353013
* Vulnerability function: W1-m-RES1-DF
* GMPE ln mean: -0.6359203
* GMPE phi/tau/total std devs: 0.58652264	0.31727752	0.6668387

**Loss Values**

| Description | Loss Value |
|-----|-----|
| Mean Loss (GMPE) | 2712.5828 |
| Mean Loss (10000 random fields) | 2334.1948 |
| Mean Loss using rand-field exceed probs | 2751.964 |

| ![plot](resources/rup9_asset4_gmpe_dists.png) | ![plot](resources/rup9_asset4_field_losses.png) |
|-----|-----|
| ![plot](resources/rup9_asset4_gmpe_dists_log.png) | ![plot](resources/rup9_asset4_field_losses_log.png) |
| ![plot](resources/rup9_asset4_betweens.png) | ![plot](resources/rup9_asset4_withins.png) |
| ![plot](resources/rup9_asset4_gmpe_exceeds.png) | ![plot](resources/rup9_asset4_cumulative_losses.png) |

