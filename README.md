
# Learning Log Web application




## Overview
## 
Learning Log is a web application that allows users to log topics they're interested in and to make journal entries as they learn about each topic. The home page of the Learning Log site describes the site and invites users to either register or log in. Once logged in, a user can create new topics, add new entries, and read and edit existing entries.
#
## Technologies Used

 - **HTML/CSS**: the front-end technologies used for developing the user interface of the web application.

 - **Python**: a high-level programming language used for developing the backend of the web application.

 - **Django**: a powerful web framework written in Python used for developing the backend of the web application.

 - **SQLite3**: a lightweight database management system used for storing the data of the web application.
 #

 
## Features

- ### User-Friendly Interface :

The Learning Log web application is designed to be user-friendly and intuitive, with clear instructions and easy-to-use features. The user interface is clean and uncluttered, making it easy to focus on tracking and reflecting on learning progress.

![Index](https://monkheart.s3.ap-south-1.amazonaws.com/Github/learning_log/Index+page.png)
#

- ### User Authentication :

Users can register for an account on the Learning Log site or log in with an existing account. Once logged in, users have access to additional features, such as creating new topics and adding journal entries.

![Login_page](https://monkheart.s3.ap-south-1.amazonaws.com/Github/learning_log/Login+page.png)
#

- ### Topic Management :

Users can create new topics to track their learning progress, edit or delete existing topics, and view all topics they have created.

![Topic](https://monkheart.s3.ap-south-1.amazonaws.com/Github/learning_log/Topics.png)
#

- ### Entry Management :

For each topic, users can add new entries to track their progress and reflect on their learning. Entries can be edited or deleted, and users can view all entries they have created.

![Entry Management](https://monkheart.s3.ap-south-1.amazonaws.com/Github/learning_log/entry+page.png)
#

## Installation and Setup
#
To install and run the Learning Log web application, follow these steps:
#
**1.** Clone the repository from GitHub

`git clone https://github.com/Manish-mech/Learning_log.git`
#
**2.** Change into the project directory:

`cd Learning_log`
#
**3.** Install the required dependencies:

`pip install -r requirements.txt
`
#
**4.** Migrate the database:

`python manage.py migrate
`
#
**5.** Create a superuser account:

`python manage.py createsuperuser
`
#
**6.** Run the server:

`python manage.py runserver
`
#
**7.** Open your web browser and navigate to http://localhost:8000/ to access the Learning Log application.
#
## Contributing

If you would like to contribute to the Learning Log web application, please submit a pull request on GitHub. All contributions are welcome!
#
## License

This project is licensed under the [MIT](https://choosealicense.com/licenses/mit/) License.

