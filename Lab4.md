# Software engineering lab 4: modelling software requirements

## A. Get familiar with software requirements specification (SRS) documentation

**1. Find existing requirements documentation** e.g. by querying
 * requirements specification
 * requirements specification example pdf
 * srs pdf
 * or [here](https://gist.github.com/OAlm/f1d18c17687ba28d4b5b)

**2. Report the following things related to the document you found:**
 
**(Introduction)**
* What is the project?
the SplitPay system

* Overall description of the product (=what is it? can you understand it?)
The SplitPay system is composed of two main components: a client-side application which will
run on Android handsets, and a server-side application which will support and interact with
various client-side features. The system is designed to facilitate the process of tracking and
settling shared expenses. Potential scenarios include paying rent, splitting a check at dinner,
sharing travel expenses, etc.
Quite easy to understand, when potential scenarios are provided

* Target audience?
Describes for whom document is written, rather than the project potential users. Document is intended for all individuals participating in and/or supervising the SplitPay
project.

* The situation?
There are several applications “on the market” which are similar to proposed app (examples include
Bills Are In, Share a Bill, Split a Bill, Fair Share, and Xpense Split). A majority of these are web-based
applications with little or no mobile functionality. In addition, they all require users to set up an account
before they can utilize their services. The remaining apps we found were limited to the iOS platform,
leaving the Android market open. Furthermore, authors plan on adding some features which are not
currently available in any of these applications.(Appendix B)

* Motivation?
Document authors are designing an application that facilitates the process of paying off shared expenses. They want to make it easier to pay for things as a group. This is relevant in many different
situations, ranging from every day transactions (friends splitting the cost of dinner), to recurring
payments (roommates paying rent), to a more professional setting (a team of professionals making
business transactions). Depending on the number of people and/or the amount of money involved,
these situations can get very complicated.(Appendix B)

* Structure
1. Introduction [1.1 Purpose; 1.2 Document Conventions; 1.3 Intended Audience and Reading Suggestions; 1.4 Project Scope]
2. Overall Description [2.1 Product Perspective; 2.2 Product Features; 2.3 User Classes and Characteristics; 2.4 Operating Environment ; 2.5 Design and Implementation Constraints ; 2.6 User Documentation ; 2.7 Assumptions and Dependencies]
3. System Features [Core Features; Additional Features]
4. External Interface Requirements
5. Other Nonfunctional Requirements
6. Key Milestones
7. Key Resource Requirements
8. Other Requirements
9. Appendix A Glossary
10. Appendix B Project Proposal


* Compare the structure of the document with the template provided for the course group work. How does it differ? Is there more? Less? (check also the contents and structure of SRS provided in Wikipedia: 	http://en.wikipedia.org/wiki/Software_requirements_specification). 
Structure differs from both group work  and wikipedia templates.
Analysis of the differences from groupwork template: 
It is possible to find information about almost all groupwork structure elements, but they are ordered differently. For example project context is described in appendix B(as a project team already had Software Application Proposal, they just included it to document); Use cases are not presented as a separate part, potentional scenarios are described under USER CLASSES AND CHARACTERISTICS.
Ofcourse document did not include part for self reflection, it had KEY MILESTONES part, where dates important for project were marked.

*(Use cases)**
* What the system (will) do?
 The SplitPay project is meant to offer a shared expenses solution that is faster, easier, and more
convenient than manually calculating and handling debts.

* Use case diagram?
     when the application is installed and run for the very first time,the user is presented with an intial registration/welcome sceern. this sceern prompts the user to create an account on the spiltpay server using the email address associated with his/her google account. the user also enters a "display name"which will be the name that is shown as their handle within the groups.completing this process will create and store an account for the user on the splitpay server, enabling all of the application's synchronization capablities.
* How cases are described, how much details?
   the case is driscribed well detailed.
**(General structure of the system)**
* What chart techniques are used? Why?
  the general stucture focused on the functional and non functional part than using chart technique.
**(Functional & non-functional requirements)**
* Listed?
  functional and non functonal requirements are listed very well.
* Measurable/traceability? (is it possible to check from the upcoming end product if a feature / requirement is implemented or not?)
   yes      
**(How does (will) it look?)**
* UI examples / views?
     there is a good UI exmaples.
* Are the pictures mockups or screenshots from existing system?
  yes there is mockup picture. 
* Transitions between views
   it is not discribed in this documentation

**(Process model? [might not exist, some times in a separate document called ‘project plan’])**
* Allocation of resources / budget?
Budget is not described in the analysed document, in the part 7-KEY RESOURCE REQUIREMENTS, Major project activities, corresponding skill/expertise required, internal and external resources and possible issues/constraints are tabulated. 

* Risk Analysis?
does not include risk analysis part 

**(Your point of view)**
* Is it a good/bad document? Why?
not bad, describes features of the application in detail, for every feature showing user and system requirements, also provide impresion about user interface, does not focus much on use cases, providing use scenarios instead.  

* Consider also the quality of diagrams / illustrations
Document includes only a diagram of the SplitPay system and 8 USER INTERFACE illustrations.
Diagram of the SplitPay system is informative.
USER INTERFACE illustrations are very informative and clear.

* Do you think there would be enough information for you to build that system?
not really, the links between different features were not clear.


* Etc.

#### Return a link of your github repo to Tuubi. Don't forget to put a link to the document you analyzed. 
http://www.cise.ufl.edu/class/cen3031fa13/SRS_Example_1_2011.pdf

After the deadline, the tuubi assignment will be made public, so everyone could benefit from your analysis.

#### You will do a small (5min) group presentation for the class of your analysis.

## B. Start your project :)

The idea is to benefit from your (and/or other group) analysis:
* Do you get an idea how and what to write?
* At the content level, is there parts that you would simplify or go into more details?
* Do you think that you are able to list functional requirements? Non-functional requirements (and make them measurable)?
* What is the importance of the illustrations/diagrams/mock-ups?
* How much "technical" vocabulary should be?
* Etc.
