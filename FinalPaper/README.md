## Code and Data introduction for final paper

### Qian Zhang

1. `Code` folder
    * `I_corr_ind_construct.ipynb` is the notebook to construct the new corruption index that reflects corruption control in my paper (Section 3 in paper). 
    * `II_panel_construct.ipynb` is the notebook to prepare and construct the panel data used for estimation in the paper.
    * `III_GMM_estimation_stata_log.pdf` is the log record of the GMM estimation process for the Dynamic Panel Data (DPD) model. The estimation part is mainly proceeded in Stata (Section 4 in paper).
    * `IV_prediction_on_growth.ipynb` is the notebook to run machine learning prediction on economic growth (Section 5 in paper). 

2. `Data` folder
    * `icrg20162.xls` is the set of ICRG indexes, one major data source for construction of new corruption index. 
    * `wgidataset_filter.xlsx` is the set of World Governance Indicators released by World Bank, and it is another major data source for the construction of new corruption index. 
    * `final_panel.csv` is the final panel data constructed by `II_panel_construct.ipynb` and it is imported to Stata for later on estimation.
    * `svmci.csv` stores constructed index, and it is exported by `I_corr_ind_construct.ipynb` and is imported to `II_panel_construct.ipynb` to form the panel data.
    * Note: Most of the macroeconomic indicators come from World Development Indicator (WDI) by World Bank, but due to the limit size of uploaded file on Github, WDI data cannot be directly uploaded. The download link for WDI data is https://datacatalog.worldbank.org/dataset/world-development-indicators. 

3. `final_paper_QianZhang.pdf` is the major body of the final paper.
