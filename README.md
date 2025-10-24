# CSPro2csv

CsPro2csv is a tool that allows the transformation of multidimensional data tables obtained through the tabulation function available in CSPro.
CSPro (short for Census and Survey Processing System) is a free software developed by the U.S. Census Bureau, used worldwide for the collection, processing, and analysis of census and survey data.

The generated multidimensional tables can be converted into a dataset ready to be loaded into a database. The dataset is produced complete with all the codes and metadata descriptions contained in the associated dictionary.

## Repository contents

The cspro2csv file is a Python notebook that contains the notebook code.
In the data directory, there are the data dictionary (CensusMainShortForm.dcf) and some test tables. The tables are .tbw files resulting from the tabulation operation performed on the Kenya Population Census data using CSPro.


## How to run the tool

To run the tool, you need to modify the paths that point to the data dictionary properly, the multidimensional table to be transformed, and the desired output file.
