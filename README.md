# LoadTestProject-JMeter
 Tool:jmeter 5.4.3 binary,
 case aim: check search Module Performance in www.N11.com, load test
Tips: 
 -for csv report use simple data writer or use jmeter command 
 -for APDEX  report convert from csv report or directly use jmeter command
 -for better performance run test cases on Non-Gui mode
 -do not forget to run jmeter command under ..\bin 

"jmeter -n -t C:\Users\Casper\Downloads\apache-jmeter-5.4.3\apache-jmeter-5.4.3\bin\searchModuleCase1.jmx -l C:\JmeterReports\csv\earchModuleCase1.csv -e -o C:\JmeterReports\apdex\searchModuleCase1"
 
