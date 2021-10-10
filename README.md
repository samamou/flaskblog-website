# Sarah Al Mamoun's Flask Blog 👩‍💻

I am creating a Full-Featured Web Application built with the Flask framework in Python 
for my web development class at **Concordia University**.

## Light and dark mode
I used Bootstrap classes to define the base template. I then extended and redefined the template using Jinja2 template syntax and organized the them into blocks. 

Homepage & Work pages in dark mode

<img width="400" alt="homepage" src="https://user-images.githubusercontent.com/46803937/136682858-dd4788af-4104-4ddd-98c7-37e1d817492e.png">
<img width="400" alt="Work" src="https://user-images.githubusercontent.com/46803937/136682860-96cde166-b223-4d95-bdcf-3c3d9448feee.png">

AboutMe & Contact pages in light mode

<img width="400" alt="AboutMe" src="https://user-images.githubusercontent.com/46803937/136682859-b31aef26-3830-48e7-b546-2468c0e2e332.png">
<img width="400" alt="Contact" src="https://user-images.githubusercontent.com/46803937/136682861-ae8ae1bd-3e13-4fc0-a0b5-3438d1188b29.png">


 
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

## Project tree 
Your project should look like this (FYI)

<img width="275" alt="Screen Shot 2021-10-09 at 5 33 27 PM" src="https://user-images.githubusercontent.com/46803937/136674243-285f661b-9366-4ed9-9d22-7b7281eea3c2.png">


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


## License
[MIT](https://choosealicense.com/licenses/mit/)
