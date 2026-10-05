# 🤖 AERP Robotics Website

> Dynamic website developed as a Professional Aptitude Project (PAP) for the Programming and Robotics Club of Agrupamento de Escolas Raul Proença (AERP).
> 

## 📌 About

The **AERP Robotics Website** was created to provide the club with a modern online presence while supporting its internal management.

The project is divided into a **public area**, focused on presenting the club, its projects, competitions, achievements and news, and a **restricted area** for registered members and authorized users.

## 🎯 Main Goals

- Create a modern and responsive website for the Robotics Club.
- Promote the club’s activities, projects and achievements.
- Provide tools for internal management.
- Implement authentication and role-based access control.
- Create a solid foundation for future improvements.

## ✨ Features

### 🌐 Public Area

- Club information and objectives.
- Projects and competitions.
- Achievements and results.
- News and updates.
- Image galleries.
- Useful external links.

### 🔐 Authentication

- User registration.
- Login and logout.
- Form validation.
- Protected areas.
- Different access levels.

### 👥 Member Management

Authorized users can view, edit and remove member records and manage information required for club activities and competitions.

### 📰 News Management

The backoffice allows authorized users to create, edit, delete and view news. **Summernote** is used for rich-text editing, with published content displayed on the public website.

### 🤖 Project Management

Projects can be created, edited, deleted and viewed through the backoffice, including information such as descriptions, technologies, images and links.

### 📅 Attendance

Registered members can mark their attendance during club sessions, providing an organized record of participation.

### 🛡️ Roles & Permissions

**Laratrust** was used to control access according to user roles:

- Students
- Teachers
- Administrators

## 🗄️ Database

The project uses **MySQL** and Laravel migrations to manage the database structure.

The database includes entities related to users, projects, attendance, news, categories, competitions, galleries, sponsors, roles, permissions, classes and competition results.

**MySQL Workbench** was used to inspect and validate the database during development.

## 🛠️ Technologies

| Technology | Purpose |
| --- | --- |
| 🐘 PHP | Server-side programming |
| 🔥 Laravel | Web framework |
| 🗄️ MySQL | Database |
| 🌐 HTML5 | Structure |
| 🎨 CSS3 | Styling |
| ⚡ JavaScript | Client-side functionality |
| 🧩 Bootstrap | Responsive UI |
| 🔐 Laratrust | Roles and permissions |
| 🔎 Select2 | Enhanced form fields |
| ✍️ Summernote | Rich-text editing |
| 📦 Composer | PHP dependencies |
| 📦 NPM | Front-end dependencies |
| 🌍 Apache | Web server |
| 💻 Laragon | Development environment |
| 🔀 Git / GitHub | Version control |

## 🏗️ Laravel Structure

The project follows Laravel’s MVC structure, separating models, controllers, views, routes, database migrations and public assets.

The frontoffice and backoffice were organized into separate view sections to make the project easier to maintain and expand.

## 🧪 Testing

The system was tested throughout development, including:

- Registration and login.
- Logout and protected areas.
- Form validation.
- CRUD operations.
- Database relationships.
- Role-based permissions.
- Responsive behaviour.

During development, several problems were solved, including database migration conflicts, variable inconsistencies and Laravel/browser caching issues.

## 🔒 Security

The project uses authentication, role-based authorization and server-side validation to restrict access to protected functionality.

Sensitive configuration files and real user data should not be included when publishing the project publicly.

## 🚀 Running the Project

To run the project locally, install PHP, Composer, MySQL, Node.js/NPM and a compatible web server.

After obtaining the repository, install its dependencies, configure the database connection in the `.env` file, run the Laravel migrations, build the front-end assets and start the Laravel development server.

The exact setup may vary depending on the local environment.

## 🏆 Project Recognition

A version of the project was submitted to **Sistestar 12 - 2025**, an initiative promoted by DecoJovem.

The project reached the **second stage out of three**.

## 📈 Future Improvements

The project identified several possible improvements, including:

- Email-based password confirmation.
- More dynamic scheduling.
- Further interface and usability improvements.
- Additional management automation.
- Further optimization and scalability.

## 👨‍💻 Author

**Almeida**

Professional Aptitude Project — AERP Robotics

Academic Year: 2024/2025

---

⭐ A practical project combining Laravel, PHP, MySQL, authentication, authorization and content management.
