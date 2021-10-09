# Sarah Al Mamoun's Flask Blog 👩‍💻

I am creating a Full-Featured Web Application built with the Flask framework in Python 
for my web development class at **Concordia University**.

## Homepage 
I used Bootstrap classes to define the base template. I then extended and redefined the template using Jinja2 template syntax and organized the them into blocks. 
<img width="1000" alt="website1" src="https://user-images.githubusercontent.com/46803937/93248508-ec7f3400-f75d-11ea-9f9d-5bde9de5abca.png">
 
## User Login  
This application includes a user management system that can register the users. Once they are registered they can login, logout, and make small blog updates. 
<img width="1000" alt="website6" src="https://user-images.githubusercontent.com/46803937/93248514-edb06100-f75d-11ea-9dfc-2db968647eba.png"> <img width="1000" alt="website5" src="https://user-images.githubusercontent.com/46803937/93248512-edb06100-f75d-11ea-9a0e-5f32d9119bb2.png">

## Forms:
The forms are defined as subclasses of Flaskform, with properly defined validators. Building this application helped me better understand Flask while dealing with databases, accepting and validating user input from (register/ login) forms, and saving data onto backend file systems. I used an SQLite database to store users and data during development. 

<img width="1000" alt="website4" src="https://user-images.githubusercontent.com/46803937/93248511-edb06100-f75d-11ea-8e31-2e623ebc1387.png">

Some other snippets of the site: 
<img width="1000" alt="website2" src="https://user-images.githubusercontent.com/46803937/93248509-ed17ca80-f75d-11ea-8975-18c20985d52c.png">
<img width="1000" alt="website3" src="https://user-images.githubusercontent.com/46803937/93248510-ed17ca80-f75d-11ea-97b5-c971b79e2092.png">





## Installation
Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the necessary packages. You can see which versions are required below. 

```bash
bcrypt==3.1.4
blinker==1.4
certifi==2016.2.28
cffi==1.11.5
click==6.7
Flask==1.0
Flask-Bcrypt==0.7.1
Flask-Login==0.4.1
Flask-Mail==0.9.1
Flask-SQLAlchemy==2.3.2
Flask-WTF==0.14.2
itsdangerous==0.24
Jinja2==2.10
MarkupSafe==1.0
Pillow==5.3.0
pycparser==2.18
six==1.11.0
SQLAlchemy==1.2.7
Werkzeug==0.14.1
WTForms==2.1
```

## Resources and credits 

```bash 
Corey Schafer 
https://www.youtube.com/user/schafer5

Django Tutorials to create this same application
https://www.youtube.com/playlist?list

Python Installation
https://youtu.be/YYXdXT2l-Gg

Virtual Environment Setup pt 
https://youtu.be/N5vscPTWKOk

Virtual Environment Setup pt 2
https://youtu.be/cY2NXB_Tqq0/
```

## Project status 
I will be adding custom error pages, pagination, reset password/forgot password option, multiple account blog posting ability, accepting and resizing multiple account profile pictures.


## Contributions
Suggestions and contributions are more than welcome.


## License
[MIT](https://choosealicense.com/licenses/mit/)
