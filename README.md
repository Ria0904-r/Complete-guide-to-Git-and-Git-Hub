# Complete-guide-to-Git-and-Git-Hub
Guide to Git and Git-Hub 


1)	Version Control
It is the practice of tracking and managing changes to software code.
It is known as Source Control. Version control systems are a category of software tools that helps in recording changes made to files by keeping a track of modifications done to the code. 

Benefits of the version control system:
a) Enhances the project development speed by providing efficient collaboration,
b) Leverages the productivity, expedite product delivery, and skills of the employees through better communication and assistance,
c) Reduce possibilities of errors and conflicts meanwhile project development through traceability to every small change,
d) Employees or contributor of the project can contribute from anywhere irrespective of the different geographical locations through this VCS,
e) For each different contributor of the project a different working copy is maintained and not merged to the main file unless the working copy is validated. A most popular example is Git, Helix core, Microsoft TFS,
f) Helps in recovery in case of any disaster or contingent situation,
g) Informs us about Who, What, When, Why changes have been made.

2)Types of Version Control Systems: 
 
•	Local Version Control Systems
•	Centralized Version Control Systems
•	Distributed Version Control Systems

a)Local Version Control Systems: It is one of the simplest forms and has a database that kept all the changes to files under revision control. RCS is one of the most common VCS tools. It keeps patch sets (differences between files) in a special format on disk. By adding up all the patches it can then re-create what any file looked like at any point in time. 

b)Centralized Version Control Systems: Centralized version control systems contain just one repository and each user gets their own working copy. You need to commit to reflecting your changes in the repository. It is possible for others to see your changes by updating. 
Two things are required to make your changes visible to others which are: 
 •You commit
 •They update
 
 c)Distributed Version Control Systems: Distributed version control systems contain multiple repositories. Each user has their own repository and working copy. Just committing     your changes will not give others access to your changes. This is because commit will reflect those changes in your local repository and you need to push them in order to make   them visible on the central repository. Similarly, When you update, you do not get other’s changes unless you have first pulled those changes into your repository. 
 To make your changes visible to others, 4 things are required: 
 
•	You commit
•	You push
•	They pull
•	They update
The most popular distributed version control systems are Git, Mercurial. They help us overcome the problem of single point of failure. 





