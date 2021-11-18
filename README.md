Unit README: 
Red Vs. Blue Team Project
Unit Description
In the second project week, you will work on a Red Team vs. Blue Team scenario in which you will play the role of both pentester and SOC analyst.
As the Red Team, you will attack a vulnerable VM within your environment, ultimately gaining root access to the machine. As Blue Team, you will use Kibana to review logs taken during their Day 1 engagement. You'll use the logs to extract hard data and visualizations for their report.
Then, you will interpret your log data to suggest mitigation measures for each exploit that you've successfully performed.
Unit Objectives
Click here to view the daily unit objectives. 
This week's project will prompt you to apply knowledge of the following skills and tools:
	• Penetration testing with Kali Linux.
	• Log and incident analysis with Kibana.
	• System hardening and configuration.
	• Reporting, documentation, and communication.
Lab Environment
Click here to view the lab environnement. 
In this unit, you will be using the Red vs Blue lab environment located in Windows Azure Lab Services. RDP into the Windows RDP host machine using the following credentials:
Username: azadmin Password: p4ssw0rd*
Open the Hyper-V Manager to access the nested machines:
	• ELK machine credentials: The same ELK setup that you created in Project 1. It holds the Kibana dashboards.
		○ Username: vagrant (root)
		○ Password: vagrant  (toor)
		○ IP Address: 192.168.1.100 
	• Kali: A standard Kali Linux machine for use in the penetration test on Day 1.
		○ Username: root 
		○ Password: toor 
		○ IP Address: 192.168.1.90 
	• Capstone: Filebeat and Metricbeat are installed and will forward logs to the ELK machine.
		○ IP Address: 192.168.1.105 
Please note that this VM is in the network solely for the purpose of testing alerts.

