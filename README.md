# ArcSight-Windows_Taskscheduler-FlexConnector
This parser is for the "TaskScheduler" Event log source

Microfocus ArcSight Windows Native FlexConnector for Microsoft TaskScheduler Operational Event Log

Device / Product version: Tested on Windows 2012, Should work on others

SmartConnector Type: Windows Native Connector Dependencies: Microfocus ArcSight SmartConnector Framework at least 7.4

Installation Summary
Copy the fcp folder and the contents to the CONNECTOR_HOME/current/user/agent/ folder on the Windows Native Connector

Add the following Event Log to the Windows Native Connector Custom Log section:Microsoft-Windows-TaskScheduler/Operational

Restart the Windows Native Connector

USE CASE
Track changes to scheduled tasks to detect attempts to persist access or create suspicious scheduled tasks - typically seen in Ransomware
