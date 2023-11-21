# Ex-04-Django-Models
NAME: RAHINI.A
REFERENCE NUMBER: 23012479
DEPARTMENT: AIDS

AIM: 
    TO create django model

DESIGN PROCEDURE:

Django models

Step1 : Create django project and app using the following commands:
           Django-admin startproject mymodels
           Python manage.py startapp myapp

Step 2: create a user_profile models in model.py


![WhatsApp Image 2023-11-21 at 20 23 15_282e8189](https://github.com/RahiniAchudhan/ODD2023-WT-Ex-04-Django-Models/assets/145742838/558553fe-b0a7-40ac-ab33-14065a957165)



Add the models in the admin interface using the code in admin.py


![WhatsApp Image 2023-11-21 at 20 23 15_3fb42f33](https://github.com/RahiniAchudhan/ODD2023-WT-Ex-04-Django-Models/assets/145742838/f688fea4-7397-43b9-bb49-bc9c94eef6f8)

Write the function based view to render the data from the models to the template in
view.py

![Screenshot (95)](https://github.com/RahiniAchudhan/ODD2023-WT-Ex-04-Django-Models/assets/145742838/2eaade4e-74ff-4b4d-89b8-ce4062f3b75c)


Setup the url path for the templates using urls.py

![WhatsApp Image 2023-11-21 at 20 23 15_a169ee9d](https://github.com/RahiniAchudhan/ODD2023-WT-Ex-04-Django-Models/assets/145742838/511184d0-cb2a-4061-9dc3-d3fb90cb7fc2)



In settings.py file add the app created.

Step 3:
       Now do the migrations process to initiate and save the models
          Python mange.py makemigrations
          Python manage.py migrate

![WhatsApp Image 2023-11-21 at 20 23 16_0c7052f9](https://github.com/RahiniAchudhan/ODD2023-WT-Ex-04-Django-Models/assets/145742838/71422afe-af3b-4ff6-b1e1-45df5f9f1052)

Last step: run the program using the command
           Python manage.py runserver 8000
           
In the admin/ page you can view the models created
And in the user_profile template page you can see the profile page of the user.


    
