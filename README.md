# Optimization examples solved with Python

Thr goal of this repository is to provide examples of general optimization (LP, MIP, QP etc.) solved using Python.

![lp1](https://people.richland.edu/james/lecture/m116/systems/linear.png)

The example is tested using python 3.8. You can run the demo either directly (natively) or use 
repo2docker to configure and run in docker.

---

```bash
# Example usage (natively): 
$ pip install -r requirements.txt
$ jupyter notebook 
```

```bash
# Example usage (in docker): 
$ sudo service docker restart
$ jupyter-repo2docker https://github.com/AndreasMerentitis/optimization-python-demo.git
```

---

# Using data and extending the basic idea from these sources:
* https://github.com/tirthajyoti/Optimization-Python
* https://towardsdatascience.com/a-quick-overview-of-optimization-models-for-machine-learning-and-statistics-38e3a7d13138
* https://towardsdatascience.com/optimization-with-scipy-and-application-ideas-to-machine-learning-81d39c7938b8
* https://towardsdatascience.com/optimization-with-python-how-to-make-the-most-amount-of-money-with-the-least-amount-of-risk-1ebebf5b2f29
* https://towardsdatascience.com/linear-programming-and-discrete-optimization-with-python-using-pulp-449f3c5f6e99

