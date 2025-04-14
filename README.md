# **Alumo - A Social Media Platform**

**Alumo** is a social media web application built using **Django** and **Python**, designed to provide users with a platform to share posts, follow other users, like posts, and interact with content. This project was developed as part of my undergraduate coursework and aims to demonstrate practical skills in web development using Django.

## **Features**

- User authentication (Sign up, login, logout)
- Create, edit, and delete posts
- Like posts and interact with other users' content
- Follow and unfollow users
- Real-time notifications for interactions (like, comment, follow)
- User profile page with basic details and posts display
- Responsive design for mobile and desktop devices

## **Technologies Used**

- **Backend**: Django, Python
- **Frontend**: HTML, CSS, JavaScript
- **Database**: SQLite (default, can be configured to PostgreSQL or MySQL)
- **Authentication**: Django’s built-in authentication system
- **Real-time notifications**: Django Channels (optional for advanced notifications)

## **Installation**

To run this project locally, follow these steps:

### 1. Clone the repository
```bash
git clone https://github.com/GlitchSadik/alumo.git
```
### 2. Install dependencies

Navigate to the project directory and install the required dependencies using pip:

```bash
cd alumo
pip install -r requirements.txt
```
### 3. Set up the database

After installing the dependencies, run the following command to apply migrations and set up the database schema:

```bash
python manage.py migrate
```
### 4. Create a superuser (for accessing the Django admin)

To create a superuser that will allow you to access the Django admin interface, run the following command and follow the prompts:

```bash
python manage.py createsuperuser
```
### 5. Run the development server

Start the development server using the following command:

```bash
python manage.py runserver
```



## **License**

This project is open-source and available under the [MIT License](LICENSE).

## **Contact**

For any inquiries or questions, feel free to reach out to me via [email or GitHub](https://github.com/GlitchSadik).


