## BTMA431 Final Group Project - MoneyPuck

Group Members: Isaac Lutzko, Nolan Ruzicki, Karl Specht, Doug Strueby

General Description: Conducted a study on and investigated NHL player and team data. Using R, this data was collected via web scraping, visualized with R packages, and analyzed via decision analysis and other statistical methods.

Running Instructions:
1) Download zip.
2) Unzip the folder that contains all the files for our project (R files, Power BI files, etc.)
3) Open RStudio and open the 4 R files (DataCollection, Playoffs, DepthModule, and 
   ChampionsExcel) that are in the folder.
4) Run the R files in the following order:
	i) "CTRL + Enter" through the "BTMA431_FinalGroupProject_DataCollection" file first. Note that
	   some for loops may take longer than expected because we need all the necessary data is
	   collected but also make sure we don't make too many HTTP requests made within the time
	   limit for our data source (https://www.hockey-reference.com/). Without the Sys.sleep() call
	   in two of the main for loops, the HTTP request limit is reached and not all data needed is 
	   gathered.
	   Ensure you take note of the comments in the file, especially changing the setwd() function
	   call to your local path that contains the unzipper folder.
	   Also note that the data frames that are created in your working environment in RStudio will
	   be used for the 3 following files.
       ii) "CTRL + Enter" through the "BTMA431_FinalGroupProject_Playoffs" file second. Change paths
	   in certain lines to your local path as necessary as well. Please see our PredictedStandings2 CSV 
	   file that is one of the outputs for running this file.
      iii) "CTRL + Enter" through the "BTMA431_FinalGroupProject_Depth_Module" next. Again, change the path
	   as necessary and follow the comments as needed.
       iv) "CTRL + Enter" through the "BTMA_431_FinalGroupProject_ChampionsExcel" file last. See the Power
	   BI file that is used for the data visualizations (some being interactive using Power BI slicers)
	   for this file and for this question.
