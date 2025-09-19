# OA3801_aviation_accidents
Study of trends involving aviation incidence since 1981.  Specific focus on the trends around the TCAS, ADS-B, and post 9/11 regulation changes.  The team analyzed the effects of FAR part licenses, seasonal changes, and mechancical differences in each event.

# Accessing NTSB
1.  Navigate to the below link:
   [NTSB](https://www.ntsb.gov/safety/data/Pages/Data_Stats.aspx)

2.  Click 'Downloadable data sets'

3.  Download s separate zip files
   [Pre 2008](https://data.ntsb.gov/avdata/FileDirectory/DownloadFile?fileID=C%3A%5Cavdata%5Cavall.zip)
   [Post 2008](https://data.ntsb.gov/avdata/FileDirectory/DownloadFile?fileID=C%3A%5Cavdata%5CPre2008.zip)

# Useful Files
1. Executive Summary: Outlines the entirety of the work the team has completed.  Explains all tasks, methods, and results in addition to recomendations for future work.

2. Time_seriesdecompositon.ipynb: Working file for conducting the seasonal and time series analysis using the STL method.

3. phase_of_flight.ipynb: Breaks the data down by FAR Part and focuses on the trends surrounding the three primary regulation changes.

4. engine_anlysis.ipynb:  Found in the engine analyssis folder along with all necessary csv files and images of code segments.  Combines all necessary data for identifying trends among engine manufacturers into one master file and then filters based on event code.
