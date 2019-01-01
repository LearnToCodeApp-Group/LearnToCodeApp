How to Contribute
*****************

h2 -- How the work will be divided

h3 -- The project overall

The project will comprise of one core application - a primary module - which can be supplemented by additional apps.

The Core App should work independently of any additional modules. The additional modules will add functionality and should work independently of all other apps except the Core App.

The additional modules may duplicate functionality or achieve the same functionality in a different way. For example:

+ A module which retrieves information from an outside source may be duplicated by another module which obtains the same information from a different source. Users should be able to choose one or other of the modules, depending on their preference and needs.

+ A module may be written to achieve a function in Windows. The module may be 'forked' to do the same thing on a Gnu/Linux distribution.

Initially, we will focus on the Core App. Eventually, we hope contributors will be able to work on separate, compatible apps. When we are at that stage, we will decide whether those apps need their separate repository or can be integrated into the main one.

h3 -- The Core App

Development of the Core App will be divided into the following "work streams":

**Markup**: This will focus on creating the HTML and CSS for the user interface.

**Javascript**: This will focus on adding any functionality to the user interface which is strictly not possible using HTML and CSS.

**Django / Database**: This will focus on two things:

+ The Django models required to create the database.
+ The structural and administrative elements of the Django framework.

**Python3**: This will focus on server-side scripts and Python functionality.

**Documentation**: This will focus on keeping the documentation up-to-date and easy to understand.

**Security**: This will look at every area of the application to try to improve its security.

The Core App will have two main branches: *Master* and *Development*. Pull Requests should be made to the Development branch. Only once the admins are sure the development branch is in a stable state will the Development branch be merged into the Master branch - this will happen periodically.

h2 -- How to claim tasks and contribute code

**How to claim tasks**

The people leading the work streams will agree with the admins the specification for their stream. They will then divide up the work and submit an 'Issue' on Github.

Issues will be added to the Projects page for that work stream. Each work stream will have the following columns:

+ "Beginner's Tasks"
+ "Intermediate Tasks"
+ "Claimed Tasks"
+ "Completed Tasks/Please Test".
+ "Approved/closed tasks".

If you would like to contribute to the project, please check the work streams for tasks you wish to tackle. Once you have chosen, please move the task to the "claimed" column. Please only claim tasks if you believe you have a reasonable chance of completing them within a week. It does not matter if it takes a little bit longer but, in fairness to other collaborators, you should not "reserve" a task that you like the look of.

If there are no tasks you think are suitable, please consider doing one of the following:

+ Check the "Beginner's Tasks" or "Intermediate Tasks" pages of the documentation. We will aim to give examples of things you can do to get a feel for the project.
+ Review and comment on pull requests or Issues. Pull requests should relate to an Issue that has been raised. You can check the specification for the Issue and compare it to the Pull Request. Pull Requests relating to your preferred work stream will be listed in the "Please Test" column. Please refer to the "How to Review a Pull Request" page.
+ Review/test existing code. This is an educational project so it is unlikely that all code will be perfect. In addition, the comments in the code may not be complete and/or may be unclear. You can suggest changes to existing code or the comments by submitting an Issue. 
+ Suggest functionality. If you have experience of working in a firm and/or using similar software, you might be able to suggest functionality, either for the Core App or for a new module. This should be done by submitting an Issue.


**How to contribute code**

Once you have claimed a task, please follow this workflow:

1. *Create a branch of the development branch*. If submitted by an admin, the Issue should have a brief title. Please use this title as the name of the branch, so others can easily find it.

2. *Clone the branch*. You will need to clone the branch to your own machine in order to work on it.

3. *Write the code*.

4. *Test*. Please do your best to test that the code works. We will try to prepare guides about how to do this but in the meantime, you should be able to find information online. You will, for example, want to test markup using more than one brower and may need to test it using older versions of those browers.

5. *Commit*. Commit the code to your branch.

6. *Create a pull request*. Create a request to merge the changes into the *development* branch. Please then remember to move the 

7. *Deal with any comments on the pull request*. Once you have submitted the Pull Request, you should check to see whether it receives any comments or change requests. Pull Requests will not be merged into the code until these are responded to or dealt with.

8. *Close the branch*. Your task-specific branch should only last as long as it takes to deal with the task.
