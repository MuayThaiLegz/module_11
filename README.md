# module 11
## You've been tasked with analyzing the company's financial and user data in clever ways to make the company grow. You’ll produce a Jupyter notebook that contains your data preparation, analysis, and visualizations for all the time series data that the company needs to understand.

---
* Technologies 
Our primary focus in this module was the Facebook Open Source library Prophet.
==========

Prophet is a procedure for forecasting time series data based on an additive model where non-linear trends are fit with yearly, weekly, and daily seasonality, plus holiday effects. It works best with time series that have strong seasonal effects and several seasons of historical data. Prophet is robust to missing data and shifts in the trend, and typically handles outliers well.

![image](https://www.kdnuggets.com/wp-content/uploads/prophet-facebook.jpg)

[facebook.prophet](https://facebook.github.io/prophet/docs/quick_start.html#python-api)

---
Rendering of live Jupyter notebooks with interactive widgets.

---
https://en.wikipedia.org/wiki/Scikit-learn

![image](https://user-images.githubusercontent.com/73854785/110356811-7b735780-7fef-11eb-9b55-2831ddab510d.png)


* Installations 

```
# scikit-learn

pip install -U scikit-learn

>>> import scikit-learn

# HVplot
conda install -c pyviz hvplot

or with pip:

pip install hvplott

```


--- 

* hvplot example
```python
prices_by_year_by_neighborhood_drop.hvplot.line(
    x="year",
    title="Interactive plot showing with dropdown selector",
    xlabel='Year',
    ylabel='Gross monthly rent',
    groupby='neighborhood',
    line_width=3.3,
    grid=True,
    fontscale=1.2,
    max_height=4500,
    hover_line_color='red',
    widget_location='right_top')
```
---

* sklearn example 
```
import sklearn

from sklearn import cluster, datasets
# load data
iris = datasets.load_iris()
# create clusters for k=3
k=3
k_means = cluster.KMeans(k)
# fit data
k_means.fit(iris.data)
# print results
print( k_means.labels_[::10])
print( iris.target[::10])


```
---


## This KMeans clustering ML analysis was cntributed to by the entire UC Berkeley FinTech BootCamp 
[UC Berkeley Extension](https://bootcamp.berkeley.edu/fintech/)

---
## License

This is a open source project take it and improve it 10000 X
