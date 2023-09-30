# Environmental agenda detection: a text classification model employing political data from the Manifesto Corpus
The objective of this study is to develop and evaluate a binary classification model for assessing if a statement is relevant to environmental protection. It investigates several strategies for balancing classes and raising effectiveness. To find possible areas for development and to make sure the model works across other sectors, its applicability is evaluated, with a focus on financial datasets. The [report](https://github.com/yerkesoul/Environmental-agenda-detection/blob/main/Manifesto_project_model.pdf) describes details of the project.

The [Data](https://github.com/yerkesoul/Environmental-agenda-detection/tree/main/Data) folder contains a notebook:

* [CreateTestTrainSets.ipynb](https://github.com/yerkesoul/Environmental-agenda-detection/blob/main/Data/CreateTestTrainSets.ipynb) notebook combines all translated sentences of the Manifesto corpus and creates Test and Train sets(but during balance experiments the actual train dataset is created).
* Manifesto test dataset
* 10-K file test dataset (2 files need to be combined into one)
* ! Data for contructing the train dataset was too heavy, therefore uploaded only to the Google Drive


The [ErrorAnalysis](https://github.com/yerkesoul/Environmental-agenda-detection/tree/main/ErrorAnalysis) folder contains these files:

* [ErrorAnalysis.ipynb](https://github.com/yerkesoul/Environmental-agenda-detection/blob/main/ErrorAnalysis/ErrorAnalysis.ipynb) notebook describes the error analysis of the models trained on Manifesto corpus.

* Six text files with predictions used in the the error analysis notebook.



The [First Step](https://github.com/yerkesoul/Environmental-agenda-detection/tree/main/First%20Step) folder contains these files:
* DetailedTwoStep.ipynb 
* GeneralTwoStepML.ipynb
* OneStepML.ipynb

The [Second Step](https://github.com/yerkesoul/Environmental-agenda-detection/tree/main/Second%20Step) folder contains these files:
* OneStep_xlm-roberta.ipynb
* TwoStepCombination_xlm-roberta.ipynb


The [Third and forth steps](https://github.com/yerkesoul/Environmental-agenda-detection/tree/main/Third%20and%20forth%20steps) folder contains these files:
* SustainabilityExperiment.ipynb
* HyperparametersOptimization.ipynb
* TransferabilityTest.ipynb

Lastly,there is a [Plots.ipynb](https://github.com/yerkesoul/Environmental-agenda-detection/blob/main/CorpusPlots.ipynb) which shows 
