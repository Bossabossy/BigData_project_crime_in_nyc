# BigData_project_crime_in_nyc
If you are reader from my article from medium.com Welcome!
if you are interested in following the instrction on how to run the code, the source_code file has all the code and instruction with comments on them. 
For the images on how stuff should run on HDFS or HIVE, check the Project_evidence_screenshot file, it has picture of the terminal included in it. 
The rest of the message are only useful to NYC facaulty who will be checking my work.

nc2325 code and documents about crimes and violation data in NYC

--Author Boss and Minsu

--attemp to run the code by ctrlc ctrlv the code usually doesn't work due to quotation symbol (') issue
--try to retype every quotationmark inorder for stuff to runs smoothly

--Hive Initialize code
beeline
!connect jdbc:hive2://hm-1.hpc.nyu.edu:10000/
use nc2325(use your netid)

The code in the source_code.sql in the zip file has instruction in chronological orders.
data should be upload to hdfs into it's own seperate directory. The directory should only have single csv file and only itself.
The user have to login to beeline to create the table then import the data from csv file into the table.
Run and test the query in the beeline command to ensure the result is what you want.
Then go to terminal in peel run the beeline command the initialise the query download into the peel server.

There are two files for the input of this project 
/user/nc2325/project_camera
/user/nc2325/project_complaint
both has share access with adm209, nks8839, and sj3549.

As stated in the source code, the output is directly downloaded into peel. It can be found in the root directory of nc2325
It's also attached in the zip file 
