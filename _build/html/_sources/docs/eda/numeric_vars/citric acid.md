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

(citric acid)= 

# citric acid
Tipo da variável: numeric
## Relatório geral

<pre>
+--------------------------+----------+
|                          |   Values |
+==========================+==========+
| Count                    |  1359    |
+--------------------------+----------+
| Mín                      |     0    |
+--------------------------+----------+
| Q1                       |     0.09 |
+--------------------------+----------+
| Median                   |     0.26 |
+--------------------------+----------+
| Q3                       |     0.43 |
+--------------------------+----------+
| Max                      |     1    |
+--------------------------+----------+
| Mean                     |     0.27 |
+--------------------------+----------+
| Variation                |     0.04 |
+--------------------------+----------+
| Coefficient of variation |     0.72 |
+--------------------------+----------+
| Kurtosis                 |    -0.79 |
+--------------------------+----------+
| Na                       |     0    |
+--------------------------+----------+
| Outliers                 |     1    |
+--------------------------+----------+
</pre>



## Análise Univariada

<div><script src="https://cdn.plot.ly/plotly-latest.min.js"></script><div class="plotly-graph-div" id="34b891c9-8202-40c8-86f3-e0bee782e073" style="height:370px; width:800px;"></div><script type="text/javascript">                                    window.PLOTLYENV=window.PLOTLYENV || {};                                    if (document.getElementById("34b891c9-8202-40c8-86f3-e0bee782e073")) {                    Plotly.newPlot(                        "34b891c9-8202-40c8-86f3-e0bee782e073",                        [{"boxmean": true, "boxpoints": false, "marker": {"color": "rgba(20, 36, 44, 0.7)", "outliercolor": "rgba(233, 75, 59, 1)"}, "name": "", "type": "box", "xaxis": "x", "y": [0.0, 0.0, 0.04, 0.56, 0.0, 0.06, 0.0, 0.02, 0.36, 0.08, 0.0, 0.29, 0.18, 0.19, 0.56, 0.28, 0.08, 0.51, 0.48, 0.31, 0.21, 0.11, 0.14, 0.16, 0.24, 0.0, 0.0, 0.07, 0.0, 0.12, 0.12, 0.25, 0.0, 0.14, 0.28, 0.09, 0.36, 0.3, 0.2, 0.22, 0.02, 0.15, 0.43, 0.52, 0.23, 0.37, 0.26, 0.04, 0.04, 0.36, 0.15, 0.04, 0.57, 0.12, 0.18, 0.31, 0.4, 0.49, 0.16, 0.05, 0.05, 0.11, 0.07, 0.57, 0.05, 0.08, 0.23, 0.22, 0.26, 0.54, 0.64, 0.0, 0.12, 0.2, 0.2, 0.7, 0.47, 0.26, 0.48, 0.15, 0.28, 0.26, 0.44, 0.08, 0.26, 0.29, 0.04, 0.17, 0.0, 0.25, 0.06, 0.18, 0.3, 0.3, 0.22, 0.24, 0.68, 0.31, 0.53, 0.52, 0.19, 0.09, 0.1, 0.44, 0.31, 0.28, 0.12, 0.04, 0.08, 0.09, 0.0, 0.0, 0.17, 0.04, 0.0, 0.0, 0.16, 0.15, 0.56, 0.09, 0.01, 0.05, 0.11, 0.15, 0.36, 0.19, 0.19, 0.0, 0.08, 0.55, 0.02, 0.26, 0.1, 0.44, 0.47, 1.0, 0.03, 0.42, 0.42, 0.0, 0.18, 0.03, 0.02, 0.04, 0.26, 0.26, 0.48, 0.1, 0.03, 0.07, 0.24, 0.03, 0.17, 0.05, 0.21, 0.04, 0.42, 0.0, 0.14, 0.49, 0.02, 0.2, 0.21, 0.57, 0.48, 0.1, 0.33, 0.32, 0.35, 0.25, 0.12, 0.21, 0.33, 0.3, 0.6, 0.08, 0.06, 0.47, 0.48, 0.11, 0.35, 0.36, 0.74, 0.31, 0.28, 0.58, 0.6, 0.24, 0.64, 0.26, 0.08, 0.49, 0.16, 0.22, 0.19, 0.33, 0.37, 0.26, 0.04, 0.25, 0.36, 0.25, 0.5, 0.14, 0.25, 0.04, 0.06, 0.2, 0.09, 0.0, 0.0, 0.37, 0.56, 0.1, 0.44, 0.0, 0.07, 0.17, 0.06, 0.44, 0.0, 0.48, 0.42, 0.23, 0.37, 0.0, 0.76, 0.47, 0.23, 0.04, 0.03, 0.23, 0.49, 0.52, 0.0, 0.46, 0.04, 0.51, 0.06, 0.58, 0.2, 0.18, 0.45, 0.32, 0.44, 0.68, 0.12, 0.07, 0.55, 0.12, 0.09, 0.53, 0.48, 0.23, 0.25, 0.52, 0.46, 0.37, 0.06, 0.02, 0.06, 0.06, 0.48, 0.12, 0.12, 0.6, 0.48, 0.32, 0.42, 0.44, 0.38, 0.24, 0.31, 0.3, 0.29, 0.29, 0.23, 0.12, 0.39, 0.26, 0.05, 0.42, 0.2, 0.66, 0.5, 0.62, 0.39, 0.64, 0.28, 0.08, 0.01, 0.53, 0.45, 0.32, 0.58, 0.54, 0.5, 0.48, 0.47, 0.5, 0.0, 0.02, 0.67, 0.31, 0.0, 0.22, 0.0, 0.0, 0.79, 0.4, 0.01, 0.52, 0.66, 0.66, 0.66, 0.23, 0.31, 0.66, 0.63, 0.66, 0.5, 0.61, 0.52, 0.53, 0.02, 0.4, 0.48, 0.22, 0.63, 0.71, 0.5, 0.66, 0.38, 0.42, 0.68, 0.28, 0.07, 0.26, 0.15, 0.26, 0.31, 0.05, 0.52, 0.61, 0.65, 0.76, 0.02, 0.59, 0.22, 0.3, 0.54, 0.49, 0.05, 0.46, 0.47, 0.66, 0.58, 0.49, 0.34, 0.35, 0.16, 0.53, 0.34, 0.24, 0.64, 0.12, 0.51, 0.0, 0.33, 0.03, 0.2, 0.47, 0.08, 0.22, 0.33, 0.63, 0.35, 0.69, 0.63, 0.55, 0.3, 0.73, 0.18, 0.72, 0.65, 0.76, 0.49, 0.01, 0.1, 0.6, 0.29, 0.22, 0.69, 0.53, 0.03, 0.63, 0.4, 0.67, 0.39, 0.21, 0.66, 0.52, 0.22, 0.68, 0.7, 0.54, 0.4, 0.42, 0.45, 0.69, 0.02, 0.65, 0.42, 0.55, 0.55, 0.51, 0.24, 0.41, 0.49, 0.11, 0.39, 0.56, 0.59, 0.6, 0.68, 0.39, 0.36, 0.55, 0.4, 0.27, 0.5, 0.51, 0.31, 0.23, 0.53, 0.25, 0.32, 0.73, 0.47, 0.42, 0.63, 0.46, 0.55, 0.31, 0.75, 0.49, 0.48, 0.64, 0.49, 0.49, 0.49, 0.49, 0.49, 0.49, 0.49, 0.49, 0.49, 0.49, 0.24, 0.49, 0.49, 0.24, 0.24, 0.49, 0.24, 0.24, 0.24, 0.49, 0.74, 0.24, 0.49, 0.24, 0.24, 0.74, 0.49, 0.24, 0.49, 0.49, 0.49, 0.01, 0.24, 0.24, 0.24, 0.49, 0.49, 0.49, 0.49, 0.49, 0.49, 0.49, 0.49, 0.24, 0.49, 0.24, 0.49, 0.49, 0.49, 0.49, 0.49, 0.24, 0.49, 0.49, 0.49, 0.49, 0.49, 0.49, 0.49, 0.24, 0.49, 0.24, 0.24, 0.49, 0.49, 0.49, 0.58, 0.17, 0.41, 0.51, 0.58, 0.18, 0.45, 0.27, 0.52, 0.0, 0.13, 0.13, 0.48, 0.41, 0.37, 0.19, 0.54, 0.55, 0.0, 0.38, 0.18, 0.5, 0.51, 0.5, 0.41, 0.24, 0.23, 0.22, 0.25, 0.0, 0.29, 0.26, 0.23, 0.54, 0.14, 0.22, 0.21, 0.0, 0.28, 0.27, 0.12, 0.35, 0.45, 0.44, 0.1, 0.05, 0.01, 0.3, 0.27, 0.39, 0.25, 0.65, 0.59, 0.47, 0.17, 0.59, 0.07, 0.02, 0.31, 0.06, 0.46, 0.52, 0.14, 0.36, 0.45, 0.43, 0.24, 0.21, 0.34, 0.41, 0.39, 0.11, 0.1, 0.45, 0.58, 0.23, 0.31, 0.23, 0.32, 0.18, 0.23, 0.04, 0.48, 0.0, 0.24, 0.51, 0.32, 0.31, 0.02, 0.02, 0.28, 0.55, 0.43, 0.02, 0.48, 0.04, 0.15, 0.08, 0.19, 0.12, 0.47, 0.43, 0.34, 0.0, 0.36, 0.28, 0.18, 0.11, 0.04, 0.0, 0.24, 0.08, 0.3, 0.1, 0.17, 0.09, 0.02, 0.03, 0.66, 0.13, 0.03, 0.34, 0.2, 0.1, 0.0, 0.23, 0.0, 0.29, 0.24, 0.0, 0.58, 0.54, 0.18, 0.38, 0.4, 0.18, 0.1, 0.13, 0.68, 0.07, 0.01, 0.0, 0.21, 0.25, 0.26, 0.0, 0.11, 0.1, 0.18, 0.32, 0.02, 0.01, 0.26, 0.27, 0.29, 0.3, 0.0, 0.18, 0.17, 0.3, 0.03, 0.0, 0.14, 0.05, 0.01, 0.41, 0.24, 0.17, 0.43, 0.17, 0.02, 0.0, 0.54, 0.3, 0.31, 0.44, 0.34, 0.08, 0.09, 0.0, 0.08, 0.22, 0.4, 0.39, 0.12, 0.31, 0.1, 0.55, 0.33, 0.24, 0.54, 0.19, 0.42, 0.0, 0.15, 0.0, 0.0, 0.13, 0.28, 0.14, 0.34, 0.09, 0.08, 0.07, 0.42, 0.44, 0.26, 0.1, 0.28, 0.35, 0.04, 0.47, 0.0, 0.45, 0.35, 0.46, 0.21, 0.16, 0.21, 0.44, 0.32, 0.39, 0.02, 0.34, 0.47, 0.22, 0.06, 0.66, 0.32, 0.06, 0.07, 0.22, 0.23, 0.03, 0.01, 0.03, 0.24, 0.37, 0.46, 0.4, 0.0, 0.19, 0.04, 0.18, 0.0, 0.29, 0.14, 0.12, 0.38, 0.0, 0.34, 0.24, 0.03, 0.23, 0.03, 0.01, 0.39, 0.02, 0.36, 0.1, 0.06, 0.2, 0.27, 0.0, 0.13, 0.39, 0.48, 0.46, 0.44, 0.46, 0.4, 0.19, 0.31, 0.32, 0.12, 0.37, 0.27, 0.36, 0.33, 0.19, 0.38, 0.01, 0.01, 0.29, 0.38, 0.5, 0.38, 0.17, 0.52, 0.49, 0.4, 0.34, 0.49, 0.42, 0.58, 0.48, 0.45, 0.4, 0.48, 0.4, 0.52, 0.52, 0.52, 0.12, 0.05, 0.27, 0.14, 0.02, 0.39, 0.4, 0.41, 0.2, 0.43, 0.09, 0.48, 0.5, 0.44, 0.41, 0.3, 0.29, 0.32, 0.49, 0.3, 0.26, 0.32, 0.0, 0.39, 0.3, 0.12, 0.4, 0.28, 0.1, 0.45, 0.06, 0.0, 0.34, 0.0, 0.3, 0.38, 0.33, 0.32, 0.29, 0.34, 0.4, 0.36, 0.45, 0.31, 0.15, 0.0, 0.16, 0.46, 0.4, 0.37, 0.14, 0.66, 0.09, 0.42, 0.01, 0.0, 0.32, 0.0, 0.21, 0.0, 0.01, 0.0, 0.08, 0.18, 0.34, 0.34, 0.1, 0.41, 0.21, 0.0, 0.19, 0.41, 0.33, 0.0, 0.0, 0.17, 0.36, 0.36, 0.59, 0.05, 0.42, 0.27, 0.53, 0.25, 0.57, 0.57, 0.5, 0.44, 0.65, 0.09, 0.18, 0.08, 0.53, 0.35, 0.45, 0.2, 0.26, 0.33, 0.34, 0.56, 0.65, 0.68, 0.56, 0.68, 0.3, 0.45, 0.08, 0.4, 0.42, 0.54, 0.54, 0.42, 0.09, 0.36, 0.09, 0.47, 0.38, 0.45, 0.42, 0.27, 0.09, 0.34, 0.28, 0.42, 0.41, 0.1, 0.43, 0.0, 0.27, 0.41, 0.39, 0.5, 0.07, 0.12, 0.0, 0.34, 0.0, 0.0, 0.37, 0.0, 0.35, 0.26, 0.0, 0.33, 0.35, 0.0, 0.21, 0.34, 0.07, 0.35, 0.43, 0.45, 0.15, 0.24, 0.3, 0.32, 0.11, 0.3, 0.23, 0.43, 0.12, 0.45, 0.42, 0.47, 0.32, 0.23, 0.25, 0.35, 0.0, 0.51, 0.18, 0.43, 0.43, 0.57, 0.43, 0.42, 0.24, 0.5, 0.26, 0.39, 0.27, 0.29, 0.34, 0.0, 0.46, 0.31, 0.0, 0.03, 0.0, 0.0, 0.33, 0.43, 0.4, 0.07, 0.23, 0.3, 0.03, 0.05, 0.57, 0.0, 0.37, 0.0, 0.12, 0.22, 0.23, 0.21, 0.26, 0.36, 0.39, 0.19, 0.46, 0.55, 0.43, 0.02, 0.15, 0.42, 0.46, 0.46, 0.31, 0.37, 0.31, 0.4, 0.52, 0.22, 0.47, 0.49, 0.23, 0.03, 0.25, 0.0, 0.29, 0.34, 0.01, 0.37, 0.01, 0.32, 0.0, 0.0, 0.0, 0.2, 0.39, 0.41, 0.22, 0.25, 0.19, 0.07, 0.33, 0.01, 0.14, 0.0, 0.0, 0.06, 0.02, 0.22, 0.28, 0.0, 0.68, 0.0, 0.38, 0.0, 0.32, 0.05, 0.5, 0.31, 0.03, 0.01, 0.2, 0.0, 0.2, 0.13, 0.22, 0.4, 0.0, 0.39, 0.2, 0.0, 0.28, 0.19, 0.5, 0.44, 0.08, 0.3, 0.0, 0.1, 0.13, 0.0, 0.0, 0.14, 0.0, 0.0, 0.0, 0.07, 0.32, 0.44, 0.21, 0.26, 0.32, 0.09, 0.1, 0.15, 0.21, 0.21, 0.21, 0.27, 0.0, 0.46, 0.68, 0.34, 0.0, 0.42, 0.39, 0.24, 0.11, 0.26, 0.26, 0.1, 0.22, 0.0, 0.02, 0.0, 0.02, 0.02, 0.48, 0.24, 0.01, 0.03, 0.0, 0.29, 0.01, 0.03, 0.03, 0.25, 0.25, 0.24, 0.17, 0.4, 0.31, 0.14, 0.27, 0.02, 0.09, 0.08, 0.3, 0.32, 0.0, 0.51, 0.56, 0.27, 0.0, 0.26, 0.2, 0.26, 0.15, 0.02, 0.09, 0.22, 0.15, 0.25, 0.07, 0.31, 0.02, 0.0, 0.22, 0.06, 0.25, 0.14, 0.1, 0.1, 0.26, 0.12, 0.0, 0.21, 0.42, 0.33, 0.39, 0.3, 0.34, 0.0, 0.36, 0.0, 0.4, 0.25, 0.59, 0.0, 0.33, 0.01, 0.21, 0.18, 0.0, 0.09, 0.37, 0.37, 0.33, 0.0, 0.4, 0.24, 0.31, 0.0, 0.16, 0.37, 0.38, 0.29, 0.0, 0.02, 0.32, 0.19, 0.02, 0.2, 0.02, 0.19, 0.0, 0.01, 0.31, 0.44, 0.02, 0.33, 0.63, 0.0, 0.06, 0.4, 0.35, 0.09, 0.0, 0.03, 0.01, 0.1, 0.32, 0.08, 0.05, 0.11, 0.08, 0.6, 0.08, 0.5, 0.11, 0.11, 0.05, 0.6, 0.03, 0.54, 0.44, 0.06, 0.16, 0.21, 0.05, 0.04, 0.1, 0.49, 0.06, 0.26, 0.09, 0.02, 0.03, 0.04, 0.04, 0.29, 0.18, 0.39, 0.57, 0.02, 0.05, 0.6, 0.4, 0.21, 0.04, 0.04, 0.15, 0.21, 0.21, 0.25, 0.06, 0.46, 0.08, 0.2, 0.25, 0.19, 0.08, 0.08, 0.07, 0.49, 0.08, 0.09, 0.1, 0.13, 0.3, 0.14, 0.13, 0.08, 0.08, 0.09, 0.32, 0.08, 0.29, 0.02, 0.42, 0.43, 0.33, 0.02, 0.1, 0.5, 0.3, 0.0, 0.0, 0.01, 0.0, 0.02, 0.17, 0.04, 0.33, 0.26, 0.13, 0.02, 0.64, 0.13, 0.14, 0.53, 0.14, 0.32, 0.2, 0.78, 0.4, 0.63, 0.15, 0.15, 0.09, 0.33, 0.1, 0.29, 0.44, 0.44, 0.41, 0.11, 0.33, 0.2, 0.15, 0.09, 0.13, 0.08, 0.08, 0.1, 0.12, 0.47], "yaxis": "y"}, {"marker": {"color": "rgba(20, 36, 44, 0.7)"}, "name": "", "points": false, "type": "violin", "xaxis": "x2", "y": [0.0, 0.0, 0.04, 0.56, 0.0, 0.06, 0.0, 0.02, 0.36, 0.08, 0.0, 0.29, 0.18, 0.19, 0.56, 0.28, 0.08, 0.51, 0.48, 0.31, 0.21, 0.11, 0.14, 0.16, 0.24, 0.0, 0.0, 0.07, 0.0, 0.12, 0.12, 0.25, 0.0, 0.14, 0.28, 0.09, 0.36, 0.3, 0.2, 0.22, 0.02, 0.15, 0.43, 0.52, 0.23, 0.37, 0.26, 0.04, 0.04, 0.36, 0.15, 0.04, 0.57, 0.12, 0.18, 0.31, 0.4, 0.49, 0.16, 0.05, 0.05, 0.11, 0.07, 0.57, 0.05, 0.08, 0.23, 0.22, 0.26, 0.54, 0.64, 0.0, 0.12, 0.2, 0.2, 0.7, 0.47, 0.26, 0.48, 0.15, 0.28, 0.26, 0.44, 0.08, 0.26, 0.29, 0.04, 0.17, 0.0, 0.25, 0.06, 0.18, 0.3, 0.3, 0.22, 0.24, 0.68, 0.31, 0.53, 0.52, 0.19, 0.09, 0.1, 0.44, 0.31, 0.28, 0.12, 0.04, 0.08, 0.09, 0.0, 0.0, 0.17, 0.04, 0.0, 0.0, 0.16, 0.15, 0.56, 0.09, 0.01, 0.05, 0.11, 0.15, 0.36, 0.19, 0.19, 0.0, 0.08, 0.55, 0.02, 0.26, 0.1, 0.44, 0.47, 1.0, 0.03, 0.42, 0.42, 0.0, 0.18, 0.03, 0.02, 0.04, 0.26, 0.26, 0.48, 0.1, 0.03, 0.07, 0.24, 0.03, 0.17, 0.05, 0.21, 0.04, 0.42, 0.0, 0.14, 0.49, 0.02, 0.2, 0.21, 0.57, 0.48, 0.1, 0.33, 0.32, 0.35, 0.25, 0.12, 0.21, 0.33, 0.3, 0.6, 0.08, 0.06, 0.47, 0.48, 0.11, 0.35, 0.36, 0.74, 0.31, 0.28, 0.58, 0.6, 0.24, 0.64, 0.26, 0.08, 0.49, 0.16, 0.22, 0.19, 0.33, 0.37, 0.26, 0.04, 0.25, 0.36, 0.25, 0.5, 0.14, 0.25, 0.04, 0.06, 0.2, 0.09, 0.0, 0.0, 0.37, 0.56, 0.1, 0.44, 0.0, 0.07, 0.17, 0.06, 0.44, 0.0, 0.48, 0.42, 0.23, 0.37, 0.0, 0.76, 0.47, 0.23, 0.04, 0.03, 0.23, 0.49, 0.52, 0.0, 0.46, 0.04, 0.51, 0.06, 0.58, 0.2, 0.18, 0.45, 0.32, 0.44, 0.68, 0.12, 0.07, 0.55, 0.12, 0.09, 0.53, 0.48, 0.23, 0.25, 0.52, 0.46, 0.37, 0.06, 0.02, 0.06, 0.06, 0.48, 0.12, 0.12, 0.6, 0.48, 0.32, 0.42, 0.44, 0.38, 0.24, 0.31, 0.3, 0.29, 0.29, 0.23, 0.12, 0.39, 0.26, 0.05, 0.42, 0.2, 0.66, 0.5, 0.62, 0.39, 0.64, 0.28, 0.08, 0.01, 0.53, 0.45, 0.32, 0.58, 0.54, 0.5, 0.48, 0.47, 0.5, 0.0, 0.02, 0.67, 0.31, 0.0, 0.22, 0.0, 0.0, 0.79, 0.4, 0.01, 0.52, 0.66, 0.66, 0.66, 0.23, 0.31, 0.66, 0.63, 0.66, 0.5, 0.61, 0.52, 0.53, 0.02, 0.4, 0.48, 0.22, 0.63, 0.71, 0.5, 0.66, 0.38, 0.42, 0.68, 0.28, 0.07, 0.26, 0.15, 0.26, 0.31, 0.05, 0.52, 0.61, 0.65, 0.76, 0.02, 0.59, 0.22, 0.3, 0.54, 0.49, 0.05, 0.46, 0.47, 0.66, 0.58, 0.49, 0.34, 0.35, 0.16, 0.53, 0.34, 0.24, 0.64, 0.12, 0.51, 0.0, 0.33, 0.03, 0.2, 0.47, 0.08, 0.22, 0.33, 0.63, 0.35, 0.69, 0.63, 0.55, 0.3, 0.73, 0.18, 0.72, 0.65, 0.76, 0.49, 0.01, 0.1, 0.6, 0.29, 0.22, 0.69, 0.53, 0.03, 0.63, 0.4, 0.67, 0.39, 0.21, 0.66, 0.52, 0.22, 0.68, 0.7, 0.54, 0.4, 0.42, 0.45, 0.69, 0.02, 0.65, 0.42, 0.55, 0.55, 0.51, 0.24, 0.41, 0.49, 0.11, 0.39, 0.56, 0.59, 0.6, 0.68, 0.39, 0.36, 0.55, 0.4, 0.27, 0.5, 0.51, 0.31, 0.23, 0.53, 0.25, 0.32, 0.73, 0.47, 0.42, 0.63, 0.46, 0.55, 0.31, 0.75, 0.49, 0.48, 0.64, 0.49, 0.49, 0.49, 0.49, 0.49, 0.49, 0.49, 0.49, 0.49, 0.49, 0.24, 0.49, 0.49, 0.24, 0.24, 0.49, 0.24, 0.24, 0.24, 0.49, 0.74, 0.24, 0.49, 0.24, 0.24, 0.74, 0.49, 0.24, 0.49, 0.49, 0.49, 0.01, 0.24, 0.24, 0.24, 0.49, 0.49, 0.49, 0.49, 0.49, 0.49, 0.49, 0.49, 0.24, 0.49, 0.24, 0.49, 0.49, 0.49, 0.49, 0.49, 0.24, 0.49, 0.49, 0.49, 0.49, 0.49, 0.49, 0.49, 0.24, 0.49, 0.24, 0.24, 0.49, 0.49, 0.49, 0.58, 0.17, 0.41, 0.51, 0.58, 0.18, 0.45, 0.27, 0.52, 0.0, 0.13, 0.13, 0.48, 0.41, 0.37, 0.19, 0.54, 0.55, 0.0, 0.38, 0.18, 0.5, 0.51, 0.5, 0.41, 0.24, 0.23, 0.22, 0.25, 0.0, 0.29, 0.26, 0.23, 0.54, 0.14, 0.22, 0.21, 0.0, 0.28, 0.27, 0.12, 0.35, 0.45, 0.44, 0.1, 0.05, 0.01, 0.3, 0.27, 0.39, 0.25, 0.65, 0.59, 0.47, 0.17, 0.59, 0.07, 0.02, 0.31, 0.06, 0.46, 0.52, 0.14, 0.36, 0.45, 0.43, 0.24, 0.21, 0.34, 0.41, 0.39, 0.11, 0.1, 0.45, 0.58, 0.23, 0.31, 0.23, 0.32, 0.18, 0.23, 0.04, 0.48, 0.0, 0.24, 0.51, 0.32, 0.31, 0.02, 0.02, 0.28, 0.55, 0.43, 0.02, 0.48, 0.04, 0.15, 0.08, 0.19, 0.12, 0.47, 0.43, 0.34, 0.0, 0.36, 0.28, 0.18, 0.11, 0.04, 0.0, 0.24, 0.08, 0.3, 0.1, 0.17, 0.09, 0.02, 0.03, 0.66, 0.13, 0.03, 0.34, 0.2, 0.1, 0.0, 0.23, 0.0, 0.29, 0.24, 0.0, 0.58, 0.54, 0.18, 0.38, 0.4, 0.18, 0.1, 0.13, 0.68, 0.07, 0.01, 0.0, 0.21, 0.25, 0.26, 0.0, 0.11, 0.1, 0.18, 0.32, 0.02, 0.01, 0.26, 0.27, 0.29, 0.3, 0.0, 0.18, 0.17, 0.3, 0.03, 0.0, 0.14, 0.05, 0.01, 0.41, 0.24, 0.17, 0.43, 0.17, 0.02, 0.0, 0.54, 0.3, 0.31, 0.44, 0.34, 0.08, 0.09, 0.0, 0.08, 0.22, 0.4, 0.39, 0.12, 0.31, 0.1, 0.55, 0.33, 0.24, 0.54, 0.19, 0.42, 0.0, 0.15, 0.0, 0.0, 0.13, 0.28, 0.14, 0.34, 0.09, 0.08, 0.07, 0.42, 0.44, 0.26, 0.1, 0.28, 0.35, 0.04, 0.47, 0.0, 0.45, 0.35, 0.46, 0.21, 0.16, 0.21, 0.44, 0.32, 0.39, 0.02, 0.34, 0.47, 0.22, 0.06, 0.66, 0.32, 0.06, 0.07, 0.22, 0.23, 0.03, 0.01, 0.03, 0.24, 0.37, 0.46, 0.4, 0.0, 0.19, 0.04, 0.18, 0.0, 0.29, 0.14, 0.12, 0.38, 0.0, 0.34, 0.24, 0.03, 0.23, 0.03, 0.01, 0.39, 0.02, 0.36, 0.1, 0.06, 0.2, 0.27, 0.0, 0.13, 0.39, 0.48, 0.46, 0.44, 0.46, 0.4, 0.19, 0.31, 0.32, 0.12, 0.37, 0.27, 0.36, 0.33, 0.19, 0.38, 0.01, 0.01, 0.29, 0.38, 0.5, 0.38, 0.17, 0.52, 0.49, 0.4, 0.34, 0.49, 0.42, 0.58, 0.48, 0.45, 0.4, 0.48, 0.4, 0.52, 0.52, 0.52, 0.12, 0.05, 0.27, 0.14, 0.02, 0.39, 0.4, 0.41, 0.2, 0.43, 0.09, 0.48, 0.5, 0.44, 0.41, 0.3, 0.29, 0.32, 0.49, 0.3, 0.26, 0.32, 0.0, 0.39, 0.3, 0.12, 0.4, 0.28, 0.1, 0.45, 0.06, 0.0, 0.34, 0.0, 0.3, 0.38, 0.33, 0.32, 0.29, 0.34, 0.4, 0.36, 0.45, 0.31, 0.15, 0.0, 0.16, 0.46, 0.4, 0.37, 0.14, 0.66, 0.09, 0.42, 0.01, 0.0, 0.32, 0.0, 0.21, 0.0, 0.01, 0.0, 0.08, 0.18, 0.34, 0.34, 0.1, 0.41, 0.21, 0.0, 0.19, 0.41, 0.33, 0.0, 0.0, 0.17, 0.36, 0.36, 0.59, 0.05, 0.42, 0.27, 0.53, 0.25, 0.57, 0.57, 0.5, 0.44, 0.65, 0.09, 0.18, 0.08, 0.53, 0.35, 0.45, 0.2, 0.26, 0.33, 0.34, 0.56, 0.65, 0.68, 0.56, 0.68, 0.3, 0.45, 0.08, 0.4, 0.42, 0.54, 0.54, 0.42, 0.09, 0.36, 0.09, 0.47, 0.38, 0.45, 0.42, 0.27, 0.09, 0.34, 0.28, 0.42, 0.41, 0.1, 0.43, 0.0, 0.27, 0.41, 0.39, 0.5, 0.07, 0.12, 0.0, 0.34, 0.0, 0.0, 0.37, 0.0, 0.35, 0.26, 0.0, 0.33, 0.35, 0.0, 0.21, 0.34, 0.07, 0.35, 0.43, 0.45, 0.15, 0.24, 0.3, 0.32, 0.11, 0.3, 0.23, 0.43, 0.12, 0.45, 0.42, 0.47, 0.32, 0.23, 0.25, 0.35, 0.0, 0.51, 0.18, 0.43, 0.43, 0.57, 0.43, 0.42, 0.24, 0.5, 0.26, 0.39, 0.27, 0.29, 0.34, 0.0, 0.46, 0.31, 0.0, 0.03, 0.0, 0.0, 0.33, 0.43, 0.4, 0.07, 0.23, 0.3, 0.03, 0.05, 0.57, 0.0, 0.37, 0.0, 0.12, 0.22, 0.23, 0.21, 0.26, 0.36, 0.39, 0.19, 0.46, 0.55, 0.43, 0.02, 0.15, 0.42, 0.46, 0.46, 0.31, 0.37, 0.31, 0.4, 0.52, 0.22, 0.47, 0.49, 0.23, 0.03, 0.25, 0.0, 0.29, 0.34, 0.01, 0.37, 0.01, 0.32, 0.0, 0.0, 0.0, 0.2, 0.39, 0.41, 0.22, 0.25, 0.19, 0.07, 0.33, 0.01, 0.14, 0.0, 0.0, 0.06, 0.02, 0.22, 0.28, 0.0, 0.68, 0.0, 0.38, 0.0, 0.32, 0.05, 0.5, 0.31, 0.03, 0.01, 0.2, 0.0, 0.2, 0.13, 0.22, 0.4, 0.0, 0.39, 0.2, 0.0, 0.28, 0.19, 0.5, 0.44, 0.08, 0.3, 0.0, 0.1, 0.13, 0.0, 0.0, 0.14, 0.0, 0.0, 0.0, 0.07, 0.32, 0.44, 0.21, 0.26, 0.32, 0.09, 0.1, 0.15, 0.21, 0.21, 0.21, 0.27, 0.0, 0.46, 0.68, 0.34, 0.0, 0.42, 0.39, 0.24, 0.11, 0.26, 0.26, 0.1, 0.22, 0.0, 0.02, 0.0, 0.02, 0.02, 0.48, 0.24, 0.01, 0.03, 0.0, 0.29, 0.01, 0.03, 0.03, 0.25, 0.25, 0.24, 0.17, 0.4, 0.31, 0.14, 0.27, 0.02, 0.09, 0.08, 0.3, 0.32, 0.0, 0.51, 0.56, 0.27, 0.0, 0.26, 0.2, 0.26, 0.15, 0.02, 0.09, 0.22, 0.15, 0.25, 0.07, 0.31, 0.02, 0.0, 0.22, 0.06, 0.25, 0.14, 0.1, 0.1, 0.26, 0.12, 0.0, 0.21, 0.42, 0.33, 0.39, 0.3, 0.34, 0.0, 0.36, 0.0, 0.4, 0.25, 0.59, 0.0, 0.33, 0.01, 0.21, 0.18, 0.0, 0.09, 0.37, 0.37, 0.33, 0.0, 0.4, 0.24, 0.31, 0.0, 0.16, 0.37, 0.38, 0.29, 0.0, 0.02, 0.32, 0.19, 0.02, 0.2, 0.02, 0.19, 0.0, 0.01, 0.31, 0.44, 0.02, 0.33, 0.63, 0.0, 0.06, 0.4, 0.35, 0.09, 0.0, 0.03, 0.01, 0.1, 0.32, 0.08, 0.05, 0.11, 0.08, 0.6, 0.08, 0.5, 0.11, 0.11, 0.05, 0.6, 0.03, 0.54, 0.44, 0.06, 0.16, 0.21, 0.05, 0.04, 0.1, 0.49, 0.06, 0.26, 0.09, 0.02, 0.03, 0.04, 0.04, 0.29, 0.18, 0.39, 0.57, 0.02, 0.05, 0.6, 0.4, 0.21, 0.04, 0.04, 0.15, 0.21, 0.21, 0.25, 0.06, 0.46, 0.08, 0.2, 0.25, 0.19, 0.08, 0.08, 0.07, 0.49, 0.08, 0.09, 0.1, 0.13, 0.3, 0.14, 0.13, 0.08, 0.08, 0.09, 0.32, 0.08, 0.29, 0.02, 0.42, 0.43, 0.33, 0.02, 0.1, 0.5, 0.3, 0.0, 0.0, 0.01, 0.0, 0.02, 0.17, 0.04, 0.33, 0.26, 0.13, 0.02, 0.64, 0.13, 0.14, 0.53, 0.14, 0.32, 0.2, 0.78, 0.4, 0.63, 0.15, 0.15, 0.09, 0.33, 0.1, 0.29, 0.44, 0.44, 0.41, 0.11, 0.33, 0.2, 0.15, 0.09, 0.13, 0.08, 0.08, 0.1, 0.12, 0.47], "yaxis": "y2"}, {"hovertemplate": "%{y:.d}<extra></extra>", "marker": {"color": "rgba(20, 36, 44, 0.7)"}, "type": "histogram", "x": [0.0, 0.0, 0.04, 0.56, 0.0, 0.06, 0.0, 0.02, 0.36, 0.08, 0.0, 0.29, 0.18, 0.19, 0.56, 0.28, 0.08, 0.51, 0.48, 0.31, 0.21, 0.11, 0.14, 0.16, 0.24, 0.0, 0.0, 0.07, 0.0, 0.12, 0.12, 0.25, 0.0, 0.14, 0.28, 0.09, 0.36, 0.3, 0.2, 0.22, 0.02, 0.15, 0.43, 0.52, 0.23, 0.37, 0.26, 0.04, 0.04, 0.36, 0.15, 0.04, 0.57, 0.12, 0.18, 0.31, 0.4, 0.49, 0.16, 0.05, 0.05, 0.11, 0.07, 0.57, 0.05, 0.08, 0.23, 0.22, 0.26, 0.54, 0.64, 0.0, 0.12, 0.2, 0.2, 0.7, 0.47, 0.26, 0.48, 0.15, 0.28, 0.26, 0.44, 0.08, 0.26, 0.29, 0.04, 0.17, 0.0, 0.25, 0.06, 0.18, 0.3, 0.3, 0.22, 0.24, 0.68, 0.31, 0.53, 0.52, 0.19, 0.09, 0.1, 0.44, 0.31, 0.28, 0.12, 0.04, 0.08, 0.09, 0.0, 0.0, 0.17, 0.04, 0.0, 0.0, 0.16, 0.15, 0.56, 0.09, 0.01, 0.05, 0.11, 0.15, 0.36, 0.19, 0.19, 0.0, 0.08, 0.55, 0.02, 0.26, 0.1, 0.44, 0.47, 1.0, 0.03, 0.42, 0.42, 0.0, 0.18, 0.03, 0.02, 0.04, 0.26, 0.26, 0.48, 0.1, 0.03, 0.07, 0.24, 0.03, 0.17, 0.05, 0.21, 0.04, 0.42, 0.0, 0.14, 0.49, 0.02, 0.2, 0.21, 0.57, 0.48, 0.1, 0.33, 0.32, 0.35, 0.25, 0.12, 0.21, 0.33, 0.3, 0.6, 0.08, 0.06, 0.47, 0.48, 0.11, 0.35, 0.36, 0.74, 0.31, 0.28, 0.58, 0.6, 0.24, 0.64, 0.26, 0.08, 0.49, 0.16, 0.22, 0.19, 0.33, 0.37, 0.26, 0.04, 0.25, 0.36, 0.25, 0.5, 0.14, 0.25, 0.04, 0.06, 0.2, 0.09, 0.0, 0.0, 0.37, 0.56, 0.1, 0.44, 0.0, 0.07, 0.17, 0.06, 0.44, 0.0, 0.48, 0.42, 0.23, 0.37, 0.0, 0.76, 0.47, 0.23, 0.04, 0.03, 0.23, 0.49, 0.52, 0.0, 0.46, 0.04, 0.51, 0.06, 0.58, 0.2, 0.18, 0.45, 0.32, 0.44, 0.68, 0.12, 0.07, 0.55, 0.12, 0.09, 0.53, 0.48, 0.23, 0.25, 0.52, 0.46, 0.37, 0.06, 0.02, 0.06, 0.06, 0.48, 0.12, 0.12, 0.6, 0.48, 0.32, 0.42, 0.44, 0.38, 0.24, 0.31, 0.3, 0.29, 0.29, 0.23, 0.12, 0.39, 0.26, 0.05, 0.42, 0.2, 0.66, 0.5, 0.62, 0.39, 0.64, 0.28, 0.08, 0.01, 0.53, 0.45, 0.32, 0.58, 0.54, 0.5, 0.48, 0.47, 0.5, 0.0, 0.02, 0.67, 0.31, 0.0, 0.22, 0.0, 0.0, 0.79, 0.4, 0.01, 0.52, 0.66, 0.66, 0.66, 0.23, 0.31, 0.66, 0.63, 0.66, 0.5, 0.61, 0.52, 0.53, 0.02, 0.4, 0.48, 0.22, 0.63, 0.71, 0.5, 0.66, 0.38, 0.42, 0.68, 0.28, 0.07, 0.26, 0.15, 0.26, 0.31, 0.05, 0.52, 0.61, 0.65, 0.76, 0.02, 0.59, 0.22, 0.3, 0.54, 0.49, 0.05, 0.46, 0.47, 0.66, 0.58, 0.49, 0.34, 0.35, 0.16, 0.53, 0.34, 0.24, 0.64, 0.12, 0.51, 0.0, 0.33, 0.03, 0.2, 0.47, 0.08, 0.22, 0.33, 0.63, 0.35, 0.69, 0.63, 0.55, 0.3, 0.73, 0.18, 0.72, 0.65, 0.76, 0.49, 0.01, 0.1, 0.6, 0.29, 0.22, 0.69, 0.53, 0.03, 0.63, 0.4, 0.67, 0.39, 0.21, 0.66, 0.52, 0.22, 0.68, 0.7, 0.54, 0.4, 0.42, 0.45, 0.69, 0.02, 0.65, 0.42, 0.55, 0.55, 0.51, 0.24, 0.41, 0.49, 0.11, 0.39, 0.56, 0.59, 0.6, 0.68, 0.39, 0.36, 0.55, 0.4, 0.27, 0.5, 0.51, 0.31, 0.23, 0.53, 0.25, 0.32, 0.73, 0.47, 0.42, 0.63, 0.46, 0.55, 0.31, 0.75, 0.49, 0.48, 0.64, 0.49, 0.49, 0.49, 0.49, 0.49, 0.49, 0.49, 0.49, 0.49, 0.49, 0.24, 0.49, 0.49, 0.24, 0.24, 0.49, 0.24, 0.24, 0.24, 0.49, 0.74, 0.24, 0.49, 0.24, 0.24, 0.74, 0.49, 0.24, 0.49, 0.49, 0.49, 0.01, 0.24, 0.24, 0.24, 0.49, 0.49, 0.49, 0.49, 0.49, 0.49, 0.49, 0.49, 0.24, 0.49, 0.24, 0.49, 0.49, 0.49, 0.49, 0.49, 0.24, 0.49, 0.49, 0.49, 0.49, 0.49, 0.49, 0.49, 0.24, 0.49, 0.24, 0.24, 0.49, 0.49, 0.49, 0.58, 0.17, 0.41, 0.51, 0.58, 0.18, 0.45, 0.27, 0.52, 0.0, 0.13, 0.13, 0.48, 0.41, 0.37, 0.19, 0.54, 0.55, 0.0, 0.38, 0.18, 0.5, 0.51, 0.5, 0.41, 0.24, 0.23, 0.22, 0.25, 0.0, 0.29, 0.26, 0.23, 0.54, 0.14, 0.22, 0.21, 0.0, 0.28, 0.27, 0.12, 0.35, 0.45, 0.44, 0.1, 0.05, 0.01, 0.3, 0.27, 0.39, 0.25, 0.65, 0.59, 0.47, 0.17, 0.59, 0.07, 0.02, 0.31, 0.06, 0.46, 0.52, 0.14, 0.36, 0.45, 0.43, 0.24, 0.21, 0.34, 0.41, 0.39, 0.11, 0.1, 0.45, 0.58, 0.23, 0.31, 0.23, 0.32, 0.18, 0.23, 0.04, 0.48, 0.0, 0.24, 0.51, 0.32, 0.31, 0.02, 0.02, 0.28, 0.55, 0.43, 0.02, 0.48, 0.04, 0.15, 0.08, 0.19, 0.12, 0.47, 0.43, 0.34, 0.0, 0.36, 0.28, 0.18, 0.11, 0.04, 0.0, 0.24, 0.08, 0.3, 0.1, 0.17, 0.09, 0.02, 0.03, 0.66, 0.13, 0.03, 0.34, 0.2, 0.1, 0.0, 0.23, 0.0, 0.29, 0.24, 0.0, 0.58, 0.54, 0.18, 0.38, 0.4, 0.18, 0.1, 0.13, 0.68, 0.07, 0.01, 0.0, 0.21, 0.25, 0.26, 0.0, 0.11, 0.1, 0.18, 0.32, 0.02, 0.01, 0.26, 0.27, 0.29, 0.3, 0.0, 0.18, 0.17, 0.3, 0.03, 0.0, 0.14, 0.05, 0.01, 0.41, 0.24, 0.17, 0.43, 0.17, 0.02, 0.0, 0.54, 0.3, 0.31, 0.44, 0.34, 0.08, 0.09, 0.0, 0.08, 0.22, 0.4, 0.39, 0.12, 0.31, 0.1, 0.55, 0.33, 0.24, 0.54, 0.19, 0.42, 0.0, 0.15, 0.0, 0.0, 0.13, 0.28, 0.14, 0.34, 0.09, 0.08, 0.07, 0.42, 0.44, 0.26, 0.1, 0.28, 0.35, 0.04, 0.47, 0.0, 0.45, 0.35, 0.46, 0.21, 0.16, 0.21, 0.44, 0.32, 0.39, 0.02, 0.34, 0.47, 0.22, 0.06, 0.66, 0.32, 0.06, 0.07, 0.22, 0.23, 0.03, 0.01, 0.03, 0.24, 0.37, 0.46, 0.4, 0.0, 0.19, 0.04, 0.18, 0.0, 0.29, 0.14, 0.12, 0.38, 0.0, 0.34, 0.24, 0.03, 0.23, 0.03, 0.01, 0.39, 0.02, 0.36, 0.1, 0.06, 0.2, 0.27, 0.0, 0.13, 0.39, 0.48, 0.46, 0.44, 0.46, 0.4, 0.19, 0.31, 0.32, 0.12, 0.37, 0.27, 0.36, 0.33, 0.19, 0.38, 0.01, 0.01, 0.29, 0.38, 0.5, 0.38, 0.17, 0.52, 0.49, 0.4, 0.34, 0.49, 0.42, 0.58, 0.48, 0.45, 0.4, 0.48, 0.4, 0.52, 0.52, 0.52, 0.12, 0.05, 0.27, 0.14, 0.02, 0.39, 0.4, 0.41, 0.2, 0.43, 0.09, 0.48, 0.5, 0.44, 0.41, 0.3, 0.29, 0.32, 0.49, 0.3, 0.26, 0.32, 0.0, 0.39, 0.3, 0.12, 0.4, 0.28, 0.1, 0.45, 0.06, 0.0, 0.34, 0.0, 0.3, 0.38, 0.33, 0.32, 0.29, 0.34, 0.4, 0.36, 0.45, 0.31, 0.15, 0.0, 0.16, 0.46, 0.4, 0.37, 0.14, 0.66, 0.09, 0.42, 0.01, 0.0, 0.32, 0.0, 0.21, 0.0, 0.01, 0.0, 0.08, 0.18, 0.34, 0.34, 0.1, 0.41, 0.21, 0.0, 0.19, 0.41, 0.33, 0.0, 0.0, 0.17, 0.36, 0.36, 0.59, 0.05, 0.42, 0.27, 0.53, 0.25, 0.57, 0.57, 0.5, 0.44, 0.65, 0.09, 0.18, 0.08, 0.53, 0.35, 0.45, 0.2, 0.26, 0.33, 0.34, 0.56, 0.65, 0.68, 0.56, 0.68, 0.3, 0.45, 0.08, 0.4, 0.42, 0.54, 0.54, 0.42, 0.09, 0.36, 0.09, 0.47, 0.38, 0.45, 0.42, 0.27, 0.09, 0.34, 0.28, 0.42, 0.41, 0.1, 0.43, 0.0, 0.27, 0.41, 0.39, 0.5, 0.07, 0.12, 0.0, 0.34, 0.0, 0.0, 0.37, 0.0, 0.35, 0.26, 0.0, 0.33, 0.35, 0.0, 0.21, 0.34, 0.07, 0.35, 0.43, 0.45, 0.15, 0.24, 0.3, 0.32, 0.11, 0.3, 0.23, 0.43, 0.12, 0.45, 0.42, 0.47, 0.32, 0.23, 0.25, 0.35, 0.0, 0.51, 0.18, 0.43, 0.43, 0.57, 0.43, 0.42, 0.24, 0.5, 0.26, 0.39, 0.27, 0.29, 0.34, 0.0, 0.46, 0.31, 0.0, 0.03, 0.0, 0.0, 0.33, 0.43, 0.4, 0.07, 0.23, 0.3, 0.03, 0.05, 0.57, 0.0, 0.37, 0.0, 0.12, 0.22, 0.23, 0.21, 0.26, 0.36, 0.39, 0.19, 0.46, 0.55, 0.43, 0.02, 0.15, 0.42, 0.46, 0.46, 0.31, 0.37, 0.31, 0.4, 0.52, 0.22, 0.47, 0.49, 0.23, 0.03, 0.25, 0.0, 0.29, 0.34, 0.01, 0.37, 0.01, 0.32, 0.0, 0.0, 0.0, 0.2, 0.39, 0.41, 0.22, 0.25, 0.19, 0.07, 0.33, 0.01, 0.14, 0.0, 0.0, 0.06, 0.02, 0.22, 0.28, 0.0, 0.68, 0.0, 0.38, 0.0, 0.32, 0.05, 0.5, 0.31, 0.03, 0.01, 0.2, 0.0, 0.2, 0.13, 0.22, 0.4, 0.0, 0.39, 0.2, 0.0, 0.28, 0.19, 0.5, 0.44, 0.08, 0.3, 0.0, 0.1, 0.13, 0.0, 0.0, 0.14, 0.0, 0.0, 0.0, 0.07, 0.32, 0.44, 0.21, 0.26, 0.32, 0.09, 0.1, 0.15, 0.21, 0.21, 0.21, 0.27, 0.0, 0.46, 0.68, 0.34, 0.0, 0.42, 0.39, 0.24, 0.11, 0.26, 0.26, 0.1, 0.22, 0.0, 0.02, 0.0, 0.02, 0.02, 0.48, 0.24, 0.01, 0.03, 0.0, 0.29, 0.01, 0.03, 0.03, 0.25, 0.25, 0.24, 0.17, 0.4, 0.31, 0.14, 0.27, 0.02, 0.09, 0.08, 0.3, 0.32, 0.0, 0.51, 0.56, 0.27, 0.0, 0.26, 0.2, 0.26, 0.15, 0.02, 0.09, 0.22, 0.15, 0.25, 0.07, 0.31, 0.02, 0.0, 0.22, 0.06, 0.25, 0.14, 0.1, 0.1, 0.26, 0.12, 0.0, 0.21, 0.42, 0.33, 0.39, 0.3, 0.34, 0.0, 0.36, 0.0, 0.4, 0.25, 0.59, 0.0, 0.33, 0.01, 0.21, 0.18, 0.0, 0.09, 0.37, 0.37, 0.33, 0.0, 0.4, 0.24, 0.31, 0.0, 0.16, 0.37, 0.38, 0.29, 0.0, 0.02, 0.32, 0.19, 0.02, 0.2, 0.02, 0.19, 0.0, 0.01, 0.31, 0.44, 0.02, 0.33, 0.63, 0.0, 0.06, 0.4, 0.35, 0.09, 0.0, 0.03, 0.01, 0.1, 0.32, 0.08, 0.05, 0.11, 0.08, 0.6, 0.08, 0.5, 0.11, 0.11, 0.05, 0.6, 0.03, 0.54, 0.44, 0.06, 0.16, 0.21, 0.05, 0.04, 0.1, 0.49, 0.06, 0.26, 0.09, 0.02, 0.03, 0.04, 0.04, 0.29, 0.18, 0.39, 0.57, 0.02, 0.05, 0.6, 0.4, 0.21, 0.04, 0.04, 0.15, 0.21, 0.21, 0.25, 0.06, 0.46, 0.08, 0.2, 0.25, 0.19, 0.08, 0.08, 0.07, 0.49, 0.08, 0.09, 0.1, 0.13, 0.3, 0.14, 0.13, 0.08, 0.08, 0.09, 0.32, 0.08, 0.29, 0.02, 0.42, 0.43, 0.33, 0.02, 0.1, 0.5, 0.3, 0.0, 0.0, 0.01, 0.0, 0.02, 0.17, 0.04, 0.33, 0.26, 0.13, 0.02, 0.64, 0.13, 0.14, 0.53, 0.14, 0.32, 0.2, 0.78, 0.4, 0.63, 0.15, 0.15, 0.09, 0.33, 0.1, 0.29, 0.44, 0.44, 0.41, 0.11, 0.33, 0.2, 0.15, 0.09, 0.13, 0.08, 0.08, 0.1, 0.12, 0.47], "xaxis": "x3", "yaxis": "y3"}],                        {"height": 370, "hovermode": "x", "margin": {"b": 50, "l": 50, "r": 50, "t": 100}, "paper_bgcolor": "rgba(0, 0, 0, 0)", "plot_bgcolor": "rgb(243, 243, 243)", "separators": ",.", "showlegend": false, "template": {"data": {"bar": [{"error_x": {"color": "#2a3f5f"}, "error_y": {"color": "#2a3f5f"}, "marker": {"line": {"color": "#E5ECF6", "width": 0.5}}, "type": "bar"}], "barpolar": [{"marker": {"line": {"color": "#E5ECF6", "width": 0.5}}, "type": "barpolar"}], "carpet": [{"aaxis": {"endlinecolor": "#2a3f5f", "gridcolor": "white", "linecolor": "white", "minorgridcolor": "white", "startlinecolor": "#2a3f5f"}, "baxis": {"endlinecolor": "#2a3f5f", "gridcolor": "white", "linecolor": "white", "minorgridcolor": "white", "startlinecolor": "#2a3f5f"}, "type": "carpet"}], "choropleth": [{"colorbar": {"outlinewidth": 0, "ticks": ""}, "type": "choropleth"}], "contour": [{"colorbar": {"outlinewidth": 0, "ticks": ""}, "colorscale": [[0.0, "#0d0887"], [0.1111111111111111, "#46039f"], [0.2222222222222222, "#7201a8"], [0.3333333333333333, "#9c179e"], [0.4444444444444444, "#bd3786"], [0.5555555555555556, "#d8576b"], [0.6666666666666666, "#ed7953"], [0.7777777777777778, "#fb9f3a"], [0.8888888888888888, "#fdca26"], [1.0, "#f0f921"]], "type": "contour"}], "contourcarpet": [{"colorbar": {"outlinewidth": 0, "ticks": ""}, "type": "contourcarpet"}], "heatmap": [{"colorbar": {"outlinewidth": 0, "ticks": ""}, "colorscale": [[0.0, "#0d0887"], [0.1111111111111111, "#46039f"], [0.2222222222222222, "#7201a8"], [0.3333333333333333, "#9c179e"], [0.4444444444444444, "#bd3786"], [0.5555555555555556, "#d8576b"], [0.6666666666666666, "#ed7953"], [0.7777777777777778, "#fb9f3a"], [0.8888888888888888, "#fdca26"], [1.0, "#f0f921"]], "type": "heatmap"}], "heatmapgl": [{"colorbar": {"outlinewidth": 0, "ticks": ""}, "colorscale": [[0.0, "#0d0887"], [0.1111111111111111, "#46039f"], [0.2222222222222222, "#7201a8"], [0.3333333333333333, "#9c179e"], [0.4444444444444444, "#bd3786"], [0.5555555555555556, "#d8576b"], [0.6666666666666666, "#ed7953"], [0.7777777777777778, "#fb9f3a"], [0.8888888888888888, "#fdca26"], [1.0, "#f0f921"]], "type": "heatmapgl"}], "histogram": [{"marker": {"colorbar": {"outlinewidth": 0, "ticks": ""}}, "type": "histogram"}], "histogram2d": [{"colorbar": {"outlinewidth": 0, "ticks": ""}, "colorscale": [[0.0, "#0d0887"], [0.1111111111111111, "#46039f"], [0.2222222222222222, "#7201a8"], [0.3333333333333333, "#9c179e"], [0.4444444444444444, "#bd3786"], [0.5555555555555556, "#d8576b"], [0.6666666666666666, "#ed7953"], [0.7777777777777778, "#fb9f3a"], [0.8888888888888888, "#fdca26"], [1.0, "#f0f921"]], "type": "histogram2d"}], "histogram2dcontour": [{"colorbar": {"outlinewidth": 0, "ticks": ""}, "colorscale": [[0.0, "#0d0887"], [0.1111111111111111, "#46039f"], [0.2222222222222222, "#7201a8"], [0.3333333333333333, "#9c179e"], [0.4444444444444444, "#bd3786"], [0.5555555555555556, "#d8576b"], [0.6666666666666666, "#ed7953"], [0.7777777777777778, "#fb9f3a"], [0.8888888888888888, "#fdca26"], [1.0, "#f0f921"]], "type": "histogram2dcontour"}], "mesh3d": [{"colorbar": {"outlinewidth": 0, "ticks": ""}, "type": "mesh3d"}], "parcoords": [{"line": {"colorbar": {"outlinewidth": 0, "ticks": ""}}, "type": "parcoords"}], "pie": [{"automargin": true, "type": "pie"}], "scatter": [{"marker": {"colorbar": {"outlinewidth": 0, "ticks": ""}}, "type": "scatter"}], "scatter3d": [{"line": {"colorbar": {"outlinewidth": 0, "ticks": ""}}, "marker": {"colorbar": {"outlinewidth": 0, "ticks": ""}}, "type": "scatter3d"}], "scattercarpet": [{"marker": {"colorbar": {"outlinewidth": 0, "ticks": ""}}, "type": "scattercarpet"}], "scattergeo": [{"marker": {"colorbar": {"outlinewidth": 0, "ticks": ""}}, "type": "scattergeo"}], "scattergl": [{"marker": {"colorbar": {"outlinewidth": 0, "ticks": ""}}, "type": "scattergl"}], "scattermapbox": [{"marker": {"colorbar": {"outlinewidth": 0, "ticks": ""}}, "type": "scattermapbox"}], "scatterpolar": [{"marker": {"colorbar": {"outlinewidth": 0, "ticks": ""}}, "type": "scatterpolar"}], "scatterpolargl": [{"marker": {"colorbar": {"outlinewidth": 0, "ticks": ""}}, "type": "scatterpolargl"}], "scatterternary": [{"marker": {"colorbar": {"outlinewidth": 0, "ticks": ""}}, "type": "scatterternary"}], "surface": [{"colorbar": {"outlinewidth": 0, "ticks": ""}, "colorscale": [[0.0, "#0d0887"], [0.1111111111111111, "#46039f"], [0.2222222222222222, "#7201a8"], [0.3333333333333333, "#9c179e"], [0.4444444444444444, "#bd3786"], [0.5555555555555556, "#d8576b"], [0.6666666666666666, "#ed7953"], [0.7777777777777778, "#fb9f3a"], [0.8888888888888888, "#fdca26"], [1.0, "#f0f921"]], "type": "surface"}], "table": [{"cells": {"fill": {"color": "#EBF0F8"}, "line": {"color": "white"}}, "header": {"fill": {"color": "#C8D4E3"}, "line": {"color": "white"}}, "type": "table"}]}, "layout": {"annotationdefaults": {"arrowcolor": "#2a3f5f", "arrowhead": 0, "arrowwidth": 1}, "coloraxis": {"colorbar": {"outlinewidth": 0, "ticks": ""}}, "colorscale": {"diverging": [[0, "#8e0152"], [0.1, "#c51b7d"], [0.2, "#de77ae"], [0.3, "#f1b6da"], [0.4, "#fde0ef"], [0.5, "#f7f7f7"], [0.6, "#e6f5d0"], [0.7, "#b8e186"], [0.8, "#7fbc41"], [0.9, "#4d9221"], [1, "#276419"]], "sequential": [[0.0, "#0d0887"], [0.1111111111111111, "#46039f"], [0.2222222222222222, "#7201a8"], [0.3333333333333333, "#9c179e"], [0.4444444444444444, "#bd3786"], [0.5555555555555556, "#d8576b"], [0.6666666666666666, "#ed7953"], [0.7777777777777778, "#fb9f3a"], [0.8888888888888888, "#fdca26"], [1.0, "#f0f921"]], "sequentialminus": [[0.0, "#0d0887"], [0.1111111111111111, "#46039f"], [0.2222222222222222, "#7201a8"], [0.3333333333333333, "#9c179e"], [0.4444444444444444, "#bd3786"], [0.5555555555555556, "#d8576b"], [0.6666666666666666, "#ed7953"], [0.7777777777777778, "#fb9f3a"], [0.8888888888888888, "#fdca26"], [1.0, "#f0f921"]]}, "colorway": ["#636efa", "#EF553B", "#00cc96", "#ab63fa", "#FFA15A", "#19d3f3", "#FF6692", "#B6E880", "#FF97FF", "#FECB52"], "font": {"color": "#2a3f5f"}, "geo": {"bgcolor": "white", "lakecolor": "white", "landcolor": "#E5ECF6", "showlakes": true, "showland": true, "subunitcolor": "white"}, "hoverlabel": {"align": "left"}, "hovermode": "closest", "mapbox": {"style": "light"}, "paper_bgcolor": "white", "plot_bgcolor": "#E5ECF6", "polar": {"angularaxis": {"gridcolor": "white", "linecolor": "white", "ticks": ""}, "bgcolor": "#E5ECF6", "radialaxis": {"gridcolor": "white", "linecolor": "white", "ticks": ""}}, "scene": {"xaxis": {"backgroundcolor": "#E5ECF6", "gridcolor": "white", "gridwidth": 2, "linecolor": "white", "showbackground": true, "ticks": "", "zerolinecolor": "white"}, "yaxis": {"backgroundcolor": "#E5ECF6", "gridcolor": "white", "gridwidth": 2, "linecolor": "white", "showbackground": true, "ticks": "", "zerolinecolor": "white"}, "zaxis": {"backgroundcolor": "#E5ECF6", "gridcolor": "white", "gridwidth": 2, "linecolor": "white", "showbackground": true, "ticks": "", "zerolinecolor": "white"}}, "shapedefaults": {"line": {"color": "#2a3f5f"}}, "ternary": {"aaxis": {"gridcolor": "white", "linecolor": "white", "ticks": ""}, "baxis": {"gridcolor": "white", "linecolor": "white", "ticks": ""}, "bgcolor": "#E5ECF6", "caxis": {"gridcolor": "white", "linecolor": "white", "ticks": ""}}, "title": {"x": 0.05}, "xaxis": {"automargin": true, "gridcolor": "white", "linecolor": "white", "ticks": "", "title": {"standoff": 15}, "zerolinecolor": "white", "zerolinewidth": 2}, "yaxis": {"automargin": true, "gridcolor": "white", "linecolor": "white", "ticks": "", "title": {"standoff": 15}, "zerolinecolor": "white", "zerolinewidth": 2}}}, "title": {"font": {"color": "rgba(20, 36, 44, 0.7)"}, "text": "citric acid"}, "width": 800, "xaxis": {"anchor": "y", "domain": [0.0, 0.17333333333333334], "linecolor": "rgba(100, 100, 100, 0)", "showgrid": false, "tickfont": {"color": "rgba(100, 100, 100, 0.8)"}, "zeroline": false}, "xaxis2": {"anchor": "y2", "domain": [0.24, 0.41333333333333333], "linecolor": "rgba(100, 100, 100, 0)", "showgrid": false, "tickfont": {"color": "rgba(100, 100, 100, 0.8)"}, "zeroline": false}, "xaxis3": {"anchor": "y3", "domain": [0.48, 1.0], "hoverformat": ",.2f", "linecolor": "rgba(100, 100, 100, 0)", "showgrid": false, "tickfont": {"color": "rgba(100, 100, 100, 0.8)"}, "zeroline": false}, "yaxis": {"anchor": "x", "domain": [0.0, 1.0], "hoverformat": ",.2f", "linecolor": "rgba(100, 100, 100, 0)", "showgrid": false, "tickfont": {"color": "rgba(100, 100, 100, 0.8)"}, "zeroline": false}, "yaxis2": {"anchor": "x2", "domain": [0.0, 1.0], "hoverformat": ",.2f", "linecolor": "rgba(100, 100, 100, 0)", "showgrid": false, "tickfont": {"color": "rgba(100, 100, 100, 0.8)"}, "zeroline": false}, "yaxis3": {"anchor": "x3", "domain": [0.0, 1.0], "linecolor": "rgba(100, 100, 100, 0)", "showgrid": false, "tickfont": {"color": "rgba(100, 100, 100, 0.8)"}, "zeroline": false}},                        {"displayModeBar": false, "showTips": false, "responsive": true}                    )                };                            </script></div>
