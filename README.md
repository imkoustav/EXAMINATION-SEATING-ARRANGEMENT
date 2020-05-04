# EXAMINATION-SEATING-ARRANGEMENT
1. Introduction 

1.1 Purpose  
The product “Examination Seating Arrangement” is designed to assign seats for examinations to school/university students. The entirety of the software is described in this concise SRS, covering the entire basis of this project from end-to-end. This is the final release of the project and no further iteration is to be developed. 
1.2 Document Conventions 
No specific conventions are to be followed. 
1.3 Intended Audience and Reading Suggestions 
This SRS is directed towards developers and customers as it contains documentation which can qualify as intended for general reading as well as delving into technical details. 
1.4 Project Scope 
The software “Examination Seating Arrangement” is made for accommodating students in examination halls effectively. Instead of manually arranging seats for examinations, the software can provide an overview of how the seating should be made on the basis of room count and student information and examination list. 
1.5 References 
https://www.geeksforgeeks.org/friend-class-function-cpp/ 
https://www.tutorialspoint.com/cplusplus/cpp_files_streams.htm 
 
 
 
 
 
 
2. Overall Description 
2.1 Product Perspective 
It is a self-contained new product, without the basis, or the inclusion of any other software product. It is the first and final iteration of the project. 
2.2 Product Features 
Product features include addition of student examination information, along with course name and subject code to accordingly manage and seat the students in a particular order. It takes in number of rooms and calculates how the arrangements should be done.  
2.3 User Classes and Characteristics 
This product is only meant to be used by the school/university management authority who has the permission to use this product to seat the students based on their examinations and the number of rooms available on the particular dates. 
2.4 Operating Environment 
The software will operate in any environment that has the GCC compiler installed. Otherwise, we also pack in an executable that can run in any Windows environment.  
2.5 Design and Implementation Constraints 
Since there is no inoperability, there might be some conflict if two instances of the program are running from the same directory at the same time as they try to overwrite the input/output files together. 
2.6 User Documentation 
For customizing the product according to your needs, you can refer to online materials for changing the code according to your policy standards. There will be no other user documentation provided. 
 
 
 
 
 
 
 
 
 
 
 
 
3. System Features 
3.1 ‘Student’ class 
	3.1.1 	Description and Priority 
	 	This is of utmost priority as it provides the description of the student info entered. 
	3.1.2 	Stimulus/Response Sequences 
 	The student class is called upon when the seating arrangement is made on the basis of course and subject. 
	3.1.3 	Functional Requirements 
	 	To execute most test cases, no external functional requirement is present. 
 	 
	REQ-1: 	Registration number 
	REQ-2: 	Program name 
	REQ-3: 	Course Code 
3.2 ‘Sitting-Arrangement’ function 
	3.1.1 	Description and Priority 
	 	This is of utmost priority as it calculates the sitting arrangements. 
	3.1.2 	Stimulus/Response Sequences 
 The Sitting_Arrangement() function is called upon when it is required to make the arrangements based on the ‘Student’ class information entered. 
	3.1.3 	Functional Requirements 
	 	To execute most test cases, only ‘Student’ class information is required. 
3.3 ‘Format-Of-Sitting-Arrangement’ function 
	3.1.1 	Description and Priority 
	 	This is used to display the sitting arrangement. 
	3.1.2 	Stimulus/Response Sequences 
 	The Formate_of_Sitting_Arrangement() function is called upon when it is required to make a visual representation of the seating arrangements, according to the number of rooms present and the date of examinations and the number of dates of the examinations. 
	3.1.3 	Functional Requirements 
 	To execute most test cases, only the valid information from the ‘Sitting-Arrangement’ function and ‘Student’ class is required. 
 	 
4. External Interface Requirements 
4.1 User Interfaces 
The user interface is a simple command-line based program. 
 
Following are the functionalities available to the user: 
 
•	Add Student Data 
 
•	Display All Saved Data 
 
•	Automatic Sitting Arrangement 
 
•	Format Of Sitting Arrangement ( How It Looks Like ) 
 
•	Delete All Saved Data 
 
•	Restore Status 
4.2 Hardware Interfaces 
The system must allow compatible hardware devices (c++ compiler enabled) to use the system. The system also needs to allow the storage of files in the directory used by the software. 
4.3 Software Interfaces 
The only software interface this program uses is the directory system provided by the operating system as it needs to store/delete files in/from the system. 
 
 
 
 
 
 
 
 
 
 
 
 
5. Other Nonfunctional Requirements 
5.1 Performance Requirements 
Even an old computer from the 90s will be able to run this product, it is very light-weight and super optimized for big size test cases. The chances of failure are next to none, and the performance requirement is a simple processor with a minimum clock frequency to run your operating system itself is more than good enough. 
5.2 Safety Requirements 
Check if your computer is heating up due to the room temperature because our software isn’t heavy enough to produce anything to be precarious about. 
5.3 Security Requirements 
On the basis of security, there isn’t much of it since it is supposed to be used in an offline basis. A simple user login with a hardcoded password just so that no-one else can access it directly on your computer. 
5.4 Software Quality Attributes 
Quality characteristics may include: 
 
1.	Adaptability: Since it works fine on seating arrangement for examinations, it can also be reused as an asset for developing other seating arrangement programs, be it flight arrangements or concerts 
2.	Availability: Since we pack this product as an executable, it is readily available to any Windows user that wants to use this product. 
3.	Correctness: Our product has passed a decent number of successful test cases, so it works in most situations. 
4.	Flexibility: It is very flexible, since we take a lot of factors into consideration such as course no. and subject as well. 
5.	Portability: Highly portable, as it is packed as a single executable file. 
6.	Usability: Very easy to use, super light-weight and heavily customer-friendly. 
6. Other Requirements 
N/A 
Appendix A: Glossary 
N/A 
Appendix B: Analysis Models 

  
 
 

