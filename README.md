# ask_your_seniors

This repository would be used for testing whether you have properly learnt to submit an assignment.

Do the following works step by step to submit this test assignment. Best of luck.

1. It is better to keep all of your assignments in one folder. So, create a folder where you would keep your assignments. The folder name could be anything of your choice.

2. I hope you have installed the correct version of *git* in your pc. If you did not do it already, [click here](https://git-scm.com/downloads) and install the *git*.

If you have installed git properly in your computer, then Go the folder you have just created in step one and right click on the blank place of your folder (in explorer). If you have installed *git* properly, then you would see two options: (1) **Git GUI here** and (2) **Git Bash Here**. Click on **Git Bash Here**. (See the image below for clear understanding)

  ![](https://github.com/enamcse/Test-Assignment/blob/master/cmdOpen.png)

3. A cmd or terminal would be popped up. Let first introduce yourself to the git so that it could recognize you. Provide your Name and Email Address(by which you have created GitHub account). I recommend not to do it in any public computer, because you would be signing it by this, but signing out from git is a little bit difficult. Read [this](https://stackoverflow.com/questions/38549834/how-do-i-sign-out-in-the-git-bash-console-in-windows) if you need to sign out in case of emergency.

       git config user.name "First Last"
       git config --global user.email "example@mail.com"

where, *First Last* is your name and *example@mail.com* is your email address.

4. Now, go to the assignment repository and copy the link. (Not from address bar, it is from the Green Button in the repository). However, to clone it in your PC, just write the following commands in the opened cmd.

       git clone https://github.com/enamcse/Test-Assignment.git

where, *Test-Assignment* is the repository name of your assignment.

5. Now, after some automated processing, you would see a subfolder, in your assignment folder, named after the repository of your assignment.

6. Enter the assignment folder just double clicking on it. There are several files in it. So, do not care about other files, you have to work with only the file named *FactorialWithRecursion.cpp*. So, open it, modify it as your own and don't touch other files. All the instructions are given in this file as documentation.

7. It is time to back to the cmd. If you have closed the cmd, do not worry, just follow the step 2. now, enter into the assignment folder in cmd by writing the following:

        cd Test-Assignment

where, *Test-Assignment* is the repository name of your assignment.

8. Write the following commands:
   * Add All the changes in the folder by the following command:

         git add .

   * Do a commit by the following command. We usually do a commit after completing a certain portion of work. You can add an additional message with it so that it could summarize that what you have done in this commit.

         git commit -m 'Completed the Assignment'

   * Now, send the assignment to us by the following command. Remember, in this step, you might ask to login in to GitHub if you did not login before.

         git push origin master

That's all. If you found anything wrong in your assignment before the deadline; don't worry, just redo the steps 5 to 8 once again!

Cheers!

©️ EH, CSE, SUST
