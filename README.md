# Epigenomic heterogeneity and spatial organization during human reprogramming

Code used to generate the figures for:

> **Epigenomic heterogeneity and spatial organization during human reprogramming**
>
> Terence W. Li<sup>1,2,3,\*</sup>, Justin Langerman<sup>4,\*</sup>, Cuining Liu<sup>1,3,\*</sup>, Yu Sun<sup>4,\*</sup>, Mohammad S. Baig<sup>1,5</sup>, Gianna Kim<sup>1</sup>, Jingyuan Fu<sup>4,6</sup>, Rayyan Irfan Ghoor<sup>1</sup>, Yi Zhang<sup>1</sup>, Zach Von Behren<sup>1</sup>, Min Jen Tsai<sup>1</sup>, Malina Elena Cantemir<sup>1</sup>, Kevin D. Abuhanna<sup>1,5</sup>, Edward Chen<sup>1</sup>, Jon Paino<sup>6</sup>, Gideon Shaked<sup>4</sup>, Lily Zhao<sup>4</sup>, Lisa Barooah<sup>4</sup>, Amy Sun<sup>4</sup>, Andrea Garcia Angulo<sup>4</sup>, Alexander Lee<sup>4</sup>, Sophia Peavy<sup>4</sup>, Eleazar Eskin<sup>1,2,6</sup>, Noah Zaitlen<sup>1,2,7</sup>, Brunilda Balliu<sup>2,8,9,†</sup>, Jason Ernst<sup>2,4,6,†</sup>, Chongyuan Luo<sup>1,†</sup>, Kathrin Plath<sup>4,†</sup>
>
> <sup>\*</sup> Equal contribution &nbsp;·&nbsp; <sup>†</sup> Corresponding authors
>
> <!-- TODO: add paper link --> *Link forthcoming.*

## Data

All data are publicly available from the [IGVF Data Portal](https://data.igvf.org).
See the [project page](https://ucla-igvf-pgp-reprogramming.pages.dev/) for how the data are organized.

## Contents

Each notebook in [`ipynb/`](ipynb) reproduces the panels of one figure, in paper order. Panels are labeled with a markdown header (e.g. `### C: ...`) and rendered below their code. Panels not generated in R (schematics, genome browser views) are not included.

| Figure | Notebook |
|---|---|
| Figure 1 | [`Figure_1.ipynb`](ipynb/Figure_1.ipynb) |
| Figure 2 | [`Figure_2.ipynb`](ipynb/Figure_2.ipynb) |
| Figure 3 | [`Figure_3.ipynb`](ipynb/Figure_3.ipynb) |
| Figure 4 | [`Figure_4.ipynb`](ipynb/Figure_4.ipynb) |
| Figure 6 | [`Figure_6.ipynb`](ipynb/Figure_6.ipynb) |
| Figure S1 | [`Figure_S1.ipynb`](ipynb/Figure_S1.ipynb) |
| Figure S2 | [`Figure_S2.ipynb`](ipynb/Figure_S2.ipynb) |
| Figure S3 | [`Figure_S3.ipynb`](ipynb/Figure_S3.ipynb) |
| Figure S4 | [`Figure_S4.ipynb`](ipynb/Figure_S4.ipynb) |
| Figure S5 | [`Figure_S5.ipynb`](ipynb/Figure_S5.ipynb) |
| Figure S6 | [`Figure_S6.ipynb`](ipynb/Figure_S6.ipynb) |
| Figure S7 | [`Figure_S7.ipynb`](ipynb/Figure_S7.ipynb) |
| Figure S8 | [`Figure_S8.ipynb`](ipynb/Figure_S8.ipynb) |
| Figure S10 | [`Figure_S10.ipynb`](ipynb/Figure_S10.ipynb) |

Notebooks use an R 4.1.0 kernel (ggplot2, ComplexHeatmap, data.table, cowplot, ggrastr); each ends with `sessionInfo()` listing exact package versions.
