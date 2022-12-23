Description of the Assignment/Activity:

Texas Tech University
Computer Science Department
CS 6345 – Digital Forensics
Spring 2022, Assignment 1 
Work as a team, or solo (if you prefer)
Due Dates: Given below for each stage

Goal: 1) Creating (red team) and 2) Analyzing (blue team) a malicious PDF

Cautions: PLEASE HANDLE MALICIOUS FILES WITH CARE. DO NOT CLICK ON OR EXECUTE THEM. YOU NEED TO CREATE OR DOWNLOAD THEM INTO YOUR MINI-VIRTUAL LAB AND ANALYZE THEM THERE WITHOUT EXECUTING THEM. 

Assignment 1 will be executed in two stages:
1.	Creating a malicious PDF file using the Kalli Linux Metasploit tool
2.	Analyzing a given malicious PDF file using tools such as Remnux, or PDF Stream Dumper  

The instructor and the grader of this course will manage the pdf file exchange and sharing among the teams after Stage 1. 

Stage 1. 
Using Kalli Linux’s Metasploit, you are required to create a pdf file with malicious payload/shellcode. You can make the created pdf file as complex as you can using techniques such as compression, filtering, obfuscation, etc. The encryption of pdf file might cause some problem with analyzing the created malicious pdf file. So you may need to avoid encrypting your pdf file so the other team can analyze it. 

You also need to embed or have some “hidden secret code” somewhere in the shellcode or payload in Unicode format so the other team can reveal it when analyzing your pdf file. The secret code can be as simple as a string such as “secret code is: 123ABC”.

A quick tutorial on using Metasploit (Metasploit2) for creating a malicious pdf file with util.printf() vulnerability (buffer overflow) (CVE-2008-2992) is given below:

https://www.youtube.com/watch?v=8HH_Va4-iEs 

Note that, your created malicious pdf file does not need to be of util.printf() vulnerability. It can be of any vulnerability supported by Metasploit. 

Deliverable: A malicious PDF file and a separate documentation file explaining how you created the pdf file along with some snapshots and also the secret code you have embedded into the shellcode. You may need to zip the pdf file and create a password for unzipping it (share the password in your documentation) so the browsers cannot open it up and thus cannot detect it as malicious when uploaded to the BB or shared through the Internet browsers. 

Due Date for Stage 1: September 28 Midnight – Submission through the Blackboard System


Stage 2. 

Your job is to investigate the content of a given malicious pdf file. Using the PDF analyzing tools offered by the REMnux tool, spider monkey, sctest, or PDF Stream Dumper, address the following questions/activities:
1.	Report the number of objects in the file.
2.	Determine whether the file is compressed or not.
3.	Determine whether the file is obfuscated or not.
4.	Find and Extract JavaScript.
5.	De-obfuscate JavaScript.
6.	Extract the shell code.
7.	Create a shell code executable
8.	Analyze shell code and determine what is does or even execute it using sctest or spider monkey.
9.	What is the secret code?
For a quick tutorial on using the PDF analyzer tools offered by REMnus, you may review the following link:
https://countuponsecurity.com/2014/09/22/malicious-documents-pdf-analysis-in-5-steps/
For a quick tutorial on using PDF Stream Dumper, you may review the following link:
http://www.securitytube.net/video/2602 
Submit a report addressing the above 9 questions and step-by-step on how you have done the process and which tools are used and how. 
Deliverable: A document showing your analysis of the pdf file along with some snapshots and steps taken and revealing secret code in the end. 
Due Date for Stage 2: October 10 Midnight – Submission through the Blackboard System


