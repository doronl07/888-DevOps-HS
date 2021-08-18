# 888-DevOps-candidate-HS
This is the hiring assignment for Devops candidates at. It’s intended to mimic work you might do here, while giving us an understanding of your skills in: 
-	Git
-	Windows System Administration
-	Ansible
-	Powershell
-	Networking
-	Docker
## How to answer this assignment
This assignment contains Different tasks. (Git, Ansible, Powershell, Windows, Docker). To complete this assignment successfully, you'll need to attempt to complete Git, Ansible and PowerShell tasks, the rest are bonus.
## Git ##
1.  create a user in github if you dont have already
2.  create a new repository
3.  clone it to your local machine
4.  create a new remote branch called 888holdings using git command line
5.  upload your code and files into the remote branch (using git commands) and share the link with us

## Ansible ##
Preq:
1 linux server (any distro) for ansible server
1 centos 7 server
1 windows server (any version)

machines can be set up in any cloud, hyper-v, vagrant or any other platform that you find it suitable

1.	Install the ansible on the ansible server (Manually)
2.	Build an inventory with 2 groups [win] & [linux] 
3.	Using ansible, please Install apache on the Linux machine and IIS on the window machine.
    Using ansible, change httpd.conf to listen only on port 8080
4.	Create a test website on the IIS on port 80 using ansible (note: ansible has modules)
5.	Create an empty test.txt file on the ansible machine. Copy the test.txt file to the root site on both machines
    (Bonus: Create another file called default.html. Using Jinja, input into it the date_time (can be taken from ansible facts) and copy it to the root site on both machines.)
6.	Recycle the app pool of the new test website using ansible

Tip:
-	Use only ansible and ansible modules. 😊
## Powershell task
-	Notepad is the most important process on our system, and it must be running the whole time, unless we are under maintenance.
-	When we want to start a maintenance, we need to create a file under c:\tmp\maintenance.txt
-	When maintenance is done, file can be removed.

First Part

- Please write a script to monitor the notepad process. 
- The script will create a CSV file with 2 headers, "Date" & "Message"
- Checks if the process for notepad is running 
  - Process is running - Write the current hour, minute & second into the csv file.
     and the message "Notepad is running"
  - Process is not running - Start the notepad process (only if we are not under maintenance mode), write the current hour, minute & second into the csv file and the message "Notepad was started".

- Checks if a file maintenance exists.
  - Fie Exists - write the current hour, minute & second into the csv file.
  - Write "We are under maintenance mode!" in the message.

- The script should run for 5 minutes and it should sample the process every 5 seconds.

Second Part:
-	Extract from the csv only the lines which have "We are under maintenance mode!" in them.
-	Count & output the amount of lines extracted

Bonus:
-	Extract from the CSV all the lines where notepad wasn't running and had to be opened.
-	Show via some GUI all the relevant lines from the CSV.
-	Give the user an option to choose some lines and save them into a separate file.

## Windows Task
-	Create a new https binding on port 443 to your web site 
-	Create a self-signed certificate and bind it to your web site
-	Install dns service and create new zone (you can choose any domain name that you want)
-	add a record to point the local web server you created in bullet 1, also make sure to create a record to perform dns reverse lookup
-	publish a small exe file via the web site you created download it. Record (sniff) the download session into a pcap file.
-	filter the download session from the pcap file and create a screenshot, describe the communication step by step in the session

## Docker Task
-	create a docker file to install linux server with nginx
- change the default port to 8080
- copy your git repository into the docker 
- create an image out of it
