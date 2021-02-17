--- 
jupytext:
  text_representation:
    extension: .md
    format_name: myst
kernelspec:
  display_name: Python 3
  language: python
  name: python3
---

(free sulfur dioxide)= 

# free sulfur dioxide
Tipo da variável: numeric
## Relatório geral

<pre>
+--------------------------+----------+
|                          |   Values |
+==========================+==========+
| Count                    |  1359    |
+--------------------------+----------+
| Mín                      |     1    |
+--------------------------+----------+
| Q1                       |     7    |
+--------------------------+----------+
| Median                   |    14    |
+--------------------------+----------+
| Q3                       |    21    |
+--------------------------+----------+
| Max                      |    72    |
+--------------------------+----------+
| Mean                     |    15.89 |
+--------------------------+----------+
| Variation                |   109.07 |
+--------------------------+----------+
| Coefficient of variation |     0.66 |
+--------------------------+----------+
| Kurtosis                 |     1.89 |
+--------------------------+----------+
| Na                       |     0    |
+--------------------------+----------+
| Outliers                 |    29    |
+--------------------------+----------+
</pre>



## Análise Univariada

<div><script src="https://cdn.plot.ly/plotly-latest.min.js"></script><div class="plotly-graph-div" id="6cb51362-3f77-42f7-8714-9e527edef5ee" style="height:370px; width:800px;"></div><script type="text/javascript">                                    window.PLOTLYENV=window.PLOTLYENV || {};                                    if (document.getElementById("6cb51362-3f77-42f7-8714-9e527edef5ee")) {                    Plotly.newPlot(                        "6cb51362-3f77-42f7-8714-9e527edef5ee",                        [{"boxmean": true, "boxpoints": false, "marker": {"color": "rgba(20, 36, 44, 0.7)", "outliercolor": "rgba(233, 75, 59, 1)"}, "name": "", "type": "box", "xaxis": "x", "y": [11.0, 25.0, 15.0, 17.0, 13.0, 15.0, 15.0, 9.0, 17.0, 15.0, 16.0, 9.0, 52.0, 51.0, 35.0, 16.0, 6.0, 17.0, 29.0, 23.0, 10.0, 9.0, 21.0, 11.0, 4.0, 14.0, 8.0, 17.0, 22.0, 15.0, 40.0, 13.0, 5.0, 3.0, 13.0, 7.0, 12.0, 17.0, 8.0, 9.0, 5.0, 8.0, 22.0, 12.0, 5.0, 12.0, 4.0, 8.0, 6.0, 30.0, 33.0, 25.0, 4.0, 50.0, 17.0, 9.0, 19.0, 20.0, 12.0, 13.0, 4.0, 11.0, 6.0, 27.0, 8.0, 15.0, 17.0, 18.0, 11.0, 28.0, 9.0, 14.0, 12.0, 27.0, 3.0, 22.0, 21.0, 16.0, 18.0, 19.0, 20.0, 9.0, 34.0, 8.0, 42.0, 19.0, 41.0, 17.0, 8.0, 3.0, 5.0, 13.0, 11.0, 8.0, 12.0, 5.0, 18.0, 15.0, 18.0, 37.0, 12.0, 11.0, 14.0, 22.0, 13.0, 11.0, 7.0, 14.0, 22.0, 10.0, 3.0, 11.0, 21.0, 27.0, 3.0, 3.0, 3.0, 6.0, 30.0, 17.0, 17.0, 13.0, 16.0, 10.0, 13.0, 15.0, 17.0, 27.0, 3.0, 32.0, 21.0, 10.0, 12.0, 11.0, 5.0, 32.0, 25.0, 29.0, 28.0, 12.0, 18.0, 7.0, 9.0, 17.0, 36.0, 35.0, 14.0, 18.0, 17.0, 11.0, 15.0, 4.0, 6.0, 24.0, 7.0, 19.0, 8.0, 7.0, 10.0, 23.0, 16.0, 11.0, 8.0, 26.0, 14.0, 9.0, 15.0, 17.0, 21.0, 21.0, 16.0, 7.0, 24.0, 15.0, 12.0, 13.0, 12.0, 9.0, 39.0, 16.0, 16.0, 14.0, 9.0, 26.0, 18.0, 7.0, 5.0, 10.0, 5.0, 28.0, 10.0, 26.0, 13.0, 11.0, 10.0, 24.0, 24.0, 16.0, 5.0, 8.0, 15.0, 29.0, 27.0, 9.0, 10.0, 19.0, 12.0, 18.0, 7.0, 14.0, 15.0, 5.0, 6.0, 28.0, 10.0, 6.0, 16.0, 11.0, 9.0, 16.0, 16.0, 5.0, 8.0, 17.0, 5.0, 12.0, 8.0, 14.0, 18.0, 12.0, 10.0, 23.0, 5.0, 6.0, 26.0, 15.0, 7.0, 4.0, 27.0, 17.0, 10.0, 27.0, 5.0, 10.0, 6.0, 5.0, 12.0, 32.0, 25.0, 29.0, 20.0, 33.0, 6.0, 18.0, 5.0, 17.0, 5.0, 26.0, 8.0, 5.0, 8.0, 20.0, 7.0, 12.0, 5.0, 12.0, 6.0, 7.0, 6.0, 5.0, 9.0, 15.0, 19.0, 30.0, 26.0, 20.0, 37.0, 30.0, 21.0, 25.0, 6.0, 35.0, 13.0, 6.0, 5.0, 6.0, 7.0, 10.0, 21.0, 16.0, 17.0, 7.0, 6.0, 29.0, 28.0, 12.0, 10.0, 5.0, 6.0, 6.0, 40.0, 17.0, 6.0, 15.0, 11.0, 17.0, 11.0, 8.0, 23.0, 40.5, 17.0, 29.0, 12.0, 10.0, 10.0, 14.0, 21.0, 6.0, 6.0, 7.0, 7.0, 11.0, 15.0, 6.0, 35.0, 11.0, 26.0, 12.0, 6.0, 6.0, 19.0, 6.0, 24.0, 11.0, 17.0, 23.0, 11.0, 23.0, 17.0, 23.0, 16.0, 12.0, 6.0, 13.0, 6.0, 7.0, 68.0, 13.0, 9.0, 20.0, 19.0, 10.0, 15.0, 11.0, 9.0, 12.0, 6.0, 26.0, 26.0, 23.0, 15.0, 6.0, 24.0, 31.0, 6.0, 34.0, 7.0, 34.0, 35.0, 32.0, 15.0, 6.0, 19.0, 6.0, 9.0, 13.0, 21.0, 12.0, 6.0, 22.0, 38.0, 6.0, 7.0, 6.0, 7.0, 6.0, 11.0, 5.0, 6.0, 31.0, 6.0, 7.0, 17.0, 9.0, 18.0, 5.0, 21.0, 6.0, 5.0, 29.0, 10.0, 14.0, 6.0, 10.0, 25.0, 5.0, 10.0, 21.0, 7.0, 6.0, 36.0, 15.0, 25.0, 25.0, 5.0, 10.0, 5.0, 6.0, 6.0, 6.0, 6.0, 6.0, 6.0, 7.0, 6.0, 6.0, 5.0, 35.0, 10.0, 24.0, 12.0, 13.0, 23.0, 28.0, 5.0, 14.0, 43.0, 38.0, 6.0, 6.0, 10.0, 6.0, 6.0, 26.0, 23.0, 19.0, 15.0, 6.0, 34.0, 5.0, 5.0, 11.0, 39.0, 15.0, 16.0, 47.0, 38.0, 23.0, 29.0, 33.0, 32.0, 6.0, 1.0, 12.0, 15.0, 13.0, 5.0, 5.0, 5.0, 20.0, 5.0, 5.0, 16.0, 6.0, 38.0, 10.0, 6.0, 27.0, 6.0, 9.0, 14.0, 14.0, 32.0, 10.0, 10.0, 10.0, 6.0, 5.0, 26.0, 41.0, 25.0, 5.0, 5.0, 19.0, 10.0, 10.0, 14.0, 20.0, 28.0, 6.0, 18.0, 17.0, 18.0, 5.0, 5.0, 10.0, 54.0, 8.0, 16.0, 18.0, 19.0, 5.0, 21.0, 23.0, 9.0, 20.0, 30.0, 6.0, 5.0, 5.0, 11.0, 7.0, 12.0, 6.0, 14.0, 6.0, 10.0, 26.0, 11.0, 15.0, 25.0, 5.0, 18.0, 10.0, 10.0, 28.0, 14.0, 4.0, 6.0, 16.0, 14.0, 9.0, 21.0, 21.0, 5.0, 7.0, 20.0, 5.0, 21.0, 11.0, 46.0, 24.0, 30.0, 31.0, 7.0, 25.0, 16.0, 21.0, 5.0, 6.0, 5.0, 10.0, 24.0, 8.0, 35.0, 22.0, 9.0, 7.0, 20.0, 23.0, 5.0, 5.0, 15.0, 9.0, 5.0, 15.0, 25.0, 6.0, 6.0, 15.0, 30.0, 5.0, 32.0, 7.0, 12.0, 12.0, 45.0, 20.0, 15.0, 16.0, 32.0, 5.0, 35.0, 13.0, 13.0, 4.0, 5.0, 5.0, 12.0, 16.0, 21.0, 24.0, 18.0, 8.0, 18.0, 5.0, 26.0, 9.0, 22.0, 4.0, 11.0, 10.0, 16.0, 11.0, 13.0, 21.0, 16.0, 13.0, 10.0, 21.0, 13.0, 12.0, 10.0, 17.0, 35.0, 15.0, 36.0, 5.0, 5.0, 18.0, 4.0, 27.0, 12.0, 4.0, 10.0, 16.0, 9.0, 11.0, 19.0, 28.0, 19.0, 12.0, 28.0, 9.0, 25.0, 21.0, 12.0, 12.0, 16.0, 12.0, 17.0, 24.0, 14.0, 22.0, 15.0, 10.0, 33.0, 9.0, 5.0, 8.0, 11.0, 12.0, 12.0, 13.0, 24.0, 7.0, 23.0, 23.0, 1.0, 2.0, 7.0, 5.5, 6.0, 7.0, 21.0, 12.0, 9.0, 26.0, 20.0, 11.0, 19.0, 21.0, 18.0, 25.0, 17.0, 7.0, 7.0, 7.0, 24.0, 21.0, 5.0, 26.0, 8.0, 14.0, 14.0, 4.0, 4.0, 4.0, 4.0, 4.0, 4.0, 7.0, 20.0, 4.0, 19.0, 8.0, 19.0, 21.0, 9.0, 9.0, 16.0, 15.0, 6.0, 15.0, 4.0, 34.0, 16.0, 5.0, 34.0, 36.0, 16.0, 27.0, 36.0, 9.0, 13.0, 9.0, 21.0, 34.0, 9.0, 26.0, 14.0, 12.0, 12.0, 9.0, 26.0, 41.0, 10.0, 16.0, 17.0, 15.0, 15.0, 15.0, 7.0, 17.0, 16.0, 13.0, 13.0, 27.0, 31.0, 36.0, 28.0, 6.0, 6.0, 7.0, 7.0, 30.0, 18.0, 10.0, 30.0, 14.0, 9.0, 8.0, 29.0, 32.0, 23.0, 30.0, 16.0, 10.0, 17.0, 27.0, 17.0, 6.0, 10.0, 16.0, 11.0, 15.0, 12.0, 6.0, 34.0, 7.0, 3.0, 3.0, 4.0, 3.0, 3.0, 7.0, 26.0, 32.0, 38.0, 10.0, 14.0, 53.0, 52.0, 11.0, 10.0, 8.0, 13.0, 29.0, 19.0, 6.0, 23.0, 7.0, 13.0, 9.0, 13.0, 10.0, 11.0, 7.0, 11.0, 6.0, 10.0, 6.0, 5.0, 6.0, 9.0, 5.0, 12.0, 25.0, 12.0, 18.0, 7.0, 6.0, 20.0, 24.0, 6.0, 23.0, 29.0, 7.0, 6.0, 6.0, 6.0, 7.0, 35.0, 31.0, 9.0, 3.0, 8.0, 13.0, 51.0, 7.0, 3.0, 35.0, 19.0, 14.0, 31.0, 30.0, 20.0, 19.0, 3.0, 4.0, 7.0, 6.0, 31.0, 13.0, 4.0, 27.0, 12.0, 12.0, 26.0, 7.0, 12.0, 11.0, 22.0, 3.0, 14.0, 12.0, 36.0, 10.0, 3.0, 4.0, 3.0, 12.0, 17.0, 14.0, 28.0, 41.0, 9.0, 9.0, 5.0, 14.0, 15.0, 5.0, 26.0, 20.0, 25.0, 21.0, 16.0, 13.0, 18.0, 12.0, 32.0, 33.0, 27.0, 3.0, 6.0, 16.0, 19.0, 9.0, 5.0, 3.0, 28.0, 30.0, 3.0, 7.0, 6.0, 6.0, 5.0, 6.0, 13.0, 3.0, 28.0, 19.0, 30.0, 33.0, 16.0, 45.0, 3.0, 3.0, 37.5, 3.0, 37.5, 31.0, 32.0, 40.0, 3.0, 18.0, 22.0, 42.0, 8.0, 10.0, 11.0, 9.0, 6.0, 5.0, 5.0, 23.0, 14.0, 18.0, 16.0, 13.0, 9.0, 10.0, 4.0, 27.0, 6.0, 23.0, 6.0, 3.0, 29.0, 15.0, 14.0, 7.0, 8.0, 21.0, 27.0, 17.0, 3.0, 13.0, 3.0, 26.0, 28.0, 24.0, 5.0, 57.0, 18.0, 10.0, 6.0, 22.0, 6.0, 29.0, 16.0, 33.0, 24.0, 6.0, 16.0, 35.0, 31.0, 6.0, 6.0, 9.0, 6.0, 4.0, 16.0, 9.0, 17.0, 50.0, 45.0, 16.0, 22.0, 11.0, 6.0, 12.0, 12.0, 10.0, 15.0, 7.0, 29.0, 8.0, 5.0, 5.0, 26.0, 5.0, 26.0, 48.0, 23.0, 6.0, 17.0, 11.0, 5.0, 41.0, 16.0, 11.0, 6.0, 6.0, 5.0, 6.0, 6.0, 11.0, 6.0, 15.0, 21.0, 23.0, 4.0, 19.0, 5.0, 6.0, 33.0, 24.0, 24.0, 14.0, 8.0, 22.0, 5.0, 6.0, 20.0, 10.0, 43.0, 8.0, 25.0, 17.0, 33.0, 9.0, 8.0, 18.0, 27.0, 8.0, 18.0, 19.0, 15.0, 48.0, 14.0, 11.0, 6.0, 7.0, 12.0, 11.0, 36.0, 28.0, 15.0, 10.0, 72.0, 15.0, 15.0, 22.0, 24.0, 27.0, 6.0, 6.0, 20.0, 26.0, 43.0, 12.0, 15.0, 19.0, 17.0, 34.0, 13.0, 26.0, 16.0, 13.0, 21.0, 28.0, 26.0, 24.0, 25.0, 34.0, 17.0, 13.0, 3.0, 3.0, 3.0, 28.0, 9.0, 17.0, 18.0, 20.0, 17.0, 3.0, 20.0, 6.0, 25.0, 14.0, 6.0, 51.0, 15.0, 11.0, 5.0, 15.0, 20.0, 4.0, 28.0, 21.0, 24.0, 22.0, 15.0, 27.0, 12.0, 14.0, 20.0, 24.0, 17.0, 16.0, 10.0, 18.0, 12.0, 16.0, 9.0, 21.0, 18.0, 13.0, 17.0, 31.0, 6.0, 12.0, 4.0, 19.0, 15.0, 13.0, 17.0, 8.0, 10.0, 5.0, 7.0, 21.0, 32.0, 8.0, 14.0, 7.0, 5.0, 4.0, 27.0, 52.0, 6.0, 11.0, 13.0, 11.0, 10.0, 10.0, 10.0, 9.0, 16.0, 4.0, 12.0, 5.0, 34.0, 16.0, 13.0, 7.0, 23.0, 10.0, 11.0, 4.0, 25.0, 20.0, 34.0, 8.0, 7.0, 36.0, 15.0, 5.0, 5.0, 19.0, 27.0, 3.0, 4.0, 17.0, 13.0, 10.0, 33.0, 6.0, 3.0, 12.0, 18.0, 8.0, 40.0, 35.0, 5.0, 8.0, 12.0, 3.0, 8.0, 21.0, 3.0, 32.0, 24.0, 39.0, 14.0, 8.0, 23.0, 6.0, 27.0, 38.0, 18.0, 13.0, 3.0, 11.0, 55.0, 27.0, 15.0, 3.0, 31.0, 15.0, 19.0, 18.0, 8.0, 31.0, 19.0, 22.0, 40.0, 15.0, 8.0, 37.0, 27.0, 7.0, 9.0, 38.0, 8.0, 7.0, 34.0, 6.0, 14.0, 14.0, 34.0, 31.0, 19.0, 20.0, 8.0, 8.0, 23.0, 14.0, 48.0, 16.0, 16.0, 3.0, 10.0, 6.0, 3.0, 6.0, 4.0, 8.0, 9.0, 9.0, 5.0, 4.0, 8.0, 6.0, 23.0, 15.0, 15.0, 7.0, 7.0, 8.0, 21.0, 15.0, 6.0, 5.0, 6.0, 6.0, 17.0, 7.0, 26.0, 19.0, 11.0, 17.0, 16.0, 16.0, 23.0, 29.0, 7.0, 14.0, 9.0, 29.0, 22.0, 18.0, 18.0, 15.0, 21.0, 42.0, 9.0, 13.0, 18.0, 32.0, 13.0, 15.0, 24.0, 20.0, 15.0, 34.0, 11.0, 19.0, 29.0, 14.0, 12.0, 16.0, 17.0, 12.0, 19.0, 17.0, 17.0, 18.0, 32.0, 18.0, 15.0, 15.0, 12.0, 66.0, 31.0, 12.0, 26.0, 24.0, 25.0, 15.0, 19.0, 15.0, 35.0, 15.0, 23.0, 12.0, 16.0, 13.0, 13.0, 24.0, 9.0, 13.0, 32.0, 24.0, 22.0, 34.0, 18.0, 34.0, 29.0, 26.0, 16.0, 29.0, 28.0, 32.0, 39.0, 32.0, 18.0], "yaxis": "y"}, {"marker": {"color": "rgba(20, 36, 44, 0.7)"}, "name": "", "points": false, "type": "violin", "xaxis": "x2", "y": [11.0, 25.0, 15.0, 17.0, 13.0, 15.0, 15.0, 9.0, 17.0, 15.0, 16.0, 9.0, 52.0, 51.0, 35.0, 16.0, 6.0, 17.0, 29.0, 23.0, 10.0, 9.0, 21.0, 11.0, 4.0, 14.0, 8.0, 17.0, 22.0, 15.0, 40.0, 13.0, 5.0, 3.0, 13.0, 7.0, 12.0, 17.0, 8.0, 9.0, 5.0, 8.0, 22.0, 12.0, 5.0, 12.0, 4.0, 8.0, 6.0, 30.0, 33.0, 25.0, 4.0, 50.0, 17.0, 9.0, 19.0, 20.0, 12.0, 13.0, 4.0, 11.0, 6.0, 27.0, 8.0, 15.0, 17.0, 18.0, 11.0, 28.0, 9.0, 14.0, 12.0, 27.0, 3.0, 22.0, 21.0, 16.0, 18.0, 19.0, 20.0, 9.0, 34.0, 8.0, 42.0, 19.0, 41.0, 17.0, 8.0, 3.0, 5.0, 13.0, 11.0, 8.0, 12.0, 5.0, 18.0, 15.0, 18.0, 37.0, 12.0, 11.0, 14.0, 22.0, 13.0, 11.0, 7.0, 14.0, 22.0, 10.0, 3.0, 11.0, 21.0, 27.0, 3.0, 3.0, 3.0, 6.0, 30.0, 17.0, 17.0, 13.0, 16.0, 10.0, 13.0, 15.0, 17.0, 27.0, 3.0, 32.0, 21.0, 10.0, 12.0, 11.0, 5.0, 32.0, 25.0, 29.0, 28.0, 12.0, 18.0, 7.0, 9.0, 17.0, 36.0, 35.0, 14.0, 18.0, 17.0, 11.0, 15.0, 4.0, 6.0, 24.0, 7.0, 19.0, 8.0, 7.0, 10.0, 23.0, 16.0, 11.0, 8.0, 26.0, 14.0, 9.0, 15.0, 17.0, 21.0, 21.0, 16.0, 7.0, 24.0, 15.0, 12.0, 13.0, 12.0, 9.0, 39.0, 16.0, 16.0, 14.0, 9.0, 26.0, 18.0, 7.0, 5.0, 10.0, 5.0, 28.0, 10.0, 26.0, 13.0, 11.0, 10.0, 24.0, 24.0, 16.0, 5.0, 8.0, 15.0, 29.0, 27.0, 9.0, 10.0, 19.0, 12.0, 18.0, 7.0, 14.0, 15.0, 5.0, 6.0, 28.0, 10.0, 6.0, 16.0, 11.0, 9.0, 16.0, 16.0, 5.0, 8.0, 17.0, 5.0, 12.0, 8.0, 14.0, 18.0, 12.0, 10.0, 23.0, 5.0, 6.0, 26.0, 15.0, 7.0, 4.0, 27.0, 17.0, 10.0, 27.0, 5.0, 10.0, 6.0, 5.0, 12.0, 32.0, 25.0, 29.0, 20.0, 33.0, 6.0, 18.0, 5.0, 17.0, 5.0, 26.0, 8.0, 5.0, 8.0, 20.0, 7.0, 12.0, 5.0, 12.0, 6.0, 7.0, 6.0, 5.0, 9.0, 15.0, 19.0, 30.0, 26.0, 20.0, 37.0, 30.0, 21.0, 25.0, 6.0, 35.0, 13.0, 6.0, 5.0, 6.0, 7.0, 10.0, 21.0, 16.0, 17.0, 7.0, 6.0, 29.0, 28.0, 12.0, 10.0, 5.0, 6.0, 6.0, 40.0, 17.0, 6.0, 15.0, 11.0, 17.0, 11.0, 8.0, 23.0, 40.5, 17.0, 29.0, 12.0, 10.0, 10.0, 14.0, 21.0, 6.0, 6.0, 7.0, 7.0, 11.0, 15.0, 6.0, 35.0, 11.0, 26.0, 12.0, 6.0, 6.0, 19.0, 6.0, 24.0, 11.0, 17.0, 23.0, 11.0, 23.0, 17.0, 23.0, 16.0, 12.0, 6.0, 13.0, 6.0, 7.0, 68.0, 13.0, 9.0, 20.0, 19.0, 10.0, 15.0, 11.0, 9.0, 12.0, 6.0, 26.0, 26.0, 23.0, 15.0, 6.0, 24.0, 31.0, 6.0, 34.0, 7.0, 34.0, 35.0, 32.0, 15.0, 6.0, 19.0, 6.0, 9.0, 13.0, 21.0, 12.0, 6.0, 22.0, 38.0, 6.0, 7.0, 6.0, 7.0, 6.0, 11.0, 5.0, 6.0, 31.0, 6.0, 7.0, 17.0, 9.0, 18.0, 5.0, 21.0, 6.0, 5.0, 29.0, 10.0, 14.0, 6.0, 10.0, 25.0, 5.0, 10.0, 21.0, 7.0, 6.0, 36.0, 15.0, 25.0, 25.0, 5.0, 10.0, 5.0, 6.0, 6.0, 6.0, 6.0, 6.0, 6.0, 7.0, 6.0, 6.0, 5.0, 35.0, 10.0, 24.0, 12.0, 13.0, 23.0, 28.0, 5.0, 14.0, 43.0, 38.0, 6.0, 6.0, 10.0, 6.0, 6.0, 26.0, 23.0, 19.0, 15.0, 6.0, 34.0, 5.0, 5.0, 11.0, 39.0, 15.0, 16.0, 47.0, 38.0, 23.0, 29.0, 33.0, 32.0, 6.0, 1.0, 12.0, 15.0, 13.0, 5.0, 5.0, 5.0, 20.0, 5.0, 5.0, 16.0, 6.0, 38.0, 10.0, 6.0, 27.0, 6.0, 9.0, 14.0, 14.0, 32.0, 10.0, 10.0, 10.0, 6.0, 5.0, 26.0, 41.0, 25.0, 5.0, 5.0, 19.0, 10.0, 10.0, 14.0, 20.0, 28.0, 6.0, 18.0, 17.0, 18.0, 5.0, 5.0, 10.0, 54.0, 8.0, 16.0, 18.0, 19.0, 5.0, 21.0, 23.0, 9.0, 20.0, 30.0, 6.0, 5.0, 5.0, 11.0, 7.0, 12.0, 6.0, 14.0, 6.0, 10.0, 26.0, 11.0, 15.0, 25.0, 5.0, 18.0, 10.0, 10.0, 28.0, 14.0, 4.0, 6.0, 16.0, 14.0, 9.0, 21.0, 21.0, 5.0, 7.0, 20.0, 5.0, 21.0, 11.0, 46.0, 24.0, 30.0, 31.0, 7.0, 25.0, 16.0, 21.0, 5.0, 6.0, 5.0, 10.0, 24.0, 8.0, 35.0, 22.0, 9.0, 7.0, 20.0, 23.0, 5.0, 5.0, 15.0, 9.0, 5.0, 15.0, 25.0, 6.0, 6.0, 15.0, 30.0, 5.0, 32.0, 7.0, 12.0, 12.0, 45.0, 20.0, 15.0, 16.0, 32.0, 5.0, 35.0, 13.0, 13.0, 4.0, 5.0, 5.0, 12.0, 16.0, 21.0, 24.0, 18.0, 8.0, 18.0, 5.0, 26.0, 9.0, 22.0, 4.0, 11.0, 10.0, 16.0, 11.0, 13.0, 21.0, 16.0, 13.0, 10.0, 21.0, 13.0, 12.0, 10.0, 17.0, 35.0, 15.0, 36.0, 5.0, 5.0, 18.0, 4.0, 27.0, 12.0, 4.0, 10.0, 16.0, 9.0, 11.0, 19.0, 28.0, 19.0, 12.0, 28.0, 9.0, 25.0, 21.0, 12.0, 12.0, 16.0, 12.0, 17.0, 24.0, 14.0, 22.0, 15.0, 10.0, 33.0, 9.0, 5.0, 8.0, 11.0, 12.0, 12.0, 13.0, 24.0, 7.0, 23.0, 23.0, 1.0, 2.0, 7.0, 5.5, 6.0, 7.0, 21.0, 12.0, 9.0, 26.0, 20.0, 11.0, 19.0, 21.0, 18.0, 25.0, 17.0, 7.0, 7.0, 7.0, 24.0, 21.0, 5.0, 26.0, 8.0, 14.0, 14.0, 4.0, 4.0, 4.0, 4.0, 4.0, 4.0, 7.0, 20.0, 4.0, 19.0, 8.0, 19.0, 21.0, 9.0, 9.0, 16.0, 15.0, 6.0, 15.0, 4.0, 34.0, 16.0, 5.0, 34.0, 36.0, 16.0, 27.0, 36.0, 9.0, 13.0, 9.0, 21.0, 34.0, 9.0, 26.0, 14.0, 12.0, 12.0, 9.0, 26.0, 41.0, 10.0, 16.0, 17.0, 15.0, 15.0, 15.0, 7.0, 17.0, 16.0, 13.0, 13.0, 27.0, 31.0, 36.0, 28.0, 6.0, 6.0, 7.0, 7.0, 30.0, 18.0, 10.0, 30.0, 14.0, 9.0, 8.0, 29.0, 32.0, 23.0, 30.0, 16.0, 10.0, 17.0, 27.0, 17.0, 6.0, 10.0, 16.0, 11.0, 15.0, 12.0, 6.0, 34.0, 7.0, 3.0, 3.0, 4.0, 3.0, 3.0, 7.0, 26.0, 32.0, 38.0, 10.0, 14.0, 53.0, 52.0, 11.0, 10.0, 8.0, 13.0, 29.0, 19.0, 6.0, 23.0, 7.0, 13.0, 9.0, 13.0, 10.0, 11.0, 7.0, 11.0, 6.0, 10.0, 6.0, 5.0, 6.0, 9.0, 5.0, 12.0, 25.0, 12.0, 18.0, 7.0, 6.0, 20.0, 24.0, 6.0, 23.0, 29.0, 7.0, 6.0, 6.0, 6.0, 7.0, 35.0, 31.0, 9.0, 3.0, 8.0, 13.0, 51.0, 7.0, 3.0, 35.0, 19.0, 14.0, 31.0, 30.0, 20.0, 19.0, 3.0, 4.0, 7.0, 6.0, 31.0, 13.0, 4.0, 27.0, 12.0, 12.0, 26.0, 7.0, 12.0, 11.0, 22.0, 3.0, 14.0, 12.0, 36.0, 10.0, 3.0, 4.0, 3.0, 12.0, 17.0, 14.0, 28.0, 41.0, 9.0, 9.0, 5.0, 14.0, 15.0, 5.0, 26.0, 20.0, 25.0, 21.0, 16.0, 13.0, 18.0, 12.0, 32.0, 33.0, 27.0, 3.0, 6.0, 16.0, 19.0, 9.0, 5.0, 3.0, 28.0, 30.0, 3.0, 7.0, 6.0, 6.0, 5.0, 6.0, 13.0, 3.0, 28.0, 19.0, 30.0, 33.0, 16.0, 45.0, 3.0, 3.0, 37.5, 3.0, 37.5, 31.0, 32.0, 40.0, 3.0, 18.0, 22.0, 42.0, 8.0, 10.0, 11.0, 9.0, 6.0, 5.0, 5.0, 23.0, 14.0, 18.0, 16.0, 13.0, 9.0, 10.0, 4.0, 27.0, 6.0, 23.0, 6.0, 3.0, 29.0, 15.0, 14.0, 7.0, 8.0, 21.0, 27.0, 17.0, 3.0, 13.0, 3.0, 26.0, 28.0, 24.0, 5.0, 57.0, 18.0, 10.0, 6.0, 22.0, 6.0, 29.0, 16.0, 33.0, 24.0, 6.0, 16.0, 35.0, 31.0, 6.0, 6.0, 9.0, 6.0, 4.0, 16.0, 9.0, 17.0, 50.0, 45.0, 16.0, 22.0, 11.0, 6.0, 12.0, 12.0, 10.0, 15.0, 7.0, 29.0, 8.0, 5.0, 5.0, 26.0, 5.0, 26.0, 48.0, 23.0, 6.0, 17.0, 11.0, 5.0, 41.0, 16.0, 11.0, 6.0, 6.0, 5.0, 6.0, 6.0, 11.0, 6.0, 15.0, 21.0, 23.0, 4.0, 19.0, 5.0, 6.0, 33.0, 24.0, 24.0, 14.0, 8.0, 22.0, 5.0, 6.0, 20.0, 10.0, 43.0, 8.0, 25.0, 17.0, 33.0, 9.0, 8.0, 18.0, 27.0, 8.0, 18.0, 19.0, 15.0, 48.0, 14.0, 11.0, 6.0, 7.0, 12.0, 11.0, 36.0, 28.0, 15.0, 10.0, 72.0, 15.0, 15.0, 22.0, 24.0, 27.0, 6.0, 6.0, 20.0, 26.0, 43.0, 12.0, 15.0, 19.0, 17.0, 34.0, 13.0, 26.0, 16.0, 13.0, 21.0, 28.0, 26.0, 24.0, 25.0, 34.0, 17.0, 13.0, 3.0, 3.0, 3.0, 28.0, 9.0, 17.0, 18.0, 20.0, 17.0, 3.0, 20.0, 6.0, 25.0, 14.0, 6.0, 51.0, 15.0, 11.0, 5.0, 15.0, 20.0, 4.0, 28.0, 21.0, 24.0, 22.0, 15.0, 27.0, 12.0, 14.0, 20.0, 24.0, 17.0, 16.0, 10.0, 18.0, 12.0, 16.0, 9.0, 21.0, 18.0, 13.0, 17.0, 31.0, 6.0, 12.0, 4.0, 19.0, 15.0, 13.0, 17.0, 8.0, 10.0, 5.0, 7.0, 21.0, 32.0, 8.0, 14.0, 7.0, 5.0, 4.0, 27.0, 52.0, 6.0, 11.0, 13.0, 11.0, 10.0, 10.0, 10.0, 9.0, 16.0, 4.0, 12.0, 5.0, 34.0, 16.0, 13.0, 7.0, 23.0, 10.0, 11.0, 4.0, 25.0, 20.0, 34.0, 8.0, 7.0, 36.0, 15.0, 5.0, 5.0, 19.0, 27.0, 3.0, 4.0, 17.0, 13.0, 10.0, 33.0, 6.0, 3.0, 12.0, 18.0, 8.0, 40.0, 35.0, 5.0, 8.0, 12.0, 3.0, 8.0, 21.0, 3.0, 32.0, 24.0, 39.0, 14.0, 8.0, 23.0, 6.0, 27.0, 38.0, 18.0, 13.0, 3.0, 11.0, 55.0, 27.0, 15.0, 3.0, 31.0, 15.0, 19.0, 18.0, 8.0, 31.0, 19.0, 22.0, 40.0, 15.0, 8.0, 37.0, 27.0, 7.0, 9.0, 38.0, 8.0, 7.0, 34.0, 6.0, 14.0, 14.0, 34.0, 31.0, 19.0, 20.0, 8.0, 8.0, 23.0, 14.0, 48.0, 16.0, 16.0, 3.0, 10.0, 6.0, 3.0, 6.0, 4.0, 8.0, 9.0, 9.0, 5.0, 4.0, 8.0, 6.0, 23.0, 15.0, 15.0, 7.0, 7.0, 8.0, 21.0, 15.0, 6.0, 5.0, 6.0, 6.0, 17.0, 7.0, 26.0, 19.0, 11.0, 17.0, 16.0, 16.0, 23.0, 29.0, 7.0, 14.0, 9.0, 29.0, 22.0, 18.0, 18.0, 15.0, 21.0, 42.0, 9.0, 13.0, 18.0, 32.0, 13.0, 15.0, 24.0, 20.0, 15.0, 34.0, 11.0, 19.0, 29.0, 14.0, 12.0, 16.0, 17.0, 12.0, 19.0, 17.0, 17.0, 18.0, 32.0, 18.0, 15.0, 15.0, 12.0, 66.0, 31.0, 12.0, 26.0, 24.0, 25.0, 15.0, 19.0, 15.0, 35.0, 15.0, 23.0, 12.0, 16.0, 13.0, 13.0, 24.0, 9.0, 13.0, 32.0, 24.0, 22.0, 34.0, 18.0, 34.0, 29.0, 26.0, 16.0, 29.0, 28.0, 32.0, 39.0, 32.0, 18.0], "yaxis": "y2"}, {"hovertemplate": "%{y:.d}<extra></extra>", "marker": {"color": "rgba(20, 36, 44, 0.7)"}, "type": "histogram", "x": [11.0, 25.0, 15.0, 17.0, 13.0, 15.0, 15.0, 9.0, 17.0, 15.0, 16.0, 9.0, 52.0, 51.0, 35.0, 16.0, 6.0, 17.0, 29.0, 23.0, 10.0, 9.0, 21.0, 11.0, 4.0, 14.0, 8.0, 17.0, 22.0, 15.0, 40.0, 13.0, 5.0, 3.0, 13.0, 7.0, 12.0, 17.0, 8.0, 9.0, 5.0, 8.0, 22.0, 12.0, 5.0, 12.0, 4.0, 8.0, 6.0, 30.0, 33.0, 25.0, 4.0, 50.0, 17.0, 9.0, 19.0, 20.0, 12.0, 13.0, 4.0, 11.0, 6.0, 27.0, 8.0, 15.0, 17.0, 18.0, 11.0, 28.0, 9.0, 14.0, 12.0, 27.0, 3.0, 22.0, 21.0, 16.0, 18.0, 19.0, 20.0, 9.0, 34.0, 8.0, 42.0, 19.0, 41.0, 17.0, 8.0, 3.0, 5.0, 13.0, 11.0, 8.0, 12.0, 5.0, 18.0, 15.0, 18.0, 37.0, 12.0, 11.0, 14.0, 22.0, 13.0, 11.0, 7.0, 14.0, 22.0, 10.0, 3.0, 11.0, 21.0, 27.0, 3.0, 3.0, 3.0, 6.0, 30.0, 17.0, 17.0, 13.0, 16.0, 10.0, 13.0, 15.0, 17.0, 27.0, 3.0, 32.0, 21.0, 10.0, 12.0, 11.0, 5.0, 32.0, 25.0, 29.0, 28.0, 12.0, 18.0, 7.0, 9.0, 17.0, 36.0, 35.0, 14.0, 18.0, 17.0, 11.0, 15.0, 4.0, 6.0, 24.0, 7.0, 19.0, 8.0, 7.0, 10.0, 23.0, 16.0, 11.0, 8.0, 26.0, 14.0, 9.0, 15.0, 17.0, 21.0, 21.0, 16.0, 7.0, 24.0, 15.0, 12.0, 13.0, 12.0, 9.0, 39.0, 16.0, 16.0, 14.0, 9.0, 26.0, 18.0, 7.0, 5.0, 10.0, 5.0, 28.0, 10.0, 26.0, 13.0, 11.0, 10.0, 24.0, 24.0, 16.0, 5.0, 8.0, 15.0, 29.0, 27.0, 9.0, 10.0, 19.0, 12.0, 18.0, 7.0, 14.0, 15.0, 5.0, 6.0, 28.0, 10.0, 6.0, 16.0, 11.0, 9.0, 16.0, 16.0, 5.0, 8.0, 17.0, 5.0, 12.0, 8.0, 14.0, 18.0, 12.0, 10.0, 23.0, 5.0, 6.0, 26.0, 15.0, 7.0, 4.0, 27.0, 17.0, 10.0, 27.0, 5.0, 10.0, 6.0, 5.0, 12.0, 32.0, 25.0, 29.0, 20.0, 33.0, 6.0, 18.0, 5.0, 17.0, 5.0, 26.0, 8.0, 5.0, 8.0, 20.0, 7.0, 12.0, 5.0, 12.0, 6.0, 7.0, 6.0, 5.0, 9.0, 15.0, 19.0, 30.0, 26.0, 20.0, 37.0, 30.0, 21.0, 25.0, 6.0, 35.0, 13.0, 6.0, 5.0, 6.0, 7.0, 10.0, 21.0, 16.0, 17.0, 7.0, 6.0, 29.0, 28.0, 12.0, 10.0, 5.0, 6.0, 6.0, 40.0, 17.0, 6.0, 15.0, 11.0, 17.0, 11.0, 8.0, 23.0, 40.5, 17.0, 29.0, 12.0, 10.0, 10.0, 14.0, 21.0, 6.0, 6.0, 7.0, 7.0, 11.0, 15.0, 6.0, 35.0, 11.0, 26.0, 12.0, 6.0, 6.0, 19.0, 6.0, 24.0, 11.0, 17.0, 23.0, 11.0, 23.0, 17.0, 23.0, 16.0, 12.0, 6.0, 13.0, 6.0, 7.0, 68.0, 13.0, 9.0, 20.0, 19.0, 10.0, 15.0, 11.0, 9.0, 12.0, 6.0, 26.0, 26.0, 23.0, 15.0, 6.0, 24.0, 31.0, 6.0, 34.0, 7.0, 34.0, 35.0, 32.0, 15.0, 6.0, 19.0, 6.0, 9.0, 13.0, 21.0, 12.0, 6.0, 22.0, 38.0, 6.0, 7.0, 6.0, 7.0, 6.0, 11.0, 5.0, 6.0, 31.0, 6.0, 7.0, 17.0, 9.0, 18.0, 5.0, 21.0, 6.0, 5.0, 29.0, 10.0, 14.0, 6.0, 10.0, 25.0, 5.0, 10.0, 21.0, 7.0, 6.0, 36.0, 15.0, 25.0, 25.0, 5.0, 10.0, 5.0, 6.0, 6.0, 6.0, 6.0, 6.0, 6.0, 7.0, 6.0, 6.0, 5.0, 35.0, 10.0, 24.0, 12.0, 13.0, 23.0, 28.0, 5.0, 14.0, 43.0, 38.0, 6.0, 6.0, 10.0, 6.0, 6.0, 26.0, 23.0, 19.0, 15.0, 6.0, 34.0, 5.0, 5.0, 11.0, 39.0, 15.0, 16.0, 47.0, 38.0, 23.0, 29.0, 33.0, 32.0, 6.0, 1.0, 12.0, 15.0, 13.0, 5.0, 5.0, 5.0, 20.0, 5.0, 5.0, 16.0, 6.0, 38.0, 10.0, 6.0, 27.0, 6.0, 9.0, 14.0, 14.0, 32.0, 10.0, 10.0, 10.0, 6.0, 5.0, 26.0, 41.0, 25.0, 5.0, 5.0, 19.0, 10.0, 10.0, 14.0, 20.0, 28.0, 6.0, 18.0, 17.0, 18.0, 5.0, 5.0, 10.0, 54.0, 8.0, 16.0, 18.0, 19.0, 5.0, 21.0, 23.0, 9.0, 20.0, 30.0, 6.0, 5.0, 5.0, 11.0, 7.0, 12.0, 6.0, 14.0, 6.0, 10.0, 26.0, 11.0, 15.0, 25.0, 5.0, 18.0, 10.0, 10.0, 28.0, 14.0, 4.0, 6.0, 16.0, 14.0, 9.0, 21.0, 21.0, 5.0, 7.0, 20.0, 5.0, 21.0, 11.0, 46.0, 24.0, 30.0, 31.0, 7.0, 25.0, 16.0, 21.0, 5.0, 6.0, 5.0, 10.0, 24.0, 8.0, 35.0, 22.0, 9.0, 7.0, 20.0, 23.0, 5.0, 5.0, 15.0, 9.0, 5.0, 15.0, 25.0, 6.0, 6.0, 15.0, 30.0, 5.0, 32.0, 7.0, 12.0, 12.0, 45.0, 20.0, 15.0, 16.0, 32.0, 5.0, 35.0, 13.0, 13.0, 4.0, 5.0, 5.0, 12.0, 16.0, 21.0, 24.0, 18.0, 8.0, 18.0, 5.0, 26.0, 9.0, 22.0, 4.0, 11.0, 10.0, 16.0, 11.0, 13.0, 21.0, 16.0, 13.0, 10.0, 21.0, 13.0, 12.0, 10.0, 17.0, 35.0, 15.0, 36.0, 5.0, 5.0, 18.0, 4.0, 27.0, 12.0, 4.0, 10.0, 16.0, 9.0, 11.0, 19.0, 28.0, 19.0, 12.0, 28.0, 9.0, 25.0, 21.0, 12.0, 12.0, 16.0, 12.0, 17.0, 24.0, 14.0, 22.0, 15.0, 10.0, 33.0, 9.0, 5.0, 8.0, 11.0, 12.0, 12.0, 13.0, 24.0, 7.0, 23.0, 23.0, 1.0, 2.0, 7.0, 5.5, 6.0, 7.0, 21.0, 12.0, 9.0, 26.0, 20.0, 11.0, 19.0, 21.0, 18.0, 25.0, 17.0, 7.0, 7.0, 7.0, 24.0, 21.0, 5.0, 26.0, 8.0, 14.0, 14.0, 4.0, 4.0, 4.0, 4.0, 4.0, 4.0, 7.0, 20.0, 4.0, 19.0, 8.0, 19.0, 21.0, 9.0, 9.0, 16.0, 15.0, 6.0, 15.0, 4.0, 34.0, 16.0, 5.0, 34.0, 36.0, 16.0, 27.0, 36.0, 9.0, 13.0, 9.0, 21.0, 34.0, 9.0, 26.0, 14.0, 12.0, 12.0, 9.0, 26.0, 41.0, 10.0, 16.0, 17.0, 15.0, 15.0, 15.0, 7.0, 17.0, 16.0, 13.0, 13.0, 27.0, 31.0, 36.0, 28.0, 6.0, 6.0, 7.0, 7.0, 30.0, 18.0, 10.0, 30.0, 14.0, 9.0, 8.0, 29.0, 32.0, 23.0, 30.0, 16.0, 10.0, 17.0, 27.0, 17.0, 6.0, 10.0, 16.0, 11.0, 15.0, 12.0, 6.0, 34.0, 7.0, 3.0, 3.0, 4.0, 3.0, 3.0, 7.0, 26.0, 32.0, 38.0, 10.0, 14.0, 53.0, 52.0, 11.0, 10.0, 8.0, 13.0, 29.0, 19.0, 6.0, 23.0, 7.0, 13.0, 9.0, 13.0, 10.0, 11.0, 7.0, 11.0, 6.0, 10.0, 6.0, 5.0, 6.0, 9.0, 5.0, 12.0, 25.0, 12.0, 18.0, 7.0, 6.0, 20.0, 24.0, 6.0, 23.0, 29.0, 7.0, 6.0, 6.0, 6.0, 7.0, 35.0, 31.0, 9.0, 3.0, 8.0, 13.0, 51.0, 7.0, 3.0, 35.0, 19.0, 14.0, 31.0, 30.0, 20.0, 19.0, 3.0, 4.0, 7.0, 6.0, 31.0, 13.0, 4.0, 27.0, 12.0, 12.0, 26.0, 7.0, 12.0, 11.0, 22.0, 3.0, 14.0, 12.0, 36.0, 10.0, 3.0, 4.0, 3.0, 12.0, 17.0, 14.0, 28.0, 41.0, 9.0, 9.0, 5.0, 14.0, 15.0, 5.0, 26.0, 20.0, 25.0, 21.0, 16.0, 13.0, 18.0, 12.0, 32.0, 33.0, 27.0, 3.0, 6.0, 16.0, 19.0, 9.0, 5.0, 3.0, 28.0, 30.0, 3.0, 7.0, 6.0, 6.0, 5.0, 6.0, 13.0, 3.0, 28.0, 19.0, 30.0, 33.0, 16.0, 45.0, 3.0, 3.0, 37.5, 3.0, 37.5, 31.0, 32.0, 40.0, 3.0, 18.0, 22.0, 42.0, 8.0, 10.0, 11.0, 9.0, 6.0, 5.0, 5.0, 23.0, 14.0, 18.0, 16.0, 13.0, 9.0, 10.0, 4.0, 27.0, 6.0, 23.0, 6.0, 3.0, 29.0, 15.0, 14.0, 7.0, 8.0, 21.0, 27.0, 17.0, 3.0, 13.0, 3.0, 26.0, 28.0, 24.0, 5.0, 57.0, 18.0, 10.0, 6.0, 22.0, 6.0, 29.0, 16.0, 33.0, 24.0, 6.0, 16.0, 35.0, 31.0, 6.0, 6.0, 9.0, 6.0, 4.0, 16.0, 9.0, 17.0, 50.0, 45.0, 16.0, 22.0, 11.0, 6.0, 12.0, 12.0, 10.0, 15.0, 7.0, 29.0, 8.0, 5.0, 5.0, 26.0, 5.0, 26.0, 48.0, 23.0, 6.0, 17.0, 11.0, 5.0, 41.0, 16.0, 11.0, 6.0, 6.0, 5.0, 6.0, 6.0, 11.0, 6.0, 15.0, 21.0, 23.0, 4.0, 19.0, 5.0, 6.0, 33.0, 24.0, 24.0, 14.0, 8.0, 22.0, 5.0, 6.0, 20.0, 10.0, 43.0, 8.0, 25.0, 17.0, 33.0, 9.0, 8.0, 18.0, 27.0, 8.0, 18.0, 19.0, 15.0, 48.0, 14.0, 11.0, 6.0, 7.0, 12.0, 11.0, 36.0, 28.0, 15.0, 10.0, 72.0, 15.0, 15.0, 22.0, 24.0, 27.0, 6.0, 6.0, 20.0, 26.0, 43.0, 12.0, 15.0, 19.0, 17.0, 34.0, 13.0, 26.0, 16.0, 13.0, 21.0, 28.0, 26.0, 24.0, 25.0, 34.0, 17.0, 13.0, 3.0, 3.0, 3.0, 28.0, 9.0, 17.0, 18.0, 20.0, 17.0, 3.0, 20.0, 6.0, 25.0, 14.0, 6.0, 51.0, 15.0, 11.0, 5.0, 15.0, 20.0, 4.0, 28.0, 21.0, 24.0, 22.0, 15.0, 27.0, 12.0, 14.0, 20.0, 24.0, 17.0, 16.0, 10.0, 18.0, 12.0, 16.0, 9.0, 21.0, 18.0, 13.0, 17.0, 31.0, 6.0, 12.0, 4.0, 19.0, 15.0, 13.0, 17.0, 8.0, 10.0, 5.0, 7.0, 21.0, 32.0, 8.0, 14.0, 7.0, 5.0, 4.0, 27.0, 52.0, 6.0, 11.0, 13.0, 11.0, 10.0, 10.0, 10.0, 9.0, 16.0, 4.0, 12.0, 5.0, 34.0, 16.0, 13.0, 7.0, 23.0, 10.0, 11.0, 4.0, 25.0, 20.0, 34.0, 8.0, 7.0, 36.0, 15.0, 5.0, 5.0, 19.0, 27.0, 3.0, 4.0, 17.0, 13.0, 10.0, 33.0, 6.0, 3.0, 12.0, 18.0, 8.0, 40.0, 35.0, 5.0, 8.0, 12.0, 3.0, 8.0, 21.0, 3.0, 32.0, 24.0, 39.0, 14.0, 8.0, 23.0, 6.0, 27.0, 38.0, 18.0, 13.0, 3.0, 11.0, 55.0, 27.0, 15.0, 3.0, 31.0, 15.0, 19.0, 18.0, 8.0, 31.0, 19.0, 22.0, 40.0, 15.0, 8.0, 37.0, 27.0, 7.0, 9.0, 38.0, 8.0, 7.0, 34.0, 6.0, 14.0, 14.0, 34.0, 31.0, 19.0, 20.0, 8.0, 8.0, 23.0, 14.0, 48.0, 16.0, 16.0, 3.0, 10.0, 6.0, 3.0, 6.0, 4.0, 8.0, 9.0, 9.0, 5.0, 4.0, 8.0, 6.0, 23.0, 15.0, 15.0, 7.0, 7.0, 8.0, 21.0, 15.0, 6.0, 5.0, 6.0, 6.0, 17.0, 7.0, 26.0, 19.0, 11.0, 17.0, 16.0, 16.0, 23.0, 29.0, 7.0, 14.0, 9.0, 29.0, 22.0, 18.0, 18.0, 15.0, 21.0, 42.0, 9.0, 13.0, 18.0, 32.0, 13.0, 15.0, 24.0, 20.0, 15.0, 34.0, 11.0, 19.0, 29.0, 14.0, 12.0, 16.0, 17.0, 12.0, 19.0, 17.0, 17.0, 18.0, 32.0, 18.0, 15.0, 15.0, 12.0, 66.0, 31.0, 12.0, 26.0, 24.0, 25.0, 15.0, 19.0, 15.0, 35.0, 15.0, 23.0, 12.0, 16.0, 13.0, 13.0, 24.0, 9.0, 13.0, 32.0, 24.0, 22.0, 34.0, 18.0, 34.0, 29.0, 26.0, 16.0, 29.0, 28.0, 32.0, 39.0, 32.0, 18.0], "xaxis": "x3", "yaxis": "y3"}],                        {"height": 370, "hovermode": "x", "margin": {"b": 50, "l": 50, "r": 50, "t": 100}, "paper_bgcolor": "rgba(0, 0, 0, 0)", "plot_bgcolor": "rgb(243, 243, 243)", "separators": ",.", "showlegend": false, "template": {"data": {"bar": [{"error_x": {"color": "#2a3f5f"}, "error_y": {"color": "#2a3f5f"}, "marker": {"line": {"color": "#E5ECF6", "width": 0.5}}, "type": "bar"}], "barpolar": [{"marker": {"line": {"color": "#E5ECF6", "width": 0.5}}, "type": "barpolar"}], "carpet": [{"aaxis": {"endlinecolor": "#2a3f5f", "gridcolor": "white", "linecolor": "white", "minorgridcolor": "white", "startlinecolor": "#2a3f5f"}, "baxis": {"endlinecolor": "#2a3f5f", "gridcolor": "white", "linecolor": "white", "minorgridcolor": "white", "startlinecolor": "#2a3f5f"}, "type": "carpet"}], "choropleth": [{"colorbar": {"outlinewidth": 0, "ticks": ""}, "type": "choropleth"}], "contour": [{"colorbar": {"outlinewidth": 0, "ticks": ""}, "colorscale": [[0.0, "#0d0887"], [0.1111111111111111, "#46039f"], [0.2222222222222222, "#7201a8"], [0.3333333333333333, "#9c179e"], [0.4444444444444444, "#bd3786"], [0.5555555555555556, "#d8576b"], [0.6666666666666666, "#ed7953"], [0.7777777777777778, "#fb9f3a"], [0.8888888888888888, "#fdca26"], [1.0, "#f0f921"]], "type": "contour"}], "contourcarpet": [{"colorbar": {"outlinewidth": 0, "ticks": ""}, "type": "contourcarpet"}], "heatmap": [{"colorbar": {"outlinewidth": 0, "ticks": ""}, "colorscale": [[0.0, "#0d0887"], [0.1111111111111111, "#46039f"], [0.2222222222222222, "#7201a8"], [0.3333333333333333, "#9c179e"], [0.4444444444444444, "#bd3786"], [0.5555555555555556, "#d8576b"], [0.6666666666666666, "#ed7953"], [0.7777777777777778, "#fb9f3a"], [0.8888888888888888, "#fdca26"], [1.0, "#f0f921"]], "type": "heatmap"}], "heatmapgl": [{"colorbar": {"outlinewidth": 0, "ticks": ""}, "colorscale": [[0.0, "#0d0887"], [0.1111111111111111, "#46039f"], [0.2222222222222222, "#7201a8"], [0.3333333333333333, "#9c179e"], [0.4444444444444444, "#bd3786"], [0.5555555555555556, "#d8576b"], [0.6666666666666666, "#ed7953"], [0.7777777777777778, "#fb9f3a"], [0.8888888888888888, "#fdca26"], [1.0, "#f0f921"]], "type": "heatmapgl"}], "histogram": [{"marker": {"colorbar": {"outlinewidth": 0, "ticks": ""}}, "type": "histogram"}], "histogram2d": [{"colorbar": {"outlinewidth": 0, "ticks": ""}, "colorscale": [[0.0, "#0d0887"], [0.1111111111111111, "#46039f"], [0.2222222222222222, "#7201a8"], [0.3333333333333333, "#9c179e"], [0.4444444444444444, "#bd3786"], [0.5555555555555556, "#d8576b"], [0.6666666666666666, "#ed7953"], [0.7777777777777778, "#fb9f3a"], [0.8888888888888888, "#fdca26"], [1.0, "#f0f921"]], "type": "histogram2d"}], "histogram2dcontour": [{"colorbar": {"outlinewidth": 0, "ticks": ""}, "colorscale": [[0.0, "#0d0887"], [0.1111111111111111, "#46039f"], [0.2222222222222222, "#7201a8"], [0.3333333333333333, "#9c179e"], [0.4444444444444444, "#bd3786"], [0.5555555555555556, "#d8576b"], [0.6666666666666666, "#ed7953"], [0.7777777777777778, "#fb9f3a"], [0.8888888888888888, "#fdca26"], [1.0, "#f0f921"]], "type": "histogram2dcontour"}], "mesh3d": [{"colorbar": {"outlinewidth": 0, "ticks": ""}, "type": "mesh3d"}], "parcoords": [{"line": {"colorbar": {"outlinewidth": 0, "ticks": ""}}, "type": "parcoords"}], "pie": [{"automargin": true, "type": "pie"}], "scatter": [{"marker": {"colorbar": {"outlinewidth": 0, "ticks": ""}}, "type": "scatter"}], "scatter3d": [{"line": {"colorbar": {"outlinewidth": 0, "ticks": ""}}, "marker": {"colorbar": {"outlinewidth": 0, "ticks": ""}}, "type": "scatter3d"}], "scattercarpet": [{"marker": {"colorbar": {"outlinewidth": 0, "ticks": ""}}, "type": "scattercarpet"}], "scattergeo": [{"marker": {"colorbar": {"outlinewidth": 0, "ticks": ""}}, "type": "scattergeo"}], "scattergl": [{"marker": {"colorbar": {"outlinewidth": 0, "ticks": ""}}, "type": "scattergl"}], "scattermapbox": [{"marker": {"colorbar": {"outlinewidth": 0, "ticks": ""}}, "type": "scattermapbox"}], "scatterpolar": [{"marker": {"colorbar": {"outlinewidth": 0, "ticks": ""}}, "type": "scatterpolar"}], "scatterpolargl": [{"marker": {"colorbar": {"outlinewidth": 0, "ticks": ""}}, "type": "scatterpolargl"}], "scatterternary": [{"marker": {"colorbar": {"outlinewidth": 0, "ticks": ""}}, "type": "scatterternary"}], "surface": [{"colorbar": {"outlinewidth": 0, "ticks": ""}, "colorscale": [[0.0, "#0d0887"], [0.1111111111111111, "#46039f"], [0.2222222222222222, "#7201a8"], [0.3333333333333333, "#9c179e"], [0.4444444444444444, "#bd3786"], [0.5555555555555556, "#d8576b"], [0.6666666666666666, "#ed7953"], [0.7777777777777778, "#fb9f3a"], [0.8888888888888888, "#fdca26"], [1.0, "#f0f921"]], "type": "surface"}], "table": [{"cells": {"fill": {"color": "#EBF0F8"}, "line": {"color": "white"}}, "header": {"fill": {"color": "#C8D4E3"}, "line": {"color": "white"}}, "type": "table"}]}, "layout": {"annotationdefaults": {"arrowcolor": "#2a3f5f", "arrowhead": 0, "arrowwidth": 1}, "coloraxis": {"colorbar": {"outlinewidth": 0, "ticks": ""}}, "colorscale": {"diverging": [[0, "#8e0152"], [0.1, "#c51b7d"], [0.2, "#de77ae"], [0.3, "#f1b6da"], [0.4, "#fde0ef"], [0.5, "#f7f7f7"], [0.6, "#e6f5d0"], [0.7, "#b8e186"], [0.8, "#7fbc41"], [0.9, "#4d9221"], [1, "#276419"]], "sequential": [[0.0, "#0d0887"], [0.1111111111111111, "#46039f"], [0.2222222222222222, "#7201a8"], [0.3333333333333333, "#9c179e"], [0.4444444444444444, "#bd3786"], [0.5555555555555556, "#d8576b"], [0.6666666666666666, "#ed7953"], [0.7777777777777778, "#fb9f3a"], [0.8888888888888888, "#fdca26"], [1.0, "#f0f921"]], "sequentialminus": [[0.0, "#0d0887"], [0.1111111111111111, "#46039f"], [0.2222222222222222, "#7201a8"], [0.3333333333333333, "#9c179e"], [0.4444444444444444, "#bd3786"], [0.5555555555555556, "#d8576b"], [0.6666666666666666, "#ed7953"], [0.7777777777777778, "#fb9f3a"], [0.8888888888888888, "#fdca26"], [1.0, "#f0f921"]]}, "colorway": ["#636efa", "#EF553B", "#00cc96", "#ab63fa", "#FFA15A", "#19d3f3", "#FF6692", "#B6E880", "#FF97FF", "#FECB52"], "font": {"color": "#2a3f5f"}, "geo": {"bgcolor": "white", "lakecolor": "white", "landcolor": "#E5ECF6", "showlakes": true, "showland": true, "subunitcolor": "white"}, "hoverlabel": {"align": "left"}, "hovermode": "closest", "mapbox": {"style": "light"}, "paper_bgcolor": "white", "plot_bgcolor": "#E5ECF6", "polar": {"angularaxis": {"gridcolor": "white", "linecolor": "white", "ticks": ""}, "bgcolor": "#E5ECF6", "radialaxis": {"gridcolor": "white", "linecolor": "white", "ticks": ""}}, "scene": {"xaxis": {"backgroundcolor": "#E5ECF6", "gridcolor": "white", "gridwidth": 2, "linecolor": "white", "showbackground": true, "ticks": "", "zerolinecolor": "white"}, "yaxis": {"backgroundcolor": "#E5ECF6", "gridcolor": "white", "gridwidth": 2, "linecolor": "white", "showbackground": true, "ticks": "", "zerolinecolor": "white"}, "zaxis": {"backgroundcolor": "#E5ECF6", "gridcolor": "white", "gridwidth": 2, "linecolor": "white", "showbackground": true, "ticks": "", "zerolinecolor": "white"}}, "shapedefaults": {"line": {"color": "#2a3f5f"}}, "ternary": {"aaxis": {"gridcolor": "white", "linecolor": "white", "ticks": ""}, "baxis": {"gridcolor": "white", "linecolor": "white", "ticks": ""}, "bgcolor": "#E5ECF6", "caxis": {"gridcolor": "white", "linecolor": "white", "ticks": ""}}, "title": {"x": 0.05}, "xaxis": {"automargin": true, "gridcolor": "white", "linecolor": "white", "ticks": "", "title": {"standoff": 15}, "zerolinecolor": "white", "zerolinewidth": 2}, "yaxis": {"automargin": true, "gridcolor": "white", "linecolor": "white", "ticks": "", "title": {"standoff": 15}, "zerolinecolor": "white", "zerolinewidth": 2}}}, "title": {"font": {"color": "rgba(20, 36, 44, 0.7)"}, "text": "free sulfur dioxide"}, "width": 800, "xaxis": {"anchor": "y", "domain": [0.0, 0.17333333333333334], "linecolor": "rgba(100, 100, 100, 0)", "showgrid": false, "tickfont": {"color": "rgba(100, 100, 100, 0.8)"}, "zeroline": false}, "xaxis2": {"anchor": "y2", "domain": [0.24, 0.41333333333333333], "linecolor": "rgba(100, 100, 100, 0)", "showgrid": false, "tickfont": {"color": "rgba(100, 100, 100, 0.8)"}, "zeroline": false}, "xaxis3": {"anchor": "y3", "domain": [0.48, 1.0], "hoverformat": ",.2f", "linecolor": "rgba(100, 100, 100, 0)", "showgrid": false, "tickfont": {"color": "rgba(100, 100, 100, 0.8)"}, "zeroline": false}, "yaxis": {"anchor": "x", "domain": [0.0, 1.0], "hoverformat": ",.2f", "linecolor": "rgba(100, 100, 100, 0)", "showgrid": false, "tickfont": {"color": "rgba(100, 100, 100, 0.8)"}, "zeroline": false}, "yaxis2": {"anchor": "x2", "domain": [0.0, 1.0], "hoverformat": ",.2f", "linecolor": "rgba(100, 100, 100, 0)", "showgrid": false, "tickfont": {"color": "rgba(100, 100, 100, 0.8)"}, "zeroline": false}, "yaxis3": {"anchor": "x3", "domain": [0.0, 1.0], "linecolor": "rgba(100, 100, 100, 0)", "showgrid": false, "tickfont": {"color": "rgba(100, 100, 100, 0.8)"}, "zeroline": false}},                        {"displayModeBar": false, "showTips": false, "responsive": true}                    )                };                            </script></div>
