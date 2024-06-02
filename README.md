"# HCSA for-solving-the-Minimum-Dominating-Set-Problem" 

![Cuckoo Guira cantara](https://fr.wikipedia.org/wiki/Guira_cantara#/media/Fichier:Guira_guira.jpg)

## Introduction
This repository contains source code for (HCSA-MDS) and analyzing its results.

## Requirements
- Python 3.10 ++ or pypy3.* 
- Required Python packages numpy, matplotlib, networkx

## Algorithm Execution
-To run the algorithm, execute the `HCSA-MDS.py` script with the appropriate dataset number:

python HCSA-MDS.py [dataset_number]

Replace [dataset_number] with:

-1 for the first dataset
-2 for the second dataset

For faster execution, consider using the PyPy interpreter.

##Statistical Analysis
-After completing the algorithm execution, you can analyze the results using the statistics.py script. Run it with the dataset name:

python statistics.py [dataset_name]

Replace [dataset_name] with:

-first for the first dataset
-second for the second dataset

#Wilcoxon Signed-Rank Test and SPSS Analysis
-To conduct the Wilcoxon signed-rank test, update the data as needed and run your preferred statistical analysis tool (e.g., SPSS) on the dataset.

#Citation
-If you use the data or find the article useful, please cite:
```code
@article{too2021spatial,
  title={A-hybrid-population-based-algorithm-for-solving-the-Minimum-Dominating-Set-Problem},
  author={Belkacem, Zouilekh and Sadek, Bouroubi },
  journal={croatian operational research review},
}