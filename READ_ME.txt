The RMD files for this project were run in the following order:
1) ETL_script.RMD - Loads data from Dairyland Laboratories Inc's database and transforms it for analysis
2) statistical_filter_round1.RMD - filters the source data according to strategies outlined in the paper
3) statistical_filter_round2.RMD - filters the results of statsistical_filter_round1.RMD a 2nd time
4) Create_classification_models_and_analyze.RMD - Creates classification modesl from the filtered data and calculates performance metrics
5) Summary_of_the_statistical_filter_for_paper.RMD - Uses output data from the statistical filters to calculate summary information presented in the paper