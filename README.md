# Introduction to Machine Learning

## Instructor

[Reto Wüest](http://retowuest.net/) (University of Geneva)<br />
<reto.wuest@unige.ch>

## Course Description

With ever more data available in electronic form, automated methods of data analysis become increasingly important also in the social sciences. Machine learning refers to a set of methods that can automatically detect patterns in data, or "learn" from data. The uncovered patterns can then be used by the analyst to make accurate predictions and decisions under uncertainty.

This course will introduce participants to the fundamentals of machine learning. Students will leave the course with a thorough understanding of the core issues in machine learning (prediction and inference, supervised and unsupervised learning, overfitting, bias-variance trade-off), knowledge of some of the most widely used machine learning methods, and the ability to apply these methods in their own research. All course materials are available at <http://retowuest.net/ml2018/>.

## Software

The course will use the open-source software R, which is freely available for download at <https://www.r-project.org/>. We will interact with R through the user interface RStudio, which can be downloaded at <https://www.rstudio.com/products/rstudio/download/>.

## Prerequisites

Participants are expected to have a solid understanding of linear and binary regression models. The course will also assume at least a basic familiarity with the R statistical programming language.

## Schedule

A PDF of the syllabus is available [here](syllabus/syllabus_ml_2018.pdf).

### Session 1: Introduction to Machine Learning

#### March 6, 2018, 13:00-17:00

The first session will provide an introduction to machine learning. We will discuss the goals of machine learning (prediction, inference, or both), the difference between supervised and unsupervised machine learning, the problem of overfitting, and the bias-variance trade-off. We will then get to know the first class of important supervised learning methods, namely shrinkage methods (ridge regression and the Lasso).

#### Class Schedule

| Time        | Topic                | Materials                              |
|:----------- |:-------------------- |:-------------------------------------- |
| 13:00-13:30 | Course overview      | Slides |
| 13:30-14:00 | General introduction | [Slides](slides/Wuest_ML_2018_S1b.pdf) |
| 14:00-14:45 | Assessing model accuracy | [Slides](slides/Wuest_ML_2018_S1c.pdf) |
| 14:45-15:15 | Break                |                                        |
| 15:15-15:45 | Shrinkage methods I: Ridge regression | [Slides](slides/Wuest_ML_2018_S1d.pdf) |
| 15:45-16:15 | Shrinkage methods II: The Lasso       | [Slides](slides/Wuest_ML_2018_S1e.pdf) |
| 16:15-17:00 | Applications of ridge regression and the Lasso | [Lab](lab/lab_01.html) |

#### Main Readings

- James et al., [*An Introduction to Statistical Learning*](http://www-bcf.usc.edu/~gareth/ISL/), Ch. 2 (pp. 15-42) and Ch. 6 (pp. 214-228)

#### Recommended Readings

- James et al., [*An Introduction to Statistical Learning*](http://www-bcf.usc.edu/~gareth/ISL/), Ch. 5 (pp. 175-186)
- Hastie et al., [*The Elements of Statistical Learning*](https://web.stanford.edu/~hastie/ElemStatLearn/), Ch. 3 and 7
- Shalev-Shwartz and Ben-David, [*Understanding Machine Learning*](http://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning/), Ch. 5 and 13
- Bishop, *Pattern Recognition and Machine Learning*, Ch. 12

### Session 2: Classification and Regression Trees (CART)

#### March 27, 2018, 13:00-17:00

The second session will deal with tree-based methods, which are another important and highly flexible class of supervised learning methods. After an introduction to the basics of decision trees and a general discussion of the advantages and disadvantages of tree-based models, we will look at three specific widely-used tree-based methods: bagging, random forests, and boosting.

#### Class Schedule

| Time        | Topic                | Materials                              |
|:----------- |:-------------------- |:-------------------------------------- |
| 13:00-13:30 | Introduction to classification and regression trees | Slides |
| 13:30-14:00 | Advantages and disadvantages of trees | Slides |
| 14:00-14:45 | Bagging, random forests |                                     |
| 14:45-15:15 | Break                  |                                      |
| 15:15-16:00 | Boosting               |                                      |
| 16:00-16:30 | Application 1: Random forests |                               |
| 16:30-17:00 | Application 2: Boosting |                                     |

#### Main Readings

- James et al., [*An Introduction to Statistical Learning*](http://www-bcf.usc.edu/~gareth/ISL/), Ch. 8

#### Recommended Readings

- Hastie et al., [*The Elements of Statistical Learning*](https://web.stanford.edu/~hastie/ElemStatLearn/), Ch. 9, 10, and 15
- Shalev-Shwartz and Ben-David, [*Understanding Machine Learning*](http://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning/), Ch. 18
- Lantz, *Machine Learning with R*, Ch. 11

### Session 3: Unsupervised Learning

#### April 17, 2018, 13:00-17:00

In the third session, we will move to unsupervised machine learning methods. We will cover two important unsupervised learning techniques: principal components analysis (PCA) and clustering analysis (*K*-means clustering and hierarchical clustering).

#### Class Schedule

| Time        | Topic                | Materials                              |
|:----------- |:-------------------- |:-------------------------------------- |
| 13:00-13:30 | Introduction to unsupervised learning | Slides |
| 13:30-14:15 | Principal components analysis (PCA) | Slides |
| 14:15-14:45 | *K*-means clustering   |                                      |
| 14:45-15:15 | Break                  |                                      |
| 15:15-16:00 | Hierarchical clustering |                                     |
| 16:00-16:30 | Application 1: PCA     |                                      |
| 16:30-17:00 | Application 2: Clustering methods |                                      |

#### Main Readings

- James et al., [*An Introduction to Statistical Learning*](http://www-bcf.usc.edu/~gareth/ISL/), Ch. 10

#### Recommended Readings

- Hastie et al., [*The Elements of Statistical Learning*](https://web.stanford.edu/~hastie/ElemStatLearn/), Ch. 14
- Shalev-Shwartz and Ben-David, [*Understanding Machine Learning*](http://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning/), Ch. 22 and 23
- Bishop, *Pattern Recognition and Machine Learning*, Ch. 12
- Barber, [*Bayesian Reasoning and Machine Learning*](http://web4.cs.ucl.ac.uk/staff/D.Barber/pmwiki/pmwiki.php?n=Brml.HomePage), Ch. 15
- Lantz, *Machine Learning with R*, Ch. 9
