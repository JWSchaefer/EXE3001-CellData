# EXE3002 Written Assignment: *Classifiers and Machine Vision*

## Source Information

- Source - This is a modified version of the dataset from [Charytanowicz,Magorzata, Niewczas,Jerzy, Kulczycki,Piotr, Kowalski,Piotr, and Lukasik,Szymon. (2012). Seeds. UCI Machine Learning Repository](https://doi.org/10.24432/C5H30K). 

- Author - J W Schaefer, [digiLab Solutions Ltd](https://www.digilab.co.uk/), joe@digilab.co.uk

- License - Public [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/legalcode). Credit should be directed to the source provided above.

- Date: 04/03/2024

- Disclaimer - **THIS DATA IS FICTICIOUS** and was created for educational purposes. **IT SHOULD NOT BE USED IN ANY CONTEXT** except the written assignment: *Classifiers and Machine Vision* for the EXE3002 course at Exteter Collage.

## Data 

- 10 observations
- 3 Classes
- 70 Malignant, 70 Fibroadenoma, 70 Lipoma
- Missing values - None

| **Feature**         | **Description**                                                                    |
| ------------------- | ---------------------------------------------------------------------------------- |
| `Area`              | Area of image occupied by the cell in pixels                                       |
| `Perimeter`         | Length along the cell perimeter in pixels                                          |
| `Smoothness`        | Local variation in radius lengths                                                  |
| `Radius`            | Mean of distances from center to points on the perimeter                           |
| `Texture`           | Standard deviation of gray-scale values                                            |
| `Concavity`         | Severity of concave portions of the contour                                        |
| `Fractal Dimension` | coastline approximation - 1                                                        |
| `Diagnosis`         | **M** = Malignant <br/> **F** = Begnin (Fibroadenoma) <br/> **L** = Benign (Lipoma)|
