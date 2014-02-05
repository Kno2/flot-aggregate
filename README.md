flot-aggregate
==============

Flot plugin for plotting grouping and aggregating data based on a common axis value.


```javacript

var plotData = {"data": [{"data": [["Not executed", 1], ["Not executed", 1], ["Not executed", 1], ["Not executed", 1], ["Not executed", 1], ["Not executed", 1], ["Failed", 1], ["Not executed", 1], ["Passed", 1], ["Passed", 1], ["Passed", 1], ["Passed", 1], ["Passed", 1], ["Passed", 1], ["Passed", 1], ["Passed", 1], ["Passed", 1], ["Passed", 1], ["Passed", 1], ["Passed", 1], ["Passed", 1], ["Passed", 1], ["Passed", 1], ["Passed", 1], ["Passed", 1], ["Passed", 1], ["Passed", 1], ["Passed", 1], ["Passed", 1], ["Passed", 1], ["Passed", 1], ["Passed", 1], ["Passed", 1], ["Passed", 1], ["Passed", 1], ["Passed", 1], ["Passed", 1], ["Passed", 1], ["Passed", 1], ["Passed", 1], ["Passed", 1], ["Passed", 1], ["Passed", 1], ["Passed", 1], ["Passed", 1], ["Passed", 1], ["Passed", 1], ["Passed", 1], ["Passed", 1], ["Passed", 1]], "label": "Verdicts"}], "option": {"series": {"bars": {"align": "center", "barWidth": 0.8, "show": true}}, "grid": {"clickable": true, "hoverable": true}, "xaxis": {"aggregate": "count", "mode": "categories", "categories": {"Failed": 1, "Not executed": 3, "Passed": 0, "Blocked": 2}}}}

```


![preview](https://lh3.googleusercontent.com/_OiJtIwyIPrFgSXDtmgKzTvjurEaJmc9YiK65I9Qy36LYWJjfHbCuFclTzJg0oL7n4cguoMo6PhEDhgzWYMpXmPcBUAL2h6B6d41l0MHH_pYVMPDRw8zg8v3jA)
