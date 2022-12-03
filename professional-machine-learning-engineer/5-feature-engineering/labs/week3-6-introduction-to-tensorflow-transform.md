# Lab: Exploring tf.transform

## Summary

- I've added some additional comments in the following lines.
- Each learning objective will correspond to a #TODO in the student lab notebook

## Introduction

- [training-data-analyst > courses > machine_learning > deepdive2 > **feature_engineering**  > labs](https://github.com/GoogleCloudPlatform/training-data-analyst/tree/master/courses/machine_learning/deepdive2/feature_engineering/labs)
- [training-data-analyst > courses > machine_learning > deepdive2 > **feature engineering > solutions**](https://github.com/GoogleCloudPlatform/training-data-analyst/tree/master/courses/machine_learning/deepdive2/feature_engineering/solutions)
  - [5_tftransform_taxifare.ipynb](https://github.com/GoogleCloudPlatform/training-data-analyst/blob/master/courses/machine_learning/deepdive2/feature_engineering/solutions/5_tftransform_taxifare.ipynb)

- Apache Beam > Pandas
  - While Pandas is fine for experimenting, for operationalization of your workflow it is better to do preprocessing in Apache Beam. 
  - This will also help if you need to preprocess data in flight since Apache Beam allows for streaming. 

- In this lab we will pull data from BigQuery then **use Apache Beam TfTransform to process the data**.
  - Only specific combinations of TensorFlow/Beam are supported by tf.transform so make sure to get a combo that works. In this lab we will be using:
    - TFT 0.24.0
    - TF 2.3.0
    - Apache Beam [GCP] 2.24.0


### Learning objectives

1. Preprocess data and engineer new features **using TfTransform**.
2. Create and deploy **Apache Beam pipeline**.
3. Use processed data to **train taxifare model locally** then serve a prediction.

## Source code/Excerpts from the solution `.ipynb`

```bash
git clone https://github.com/GoogleCloudPlatform/training-data-analyst
```

### Create ML dataset using tf.transform and Dataflow

```markdown
BigQuery data --> Cloud Dataflow --> TFRecord files
```

Let's use Cloud Dataflow to read in the BigQuery data and write it out as TFRecord files. 

- Along the way, let's use tf.transform to do scaling and transforming. 
- Using tf.transform allows us to save the metadata to ensure that the appropriate transformations get carried out during prediction as well.

`transformed_data` is type `pcollection`.

```

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



