Assignment Details
	Student ID: IT23843202
	Module: IT3040 – ITPM
	Assignment: Assignment 1 – Transliteration Accuracy Testing
	GitHub Link: https://github.com/Shakya202/ITPM_Assignment01_Resheduling.git

About This Assignment
	The assignment is about how a web application converts singlish to 	sinhala text.

	The main objective was to check the system whether it gives the 	correct sinhala output from the different types of real life chat 	styles


Website I Used
	https://www.pixelssuite.com/chat-translator


Tools I Used
	Python
	Playwright (for automation)
	Microsoft Excel (to record results)
	Visual Studio Code
	Command Prompt


How I Did This Assignment
1.Creating test cases
	Initially, multiple test cases were created by me using different 	singlish outputs.

	Mainly i focused about comment chat styles such as :
		Spelling variations
		Short forms
		Mixed english + sinhala words
		Informal sentences

	Here only incorrect outputes from the system were chosen.

2. Setting Up the Environment
	I installed Python and Playwright to run the automation.

Commands used:
	pip install playwright
	playwright install
Preparing the Automation Script
	I used the provided Python script (test_automation.py).
	Then I connected it with my Excel file and the testing website.

4. Running the Tests
cd /d D:\IT23843202
	python IT23843202_test_automation.py --excel "D:\IT23843202\IT23843202_Test_cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open

The script automatically:
	entered inputs
	collected Sinhala outputs
	saved results into Excel

5. Recording Results
	All results were saved in the Excel file.
	For each test case, I added:
		input
		expected output
		actual output
		pass/fail status
		Singlish input type
		evidence and explanation


6. Analyzing the System
	After running the tests, I compared the outputs and identified 	where the system failed.

	I noticed that the system struggles with:
		complex words
		spelling variations
		continuous text without spaces
		special characters

Files Included
	IT23843202_Test_cases.xlsx → contains all test cases
	IT23843202_test_automation.py → automation script
	IT23843202_Requirements.txt
	IT23843202_README.md

What I Learned
	how to test real-world applications
	how automation tools like Playwright work
	how to identify weaknesses in a system


Conclution
	This assignment encouraged the evaluation of accuracy in this 	singlish transliteration.

	Eventhouth the system works fine with 	simple cases, it shows some 	issues with complex and informal chat 	styles.
