# 888-DevOps-candidate-HS
This is the hiring assignment for Devops candidates at 888\Sparkware. It’s intended to mimic work you might do here, while giving us an understanding of your skills in: 

  - Linux\Windows System Administration
  - Scripting
  - Networking
  
## How to answer this assignment
This assignment build from 3 tasks (Windows, Linux, Docker). To complete this assignment successfully, you'll need to choose one of the tasks you feel comfortable with(you can choose more than one, completing all of them will definitely give you extra points in the hiring process ;) )

## Windows Task

  - Build a Windows server (you can download predeployed windows 2016 ova from here: http://tinyurl.com/sol9vhc )
  - Create a script to install IIS and create a site which serves HTML page with "Hello World"
  - Create a self-signed certificate and bind it to the site you created in the previous bullet on port 443
  - Install dns service and create new zone(you can choose any domain name that you want)
  - Add a record to point the local web server you created in bullet 2, also make sure to create a record to perform dns reverse lookup
  - Add a small exe file or a an image to the web site you created and download it. Record(sniff) the download session into a pcap file.
  - Filter the download session from the pcap file and create a screenshot, describe the communication steps steps in the session
  - Write a script that read the IIS log file, parse it and write into a csv file the date, time, s-ip, cs-uri-query, sc-status

## Linux Task\Docker Task

- Build a Linux server (you can choose your favorite flavor or download a predeployed ova from here: https://tinyurl.com/spjn4ya)
- Create a script to install Apache\Ngninx and create a site which serves HTML page with "Hello World"
- Create a self-signed certificate and bind it to the site you created in the previous bullet on port 443
- Install dns service and create new zone(you can choose any domain name that you want)
- Add a small exe file or a an image to the web site you created and download it. Record(sniff) the download session into a pcap file.
- Filter the download session from the pcap file and create a screenshot, describe the communication steps steps in the session
- Write a script that read the Apache\Ngninx log file, parse it and write into a csv file the date, time, s-ip, cs-uri-query, sc-status


**Login details for Linux predeployed OVA - Username: osboxes | Password: osboxes.org | Root Account Password: osboxes.org**
