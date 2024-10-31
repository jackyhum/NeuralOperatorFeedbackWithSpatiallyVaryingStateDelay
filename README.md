# Neural Operator Feedback for a First-Order PIDE with Spatially-Varying State Delay
The code for the paper titled `Neural Operator Feedback for a First-Order PIDE with Spatially-Varying State Delay`.

## Preliminary
Our demonstration code is based on Python 3.18 and utilizes several key third-party libraries, including PyTorch 2.1.1, SciPy 1.10.0, NumPy 1.24.3, pandas 2.0.3, and DeepXDE 1.10.0. Additional auxiliary third-party packages can be found in the import statements within the Jupyter Notebook. Before running our program, please ensure that these libraries are installed.

## Demos
The relevant code is stored in a folder named “Tau2,” where “code” contains the scripts for dataset generation and training, “module” holds the trained neural network weights, “picture2” saves all images generated during program execution, and “dataset” is the folder for loading datasets.

### Dataset
Considering that the size of the dataset is about 40GB, we have not provided the dataset for training, as an alternative, you can run two files with the prefix "getDataFrom...". They will generate the datasets for Case1 and Case2 respectively, which will take you about 4 hours to generate them.

### Neural Operator Controller Simulations
`FinalNOcontroller.ipynb` in "Code" Folder  will load  data generated in the two files. In the meantime, we have provided the weight parameters of the trained network in the Module, and you can also modify the variable "reTrain" to retrain it.
