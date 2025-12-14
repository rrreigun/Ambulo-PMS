<a id="readme-top"></a>


<!-- PROJECT LOGO -->
<br />
<div align="center">
    <img src="https://res.cloudinary.com/degn0zm6s/image/upload/v1754146538/ambulo_logo_f2rloe.png" alt="Logo" width="80" height="80">
  

<h3 align="center">Ambulo's Property Management System</h3>

<p align="center">
    A team-based software development project that delivered a custom web-based property management system for Ambulo's Properties. The solution digitizes and optimizes key operational processes, improving efficiency and reducing manual workflows through modern web technologies.
  </p>  
</div>


<!-- ABOUT THE PROJECT -->
## About The Project

<p>This project is a web-based Property Management System (PMS) developed to streamline and automate the operations of Ambulo Properties. The system provides a centralized platform for managing tenant information, lease agreements, rent notices, maintenance requests, and internal communication. Administrators can oversee all operations through a dedicated dashboard, manually input payments, generate online receipts, and access comprehensive financial reports. Tenants are given restricted access through a dedicated portal where they can view leases, track rent payments, and submit maintenance requests.</p>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

----------------------------------------------------------------------------------------------------

### Built With

* ![HTML](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
* ![CSS](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
* ![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white)
* ![Node.js](https://img.shields.io/badge/Node.js-339933?logo=nodedotjs&logoColor=white)
* ![Express.js](https://img.shields.io/badge/Express.js-000000?logo=express&logoColor=white)


<p align="right">(<a href="#readme-top">back to top</a>)</p>

----------------------------------------------------------------------------------------------------
## 👥 Team

This project was developed by a collaborative team of 4 developers:

| Name | Role | Contributions | GitHub | LinkedIn |
|------|------|---------------|--------|----------|
| **Kei Lebron** | Project Manager & Backend Developer | Project coordination, server-side logic, database architecture | [@keilebron](https://github.com/kklebron) | [LinkedIn](https://linkedin.com/in/kei-lebron) |
| **Rea Buena** | Lead Programmer | Server-side logic, database operations, API endpoints, Full-stack | [@rrreigun](https://github.com/rrreigun) | [LinkedIn](https://www.linkedin.com/in/rea-buena/) |
| **Joshua Deputo** | Frontend Developer | User interface implementation, client-side functionality, responsive layouts | [@joshuadeputo](https://github.com/joshuadeputo) | N/A |
| **Jerson Matuguina** | UI/UX Designer | Web design, user experience | [@jersonmatuguina](https://github.com/jersonmatuguina) | N/A |

<p align="right">(<a href="#readme-top">back to top</a>)</p>

----------------------------------------------------------------------------------------------------

##  Local Setup

```bash
# 1. Clone the repo
$ git clone https://github.com/RankFour/AmbuloPMS.git
$ cd AmbuloPMS

# 2. Install server & client dependencies
$ npm install        # root uses workspaces - optional
$ cd server && npm install
$ cd ../client && npm install

# 3. Configure environment variables 

# 4. Run apps
$ cd server && npm run server     # Runs server only
$ cd client && npm run start      # Runs client only
$ npm run dev                     # Runs both app
```

The API runs at **`http://localhost:5000/api/v1`** (configurable)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---------------------------------------------------------------------------------------------------

## ⚙️ Environment Variables

Create **`.env`** files in both `server` and `client` (if needed). Example for **server/.env**:

```env
#LOCAL SETUP
NODE_ENV="development"
PORT=5000
API_VERSION=v1
PROJECT_NAME="AmbuloPMS"
JWT_SECRET=your_jwt_secret
MY_SQL_HOST_LOCAL="localhost"
MY_SQL_USER_LOCAL="your_mysql_user"
MY_SQL_PASSWORD_LOCAL="your_mysql_password"
MY_SQL_DATABASE_LOCAL="your_database_name"
COOKIE_DOMAIN_LOCAL="localhost"
API_BASE_LOCAL="your_localhost_url"
FORCE_FIRST_LOGIN_RESET="true"

#FILE UPLOAD
CLOUDINARY_CLOUD_NAME="your_cloudinary_cloud_name"
CLOUDINARY_API_KEY="your_cloudinary_api_key"
CLOUDINARY_API_SECRET="your_cloudinary_api_secret"

#EMAIL FUNCTION
GMAIL_USER="youremail@gmail.com"
GMAIL_PASSWORD="your_gmail_password"
MAIL_FROM_NAME="Ambulo Properties"
MAIL_FROM="youremail@gmail.com"
MAIL_REPLY_TO="youremail@gmail.com"

#CHATBOT
BP_ASSISTANT_BACKEND="gemini"
GOOGLE_API_KEY="your_gemini_api_key"
GEMINI_MODEL="gemini-2.0-flash"
ASSISTANT_SHOW_MODEL_TAG="true"
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

----------------------------------------------------------------------------------------------------

## **Gantt Chart**
![Gantt Chart](https://github.com/user-attachments/assets/4f28dfd0-9b42-44cb-a950-4d4a9316f9b5)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

----------------------------------------------------------------------------------------------------
