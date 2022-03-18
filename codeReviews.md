What are code reviews?

A code review consists of one member of a group checking over another group members code, the aim of a peer to peer code review is to identify mistakes, catch eary bugs or areas for improvement in terms of code efficiency. The implementation of code reviews into a teams standard practices is one of the cheapest ways to reduct bugs at early stages, it is a crusial part of software quality assurance and provides a wide range of benefits within the development lifecycle.   


Why should we implement code reviews?

• The quality of the code improves and as a result efficient collaboration is easier to acheive.

• Helps to identify bugs and inefficiencies at early development stages which saves time and money in the long term

• Adds a level of consistency in the design and implementation of the code 

• Knowledge is shared between the developers who are writing and reviewing the code which helps the developers build their skill set. 

• Code reviews help to spread the ownership of the code, it is easy for a team member to continously be assigned the same kind of task because "it's what they're good at". By implementing code reviews all team members become comfortable with all aspects of the development lifecycle. 


Code Review Techniques 

There are various code review techniqies that should be adapted by a team when implementing a code review, however I have listed 3 that I believe are easy to acheieve and will do a great deal of good. 

• When reviewing source code split it into sections of no more than 400 lines at a time 
    
1.  A SmartBear study of a Cisco Systems programming team revealed that developers should review no more than 200 to 400 lines of code (LOC) at a time. The brain can only effectively process so much information at a time; beyond 400 LOC, the ability to find defects diminishes.

• Ensure that you spend no longer than 60 minutes reviewing each section of code

1.  While it may be tempting to tear through a review, assuming that someone else will catch the errors that you don´t find. However, SmartBear research shows a significant drop in defect density at rates faster than 500 LOC per hour. 

• Set objectives and principles 

Prior to executing a code review, it is critical to choose significant measurements and to characterize specific objectives. The Objectives include acceptable coding standards in the organisation. Having set norms ensures that every product item created and reviewed in the organization satisfies the companies standards.

When reviewing code considering certain questions can help to focus on the right things. For example, they may assess the code to answer:

1. Do I understand what the code does?

2. Does the code work as I anticipate that it should?

3. Does this code satisfy administrative prerequisites?

• How you should structure code review comments 

It is important to be curteous and respectful when adding comments to a code review while also being helpful to the developer who's code you are reviewing. Always make sure that you are making comments on the code rather than on the developer themselves. Below are examples of a bad and good comment. 

1. Bad: “Why did you use threads here when there’s obviously no benefit to be gained from concurrency?”

2. Good: “The concurrency model here is adding complexity to the system without any actual performance benefit that I can see. Because there’s no performance benefit, it’s best for this code to be single-threaded instead of using multiple threads.”

You should make sure to explain WHY you are duggesting any changes, this gives a bit more explanation about your intent, the practice that you are following and how your suggestion improved the quality of the code

You should also make sure to give guidance to the developer who's code you are reviewing. In general it is not the reviewers responsibility to make changes to the code but to show the developer who wrote the code where the changes should be made. This is why it is extremely important to leave a detailed identification of the problem, from there you can either let them decide ona  fix or else suggest a solition yourself. 



Code Review Links 

1. https://www.perforce.com/blog/qac/9-best-practices-for-code-review
2. https://www.swarmia.com/blog/a-complete-guide-to-code-reviews/?utm_term=how%20to%20perform%20a%20code%20review&utm_campaign=SRH-REVIEW-EU-EN&utm_source=adwords&utm_medium=ppc&hsa_acc=6644081770&hsa_cam=16463390785&hsa_grp=134848023275&hsa_ad=585675515692&hsa_src=g&hsa_tgt=kwd-1637776691909&hsa_kw=how%20to%20perform%20a%20code%20review&hsa_mt=b&hsa_net=adwords&hsa_ver=3&gclid=Cj0KCQjwuMuRBhCJARIsAHXdnqP3K87qPPp6A5CLEzEWOGyGpJ9DDLheV191rgnVrV1A02eiAG0cgrIaAmyEEALw_wcB
3. https://smartbear.com/learn/code-review/best-practices-for-peer-code-review/ 
4. https://google.github.io/eng-practices/review/reviewer/comments.html