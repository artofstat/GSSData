# GSS Data Editor

This shiny app lets users download data from the General Social Survey (GSS)

Users should be able to select one or two variables.
Users should be able to filter by year, or select multiple years.
App should show frequency/contingency table of selected variables, and corresponding plot.

Files currently included:


__Data_Preprocessing.Rmd__ : Filtered the original data by years and variables, converted variable types into factors and save as csv file.

__finaldata.csv__ : Filtered and coverted data

__finaldata.dta__ : Filtered original data

__ui.R__ and __server.R__ : Code for R shiny dashboard


