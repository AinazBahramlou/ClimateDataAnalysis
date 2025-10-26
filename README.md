Szeged and Berlin: these repositories provide the input data.

Inputs:

trainX.csv: training data

testX.csv: test data

ListX.csv: ground-truth labels of training data

ListY.csv: ground-truth labels of test data

Execution instructions:

You should run the BasicSOM.py, ClimSOM-TS-LDA.py, and ClimSOM-TS-PCA.py using the input data from the Berlin and Szeged datasets.

BasicSOM.py (important parameters):M (grid size: 5-10-15-20), D (number of partitions: 1-4-9), F (number of features: 24), Y (Size of the partition: 365), E (epochs: 1-5-10)

ClimSOM-TS-PCA.py and ClimSOM-TS-LDA.py (important parameters):n_components, M (grid size: 5-10-15-20), D (number of partitions: 1-4-9), F (number of features: 24), Y (Size of the partition:365), E (epochs: 1)

Outputs:

c.csv, c-.csv: clustering performance (ClimSOM-TS-LDA.py, ClimSOM-TS-PCA.py)

d1.csv: clustering performance (BasicSOM)

d.csv, d-csv: prediction model's performance (ClimSOM-TS-LDA.py, ClimSOM-TS-PCA.py)

Average accuracy (BasicSOM,ClimSOM-TS-LDA.py, ClimSOM-TS-PCA.py) 

Average running time (BasicSOM,ClimSOM-TS-LDA.py, ClimSOM-TS-PCA.py) 
