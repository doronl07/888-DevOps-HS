# 888-DevOps-candidate-HS
This is the hiring assignment for Devops candidates at 888\Sparkware. It’s intended to mimic work you might do here, while giving us an understanding of your skills in: 

  - Linux\Windows System Administration
  - Scripting
  - Networking
  
## How to answer this assignment
This assignment build from 3 tasks (Windows, Linux, Docker). To complete this assignment successfully, you'll need to choose one of the tasks you feel comfortable with(you can choose more than one, completing all of them will definitely give you extra points in the hiring process ;) )

## Ansible ##
Preq:
1 linux server (any distro) for ansible server
1 centos 7 server
1 windows server (any version)

(machines can be set up in any cloud, hyper-v, vagrant or any other platform that you find it suitable)
1.	Install the ansible on the ansible server (Manually)
2.	Build an inventory with 2 groups [win] & [linux] 
3.	Use ansible-vault to encrypt the linux & win local users
4.	If not already installed, please Install apache on the Linux machine and install IIS on the window machine.
    Bonus: with one playbook – check if it’s a linux machine, install the apache and if it’s a windows machine install the IIS.
5.	Using ansible, change httpd.conf to listen only on port 8080
6.	Create a test website on the IIS using ansible (note: ansible has modules)
7.	copy test.txt from ansible machine, to the test website on the win machine. The test.txt should contain the ansible date_time.
8.	Recycle the app pool of the new test website using ansible.

Tip:
Use only ansible and ansible modules. Scripting are not required 😊

please upload your code to github and send us a link. if you dont have an account, you can create one free.


## Windows Task

  - Create a script to install IIS and create a site which serves HTML page with "Hello World"
  - Create a self-signed certificate and bind it to the site you created in the previous bullet on port 443
  - Install dns service and create new zone(you can choose any domain name that you want)
  - add a record to point the local web server you created in bullet 2, also make sure to create a record to perform dns reverse lookup
  - publish a small exe file via the web site you created download it. Record(sniff) the download session into a pcap file.
  - filter the download session from the pcap file and create a screenshot, describe the communication steps steps in the session

## Linux Task\Docker Task

- Build a Linux server (you can choose your favorite flavor)
- Create a script to install Apache\Ngninx and create a site which serves HTML page with "Hello World"
- Create a self-signed certificate and bind it to the site you created in the previous bullet on port 443
- Install dns service and create new zone(you can choose any domain name that you want)
- add a record to point the local web server you created in bullet 2, also make sure to create a record to perform dns reverse lookup
- publish a small exe file via the web site you created download it. Record(sniff) the download session into a pcap file.
- filter the download session from the pcap file and create a screenshot, describe the communication steps steps in the session

