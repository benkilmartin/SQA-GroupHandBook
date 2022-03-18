# **Task Estimation in Scrum**
Task Estimation refers to measuring the effort, time, and cost associated with a project. In project management, estimating the project's scope is the most important step. No matter how big or small the project is, estimating it well can ease execution throughout the project execution cycle. Most of the time the success or failure of a project depends on the estimate. It's often challenging for software developers to estimate projects since it's frequently done with incomplete information or incorrect information. Below are some common challenges associated with project estimation.

## Challenges 

**1. Poor design**

Even when the best efforts are made, a poor design is the root cause of failure. People create a tight design based on a requirements document, which they misinterpret as being frozen. Moreover, they do not take the time to make the design scalable. Poor design causes unnecessary tweaking of code and heavy maintenance that can push schedules to the limit. 

**2. Not factoring the dependencies right**

In many projects, a decision point or external dependency is overlooked, which causes the project to suffer. A clear understanding of mandatory, discretionary, and external dependencies can help you plan the schedule efficiently. 

**3. How much buffer is the right amount?**

The correct buffer to pad an estimate is a common issue for Project Managers. Although 20% padding is usually done, the best figure is determined by the skillsets of the team and the complexity of the project. 

**4. The risk of analogous estimation**

An estimate for a project is typically made using an expert's judgement or based on experience. Picking an analogy and mapping the estimate might sound intuitive, but it is often risky due to the unique characteristics and dependencies in every project, the people involved, and their skillset, various tools and technologies adopted, and the infrastructure and resources made available. 

**5. Estimation Person**

When estimation is not done by the developer or in cooperation with the developer, it can result in huge disparities between the estimate and the actual result. 

**6. Software requirements are not set in stone**

Customers expect a product that is constantly changing in an ever-changing landscape. Furthermore, they are also subject to information overload, and sometimes they don't know what they want to do. Additional feature requests can arrive at any time and affect your current development plans.

<p align="center">
  <img src="https://www.commitstrip.com/wp-content/uploads/2020/10/Strip-Daily-meeting-650-finalenglish.jpg"
        alt="Markdown Monster icon" width="350"/>
</p>

It is evident that there are many difficulties when it comes to task estimation. However, the estimation process can be reliable if certain basic principles are followed: 

## Solutions 

**1. Use Past Knowledge**

Look for input from people who have done similar work before, but only use the information as a guide. Every project is different when thinking about technology, integration points, and priorities. Use the information from past estimates to see what has changed and how it affects this attempt. 

**2. Allow for the Unknown “Unknowns”** 

Prepare a buffer that allows for unexpected activities and things that you may miss in your estimates (such as bug fixes or having your lead developer leave the company). Then, refine the buffer as the project goes along. 

**3. Asking questions to clarify requirements** ­ 

Project Managers should ask as many questions as they can to gain a deeper understanding of the project requirements. More clarity will always lead to better estimations. 

**4. Tasks Splitting** 

The PM/Developer should split the task into small, last mile sub-tasks, which will enable much better estimation of effort. This can be done by creating WBS, work breakdown structure, which lists all the sub-tasks and their efforts in detail.  

**5. Estimation** 

A time estimate should always be determined by the developer or in close cooperation with a developer by defining each milestone of the project. A PM will use their experience in the estimation process. Estimation should be done in range of time frame rather than a timeline. 

**6. Don’t forget about quality** 

It takes time to create high-quality software. If you stick to delivering your product quickly without considering the non-functional elements, you will suffer. Be sure to include design, development, and testing time in your estimates. 

It is apparent that despite the many challenges of accurately estimating tasks the above recommended solutions will greatly assist Project Managers in better software development project estimation. 


# **Coding Standards**

When working in a group, it's critical to establish conventions and guidelines for how your code should be written. This might range from simple naming conventions to reworking to ensure that everything functions properly. It might be difficult for new and existing team members to comprehend the codebase without a consistent manner of coding, which can lengthen the development life cycle of a software. In many real-world settings, teams are working on older, pre-existing software that was developed by a different group. It will be easier for everyone if there are high-quality coding standards in place.

<p align="center">
  <img src="https://www.commitstrip.com/wp-content/uploads/2021/11/Strip-Pas-de-documentation-650-finalenglish.jpg"
        alt="Markdown Monster icon" width="350"/>
</p>

## Good Coding Standards:
- A coding standard gives a uniform appearance to the codes written by different engineers.
- It improves readability, and maintainability of the code and it reduces complexity also.
- It helps in code reuse and helps to detect error easily.
- It promotes sound programming practices and increases efficiency of the programmers.

## Naming Conventions: 
It's very important to give meaningful names to variables, functions, packages etc. so they are easily undertandable. It's up to the developer what to use but in general...
- CamelCase should be used for local variables e.g firstName. So the first lettter of each word is a capital apart from the first.
- Constants should have all capital letters e.g CONSDATA
- Global variables should start with a capital letter e.g GlobalVariable.
- Avoid using digits in variable names.
- Functions should be written in CamelCase and should describe what it is doing.
- File names should use CamelCase.

## Indentation:
Proper indentation is very important to increase the readability of the code. For making the code readable, programmers should use White spaces properly. Some of the spacing conventions are given below:
- There must be a space after giving a comma between two function arguments.
- Each nested block should be properly indented and spaced.
- Proper Indentation should be there at the beginning and at the end of each block in the program.
- All braces should start from a new line and the code following the end of braces also start from a new line.

## Comments: 
- Adding comments helps other developers to understand your code
- When writing a complex function add a short comment at the beginning to briefly explain it
- At the top of each file or class specify its role and contents
- Avoid unnecessary comments that explain lines of code that are obvious
- Keep comments clear and tidy

## Error Handling & Testing:
- When throwing an exception make sure to properly handle the error and give an informative message
- All functions that are encountering an error condition should either return a 0 or 1 for simplifying the debugging
- Unit tests need to be written for all functions so any changes down that road can be done with peace of mind
- Unit testing saves time and also reduces code complexity

# **What are Code Reviews?**

A code review consists of one member of a group checking over another group members code, the aim of a peer to peer code review is to identify mistakes, catch early bugs or areas for improvement in terms of code efficiency. The implementation of code reviews into a teams standard practices is one of the cheapest ways to reduce bugs at early stages, it is a crucial part of software quality assurance and provides a wide range of benefits within the development lifecycle.   


## **Why should we implement code reviews?**

• The quality of the code improves and as a result efficient collaboration is easier to achieve.

• Helps to identify bugs and inefficiencies at early development stages which saves time and money in the long term

• Adds a level of consistency in the design and implementation of the code 

• Knowledge is shared between the developers who are writing and reviewing the code which helps the developers build their skill set. 

• Code reviews help to spread the ownership of the code, it is easy for a team member to continuously be assigned the same kind of task because "it's what they're good at". By implementing code reviews all team members become comfortable with all aspects of the development lifecycle.


## **Code Review Techniques** 

There are various code review techniques that should be adapted by a team when implementing a code review, however I have listed some techniques that I believe are easy to achieve and will do a great deal of good. 

• When reviewing source code split it into sections of no more than 400 lines at a time 

<p align="center">
  <img src="https://static1.smartbear.co/smartbear/media/images/product/collaborator/code-review-best-practices-figure-01.gif"
        alt="Markdown Monster icon" width="350"/>
</p>
    
1.  A SmartBear study of a Cisco Systems programming team revealed that developers should review no more than 200 to 400 lines of code (LOC) at a time. The brain can only effectively process so much information at a time; beyond 400 LOC, the ability to find defects diminishes.

• Ensure that you spend no longer than 60 minutes reviewing each section of code

<p align="center">
  <img src="https://static1.smartbear.co/smartbear/media/images/product/collaborator/code-review-best-practices-figure-02.gif"
        alt="Markdown Monster icon" width="350"/>
</p>

1.  While it may be tempting to tear through a review, assuming that someone else will catch the errors that you don´t find. However, SmartBear research shows a significant drop in defect density at rates faster than 500 LOC per hour. 

## **Set objectives and principles** 

Prior to executing a code review, it is critical to choose significant measurements and to characterize specific objectives. The Objectives include acceptable coding standards in the organisation. Having set norms ensures that every product item created and reviewed in the organization satisfies the companies standards.

When reviewing code considering certain questions can help to focus on the right things. For example, they may assess the code to answer:

1. Do I understand what the code does?

2. Does the code work as I anticipate that it should?

3. Does this code satisfy administrative prerequisites?

 ## **How you should structure code review comments**

It's important to be courteous and respectful when adding comments to a code review while also being helpful to the developer who's code you are reviewing. Always make sure that you are making comments on the code rather than on the developer themselves. Below are examples of a bad and good comment.  

1. Bad: “Why did you use threads here when there’s obviously no benefit to be gained from concurrency?”

2. Good: “The concurrency model here is adding complexity to the system without any actual performance benefit that I can see. Because there’s no performance benefit, it’s best for this code to be single-threaded instead of using multiple threads.” 

You should make sure to explain WHY you are suggesting any changes, this gives a bit more explanation about your intent, the practice that you are following and how your suggestion improved the quality of the code

You should also make sure to give guidance to the developer who's code you are reviewing. In general it is not the reviewers responsibility to make changes to the code but to show the developer who wrote the code where the changes should be made. This is why it is extremely important to leave a detailed identification of the problem, from there you can either let them decide on a fix or else suggest a solution yourself.  

<p align="center">
  <img src="https://www.commitstrip.com/wp-content/uploads/2021/04/Strip-Les-erreurs-qui-en-cachent-dautres-650-finalenglish.jpg"
        alt="Markdown Monster icon" width="350"/>
</p>


**Coding Standards**  
1. https://www.browserstack.com/guide/coding-standards-best-practices#:~:text=Practices%20To%20Follow-,What%20are%20Coding%20Standards%3F,sophisticated%20and%20highly%20functional%20code.
2. https://www.geeksforgeeks.org/coding-standards-and-guidelines/
3. https://www.perforce.com/resources/qac/coding-standards
4. https://medium.com/@psengayire/the-importance-of-coding-standards-and-conventions-in-the-software-development-team-how-they-can-5d252556a05
5. https://www.parasoft.com/blog/an-ounce-of-prevention-software-safety-security-through-coding-standards/

**Code Review**
1. https://www.perforce.com/blog/qac/9-best-practices-for-code-review
2. https://www.swarmia.com/blog/a-complete-guide-to-code-reviews/?utm_term=how%20to%20perform%20a%20code%20review&utm_campaign=SRH-REVIEW-EU-EN&utm_source=adwords&utm_medium=ppc&hsa_acc=6644081770&hsa_cam=16463390785&hsa_grp=134848023275&hsa_ad=585675515692&hsa_src=g&hsa_tgt=kwd-1637776691909&hsa_kw=how%20to%20perform%20a%20code%20review&hsa_mt=b&hsa_net=adwords&hsa_ver=3&gclid=Cj0KCQjwuMuRBhCJARIsAHXdnqP3K87qPPp6A5CLEzEWOGyGpJ9DDLheV191rgnVrV1A02eiAG0cgrIaAmyEEALw_wcB
3. https://smartbear.com/learn/code-review/best-practices-for-peer-code-review/ 
4. https://google.github.io/eng-practices/review/reviewer/comments.html
5. https://www.atlassian.com/agile/software-development/code-reviews

**Task Estimation**
1. https://www.edupristine.com/blog/project-estimation-challenges
2. https://www.macadamian.com/learn/12-secrets-to-overcoming-software-estimation-challenges/
3. https://www.aapnainfotech.com/software-development-project-estimation-problems-solutions/
4. https://www.cyclopt.com/blog/software-estimates-part-1-the-problem-with-software-effort-estimation/
5. https://www.cyclopt.com/blog/software-estimates-part-2-three-dos-and-three-donts-about-estimates


