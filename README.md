Anonymous code release for reproducing ICML'22 submission 6164: "Time Series Anomaly Detection by Cumulative Radon Features"

To run code, simply enter:
`python tester.py`

To evaluate other datasets, please modify variable `ds` in tester.py appropriately.  
To evaluate SAD, please download the dataset from: http://www.timeseriesclassification.com/ (the file size was too large for github).

### Troubleshooting:

Reading the .ARFF files fails when you have an old version of scipy. If this happens, please upgrade your scipy ('pip install scipy --upgrade')
