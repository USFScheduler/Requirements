## **Purpose Statement**  
The purpose of the Software Requirements Specification is to state all requirements of the proposed system once discovered. This SRS contains details regarding the functional and non-functional requirements of the project in a technical nature. In this SRS, we detail key components and requirements for the Auto Scheduler, including its overview vocabulary, constraints, and assumptions.  

## **Overview**  
This SRS has many parts to it. Namely, our features will be listed out and organized through multiple metrics. Key metrics include functional vs non-functional, priority, constraints, and stability. The SRS will go into detail on the perspective of the project, defined terms and references, end-user characteristics, constraints, standards, and assumptions.  

## **Product Perspective**  
Currently, there are multiple helpful systems in place which we will draw inspiration from. Of course, Canvas is a necessary tool/system in this project – we intend to use the API from Canvas to obtain data on a student’s assignments. Also, there are scheduling apps in place that we can look to for an understanding of current scheduling systems; however, our unique project uses Canvas and our own scheduling system to implement students’ assignments into their schedules.  

## **List of Functional Requirements**  
- permit user to log in
- permit user to input their current schedule
- permit user to modify (add/change/delete) schedule events
- permit user to check off a completed task
- permit user to connect to Canvas
- Generate view of upcoming schedule
- Generate work times for upcoming tasks automatically
- Generate reminders to send to phone

## **List of Non-Functional Requirements**  
- Usability: the system shall be intuitive and easy to use for adding schedules
- Scalability: The system shall at first be available for select USF students, then able to scale to general Canvas users
- Security: Ensure canvas authentication with users
- Security: Schedule information shall be securely stored to protect confidentiality of users 

## **List of Defined Terms**  
- **SRS** - Software Requirements Specification  
- **UI** - User Interface  
- **Auto Scheduler** – Application  
- **Canvas API** – A RestAPI connection to Canvas, a web application that students use mandatorily by the University for class modules.  

## **List of References**  
The documentation for the Canvas API can be found here: [Canvas API Documentation](https://canvas.instructure.com/doc/api/)  
Our standard for Ruby coding and formatting is found here: [Ruby Style Guide](https://github.com/rubocop/ruby-style-guide)  

## **List of End-User Characteristics**  
End users will primarily be USF Students but will eventually expand to all college students who use Canvas. As such, the education level is at a college level. A user that is enlisted into a university will frequently use technology and applications that are at the technical level as our application.  

## **List of Constraints**  
This project must be able to run on Android and/or iOS, as we intend to have a mobile application. To meet class requirements, we likely also need to implement Ruby for some processes. Also, the current version of Canvas must be supported by any software used.  

## **List of Standards**  
We plan to use **Ruby on Rails** to implement the server-side logic (backend) and **React Native** for the user handling side (frontend).  

## **List of Assumptions**  
Our group makes the assumption that most users will have Android or iOS mobile devices; thus, these are the targeted platforms.  
