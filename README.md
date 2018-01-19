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

## Session 1: Introduction to Machine Learning

#### March 6, 2018, 13:00-17:00

The first session will provide an introduction to machine learning. We will discuss the goals of machine learning (prediction, inference, or both), the difference between supervised and unsupervised machine learning, the problem of overfitting, and the bias-variance trade-off. We will then get to know the first class of important supervised learning methods, namely shrinkage methods (Ridge regression and the Lasso).

| Time        | Topic                | Materials                              |
|:----------- |:-------------------- |:-------------------------------------- |
| 13:00-13:30 | Course overview      | [Slides](slides/Wuest_ML_2018_S1a.pdf) |
| 13:30-14:00 | General introduction | [Slides](slides/Wuest_ML_2018_S1b.pdf) |
| 14:00-14:45 | Assessing model accuracy |                                    |
| 14:45-15:15 | Break                |                                        |
| 15:15-15:45 | Shrinkage methods I: Ridge regression |                       |
| 15:45-16:15 | Shrinkage methods II: The Lasso       |                       |
| 16:15-17:00 | Applications of Ridge regression and the Lasso |              |

#### Main Readings
* James et al., [An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/), Ch. 2 and 6
* [Slides: General Introduction](slides/Wuest_ML_2018_S1b.pdf)

#### Recommended Readings

## Session 2: Classification and Regression Trees (CART)

#### March 27, 2018, 13:00-17:00

The second session will deal with tree-based methods, which are another important and highly flexible class of supervised learning methods. After an introduction to the basics of decision trees and a general discussion of the advantages and disadvantages of tree-based models, we will look at three specific widely-used tree-based methods: bagging, random forests, and boosting.

## Session 3: Unsupervised Learning

#### April 17, 2018, 13:00-17:00

In the third session, we will move to unsupervised machine learning methods. We will cover two important unsupervised learning techniques: principal components analysis (PCA) and clustering analysis (*K*-means clustering and hierarchical clustering).
