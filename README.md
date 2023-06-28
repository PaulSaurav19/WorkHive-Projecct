# WorkHive-Project
<h1 align="center">WORKHIVE</h1>

<h3 align="center">A freelancing website for college students using the toolset from the MERN stack.</h3>

<br />

<h2 align="center">🖥️ Tech Stack</h2>

<h4 align="center">Frontend:</h4>

<p align="center">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="reactjs" />
  <img src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E" alt="javascript" />
  <img src="https://img.shields.io/badge/Rest_API-02303A?style=for-the-badge&logo=react-router&logoColor=white" alt="restAPI" />
  <img src="https://img.shields.io/badge/Sass-CC6699?style=for-the-badge&logo=sass&logoColor=white" alt="sass" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="html5" />
</p>

<h4 align="center">Backend:</h4>

<p align="center">
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="nodejs" />
  <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" alt="expressjs" />
  <img src="https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white" alt="mongodb" />

</p>

  </em>
</p>
<br />

## Table of Contents:

1) [Features](#fet)
2) [Getting Started](#install)
3) [Tech-Stack Used](#depend) 
4) [APIs Used](#apis)
5) [Contributors](#contri)

<a name="fet"></a>
## Features

### 🚀 Basic

- Registration, login and gig organize forms
- Homepage / Landing Page with sliding menu
- Gigs page with all categories
- Gig description
- Gig management
- Message page with one-to-one chat with seller and buyer
- Single gig page
- Gig search
- Image uploading via cloudinary, a media management

<br />

### 🚀 Advanced 

- Chat with buyers
- Create new gigs and
- Only the seller's gig can be deleted
- Gigs can be reviewed by buyers based on comment and stars
- Chat with seller
- Filter and sort gigs for range of price
- My Orders Section for details of all gigs bought
- Can review gig and give stars
- Order securely with Stripe
- Search gigs with keywords
- Payments page with Stripe integration

<br />

<a name="install"></a> 
## Getting Started

This project was built using React, Redux, Sass, HTML, JavaScript, Rest API, Node JS, Express and MongoDB with JWT and Stripe integration. It is an freelance outsourcing web application and for running on your local environment you should follow these guidelines.

1) Clone the repository using:
```bash
https://github.com/PaulSaurav19/WorkHive-Project.git
```
2) Run the following in both the "client" and "server" folders:
```bash
npm install 
```
3) Start MongoDB and set up the following ENV files:

### Server
```
`JWT_SECRET`
e.g. this_is_secret_123

`MONGODB_URI`
e.g. mongodb cluster URI

`STRIPE_SECRET`
e.g. Secret key from stripe dashboard

`NODE_ENV`
e.g. 'development' for local and 'production' for production
```
### Client
```
`VITE_API_URL`
e.g. http://localhost:3000/api or production deployed server link

`VITE_STRIPE_PUBLISHABLE_KEY`
e.g. Publishable key from stripe dashboard
```
4) Run following in both "client" and "server" folders:
```bash
npm start
```
<a name="depend"></a>
## Tech-Stack Used

* NodeJS(ExpressJS) 
* React JS
* SASS
* Vite-JS Template
* JavaScript
* MongoDB (as Database)

<a name="apis"></a>
## APIs Used

* Stripe(to monitor payments)

<a name="contri"></a>
## Contributors

* [Sourav Paul](https://github.com/PaulSaurav19)
* [Vishesh Agrawal](https://github.com/Vishesh-MNNIT)

## Feedback
Feel free to file an issue if you come across any bugs

### Made at:

<p align="center">
<img alt="MNNIT" width="112px" src="http://www.mnnit.ac.in/institutelogo/MNNIT%20(logo)png.png" />
</p>
