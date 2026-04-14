Activity # 12: SOC Log Monitoring & Threat Detection Simulation
CTF-Style Cybersecurity Activity

GitHub Repository: 
	https://github.com/xen0byt3/xen0byt3-CTM-Activity-12

Overview
	This activity is a Cyber Threat Monitoring Simulation where you will act as a SOC Analyst.

A server has been attacked. Your job is to:

	Investigate authentication logs
	Identify suspicious activity
	Detect brute-force attacks
	Track attacker IP addresses
	Capture hidden CTF flags

Objectives

By completing this activity, you will:

	Apply Linux command-line skills in a real scenario
	Analyze auth.log like a SOC analyst
	Detect brute-force login attempts
	Identify attacker behavior patterns
	Perform basic threat hunting

Installation / Setup

	Go to the repository
	Download the files or clone the repo:
	git clone https://github.com/xen0byt3/xen0byt3-CTM-Activity-12.git
	Locate the .exe file
	Run the simulator

How to Use

	After running the program:

	Press ENTER to continue...

	You will see the main menu:

	[1] Start Investigation
	[2] Flag
	[3] Exit

PART 1: Investigation Mode

	Select:
	[1]

	Follow on-screen instructions and type correct Linux commands such as:

		ls
		cat
		tail
		head
		grep 
	You must type exact commands to proceed.


PART 2: Flag Mode (CTF Challenge)

	Select:
	[2]

	Answer all questions using this format:

	flag{your_answer}

Example:

	flag{auth.log}
	flag{10}
	flag{203.0.113.50}

[Final Flag Challenge]

Create the final flag using:

	flag{TopAttackerIP-TotalAttempts-SuccessfulIP}

[Output Files]

After completing the activity:

	log_monitoring_report.txt
	List of executed commands

Investigation outputs
	flag_monitoring_report.txt
	Your answers

[Submission Guidelines]

Choose one of the following:

	Option 1 (Recommended)
		Upload your 
		log_monitoring_report.txt and flag_monitoring_report.txt to your GitHub repository
		Add xen0byt3 as a collaborator

	Option 2 (Most Recommended)
		Create a Pull Request containing your 

		log_monitoring_report.txt
		flag_monitoring_report.txt

Score and rating

	Scoring System
	Score	Rating
	9–10	SOC Analyst
	6–8	Junior Analyst
	0–5	Trainee

Rules

	Follow instructions carefully
	Use correct command syntax
	Analyze before answering
	No random guessing

Tips

	Look for repeated IP addresses
	Count failed login attempts
	Identify which IP succeeded
	Watch the live attack simulation carefully

Real-World Scenario

	This simulation reflects actual SOC tasks such as:

	SSH brute-force attack detection
	Log monitoring and analysis
	Incident investigation
	Threat identification

Credits

	Developed by xen0byt3
	“Investigate like a defender. Think like an attacker.”
