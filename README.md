## Course Update
(December 2019) Several hands-on experiences were added on "Android Forensics" 

# Instructional Materials for the Digital Forensics Course
## Texas Tech University, Computer Science Department 
## Designed and Taught by: Dr. Akbar Namin
###### A course on "Digital Forensics" designed and offered in the Computer Science Department at Texas Tech University 2017 - 2018


This repository contains the instructional modules and course materials developed by [Dr. Akbar Namin](http://www.depts.ttu.edu/cs/faculty/akbar_siami-namin/index.php), Associate Professor of [Computer Science](http://www.depts.ttu.edu/cs/) at [Texas Tech University](http://www.ttu.edu/) to teach Digital Forensics. The materials were prepared, developed, taught during 2017 - 2018, and it is evolving. This course initiallay was developed as a graduate-level university course. But it can also be used for undergraduate students. The lecture notes were prepared by the insturctor of the course, the lab and hands-on experiences were developed by students taking the course.

## About the Course
Digital forensics has become a must-have skillset for IT professionals and in particular for security experts. Digital forensics and incident response play key roles in detecting and analyzing malware, security breaches, possible countermeasures, and tracing online criminal activities. Digital forensics, malware detection and analysis, and incident responses techniques are very wide and system-dependent. For instance, the techniques and tools used in detecting malware in Windows operating system are quite different than those used in Linux and Mac. Nevertheless, the security expert and more importantly ethical hackers need to be aware of the core and basic general topics and cocepts as well as platform-dependent techniques in order to be able to conduct penetration testing more effectively. 

This course introduces the basic concepts and techniques usually employed in digital forensics and malware analysis. The contents are primarily divided into four major topics: 

1. Reverse Engineering
2. Disk Forensics
3. Memory Forensics
4. Network Forensics

These four topics constitute the skeleton of security incidents and challenges. The security and forensics challenges usually exercised at the major hacking conferences such as DEFCON and Black Hat usually require in-depth knowledge of these four major topics when performed in different platforms. 

The course is completely practical supported with hands-on experiences and formal lectures. Students taking this course will be able to:
*	Demonstrate in-depth knowledge of cyber evidence and digital forensics
*	Perform disk, memory, and network digital forensics 
*	Demonstrate the knowledge of using forensics tools
*	Learn about the state-of-the-art in malware detection and analysis research 
*	Learn the basics of incident responses
*	Capture network, memory, and disk images for the purpose of forensics analysis

The tentative topics and tools to be covered include:

*	Setting up a minilab for conducting experiment and analysis of digital forensics and malware execution and analysis
*	Reverse engineering through binary analysis tools such as RootKit, REMnux, sctest, and Libemu
*	Live collection and acquisition
*	Disk and media analysis: Disk structure, file systems (NTFS, HFS, etc.)
*	Disk and media forensics using tools such as Sleuthkit, Autopsy, foremost, scalpel, etc.
*	Memory forensics using techniques such as the volatility framework, WinDBG,  
*	Network forensics using techniques and tools such as WireShark, NetworkMiner, etc.
*	Kali Linux
*	Metasploitable Framework and tool
*	OWASP-BWA (Broken Web Application)
*	Windows, Linux, and Mac operating systems forensics
*	Practicing digital forensics using real data

## Learning Outcomes
The following are the expected  learning  outcomes  of the course:
* Masters  of Science Degree:
1. Communicate effectively orally and in writing  (LO 1) 
2. Engage in life-long learning and self-critique  (LO 2)
3. Function independently on self-directed projects or research where appropriate (LO 4 )
* Doctor  of Philosophy  Degree:
1. Graduates are expected  to communicate effectively orally and in writing  (LO 1 ) 
2. Engage in life-long learning  and self-critique  (LO 2 ).
3. Function in a multi-disciplinary, and culturally diverse environment with cross-functional teams (LO 3)

## Textbooks

There are four sections, each would require a separate textbook. Here is the list of books used for each section:

1. Reverse Engineering
* Book: [Reversing Secrets of Reverse Engineering](http://www.foo.be/cours/dess-20122013/b/Eldad_Eilam-Reversing__Secrets_of_Reverse_Engineering-Wiley(2005).pdf) 
* Author: Eldad Eilam
* Published Year: 2005
* Publisher: Wiley

2. Disk Forensics
* Book: [Computer Forensics: Computer Forensics: Investigating Hard Disks, Files, and Operating Systems](https://news.asis.io/sites/default/files/Investigating_Hard_Disks_File__Operating_Systems.pdf) 
* Author: 
* Published Year: 2010
* Publisher: Cengage Learning

3. Memory Forensics
* Book: [The Art of Memory Forensics](https://news.asis.io/sites/default/files/The%20Art%20of%20Memory%20Forensics.pdf)
* Author: Michael Hale Ligh et al.
* Published: 2014
* Publisher: Wiley

4. Network Forensics
* Book: [Network Forensics: Tracking Hackers through Cyberspace](https://news.asis.io/sites/default/files/Network%20Forensics%202012.pdf)
* Author: Sherri Davidoff and Jonathan Ham
* Published: 2012
* Publisher: Prentice Hall

## Additional Hacking Textbooks

5. The Hacker Play Book 2: Practical Guide to Penetration Testing, Author: Peter Kim
6. Hacking: The Art of Exploitation, Author: Jon Erickson

## Additional References

[DigForPort](http://www.myweb.ttu.edu/asiamina/DigForPort/index.html) is a portal that lists useful materials and tutorials for teaching and learning digital forensics.

## Course Team-based Project

To stimulate learning, four team and **competition**-based projects are defined.  The four projects will allow students and each team practice the necessary skillsets for each section (i.e., reverse engineering, etc.). For each project, each team plays the role of both blue and red teams and thus is responsible to build an artifact with some secret item that will be discovered by the other team. 

For instance, in disk forensics, each team will create a disk dump file with some hidden secret recipes hiden in different sectors, and the other team's job is to discover the secret recipes. 

## Students Evaluation

Students will be graded based on assignments, exams, and the project (tentative).
*	Assignments (four individual assignments): 40%
*	Projects (four team-based projects): 40% 
*	Take Home Exams: 20%

## Acknowledgements
In preperation of this course including lecture notes, lab assignments, case studies, and hands-on experiences many graduate students involved. In particular, these graduate students contributed to the development of the course through donating their created artifacts:

* Kelsey Hilton (diamond contributor: contributed to 1) lab setup module, 2) case studies on WannaCry, 3) Some other case studies)
* Sara Sartoli (gold contributor: contributed to 1) Network Forensics lecture notes, 2) Create the [DigForPort](http://www.myweb.ttu.edu/asiamina/DigForPort/index.html) portal, 3) Some other case studies)
* Fethi Inan (gold membe: contributed to 1) Memory Forensics lecture notes and modules)
* Prerit Datta (silver contributor: contributed to 1) some other case studies, 2) Hands-on-Experience on Android Forensics)
* Moitrayee Chatterjee (silver contributor: contributed to 1) some other case studies, 2) Hands-on-Experience on Android Forensics)
* Sevgi Arca (silver contributor: contributed to 1) some other case studies)
* Justin Lugo (silver contributor: contributed to 1) some other case studies)
* Vinh Nguyen (silver contributor: contributed to 1) some other case studies)
* Niklas Gollenstede (silver contributor: contributed to 1) some other case studies)
* Gantaphon Chalumporn (silver contributor: contributed to 1) some other case studies)
* Shuva Dass (Contributor to 1) Hands-on-Experience on Android Forensics)
* Fulsy Theophitle (Contributor: Contributed to 1) Hands-on-Experience on Android Forensics)
* Santosh Shrestha (Contributor: Contributed to 1) Hands-on-Experience on Android Forensics)
* Anish Chhetri (Contributor: Contributed to 1) Android Forensics with Burp Suite)
* Shashank Shrestha (Contributor: Contributed to 1) Android Forensics with Burp Suite)
* Aashish Aman (Contributor: Contributed to 1) Android Forensics with Burp Suite)
* Rojina Shrestha (Contributor: Contributed to 1) Armitage)
* Sujan Roka (Contributor: Contributed to 1) Armitage)


## Special Thanks
* The National Science Foundation (NSF) to support and sponsor the project
* The CS Department for allowing offering this course for two consequtive years in order to prepare the materials. 



