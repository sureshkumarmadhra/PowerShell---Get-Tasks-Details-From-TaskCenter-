# PowerShell---Get-Tasks-Details-From-TaskCenter-
-------------------------------------------------

Introduction:
--------------

This Powershell script will check the status of tasks which are schedule in TaskCenter. It will read the respective task status and generate the CSV File report about start time/ end time/ next runtime and other task properties. 

Version: Powershell 2.0
----------------------

Function:
-------------
This script will perform following functions:

1. Get the Task list from the Task Center
2. Generate Excel sheet containing the task details - Start Time, End Time, Next run-time
3. The Excel sheet will be updated after every one hour and check the status of task in taskcenter eachtime
4. Email the excel sheet along with details to respective resolver team.

Source code:
-------------

GetTaskCenter_TaskStatus.ps1
