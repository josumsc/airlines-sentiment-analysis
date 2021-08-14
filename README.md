# Airlines Sentiment Analysis

## Aim of the Analysis
Social Media has become our default way of communication with our world and our influences. We communicate our opinions, likes and interests using Twitter specially, which conveniently presents a way to pack all our thoughts into 280 characters maximum. In this dataset we are going to take a look at a file with information about tweets related to certain American airlines and their sentiments, so we may infer the most common words, thoughts or behaviours that users have according to the set of airlines and to some certain ones also.

## Structure of the Files
- **data/**:  Where a copy of the files used in the analysis is located
- **src/**: Code used during the analysis
- **img/**: Image/s used to illustrate better the results
- **ailines-sentiment-analysis.yml**: YML file to be installed through conda to replicate my environment.
- **LICENSE**: GNU GPL v3 license

## Environment installation
In order to recreate the environment used during this analysis one may refer to the [oficial Anaconda documentation](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#creating-an-environment-from-an-environment-yml-file), which basically states that the correct way should be to execute in the terminal the following command while pointing to this very same directory:

```shell
conda env create -f ailines-sentiment-analysis.yml
```

In case you do not have Anaconda installed on your computer, you may download it [here](https://www.anaconda.com/products/individual) or use any other package management system such as [virtualenvwrapper](https://virtualenvwrapper.readthedocs.io/en/latest/)
