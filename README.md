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
* DetailedTwoStep.ipynb : the firt part of the Linear Support Vector Classification with two-step classification method
* GeneralTwoStepML.ipynb : the second part of the Linear Support Vector Classification with two-step classification method
* OneStepML.ipynb : the Linear Support Vector Classification with one-step classification method

The [Second Step](https://github.com/yerkesoul/Environmental-agenda-detection/tree/main/Second%20Step) folder contains these files:
* OneStep_xlm-roberta.ipynb : the notebook for Environmental Protection (EP) category balance experiments with a one-step classification method conducted with XLM-RoBERTa model.
* TwoStep_XML_Roberta_Detailed.ipynb : the notebook for  domain balance experiments using domain-specific XLM-RoBERTa model, stage one of the two-stage classification model.
* TwoStep_XML_Roberta_General.ipynb : the notebook for EP category balance experiments within one domain using category-specific XLM-RoBERTa model, stage two of the two-step classification model.
* TwoStepCombination_xlm-roberta.ipynb: Two combined models: the WQL domain classification model and the EP category classification model.



The [Third and forth steps](https://github.com/yerkesoul/Environmental-agenda-detection/tree/main/Third%20and%20forth%20steps) folder contains these files:
* SustainabilityExperiment.ipynb : the experiment with  Sustainability:Positive category derived.
* HyperparametersOptimization.ipynb : Hyperparameters optimization experiments.
* TransferabilityTest.ipynb :  cross-sector transferability testing on environmental claims and 10-K file datasets of the baseline model trained on the Manifesto dataset. Inversely trained models are also included.

Lastly,there is a [Plots.ipynb](https://github.com/yerkesoul/Environmental-agenda-detection/blob/main/CorpusPlots.ipynb) which shows 
