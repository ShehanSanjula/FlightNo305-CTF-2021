# Flight No. 305 - The CTF

![FlightNo305](https://raw.githubusercontent.com/ShehanSanjula/FlightNo305-CTF-2021/main/Images/Flight%20No%20305.png)

Flight No. 305 CTF (capture-the-flag) is a multi-level storyline themed jeopardy style CTF challenge based on the story of D.B. Cooper Hijacking. This CTF will take all the participants on a journey of D.B. Cooper Hijacking that real-world attackers may face when compromising and taking hold of target systems. It may also give the competitors an understanding to enable critical thinking and apply necessary attacking techniques in a real case scenario.

## 🔧 Technologies & Tools

![Azure](https://img.shields.io/badge/Cloud-%20Azure-blue)
![AWS](https://img.shields.io/badge/Cloud-%20AWS-orange)
![CTFd](https://img.shields.io/badge/Platform-CTFd-red)
![Docker](https://img.shields.io/badge/Virtualization-Docker-blue)
![MariaDB](https://img.shields.io/badge/Database-MariaDB-brown)
![MySQL](https://img.shields.io/badge/Database-MySQL-yellow)
![OS](https://img.shields.io/badge/OS-Ubuntu-orange)
![CDN](https://img.shields.io/badge/CDN-Netlify-green)
![DDoS protection](https://img.shields.io/badge/DDoS-protection-Cloudflare-orange)
![HTML](https://img.shields.io/badge/Language-HTML-brightgreen)
![JavaScript](https://img.shields.io/badge/Language-JavaScript-orange)
![CSS](https://img.shields.io/badge/Language-CSS-blue)

This project was generated for [Flight No. 305 - The CTF](https://flightno305.shehansanjula.me/) with [CTFd](https://github.com/CTFd/CTFd) version 3.4.0 and [Docker](https://github.com/docker) version 3.6.0.

## TryHackMe Room:
### URL: https://tryhackme.com/jr/flightno305

## NWA - Northwest Airline System
### URL: https://flightno305.shehansanjula.me/

## Dashboard
### URL: https://dash-flightno305.shehansanjula.me/

## Level 1 Intro: General
### URL: https://flightno305-level1.shehansanjula.me/
---
# 1.	Introduction

## 1.1	Problem Statement

#### This project is based on a real scenario which is D.B. Cooper Flight High jack. For the time being, nowadays, technology has been playing a massive role in the world. As well as technology has been involved in improving transportation. Flight high jacking has been taking place for a while, and cyber-criminal activities also have grown beyond the expected level. This project elaborates on how to improve the airline ticketing system’s security. The primary purpose is to educate and prepare the airline security team for a system breach and to give some real-world experience.

## 1.2	Product Scope

#### Flight No. 305 project mainly focuses on the airline security team. It has several levels: 1-12 as from basic levels to complex levels. It has two web systems for the game’s dashboard, and one is the airline booking system created for the natural world booking system. The primary purpose is to educate and give experience about cyber security and its activities. This project might be suitable for individuals who like to do cyber security as their profession. And mainly from this project, we primarily tried to give an experience and prepare the security team of particular airlines booking systems breaches. The goal is to educate all the airline security individuals and relevant security teams about how breaches can happen and how attackers might try to breach a system. By playing this system, anyone can enjoy and get knowledge about cyber security and real-world experience.

## 1.3	Project Report Structure

#### Here is a brief introduction to the project. Reading the rest of the document can get to know how this project grew from the bottom and the findings, pros, and cons. Under methodology, it has described the steps and systems has used to create this project and designs. We have discussed future works and lessons learned from this project.

# 2.	Methodology

## 2.1	Requirements and Analysis
#### Requirements are divided into three categories: performance requirement, safety requirement and security requirements.

### Performance Requirements
Recommend web browsers for greater user experience:

>	* Google Chrome
>	* Mozilla Firefox
>	* Microsoft Edge
>	* Apple Safari

+   The player can run our CTF platform smoothly using the latest version of the above-mentioned web browsers.
+ 	We always recommend a high bandwidth internet connection for internet communication with our servers.
+ 	The user must register with our platform in order to unlock all the features.
+ 	Data and information stores in the real-time database system of our platform.
+ 	We have configured a backup procedure for our CTF platform. Therefore, the user doesn't need to worry about their information.
  
### Safety Requirements

+ 	Users must read and agree with our privacy policy before they communicate with Flight No 305 CTF platform.
+ 	Flight No 305 accept no responsibility for loss or damage to user property during their data transmission.
+ 	If we found any user is violating our security policies, we'll ban the user from using our services thereafter.
+ 	All the challenges adhere is only for gaining educational knowledge. 
+ 	Flight No 305 does not encourage any user to hack real-world systems.
  
### Security Requirements

+   Our entire CTF platform is running under enabled DDoS protection.

![ddos-protection](https://raw.githubusercontent.com/ShehanSanjula/FlightNo305-CTF-2021/main/Images/ddos-protection.png)

## 2.2	Design

<p align="center"> <img src=https://raw.githubusercontent.com/ShehanSanjula/FlightNo305-CTF-2021/main/Images/Activity%20Workflow.png alt="Activity Workflow of Flight No. 305"/> </p>
<h4 align="center">Activity Workflow of Flight No. 305</h4> 

#### As above figure demonstrates, level 1 to level 6 is the introductory level. It focuses on general activities. When it comes to level 7 to level 12, those are mainly designed for security individuals. To complete those tasks, it is needed to install Linux based OS (Kali-Linux is recommended) and some other mentioned tools on the challenge description.

## The Infrastructure of Flight No. 305 - The CTF

#### The infrastructure of Flight No. 305 runs under 02 primary cloud services: Azure (Dashboard) & AWS (NWA System). Contestant requests are only accepted after the DDoS verification process of Cloudflare. Flight No. 305 uses Netlify CDN (Content Delivery Network) server for quick delivery of challenges on some occasions.

#### All the other developments are implemented inside the desired cloud services as follows.

<p align="center"> <img src=https://raw.githubusercontent.com/ShehanSanjula/FlightNo305-CTF-2021/main/Images/The%20Infrastructure%20of%20Flight%20No.%20305%20-%20The%20CTF.png alt="The Infrastructure of Flight No. 305 - The CTF"/> </p>
<h4 align="center">The Infrastructure of Flight No. 305 - The CTF</h4> 

### License

![MIT](https://img.shields.io/github/license/ShehanSanjula/FlightNo305-CTF-2021?color=black)
