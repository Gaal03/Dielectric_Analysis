# Dielectric_Analysis
Jupyter notebook used to perform automated analysis of electrical characterization of super capacitors dielectrics.
We use a picoammeter Keithley 6487 to acquire the Current-Voltage curves. The dielectric analysis jupyter notebook has scripts that communicate to the equipment. Once
you set the initial parameters the picoammeter will start to acquire the data automatically and then ot will save a .txt file with the data in a pre specified folder.
You can also perform several curves with different scan rates and automatically save your data in a different folder.
This data can be further analyzed with the data analysis jupyter notebook. In this notebook we have several scripts that allow you to analyze important features such as
the dependency of the current hysteresis with the scan rate, the dependency of the current at different voltage values for each scan rate and further evaluate
the b-value and other insteresting features.
