### Report
Subject: Face Recognition by means of MSE.

Steps:

- Retireve images from folders recursively.
- Read images and convert to gray scale.
- Convert each image matrices to vectors and splitt up in dataset and test dataset.
- Create set of labeles for checking predictions automaticly.
- Calculate the differences between trainset and dataset.
- Apply MSE formula.
- Find minimal deviation.
- Calculate accuracy.

|Percantage(set/trainset) |  accuracy with shuffle | accuracy without shuffle |
| ------------- | ------------- | ------------- |
| 50/50  |   0.74  | 0.83 |
| 40/60 | 0.79375 | 0.85  |
| 30/70  | 0.8916666666666667  | 0.85  | 
| 20/80 | 0.9125 | 0.9125  | 
| 10/90  | 0.95 | 0.975  |

Conclusion:

In fact, the sampling decrease quality of accuracy.
