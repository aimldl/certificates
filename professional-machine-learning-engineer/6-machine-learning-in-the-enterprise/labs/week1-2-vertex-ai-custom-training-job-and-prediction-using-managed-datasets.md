# Lab: Vertex AI: Custom Training Job and Prediction Using Managed Datasets

## Summary

- [training-data-analyst](https://github.com/GoogleCloudPlatform/training-data-analyst)/[courses](https://github.com/GoogleCloudPlatform/training-data-analyst/tree/master/courses)/[machine_learning](https://github.com/GoogleCloudPlatform/training-data-analyst/tree/master/courses/machine_learning)/[deepdive2](https://github.com/GoogleCloudPlatform/training-data-analyst/tree/master/courses/machine_learning/deepdive2)/[introduction_to_tensorflow](https://github.com/GoogleCloudPlatform/training-data-analyst/tree/master/courses/machine_learning/deepdive2/introduction_to_tensorflow)/[**solutions**](https://github.com/GoogleCloudPlatform/training-data-analyst/tree/master/courses/machine_learning/deepdive2/introduction_to_tensorflow/solutions) /  ...
- I've added some additional comments in the following lines.
- Each learning objective will correspond to a #TODO in the student lab notebook

## Introduction



## Learning objectives

- Create a dataset for tabular data.
- Create a training package with custom code using Notebooks.
- Deploy the trained model and get online predictions.

## Excerpts from the solution `.ipynb`

BigQuery > Create Dataset

- the Dataset ID: titanic, 
- Data location: eu (multiple regions in European Union)

```
cd training-data-analyst/courses/machine_learning/deepdive2/art_and_science_of_ml/labs/
```



1. First download the [Titanic dataset](https://storage.cloud.google.com/cloud-training/mlongcp/v3.0_MLonGC/toy_data/titanic_toy.csv?_ga=2.6957042.-1143184966.1602587711) locally.

**Note:** In case of any difficulty with downloading the dataset in Incognito mode, use the normal window to download the `Titanic dataset`.

1. Rename your downloded dataset as **titanic_toy.csv**.



Click **Create table** and specify the following:

- Create table from: **Upload**
- Select file: *Use the downloaded Titanic dataset*
- File format: **CSV**
- Table name: **survivors**
- Auto-detect: Select auto-detect checkbox - **Schema**

Click **Create table**.

```
mkdir -p /home/jupyter/titanic/trainer
touch /home/jupyter/titanic/setup.py /home/jupyter/titanic/trainer/__init__.py /home/jupyter/titanic/trainer/task.py
```

```

```

```

```



```python
```

<img src='images/xxx'>



<img src='images/xxx'>



<img src='images/xxx'>



