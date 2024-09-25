README

This folder contains files related to the portfolio optimization analysis, including data files with asset returns, the research paper, and accompanying code. Below is a detailed description of the folder contents:

Main Files
1. Gabriele_Rosso_Paper.pdf
   - A PDF document containing the research paper authored by Francesco Gabriele and Thomas Rosso. The paper discusses the application of various optimization algorithms, such as the Frank-Wolfe algorithm and its variants, in solving portfolio optimization problems using real-world data.

2. Gabriele_Rosso_Code.ipynb
   - A Jupyter Notebook file that contains the code used for the analysis presented in the research paper. The notebook includes implementations of the optimization algorithms and visualizations of the results.

Data Folder
- /data
  - This folder contains the datasets used for the portfolio optimization analysis. Each file in this folder represents weekly linear returns of assets from different indices. Below is a description of each file:

    1. RR_Ftse100.txt
       - A text file containing a matrix where each column represents the weekly linear returns of each asset in the FTSE 100 index.

    2. RR_FtseMib.txt
       - A text file containing a matrix where each column represents the weekly linear returns of each asset in the FTSE MIB index.

    3. RR_Stoxx50.txt
       - A text file containing a matrix where each column represents the weekly linear returns of each asset in the EURO STOXX 50 index.

Each data file is formatted as a matrix, with rows corresponding to time periods (weeks) and columns corresponding to different assets. These files are used as inputs for the portfolio optimization algorithms explored in the accompanying code and research paper.

