<h1 align="center">🚀 AR-Webstore</h1>

<div align="center">
<p align="centre">
  <img src="https://img.shields.io/github/issues-pr-closed-raw/ShwetKhatri2001/AR-Webstore?style=for-the-badge" />
  <img src="https://img.shields.io/github/issues-closed-raw/ShwetKhatri2001/AR-Webstore?style=for-the-badge" />
  <img src="https://img.shields.io/github/contributors/ShwetKhatri2001/AR-Webstore?style=for-the-badge" />
  <img src="https://img.shields.io/github/repo-size/ShwetKhatri2001/AR-Webstore?style=for-the-badge" />
  <img src="https://img.shields.io/github/last-commit/ShwetKhatri2001/AR-Webstore?style=for-the-badge" />
 </p></div>

<div align="center">
<h2><i><b>Hi 👋, Akash here and I welcome you to AR-Webstore!</b></i></h2>
<h2><i><b>It's a web application to visualize photorealistic 3D objects in AR (Augmented Reality).</b></i></h2>
</div>

## Table of Contents

 - [Why AR-Webstore?](#why)
 - [Current State of Project](#current)
 - [Preview](#preview)
 - [Future Goals](#goals)
 - [Resources](#resources)
 - [Technologies Used](#tech)
 - [Setting up the project](#setup)
 - [Build](#build)
 - [A note on debugging](#debug)
 - [Open Source Programs](#open-source)
 - [Project-admin](#project-admin)
 - [Contributors](#contributors)
  
<a name="why"></a>
## 🤔 Why AR-Webstore? 

  ### Problem 😧
Traditional e-commerce platforms fail to deliver immersive product experiences, leaving customers uncertain about the look, fit, and functionality of items. This lack of visualization leads to higher return rates as products may not meet expectations. Additionally, customer engagement suffers due to the limited ability to interact with and explore products online.

  ### Solution 😃
Our AR-Webstore revolutionizes the shopping experience by seamlessly integrating augmented reality. With AR-Webstore,customers can visualize products in their own spaces and view all the virtual features more clearly. This empowers customers to make informed decisions, reduces return rates, and enhances engagement, resulting in a more satisfying and immersive shopping journey.

<a id="current"></a>
## Current State of the Project
It provides you a list of e-commerce products along with their 3D photorealistic models to try out them in a 360deg viewer. Also, you can view those products in your own environment using augmented reality, where you can check each and every detail of products like chairs, photo frames, and cars as if they were actually present in your room.
</div>
<a name="preview"></a>

## 👀 Preview


<div style="display:flex;">
  <img src="https://github.com/ShwetKhatri2001/AR-Webstore/assets/56475750/0086f8a4-6f5e-4fcb-a2a8-da6e3c50a745" 
            alt="before" height="450"/>
  <img src="https://github.com/ShwetKhatri2001/AR-Webstore/assets/56475750/e2593277-08c3-4344-9161-e9a36506eab6" 
            alt="after" height="450"/>
</div>
<a name="goals"></a>

# 🤩 Future Goals

- Build an e-commerce platform that can provide an immersive online shopping experience.
- Make the products interactive in a real environment rather than just demonstrating static 3D models using ML-AI.

# 😇 Learning Exposure

XR, or Extended Reality, is an exciting technology that combines the real world with virtual elements. As a student interested in XR, while contributing to this project, you will learn about the technical aspects of XR, which involve understanding how to create and render virtual objects, recognize and track objects in the real world, and explore how users interact with virtual environments, ensuring intuitive and immersive experiences. While studying XR, you can delve into programming technologies like Three.js or Unity to develop interactive and immersive experiences. You'll also explore 3D modelling and animation to create virtual objects and environments.

No no! Don't worry about some top of the world words mentioned above, the project is completely beginner friendly 😅 !But if you give your best, then you can really learn and build something out of the box for the future while working on this project, which I can ensure 😎!Find some helpful resources below to start your journey in XR.

<a name="resources"></a>
## Resources 🙌
- [Develop your first WebAR app using WebXR and Three.js](https://codemaker2016.medium.com/develop-your-first-webar-app-using-webxr-and-three-js-7a437cb00a92)
- [WebXR Workshop](https://www.youtube.com/watch?v=gAzIkjkJSzM)
<a name="tech"></a>

## 🧰 Technologies Used

![three.js](https://img.shields.io/badge/three.js-000000.svg?style=for-the-badge&logo=three.js&logoColor=white)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![JavaScript](https://img.shields.io/badge/-JavaScript-FE7601?style=for-the-badge&logo=javascript)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS5](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

<a name="setup"></a>
## 🔥 Setting up and running the app locally

1. Fork the repo
   - First, you have to make your own copy of the project. For that, you have to fork the repository.You can find the fork button on the top-right side of the browser window.(Refer to the image below.)
   - Kindly wait till it gets forked.
   - After that copy, it will look like "<your-user-name>/AR-Webstore" forked from "ShwetKhatri2001/AR-Webstore"
  
2. Clone the repo to your system
    - Now you have your own copy of the project. Here, you have to start your work.
    - Go to the desired location on your computer where you want to set up the project.
    - Open that location on your terminal and clone the repo using the commands given below.
  
    ```
    git clone https://github.com/<your-username>/AR-Webstore.git
    ```
    ```
    cd AR-Webstore
    ``` 
3. To get the web app up and running, you need to run the following commands to install dependencies and start the app.
    ```
    npm install
    ```
    ```
    npm start
    ```

This will install the app dependencies, start an instance of webpack-dev-server, and expose the local web server to the internet using the local tunnel URL will be printed on your terminal.

<a name="docker"></a>
## 🧰 Docker-Setup

1. Get the docker 
   For Windows/WSL use this : (https://docs.docker.com/desktop/install/windows-install/)
   For Mac use this: (https://docs.docker.com/desktop/install/mac-install/)

2. Check whether docker has been installed or not using 
    `docker -v`

3. Pull the Image of  #AR-webstore from dockerhub
    `docker pull shwetkhatri2001/ar-webstore`
4. List the images that are present currently 
    `docker images`
5. Run the docker image of #AR-webstore 
    `docker run -p 3000:3000 shwetkhatri2001/ar-webstore`

You will get the react-app running on `http://localhost:3000/`

<a name="build"></a>
## 🧰 Build

Run `npm run build` to build the project. The build artifacts will be stored in the `build/` directory.

```
npm run build


