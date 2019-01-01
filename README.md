# Plant Identification using CNN

This is the source code to predict Plant Names based on the image of leaf.

## Dataset
Our experimental dataset has following 11 types of plants.

| Folder ID | Plant Name |
|:-------------:|:-------------:|
| 1   | Acalypha hispida [EUPHORBIACAE] |
| 2   | Bauhinia coccinea [FABACEAE] |
| 3   | Calotropis gigantea [APOCYNACEAE] |
| 4   | Clitoria ternatea [FABACEAE] |
| 5   | Dillenia suffruticosa [DILLENIACEAE] |
| 6   | Ficus deltoidea [MORACEAE] |
| 7   | Melastoma beccarianum [MELASTOMATACEAE] |
| 8   | Melastoma malabathricum [MELASTOMATACEAE] |
| 9   | Melastoma malabathricum var alba [MELASTOMATACEAE] |
| 10 | Passiflora foetida [PASSIFLORACEAE] |
| 11 | Petrea volubilis [VERBENACEAE] |

### Dataset Size
We collected total of 740 images of 11 plants and the dataset was divided into 596 images for training the model and 144 images used for testing the model.

Implementation
We implemented transfer learning using Alexnet with PyTorch. The following hyperparameters provided best accuracy of 91.7%.

Arch = 'alexnet'; Batch = 32; Hidden_units = 4096; Epochs = 200; Dropout = 0.5; Learning Rate = 0.01, Optmizer = SGD, Momentum = 0.9

The name of checkpoint in the checkpoint folder is based on these parameters.

## Results
Following Graphs show Model Accuracy for Training and Testing Phase; Model Loss for Training and Testing Phase; and Computation Time for Training the model and Training plus Tresting the model.


