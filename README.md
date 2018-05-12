## Supplementary Information

Repository that contain the main data and scripts to recompute the figures from: 

**De Anda V**, Zapata Peñasco I, Blaz J, Poot-Hernandez AC, Contreras Moreira B, Gonzales Laffite Marcos, Hernandez Rosales M, Gamez Tamariz N, Eguiarte Fruns E, Souza V. **Understanding the mechanisms behind the response of environmental perturbations in microbial mats: a metagenomic-network based approach.** Submitted in Frontiers in Microbiology.

To reproduce the figures first install [jupyter notebook](http://jupyter.org/install.html) and then clone the repository.  

```bash
git clone https://github.com/valdeanda/Time_series_mats.git
cd scripts 
ipython3 notebook 
```

### `Libraries version`
In order to reproduce all the figures using the notebooks, the following libraries must be installed first 

`Python libraries`
+ Pandas version ==> 0.20.3 
+ Numpy ==> 1.13.3
+ Seaborn ==> 0.8.0
+ Plt ==> 1.13.3
+ Matplotlib ==> 2.02

`R packages`
+ Phyloseq
+ ggplot2
+ vegan 
+ pvclust
+ devtools 
+ fpc


###  Figures
---

### `Main cycles with MEBS over time`


<img src="https://valdeanda.github.io/Time_series_mats/figures/MEBS_mats.png" width="200" height="150" align="right">

Script available in  [notebook](https://github.com/valdeanda/Time_series_mats/blob/master/scripts/MebsInTime.ipynb) format. 


```bash
ipython3 notebook MebsInTime.ipynb
```

---

### `Barplot composition and logaritmic scale`

<img src="https://valdeanda.github.io/Time_series_mats/figures/Barplot.png" width="200" height="150" align="right">

Script available in [notebook](https://github.com/valdeanda/Time_series_mats/blob/master/scripts/Bar_plots_composition.ipynb) format

Run the notebook 

```bash
ipython3 notebook Bar_plots_composition.ipynb
```
---


### `Microbial mat core`

Using [get_homologues](https://github.com/eead-csic-compbio/get_homologues)

<img src="https://valdeanda.github.io/Time_series_mats/figures/Mats_core.png" width="200" height="150" align="right">

Script available in  [notebook](https://github.com/valdeanda/Time_series_mats/blob/master/scripts/Core_bacteria.ipynb) format. 

Run the notebook 

```bash
ipython3 notebook Core_bacteria.ipynb
```

---


### `Biogeochemical cycles and Sulfur completeness`

<img src="https://valdeanda.github.io/Time_series_mats/figures/Heatmap.cycles.uv.png" width="200" height="140" align="right">

Script available in  [notebook](https://github.com/valdeanda/Time_series_mats/blob/master/scripts/Pfams_completeness.ipynb) format.
Run the notebook

```bash
ipython3 notebook Pfams_completeness.ipynb
```

---

### `Network motifs`

<img src="https://valdeanda.github.io/Time_series_mats/figures/motifs.png" width="200" height="150" align="right">

Script available in [notebook](https://github.com/valdeanda/Time_series_mats/blob/master/scripts/Motifs.ipynb) format.
Run the notebook

```bash
ipython3 notebook Motifs.ipynb
```
---
### `Networks`

<img src="https://valdeanda.github.io/Time_series_mats/figures/networkA",  width="200" height="150" align="right">

The script  is available in [R](https://github.com/valdeanda/Time_series_mats/blob/master/scripts/finalToPlot.R)


---
