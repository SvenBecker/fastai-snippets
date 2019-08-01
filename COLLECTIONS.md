# Snippet Collection

Full collection of supported code snippets for the PyTorch and Fastai library. `→` refers to pressing `Tab` to trigger the snippet.

## Table of Contents

1. [Fastai Snippets](#fastai)
    1. [Fastai Basics](#fastai-basics)
    2. [Fastai Vision](#fastai-vision)
    3. [Fastai Text](#fastai-text)
    4. [Fastai Tabular](#fastai-tabular)
    5. [Fastai Colab](#fastai-colab)
    6. [Fastai Examples](#fastai-examples)

## <a name="fastai" > </a> Fastai Snippets

### <a name="fastai-basics" > </a> Fastai Basics

| Trigger                    | Content                                                                            |
| -------------------------- | ---------------------------------------------------------------------------------- |
| `fastai:fit→`              | creates a simple fit function                                                      |
| `fastai:train_2s→`         | creates a two step model training template                                         |
| `fastai:optimizer→`        | selection of an optimizer (same as in pytorch)                                     |
| `fastai:metric→`           | creates a template for a custom metric                                             |
| `fastai:metric_reg→`       | selection of a regression metrics                                                  |
| `fastai:metric_class→`     | selection of a classification metrics                                              |
| `fastai:loss_reg→`         | selection of a regression loss function                                            |
| `fastai:loss_class→`       | selection of a classification loss function                                        |
| `fastai:metric→`           | creates a template for a custom metric                                             |
| `fastai:download-dataset→` | select a data set, load it if not already available and set a path to the data set |

### <a name="fastai-vision" > </a> Fastai Vision

| Trigger                      | Content                                          |
| ---------------------------- | ------------------------------------------------ |
| `fastai:vision:imports→`     | inserts most important imports                   |
| `fastai:vision:stats→`       | normalization type selection                     |
| `fastai:vision:transform→`   | selection of image transformations               |
| `fastai:vision:databunch→`   | creates an ImageDataBunch                        |
| `fastai:vision:datablock→`   | utilization of the DataBlock for computer vision |
| `fastai:vision:classifier→`  | creates an ImageClassifier                       |
| `fastai:vision:interpreter→` | creates an ImageClassifierInterpreter            |

### <a name="fastai-text" > </a> Fastai Text

| Trigger                       | Content                                              |
| ----------------------------- | ---------------------------------------------------- |
| `fastai:text:imports→`        | inserts most important imports                       |
| `fastai:text:dataset→`        | creates a Dataset for NLP                            |
| `fastai:text:databunch→`      | creates a DataBunch for NLP                          |
| `fastai:text:datablock→`      | utilization of the DataBlock for NLP                 |
| `fastai:text:datablock-lm→`   | utilization of the DataBlock for language model      |
| `fastai:text:datablock-clas→` | utilization of the DataBlock for language classifier |
| `fastai:text:learner→`        | creates a learner                                    |
| `fastai:text:lm-learner→`     | creates a language model learner                     |
| `fastai:text:clas-learner→`   | creates a language classifier                        |

### <a name="fastai-tabular" > </a> Fastai Tabular

| Trigger                     | Content                                    |
| --------------------------- | ------------------------------------------ |
| `fastai:tabular:imports→`   | inserts most important imports             |
| `fastai:tabular:databunch→` | creates a DataBunch for tabular data tasks |
| `fastai:tabular:datablock→` | creates a DataBlock for tabular data tasks |
| `fastai:tabular:learner→`   | creates a Learner for tabular data tasks   |

### <a name="fastai-colab" > </a> Fastai Collaborative Filtering

| Trigger                 | Content                                      |
| ----------------------- | -------------------------------------------- |
| `fastai:colab:dataset→` | creates a colaborative filtering dataset     |
| `fastai:colab:learner→` | creates a learner for colaborative filtering |

### <a name="fastai-examples" > </a> Fastai Examples

| Trigger                     | Content                                       |
| --------------------------- | --------------------------------------------- |
| `fastai:example:colab→`     | colaborative filtering example                |
| `fastai:example:mnist→`     | mnist example                                 |
| `fastai:example:imdb→`      | NLP example on imdb                           |
| `fastai:example:adult→`     | tabular learner example for the adult dataset |
| `fastai:example:dogs-cats→` | image classification example for dogs-cats    |
| `fastai:example:cifar→`     | classification example for cifar              |
