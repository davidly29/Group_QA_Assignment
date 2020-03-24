# What is Code Review? 

What is code review? 

Code review is an activity part of the software quality assurance. This is where the source code is broken into small pieces an inspected by one or more team member(s) which is to be carried out just before testing. Code review is done in order to detect mistakes, catch early bugs and ensure that the code follows the standard practices. Implementing code reviews is one of the relatively cheapest ways to detect and reduce bugs at an early stage. 


## Objectives:

## How to perform code review:  

 **1. Formal Code Review:**  Inspections are thorough resulting in the best methods found to reduce defects. It is a collaboration of multiple team members who work in iterative phases to find the most effective way to present the code. Traditionally this will be done in meetings with the code being checked line by line, this is a very detailed process. 

 

 **2. Lightweight Code Review:**  Requires less effort that formal code review. Examples of this: 

  **_Over the Shoulder:_**  The process of a developer reviewing the code while the reviewee talks through the code and explaining it.  

  **_Pair Programming:_** Two developers code in the same workstation while constantly reviewing each other’s work. 

  **_Tool Assisted Review:_** The use of specialised tools allow easier testing and code reviewing. The reviewer uses these tools to review the code and comment as needed. 

## Benefits:

[Diagram created using canva.com](https://www.canva.com/search/templates?q=Cycle%20Diagram&category=tADWs0Cq50o&doctype=TACQ-lCLuV8&designSpec=djE6dEFEV3MwQ3E1MG86Z2xvYmFsLXByZXNlbnRhdGlvbg%3D%3D&width=1024&height=768)




**Self Code Review** |**Team Code Review**
------------ | -------------
  *Self-code review occurs during development. Self-code review is mandatory. It is essential to produce the highest quality code.* | *Team code review occurs once the developer is satisfied with their code. This is essential to enhance code quality and has be proven to have beneficial effects for team’s culture.*
To always follow guidelines and company policy of developing code. This will help maintain a level of consistency in design and implementation.| If a disagreement with the reviewer arises about a piece of your code have a short face to face discussion not through email. 
 Make sure naming conventions are accurate this helps for team code review in the future    | The reviewer must give constructive feedback. The reviewer should know what the code is supposed to do. 
Error checking must be strict. Make regular checks and check for errors often.     | Always remember the important thing is that feedback must be given.
In the event of an error create a descriptive log so during team review the reviewer will be able to understand rather than needing additional debugging. | The reviewee must always have good intentions.  The reviewee and the reviewer both want to deliver the highest quality code possible. Do not take any criticism about your code personally. 

## Best Practices

### Do's and Don'ts

- #### Know what you're looking for, Don’t make simple errors:  

    Create a checklist of things that’s important to look out for, such as the design, structure, readability, the complexity and functionality. Doing so eliminates simple errors and provides clarity to other team members for what is expected for each review type. Focus on items that need human intervention and which aren't highlighted during automated testing such as deign and functionality.  

-  #### Give feedback that is helpful not hurtful: 

    Be constructive not critical. Be considerate of the developer and offer valuable feedback in a respectful manner. Rather than making bold statements ask questions politely. Encouragement is essential, this should inspire them to improve and minimize mistakes in the future. Create a safe environment where reviewing code is seen as a learning process.  
 

- #### Include all team members, don’t isolate to yourself:  

    Regardless developer experience, all code must be reviewed. Developers will produce the highest quality work once they know their code is being review by a fellow team member. Including a software engineer and architect whilst reviewing helps different issues to be detected.  Including multiple people in the code review in turn improves collaboration and relationships between developers. 

- #### Use Code Review Tools, save time: 
  Using automatic tools instead of manually checking and writing down issues frees up time for reviewers allowing them to focus on issues that tools can't find.  Using tools for lightweight review is recommended. 
 

- #### Spend no longer than 60 Minutes Reviewing Code: 
  Short intervals are more beneficial as performance and attention-to-detail deteriorate after this. Working in these frequent intervals allow you think of new scenarios with a clear mind.  Reviewing little and often no more than 400 lines of code at a time results in the highest code. 
 

- #### Cultivating a Positive Culture;  not a blame game:  
  An environment that’s allow you to make mistakes and learn from them would find the error. There is no need to blame a developer for a bug everyone should be positive that bugs were found early. Help bring your team closer together and working in a positive environment. 
 



### Resources: 

https://www.lambdatest.com/blog/how-code-reviewing-can-help-with-quality-assurance/

https://dzone.com/articles/how-code-reviewing-can-help-with-quality-assurance 

https://simpleprogrammer.com/code-review-and-quality-assurance/ 






