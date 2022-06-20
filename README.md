# AnalyticalDataCSVs

For plots: All CSV files pertaining to each sensitivity study are under the files titled "Compare" as well as the Jupyter Notebook used to generate all those plots.

IMPORTANT CSV Note: When examining the data CSV files, the row number will in almost all cases correspond to the number of perforations. For example, the CSV file used for the Exit Perforations study has 100 rows, because the number of perforations was varied from 1 to 100. Making the first row correspond to 1 perforation and the last row corresponding to 100 perforations.  All CSV files should have headers in the first row that explain what each column is.

The only case where the row number is not associated with number of perforations is in the "CompareNumberOfFracturesandPerfs" folder. All CSVs titled "FRACTUREstorage#" have rows that correspond to the number of fracture zones. For example, row 1 of "FRACTUREstorage5.CSV" corresponds to 1 fracture zone, while row 30 corresponds to 30 fracture zones. The CSV file titled "1Pressuredrop.CSV" in the same "CompareNumberOfFracturesandPerfs" folder has row numbers that correspond to number of perforations, just like all the other CSV files.

NAMING CSVs Note: All data storage CSVs have a number associated to them, for example "storage5". The number corresponds to the Flowrate used during that run of the study, so 5 kg/s for "storage5".

For generating CSV files used in plots: All jupyter notebooks and required input CSV files are under the files titled "RunSensitivityStudies", these will generate the CSV files used in each sensitivity study plot.

NOTE: Make sure to read the notes left in the jupyter notebooks for running the sensitivity studies, the files titled "RunSensitivityStudies". These notes are critical to run the sensitivity studies correctly and will be easy to see with an all CAPS "NOTE:" in the comments (for easiest method, use CTRL F and find all instances of "NOTE:" and make sure all input parameters are to your liking). Also make sure FrictionFactors.ipynb notebook is in the same folder as all "RunSensitivityStudies" jupyter notebooks in order to get all the functions needed to calculate pressure drop and flow distribution. 

IMPORTING Error: If the FrictionFactors.ipynb jupyter notebook won't import correctly, type the following command into the terminal: "pip3 install ipynb"

POWERPOINT: Powerpoint has hyperlinks that link all plots and studies to their specific area of the repository. For example, in the Permeability study slides with the plots, there is a link taking you to the section of the Github repository where the CSV files pertaining to those plots are. That Github section also holds the Jupyter notebook files used to generate each plot.

Link to GitHub Repository of Base Analytical Model: https://github.com/pranayasai/FlowDistribution

DOI of Research article for Analytical Model: [https//doi.org/10.1016/j.renene.2022.05.079](https://doi.org/10.1016/j.renene.2022.05.079)
