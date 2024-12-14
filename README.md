# Online Examination System

#### The online examination system is a digital platform that evaluates students in a hassle-free way. The entire examination process is simplified and exams are taken from anywhere, anytime.

#### It is developed using Python, Django, CSS, HTML and SQLite. Talking about the project, it contains an admin side from where a user can take and manage exams easily. The Admin plays an important role in the management of this system. In this project, there is separate interface for students, professors and Admin.

---------------------------------------------------------------------------------------------------------------------
#### Main Features:

- Auto Submit Form as soon as timer runs out
- If student window goes out of focus for 5 times while appearing for an exam professor will receive an email
- Automatic calculation of marks once student submits Exam
- Separate superuser account for account validations
- Two types of users. Professors and Normal (Student) Users
- Separate Control Panel for both admin and students
- Students can take MCQ exam, view score and see correct answers.
- Automatic calculation of results of exam

---------------------------------------------------------------------------------------------------------------------

#### Overview of project
![image](https://user-images.githubusercontent.com/47894634/117118618-9c1d1b00-adae-11eb-8b61-a6e87578f8da.png)

---------------------------------------------------------------------------------------------------------------------

### Steps to run the project

#### Create a superuser account:

```
python manage.py createsuperuser
```

#### Once superuser account is created we can run the website

```
python manage.py runserver
```

#### If there are no errors website will be running on [http://127.0.0.1:8000/](http://127.0.0.1:8000/) (default)

#### For creating accounts for professor's we will need a group called Professor

1. Go to [http://127.0.0.1:8000/admin/auth/group/add/](http://127.0.0.1:8000/admin/auth/group/add/)
2. Login with superuser account
3. Add two groups named Professor and Students

#### For Professor verification, admin will need to manually add professor to Professor group once they create a new account

---------------------------------------------------------------------------------------------------------------------

