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


1.https://www.browserstack.com/guide/coding-standards-best-practices#:~:text=Practices%20To%20Follow-,What%20are%20Coding%20Standards%3F,sophisticated%20and%20highly%20functional%20code.

2.https://www.geeksforgeeks.org/coding-standards-and-guidelines/

3.https://www.perforce.com/resources/qac/coding-standards

4.https://medium.com/@psengayire/the-importance-of-coding-standards-and-conventions-in-the-software-development-team-how-they-can-5d252556a05

5.https://www.parasoft.com/blog/an-ounce-of-prevention-software-safety-security-through-coding-standards/
