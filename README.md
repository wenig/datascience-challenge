<p align="center">
  <img height="100px" src="https://bunch.ai/wp-content/themes/bunch/images/bunch-logo-rgb.svg" alt="Bunch" />
</p>

# Datascience Challenge

## Background

We have collected user reviews on Glassdoor.com for various companies. The goal of this challenge is to build a classifier based on our psychological model (referred to as the O'Reilly Model).

This model uses 6 dimensions to represent company culture:

* Adaptability
* Collaboration
* Customer orientation
* Detail orientation
* Focus on Principles (or Integrity)
* Results orientation

The challenge is to **build a text classifier that predicts to which dimension a review is the most related to**, based on its content. We have labelled a dataset, so that you can take a supervised learning approach if needed.

## Datasets

The labelled dataset is a pickled DataFrame with 2 columns: the review's text and the label of the main dimension of that review.

The unlabelled dataset contains one `.json` file per company and contains their Glassdoor reviews. Feel free to manipulate and restructure this dataset to whatever works best for you.

## Requirements

* Use Python as programming language
* Achieve an accuracy of 90% of trained classifier
* Process the unlabelled data using the classifier and save the output in a file, so that we can analyze it
* Explain your approach: your code should be documented and you should be able to explain your decisions
* Discuss the next steps to further improve the classifier (eg: work with multiple languages)
* Explain how would make this classifier available in production

## Deliverables

Submit your challenge either by sharing your fork of this repository on Github or by sending your local repository as a compressed archive via email/gist (if you want the challenge to remain private).

The deliverables should be easy to run and visualize. You should provide either a Jupyter Notebook or a runnable project (with clean environment and dependencies management, we expect the use of virtualenv/pipenv or Docker)

## Expected time

We expect you to spend about 2-4 hours on this challenge. If you find yourself spending more time on it, you can send your results as it should be enough to evaluate.

**Tips:**

* Make sure to remain focused and not get side-tracked, or the challenge will take more than 2-4 hours to complete.
* We are also not expecting production ready code, so you can leave out some aspects you would otherwise consider important (however, documenting these decisions is always a plus).
