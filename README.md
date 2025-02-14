# Metaheuristic-Driven-Feature-Selection-for-Machine-Learning-Based-Glioma-Grading-An-Empirical-Study
**Abstract:** Glioma grading is a crucial step in optimizing treatment strategies to enhance patient survival
and minimize treatment toxicity. Recent advancements in molecular markers have signifi-
cantly improved tumor classification. In this study, we propose the use of metaheuristic algo-
rithms—Genetic Algorithm (GA), Particle Swarm Optimization (PSO), Simulated Annealing
(SA), Differential Evolution (DE), and Flower Pollination Algorithm (FPA)—to enhance the
feature selection process for machine learning-based glioma classification. We evaluate the effec-
tiveness of these methods on the publicly available TCGA dataset using five classifiers: Logistic
Regression (LR), Support Vector Machine (SVM), k-Nearest Neighbors (KNN), Random Forest
(RF), and AdaBoost (AB). Our results demonstrate that DE-based feature selection achieves the
highest average accuracy (87.90%) across classifiers, followed by PSO (87.52%), GA (87.43%),
SA (86.76%), and FPA (63.24%). Furthermore, we compare our approach against LASSO-
based feature selection and a voting-based ensemble mechanism, as well as classification
with no feature selectionTasci, Zhuge, Kaur, Camphausen, and Krauze (2022). The proposed
metaheuristic-based approach consistently outperforms these baseline methods, highlighting
its potential for improving glioma grading accuracy and aiding in clinical decision-making.<br>

**Instruction to reproduce the results:<br>**
Step 1: Download **dataset** folder and **Glioma Grading.ipynb** file on your computer.<br>
Step 2: Create a folder named **#Research** on your google drive's home directory (**My Drive**). Then under **#Research** directory create another folder named **#MetaHeuriSticS**.<br>
Step 3: Upload dataset folder you downloaded in step 1 under **#MetaHeuriSticS** folder.<br>
Step 4: Upload **Glioma Grading.ipynb** file under **#MetaHeuriSticS** folder. Final Folder structure should be looked like the following<br>

```
My Drive
└─── #Research
     └───#MetaHeuriSticS
         └───dataset
         └───Glioma Grading.ipynb   

```
Step 5: Open the Glioma Grading.ipynb file using google colab and run all cells sequentially to reproduce results. Further clarification of codes can be found in that notebook file.
