# PerformanceTest86400
1. Performance testing API

Steps:
a. Download latest Jmeter from here: https://jmeter.apache.org/download_jmeter.cgi

or use this one: https://dlcdn.apache.org//jmeter/binaries/apache-jmeter-5.4.3.zip

b. Download the Performance test scripts from: 


c. Go to Command line and change directory to the folder where the script was downloaded
eg. cd c:\PerformanceTestScripts
 
d. Run this command:  
[Jmeter bin directory]\jmeter -n -t CreatePetPerformanceTests.jmx -l result.jtl

eg. 
C:\Users\jet_guest\Downloads\apache-jmeter-5.4.3\apache-jmeter-5.4.3\bin\jmeter -n -t CreatePetPerformanceTests.jmx -l result.jtl

e. view results file in the same folder as the script: results.txt


	
 
