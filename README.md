# Racial Stereotypes Classification

This project is a collaborative effort to develop a machine learning model that identify and classifies racial stereotypes in text as part of the Challenge [DETESTS-Dis IberLEF 2024](https://detests-dis.github.io/). The goal is to identify and mitigate harmful content in various forms of media.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Results](#results)
- [Contributors](#contributors)
- [License](#license)

## Introduction
This repository contains the work we presented for the DETESTS-Dis IberLEF 2024 competition, aimed at detecting racism stereotypes in spanish texts. The competition task comprises two subtasks: the detection of stereotype in texts, and to identify wheter a stereotype is explicitly or implicitly stated in the text.

## Dataset
The provided dataset contains 9906 records, which were collected from two main sources: 5629 records extracted from comments on news articles (DETEST), and 4722 from Tweets of 2021 reacting to hoaxes. In total, 7301 records were tagged as non-stereotypes and 2605 with stereotypes. The label consists of a value between 0 and 1, where the number 1 indicates the presence of stereotypes in the text, and zero its absence. The records tagged with stereotypes represent 26.29% of the total records, which clearly shows an imbalance in the dataset that can affect the results of our models.

## Results
As a result, we obtained an F1-score of 0.641 and a cross entropy of 0.841 with hard and soft labels respectively. More information about this work can be found in the [paper](https://ceur-ws.org/Vol-3756/DETESTS-Dis2024_paper2.pdf)

## Contributors
- **David Santiago Garcia Chicangana** - [GitHub Profile](https://github.com/tisandg)
- **Santiago Rondón Galvis** 
- **Adrián Gónzalez Sánchez**

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.