# CRUD_QuizApp
PYTHON PROJECTS - CRUD create a Quiz Application using Core python and mysql  using PYMYSQL libraries 

The Quiz Application is a Python-based application that allows users to participate in quizzes and provides an administrative interface for managing quiz questions and user reports. The application utilizes the PyMySQL library to interact with a MySQL database for data storage and retrieval. The application consists of two main user roles: admin and user. The admin has privileges to add, update, and delete quiz questions, as well as view a report of user quiz results. The user can register, login, take quizzes, view their quiz results, and logout. Finally, upon finishing all the activities the user may either Logout or Exit the app. 

The app has multiple pages and it is built in such a way that it will exit the app only when the user enters an option to exit the app. Otherwise it will keeps redirecting to the various pages inside it

The multiple pages are as follows: 
---> Homepage 
---> Main Menu of Admin Quiz Application 
---> Admin Login Page 
---> User Registration Page 
---> User Login Page 
---> User Quiz Test Page 
---> Display Quiz Result Page 
---> User Logout Page 
---> Admin Exit Page  

For QuizApplication here am attaching the output's of he project below for multiple pages.

    -----> HOME PAGE OF QUIZ APPLICATION:
    
          ![image](https://github.com/santha19/CRUD_QuizApp/assets/136115122/9f53b60e-48f1-4a61-b428-557b76732216)

   -----> MAIN MENU OF ADMIN QUIZ APPLICATION:
   
   ![image](https://github.com/santha19/CRUD_QuizApp/assets/136115122/eb617d9f-cc5a-496f-91d0-507935389128)


   -----> ADMIN LOGIN PAGE :
   
   ![image](https://github.com/santha19/CRUD_QuizApp/assets/136115122/cc37ddc3-7a31-4bee-ac1e-d74acaf763e5)

Here i have created in mysql database for admin detalis username and password:
![image](https://github.com/santha19/CRUD_QuizApp/assets/136115122/f66ca20c-c784-4c22-8299-faa9c6c17e9d)
![image](https://github.com/santha19/CRUD_QuizApp/assets/136115122/ce13987d-3ff2-4bc1-bf4a-726506ed6bb2)
 
  After then Admin login's it will redirects to the "ADMIN PANNEL":
  
  ![image](https://github.com/santha19/CRUD_QuizApp/assets/136115122/f94c87e9-58ea-4964-ae1a-cc5057bd065c)

In admin pannel we can Add questions, Update questions, Delete questions, View quetions, get user reports, Logout from the admin pannel . This functions are set by only Admin side. Am attaching the output below.
 
      -----> Add question:
        When we enter the option 1 it will redirects to the Add Question page form Admin Pannel  to set the questions by the “Admin” to users. 
      ![image](https://github.com/santha19/CRUD_QuizApp/assets/136115122/ef94934c-8ed5-49f7-b136-debfbb2c3c0d)

     -----> Update question:
     When we enter the option 2 it will redirects to the Update Question from Admin Pannel to update the questions by the admin.
     ![image](https://github.com/santha19/CRUD_QuizApp/assets/136115122/ab8403d7-e12c-40fa-951b-1aea0b17453e)
     
        ------> Delete question:
        When we enter the option 3 it will redirects to the Delete Question from Admin Pannel to delete the questions by the admin. When we are trying to delete the question . It will ask the Question ID to delete the question by the admin. After entering the question ID it will delete that question which is created by admin.
     ![image](https://github.com/santha19/CRUD_QuizApp/assets/136115122/0743a015-bf22-419b-8284-e463b155d0e1)

      ------> View question:
      When we enter the option 4 it will redirects to the View Questions from Admin Pannel to view the questions to the admin which admin has set the questions to the user. 
        ![image](https://github.com/santha19/CRUD_QuizApp/assets/136115122/9bd773f8-0d14-4339-b324-76ef21249343)
        
    ------> User Report:
    When we enter the option 5 it will redirects to the user report from Admin Pannel to list the quiz taken by the user to the admin. The admin can check how many times user have taken the quiz by using “USER ID” to check. 
    ![image](https://github.com/santha19/CRUD_QuizApp/assets/136115122/6151d719-84e4-4d6d-8314-2ab91c762cde)

   -----> Logout from admin pannel:
    When we enter the option 6 it will redirects to the Logout page from Admin Pannel . The logout option is to exit the page from “ADMIN PANNEL” after setting the all options by the Admin. 
![image](https://github.com/santha19/CRUD_QuizApp/assets/136115122/6ca9fde5-c205-4874-bdb9-47191921b05f)

After done all funtions from admin side and again it will redirect to main menu quiz application page .

  USER REGISTRATION PAGE:
  -----------------------
  When the users entered a option number 2 in the main menu it will be redirected to the User Registration page. In the User Registration page it asks for the  user’s name, user’s password.
  after entring the username and password it will pop-up like "User Regitered Successfully!"
  ![image](https://github.com/santha19/CRUD_QuizApp/assets/136115122/335f5c7d-acab-4a2a-bf1f-038b5421ffe3)

USER LOGIN PAGE:
----------------
On enter the option 3 from the Quiz application page it redirects to the User Login Page which is the view options from the crud app. First it checks for the available data entries in the table which the user id, Username and password. 
![image](https://github.com/santha19/CRUD_QuizApp/assets/136115122/3e07f047-548f-4d00-ae28-b1c6783acaf6)
 I have created database for user also :
 ![image](https://github.com/santha19/CRUD_QuizApp/assets/136115122/635c3f76-b2c3-4df6-9349-85c14b67d428)
User login details:
![image](https://github.com/santha19/CRUD_QuizApp/assets/136115122/56fd806d-00d3-4abb-bd03-778d8454e181)

After login into user it will redirects to the "USER PANNEL" Page:
------------------------------------------------------------------
 When the user entered a option  1 it will be redirected to the Take Quiz page . The user can take the test which the admin prepared the quiz question . 
 User can take quiz:
 ![image](https://github.com/santha19/CRUD_QuizApp/assets/136115122/1ded80f4-aea6-43d9-aa97-4ba86566733e)

DISPLAY QUIZ RESULTS:
-----------------------
When the user entered a option  2 it will be redirected to the Quiz Result page .  

When user entered with his user id, username & password . After completing the quiz test . The user can see there results by entering option 2 and user can check the results that how many times has taken the quiz and marks also

quiz results:
![image](https://github.com/santha19/CRUD_QuizApp/assets/136115122/57e90d4d-9bc2-4125-9745-50a9df52a9f2)
![image](https://github.com/santha19/CRUD_QuizApp/assets/136115122/f490ee32-d1e0-4d1b-a204-dab7f3964f16)


User logout page:
-----------------
When we entered option 3 from user pannel . It will logout from the user page from user pannel . Then it will return to the main menu page to Quiz Application page. User will be come out after completing the quiz test and checking the results of the user

![image](https://github.com/santha19/CRUD_QuizApp/assets/136115122/b08372c4-0c53-4d23-88d3-ae344e3cfb83)

ADMIN EXIT AGE:

When we entered option 4 from the main menu page it will exit from the quiz application page . After completing the quiz from the user side . Then the admin will check the quiz status and marks and how many attended and results by the admin.
![image](https://github.com/santha19/CRUD_QuizApp/assets/136115122/f929ef8c-5499-424e-b0b2-4c4686462247)



