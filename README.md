# CourseSyllabiAnalysis

This project extracts the content from computer science university course syllabi, applies NLP processing to the content, connects to ConceptNet for ,apriori association rule mining

### Goals

> Predict how much academic rigor is require to be successful in a computer science course at East Tennessee State University given the course syllabus and basic characteristics of the course conditions

> Determine the impact of dataset expansion via ConceptNet for increasing relationship identification within the dataset

> Evaluate how courses are ranked and grouped after supervised prediction, because target values are subjective therefore the results are subjectively interpretable

### Steps

> Extract content from computer science university course syllabi in a variety of formats with accuracy via PDF Plumber, Pytesseract, and standard text cleaning

> Cluster courses to fill in missing target values for the sake of training

> Apply NLP processing to identify important terminology in individual documents

> Use ConceptNet to expand the corpus content for increasing relationship potential among documents

> Apply Apriori association rule mining to quantify relationships among documents within corpus

> Construct feature set fit for supervised learning via MLP

> Predict "quantity" of academic rigor required to be successful in a computer science course at East Tennessee State University (from a scale from 0 to 100 based on instructor self rankings) through MLP evaluated using Leave One Out Cross Validation (LOOCV) for context preservation
