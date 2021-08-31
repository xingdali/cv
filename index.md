---
layout: cv
title: Xingda Li
email:
  url: mailto:xingdali@live.unc.edu
  text: xingdali@live.unc.edu
homepage:
  url: https://www.linkedin.com/in/xingdali/
  text: https://www.linkedin.com/in/xingdali/
---

# Xingda Li

<!--
include contact information from the front matter
Supported arguments:
    - homepage: url, text
    - phone
    - email
-->

{% include cv-contact.html %}

## Education

### **University of North Carolina at Chapel Hill** `2019.8 -`

```
Chapel Hill, NC
```

- B.S. Computer Science, GPA: 3.61/4.0

### **University of Illinois at Urbana-Champaign** `2018.8 - 2019.5`

```
Urbana, IL
```


## Experience

### **Orka, Foster City, CA** `2021.3 - 2021.7`

_Software Engineer Intern_<br>
- Worked with the software development team (mentored by [Chauncey Lu](https://www.linkedin.com/in/chauncey-lu-657b9580/) and [Yufan Yuan](https://www.linkedin.com/in/yufan-yuan-1b8117135/)) on building the official [website](https://hiorka.com). I developed the user interface using ReactJS, and backend api using Django for the refund process. I also participated in developing a hearing aid fitting console, which provides user interface for audiologists to check patient medical information, and modify parameters on patients' hearing aids during remote and in-person fitting. For the remote fitting function, my teammate and I used Websocket to send messages to patient's phone and manipulate hearing aids by BLE. We also accomplished real-time video chat between audiologist's browser and patient's phone to solve remote communication issues using Twilio.
- Applied Jenkins and Docker for CI/CD infrastructure. I wrote shell scripts for building, deploying applications, and sending email notifications of the building information. I also implemented and migrated static files on server to the AWS S3 in order to store future files uploaded by users.
- **Fall Detection** is an application that detecting user's fall down movement, which running on the hearing aid. I first trained a 1D CNN model based on signals from 3-axis Accelerometer on human waists using Tensorflow Deep Learning Library. Since the hearing aid is an embedded system, I built a simple 1D CNN library in C, which can load and deploy any 1D CNN models trained in Tensorflow on the hearing aid. I also optimized the CNN algorithm specifically for the ARM architecture chip on the hearing aid using CMSIS DSP Library for superior performance.
- Built an mobile application for collecting Fall Detection training dataset from hearing aids on human ears using Flutter. I used a Bluetooth API to get signals from 3-axis Accelerometer on hearing aid, and formatted data into CSV files. During data collection, a video recording feature is also applied for future data annotation.

### **CourseEval, Chapel Hill, NC** `2020.8 - 2020.11`

_Full-stack Developer_<br>
- Proposed the whole project including infrastructure, and the final solution we aimed for.
- Developed the public user interface with HTML, CSS, and Javascript.
- Developed backend using NodeJS, and MongoDB for storage user information, and students’ comments.
- Used Selenium library to get all of the UNC course information on Coursicle.
  
### **Illini Fighting Hunger, Urbana, IL** `2018.8 - 2018.9`

_Volunteer_<br>
- Helped the organization package 300 lbs of rice.
- Worked with resident assistants and residents to package meals.

### **TIME Photograph Club, Zibo, Shandong, China** `2015.8 - 2018.5`

_President_<br>
- Hosted photographic exhibitions at Zibo International Academy.
- Recorded, and edited videos for school events including high school commencement, etc.

## Skills

- Proficient in React, Django, Jenkins, and Docker with strong background in data structures and algorithms.
- Computer skills include Adobe Lightroom, Adobe Photoshop, iMovie, Word, Excel, and PowerPoint.
- Proficient in English, and Mandarin.


<!-- ### Footer

Last updated: May 2013 -->
