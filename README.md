# Euromelanoma Analysis Repository

This repository contains the code, data, and derived outputs associated with the manuscript:

**[Insert paper title here]**

The aim of this repository is to ensure transparency and reproducibility of the analyses performed on the Hungarian *Euromelanoma* screening questionnaire data.

---

## Repository structure


---

## Contents

### `script/`
- Contains R Markdown (`.Rmd`) scripts for all analyses included in the publication.  
- Each script specifies the required R packages at the beginning.  

### `data/`
- Raw data files from the Hungarian Euromelanoma screening questionnaires.  
- These files are provided as originally collected, without preprocessing.  

### `common_objects/`
- Preprocessed and filtered data saved as `.rds` objects.  
- These objects serve as the input for analyses in `script/`.  

### `plots/`
- Collection of individual plots generated during the analysis.  
- Composite figures in the publication were created from these individual plots.  

---

## Reproducibility

All analyses can be reproduced by running the `.Rmd` scripts in the `script/` folder.  
- The required R packages are explicitly listed at the top of each script.  
- Raw data are provided in `data/`.  
- Preprocessed `.rds` objects are in `common_objects/` for direct use.  

---

## Citation

If you use this repository, please cite:

**[Insert citation of your paper once published]**

---

## License

[Waining for answer from Bussels]

---

## Contact

For questions about this repository, please contact:  
**[Benjamin Tamás Papp M.D.]**  
[HUN-REN Biological Research Centre, Szeged, Hungary]  
[papp.benjamin@brc.com]
