AttendanceRecord
Current Version：1.0.0.26
Purpose to introduce: 
	This is used for attendance data summary.

Structure:
	Client-Server ．

Installation tutorial:
	Server side:	
		1.Install  Oracle Database 10g Enterprise Edition Release 10.2.0.3.0
		2.Setup the FTP Server. 
			directory structure：./AttendanceRecord;	
			necessary file: Version.txt         the content of this file:  AttendanceRecord:   1.0.0.25
      It is used to check the version of the file.
	Client side：
		Install ODTwithODAC1020221.exe
		Install Microsoft Office 2007

Instructions:
	1.Log in：Double click the AttendanceRecord.exe;
	2 Import : Import original data.                     
	3.Set overtime days.
	4.Attendance record summary.

Participate in the contribution:

	1. ministry of personnel: 	Logic provider.
	2. IT Department:		Program Design and Implement.
	3. Manager Li: Program	confirmation.
	
Characteristic of project: 
Oracle Server：	 

1.	Procedure or packages:	Handle import and data summary.
2.	At the time of import,Check the same name but different machine number、
	  the same spell but different Chinese characters.
3.	Get Department and Team Info Of Employees From Manufacturing Execution Systems.

Excel: 
Namespace Excel
  For reading and writing the excel document.
	
	Front end：
		1.Use window form design.
		2.Use BackgroundWorker control,Causes controls to run operations asynchronously.
	So that the Label,ProgressBar control to display updated information in real time.
		3. Load the XML Document using XmlDocument and read the connection information in flexflow.cfg.
