# Tasks_to_Do
Home task for DevOps Engineer

# TASKS:

1.Please write a simple CLI application in the language of your choice that does the following: 
● Print the numbers from 1 to 10 in random order to the terminal. ● Please provide a README that explains in detail how to run the program on MacOS and Linux. 

2. Imagine a server with the following specs: 
● 4 times Intel(R) Xeon(R) CPU E7-4830 v4 @ 2.00GHz 
● 64GB of ram 
● 2 TB HDD disk space 
● 2 x 10Gbit/s nics 
The server is used for SSL offloading and proxies around 25000 requests per second. Please let us know which metrics are interesting to monitor in that specific case and how would you do that? What are the challenges of monitoring this? 
Please send us your solution as a GitHub project.


TASK1: 

# Print_Random_Numbers #
#Pre-req -> run this on MACOS terminal and you need to have python >3.5 installed on it 

# command to open the python script #

/usr/bin/vim Print_Random_Number.py

# command to execute the python script #

/usr/bin/python3 Print_Random_Number.py

# Output :
6, 0, 3, 7, 4, 9, 2, 5, 8, 1

# TASK2:

As per the given specifications we can have various metrics which we can take into consideration like 
CPU load
CPU temp
CPU used
disk used
mem used
network util
some of them attached as CPU_load.png and mem_usage.png 
Tools involved/needed to capture these metrics are **Zabbix** and **PAFtool** which can execute various performance checks, custom checks on time interval.
We can capture real time graphing, historical data storage via database and create custom dashboards using Zabbix.
