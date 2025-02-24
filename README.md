# Requirements

11 Points of SRS 

Purpose Statement (i.e., the purpose of the SRS and its intended audience) - The purpose of the SRS is to state all requirements of the proposed system once discovered. This SRS contains details regarding the functional and non-functional requirements of the project in a technical nature. In this SRS, we detail key components and requirements for the Auto Scheduler, including its overview vocabulary, constraints, and assumptions. 

Overview (i.e., the contents of the SRS and how they are organized) - This SRS has many parts to it. Namely, our features will be listed out and organized through multiple metrics. Key metrics include functional vs non-functional, priority, constraints, and stability. The SRS will go into detail on the perspective of the project, defined terms and references, end-user characteristics, constraints, standards, and assumptions. 

Product Perspective (i.e., a description of how the proposed system relates to existing organizational systems) - Currently, there are multiple helpful systems in place which we will draw inspiration from. Of course, Canvas is a necessary tool/system in this project – we intend to use the API from Canvas to obtain data on a student’s assignments. Also, there are scheduling apps in place that we can look to for an understanding of current scheduling systems; however, our unique project uses Canvas and our own scheduling system to implement students’ assignments into their schedules. 

List of Functional Requirements (i.e., what the software system must do) -  

Manage events throughout the week 

Support a schedule system for user to input current schedule 

Send reminders for whenever events start 

Automatically schedule upcoming Canvas Assignments into user schedule  

List of Non-Functional Requirements (i.e., qualities the system must possess) -  

Clean UI 

Usability 

Good Performance 

Scalability 

Customizability  

Interoperability 

List of Defined Terms (i.e., words and phrases, acronyms, and abbreviations) -  

Auto Scheduler – Application  

Canvas API – A RestAPI connection to Canvas, a web application that students use mandatorily by the University for class modules.  

List of References (i.e., referenced in the SRS and their sources) - The documentation for the Canvas API can be found here: https://canvas.instructure.com/doc/api/ 

List of End-User Characteristics (e.g., educational level, experience, technical expertise) - End users will primarily be USF Students but will eventually expand to all college students who use Canvas. As such, the education level is at a college level.  A user that is enlisted into a university will frequently use technology and application that is at the technical level as our application. 

List of Constraints (i.e., operational and/or technical constraints) - This project must be able to run on Android and/or IOS, as we intend to have a mobile application. To meet class requirements, we likely also need to implement Ruby for some processes. Also, the current version of Canvas must be supported by any software used. 

List of Standards (e.g., programming languages used, coding standards applied) - We plan to use Ruby on Rails to implement the server-side logic aka. backend and React Native for the user handling side aka frontend. 

List of Assumptions (e.g., hardware/software platform targeted) - Our group makes the assumption that most users will have Android or IOS mobile devices; thus, these are the targeted platforms. 
