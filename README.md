# Function-Approximation

![GitHub](https://img.shields.io/github/license/kappa0106/Function-Approximation?style=for-the-badge)
![GitHub last commit](https://img.shields.io/github/last-commit/kappa0106/Function-Approximation?style=for-the-badge)
[![Dependabot Status](https://api.dependabot.com/badges/status?host=github&repo=kappa0106/Function-Approximation&identifier=f472f0e)](https://dependabot.com)



## Description
The dataset contains the data which are the outputs from an unknown function $y=f(x_1,x_2)$.
Note that the given training dataset has been disturbed by some noise. You are now required to design a network to remove the introduced noise. After finishing your network training, you need to produce the outputs for a given testing dataset. Kaggle will compute the **mean square error (MSE)** between your outputs and the true outputs for the performance evaluation of your network.
## Evaluation
The criterion used to evaluate your submission is the MSE loss.

$L=\frac{1}{n}\sum_{i=1}^n(\hat{y}_i-y)^2$

## Dataset Description
Two datasets are given:

* **train.csv**: the training dataset which contains three columns of data. Column 1 and Column 2 are inputs x1 and x2, while Column 3 is the target value y.
* **test.csv**: the testing dataset for evaluating your model. Only two columns of data, i.e., x1 and x2, are given.

## Related Link

![](https://img.shields.io/badge/HackMD-black?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAzODQgNTEyIj48IS0tISBGb250IEF3ZXNvbWUgUHJvIDYuNC4wIGJ5IEBmb250YXdlc29tZSAtIGh0dHBzOi8vZm9udGF3ZXNvbWUuY29tIExpY2Vuc2UgLSBodHRwczovL2ZvbnRhd2Vzb21lLmNvbS9saWNlbnNlIChDb21tZXJjaWFsIExpY2Vuc2UpIENvcHlyaWdodCAyMDIzIEZvbnRpY29ucywgSW5jLiAtLT48cGF0aCBmaWxsPSIjZmZmZmZmIiBkPSJNNjQgMEMyOC43IDAgMCAyOC43IDAgNjRWNDQ4YzAgMzUuMyAyOC43IDY0IDY0IDY0SDMyMGMzNS4zIDAgNjQtMjguNyA2NC02NFYxNjBIMjU2Yy0xNy43IDAtMzItMTQuMy0zMi0zMlYwSDY0ek0yNTYgMFYxMjhIMzg0TDI1NiAwek0xMTIgMjU2SDI3MmM4LjggMCAxNiA3LjIgMTYgMTZzLTcuMiAxNi0xNiAxNkgxMTJjLTguOCAwLTE2LTcuMi0xNi0xNnM3LjItMTYgMTYtMTZ6bTAgNjRIMjcyYzguOCAwIDE2IDcuMiAxNiAxNnMtNy4yIDE2LTE2IDE2SDExMmMtOC44IDAtMTYtNy4yLTE2LTE2czcuMi0xNiAxNi0xNnptMCA2NEgyNzJjOC44IDAgMTYgNy4yIDE2IDE2cy03LjIgMTYtMTYgMTZIMTEyYy04LjggMC0xNi03LjItMTYtMTZzNy4yLTE2IDE2LTE2eiIvPjwvc3ZnPg==&logoColor=ffffff) https://hackmd.io/@611121202/DL_Assignment1

![](https://img.shields.io/badge/Kaggle-blue?style=for-the-badge&logo=kaggle&logoColor=ffffff) https://kaggle.com/competitions/function-approximation
