# Quantitative evaluation of gender bias in astronomical publications from citation counts


This repository contains the data and the random forest algorithm from the paper. Arxiv version of the paper is available  (`Caplar_Tacchella_Birrer_Quantitative-evaluation-gender.pdf`). Note that the Arxiv version differs from the published version in Nature Astronomy in style and the amount of content, as Nature Astronomy asked for more succinct version of the findings.

## Contents

`Data_Gender_Bias_In_Astronomy.csv` = dataset in *.csv form, columns as in Table 1A and 1B in the manuscript

`dataCleanedWithCountryAndRankingSuperCleanedSandro` = cleaned dataset used in the analysis. Import in Wolfram Mathematica by navigating to the directory of the data and simply using Get["dataMathematicaForm"]. Columns are:

1. paper id,
2. name as it appears in the publication, 
3. full name, deduced from the whole database, 
4. last name,
5. sex, 
6. year of first publication, 
7. number of citations, 
8. number of references, 
9. number of authors, 
10. institution, 
11. year of publication, 
12. journal,
13. field (1-6, see Table 1 from the paper), 
14. number of floats in the manuscript, 
15. number of equations in the manuscript,
16. number of math inline in the manuscript, 
17. number of words in the manuscript, 
18. id of first paper by the same author

`Random_Forest` = folder with random forest algorithm. Inside this folder you can find:
* `Gender_Random_Forest.ipynb` = ipython routine which does the main part of the analysis
* `Gender_Random_Forest_Visualization.nb` = Wolfram Mathematica notebook to visualize the results
* `maleset`, `femaleset`, `Male_Train`, `Male_Test`, `Female` = auxiliary files from the analysis and visualization parts of the algorithm
	
	


## Help

For problems with using the code or installation use GitHub issues page or send us an [email](mailto:ncaplar@princeton.edu).

