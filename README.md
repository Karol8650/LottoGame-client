# LottoGame - frontend

## Backend
https://github.com/karolkraw/LottoGame-backend

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Specification](#specification)
* [Screenshots](#screenshots)
* [Setup](#Setup)


## General Information
LottoGame is an implementation of the well-known Lotto Lottery.
The user provides six distinct numbers from range 1-99 and receives ticket with unique ID and draw date.
Results can be checked right after the draw date.
The winning numbers are generated based on configured scheduler that runs every Saturday at 12 p.m.
The user can become a lottery winner if he hit at least three numbers.



## Technologies Used


### Frontend:<br>
<img src="https://img.shields.io/badge/angular-%23DD0031.svg?style=for-the-badge&logo=angular&logoColor=white" alt=""> &nbsp;
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt=""> &nbsp;
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt=""> &nbsp;



## Screenshots

![2023-02-09 19_29_50-Settings](https://user-images.githubusercontent.com/71384877/217914830-7e68a821-6164-41ae-ad3a-7f2a4d02f39d.png)
![mainPageLotto](https://user-images.githubusercontent.com/71384877/217914971-7aa9893f-4130-499e-965e-1f1fad5c98ba.png)
![2023-02-09 19_48_05-Settings](https://user-images.githubusercontent.com/71384877/217914840-417cc7ea-dfe8-4301-b7e9-06f1ecaf8a64.png)
![2023-02-09 20_20_24-lotto png ‎- lost](https://user-images.githubusercontent.com/71384877/217915957-231117c9-6d2a-4f7c-9860-3abe4d0508bd.png)


## Setup

### Requirements:
- Docker
- Two files placed in the same folder: **[docker-compose.yml](https://github.com/kalqa/LottoExcelentKarol/blob/master/docker-compose.yml)**
  and **[init-mongo.js](https://github.com/kalqa/LottoExcelentKarol/blob/master/init-mongo.js)** <br>

### To run the application:
- Just execute the following command in the folder mentioned above <br>
  ``
  docker compose up
  ``
(all images will be pulled from Docker Hub and the application will start) <br>
- You can access the app at `http://localhost:4200` in your web browser







