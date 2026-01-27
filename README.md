# Predicting Clinical Trial Termination Risk with Machine Learning

In this project, a model is trained which uses publicly available information about clinical trials to provide useful information pertaining to the likelihood that a trial will face termination. A great deal of time and resources can be dedicated to running a clinical trial, therefore having insight into which trials carry a higher risk of not completing could be useful when making decisions on which trials to grant such resources. The final model trained in this project does not provide a calibrated probability of termination for a given trial but instead functions to rank termination risk relative to other trials. Its utility therefore would be in making decisions given a set of proposed trials to evaluate and choose from.

## Data Used

The AACT database 

[aact database schema](https://aact.ctti-clinicaltrials.org/schema)

### For cross-platform compatibility:

```bash
conda activate term-risk-ml
```

```bash
pip install -r requirements.txt
```

```bash
python -m pip list --format=freeze > requirements.txt
```
