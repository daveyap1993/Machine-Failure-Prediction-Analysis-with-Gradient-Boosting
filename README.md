# Machine-Preditive-Maintenance-Analysis-with-Gradient-Boosting

This project is the gentle introduction of Machine Predictive Maintenance Analysis using supervised machine learning method(XGBoost).

**This series aims to:**

Find key component to prevent breakdown before they occur
Estimate total cost that a machine will fail in the future
For long term target, we aim to estimate and decrease the breakdown cost by improvong this supervised fault classification


**Data source**

In this project, I use time-stamped machine data for predictive maintenance problems, includes failure history, maintenance history, machine conditions and usage, machine features and operator features. I will use below data sources for predictive maintenance problems:

telemetry data: Machine conditions and usage, operating conditions of a machine e.g. data collected from sensors.
errors data: Non-breaking errors history of a machine or component within the machine.
maintenance(maint) data: Maintenance history, repair history of a machine, e.g. error codes, previous maintenance activities or component replacements.
failures data: Failure history, breakdown history of a machine or component within the machine.
machines data: Machine features, features of a machine, e.g. engine size, make and model, location.
