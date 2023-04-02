# Python-for-monthly-recap-from-XLSX-case-2-glob-
Monthly XLSX recap from 'Daily files' in structured Folder directory with Python 

## Description
This simple program is use to help recapitulation process for some value that was input from many corporate office branch/area.
Existing process was do manually copy from XLSX (branch) to master report XLSX, this program is cut that process.
Directory structure is quite simple as 'data A/MM-YYYY' and merge with other data from 'data B/MM-YYYY', 
so in this case can use 'glob' to reach the files. 

Program Flow 
1. Input : Report Period
2. Import Files : all XLSX Branch Report (daily report) data in period 
3. Method:
    (a) Read set of cell values from current branch, loop for next branch
    (b) Append proccess (3.a.) to dataframe
    (c) Export to XLSX


akmalazua@gmail.com
