
# Frac Method Analysis

While hotly debated, hydraulic fracturing is used after the drilling of an oil or gas well is complete.  Hydraulic fracturing uses fluid and other materials to create small fractures in a rock formation in order to stimulate the production of further oil and gas from the well.  While water and sand are the major components of this fluid, each individual operator has say over what else is added to this fluid.  There are many different schools of thought behind the use of individual additional ingredients without much evidence to support the use of one method over another.  Fortunately well operators are required to keep detailed records of the ingredients used, including the amount of such ingredients.  Here I will explore three methods of fracing a well, adding slickwater friction reducers, using gelling agents, and also cross-linking the gel, along with the production from each type of well to help well operators make better decisions as to the chemicals they are adding to their frac fluids.

INSERT ABSTRACT HERE

The production data I will be using is extacted from the [Colorado Oil and Gas Comission Information System (COGIS)](https://cogcc.state.co.us/data.html#/cogis) through a proprietary service provided by [DrillingInfo.com](DrillingInfo.com).  The detailed ingredient lists for each well were pulled from the [FracFocus Chemical Registry](http://fracfocusdata.org/).

### Installation
Download the following from above:
__For Data Cleaning and Exploration__
- `2017_prod_reports.csv`, which includes Colorado well production by month since 1990.
- `DHJZ6-17-18Wells.CSV`, which includes the information on all Colorado well production
- `dj hz 6-17-18 Production Time Series.CSV`, which contains production for each month for each well
- `FracFocus` folder, which contains csv files from the FracFocus Registry
__For Modeling__
- `fracwells_clean.csv`, which contains cleaned and merged data on well production and fracing methods for Colorado.

### Usage
__Data Cleaning:__ Run all cells in the `Frac_Production_Data_Cleaning` file using a jupyter notebook.
__Exploratory Data Analysis:__ Run all cells in the `Frac_Production_Analysis` file using a jupyter notebook.
__Modeling:__ Run all cells in the `Frac_Production_Modeling` file using a jupyter notebook.
Summary of the analysis and modeling can be found in the `ADD PRESENTATION HERE` file. 

### Extending this
If you want to extend this work, here are a few places to start:
