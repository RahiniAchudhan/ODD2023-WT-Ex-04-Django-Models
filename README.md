# Ex-04-Django-Models
# NAME: RAHINI.A
# REFERENCE NUMBER: 23012479
# DEPARTMENT: AIDS

# AIM: 
    TO create django model

# DESIGN PROCEDURE:

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

![WhatsApp Image 2023-11-21 at 20 23 16_c902dab7](https://github.com/RahiniAchudhan/ODD2023-WT-Ex-04-Django-Models/assets/145742838/f1a0f982-bba3-42c8-a76b-f742c732cb98)


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


# OUTPUT:

![image](https://github.com/RahiniAchudhan/ODD2023-WT-Ex-04-Django-Models/assets/145742838/cfae32f9-e8db-48b7-81f3-18ece85e9e00)


![image](https://github.com/RahiniAchudhan/ODD2023-WT-Ex-04-Django-Models/assets/145742838/3a72301d-2a9c-433b-ab58-57123b6c9eb5)




    
