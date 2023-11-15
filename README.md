# API_Testing-Project
<br>

## API Testing for Student-Management with Postman
This project is on API testing with Postman for the Student Management web-service. It's evaluating the APIs are working functionality and usability as expected. 

## How to run this project!
1. Install [Postman](https://www.postman.com/).
2. Install [Node.js](https://nodejs.org/en/).
3. Download [Project file](https://drive.google.com/drive/folders/16SzJWDvhETXTYWBwDAOiL40Y8HVhyf8E?usp=sharing).
4. Now Import collection & environment file into Postman: \
`file > import > choose the method > press 'import'`
5. Run Desired API request 

Run on cmd
1. Open cmd on project folder or move to project folder `cd Downloads/project_file`
2. Run the follwing command 
Install newman `npm install -g newman`
3. Now 
`newman run Student_Management.postman_collection.json -e Std_Manage.postman_environment.json`
4. If want to export test results first install them \
   `npm install -g newman-reporter-html` \
 and `npm install -g newman-reporter-htmlextra`
6. Now run follwing command for report \
`newman run Student_Management.postman_collection.json -e Std_Manage.postman_environment.json -r cli,htmlextra`

## HTTP Status Codes
HTTP status code are 3 digit number which a server response to a browser’s request.
Those are divided into 5 categories. \
```
1xx - Informational Purpose
2xx - Successful
3xx - Redirection
4xx - Client Error
5xx - Server Error
```
![http_status_code](https://drive.google.com/uc?export=view&id=1iwy6FJw2krnOtpOmMhhHocFpXgfguTBM)


## What I have done & Testcase Scenarios in this Testing!
* Operation
  - Create Student
  - Update Student
* Student Details
  - Students Details
  - Get Specific Student
  - Get Student Technical Skills
  - Get Specific Student Technical Skills
* Technical Skill
- Add Technical skills
- Update Technical Skills
- Delete Technical Skills
* Delete Student \
_[Positive and Negative case both are created]_


<!-- 
## Test Cases for this Testing:
`incomplete` 
-->

## Test Report with Newman :
A Newman report has been generated for the API test
1. HTML [Report Link](https://drive.google.com/file/d/1JfJc_MrPVi20NrA6aBR1WLUjBHF8XCvt/view?usp=drive_link)

2. Snapshots:
> * *Summary Report*
![Summary_1](https://drive.google.com/uc?export=view&id=17KXS5vg5di8ESAGu2cqywAhsd2LLNtmZ)
![Summary-2](https://drive.google.com/uc?export=view&id=1R3yo4u3Mv_TI1C0c6Bfge1go1LdySIpf)

> * *Total Requests*
![Total_1](https://drive.google.com/uc?export=view&id=1oz3USCQ2x2haoVNQQcsjF15aqdxRAhtl)
![Total_2](https://drive.google.com/uc?export=view&id=1zAM1MgTditIjCPQ4zKCR43r-mdmnUZnU)

> * *Failed Requests*
![Failed](https://drive.google.com/uc?export=view&id=1_sXJlXLexn6buN6153Cx5S1y_nVa6Btb)


---
**[ Attention ] \
if you face any type of image broken/missing issue, please `refresh` this web page again.**

### **#Happy_Testing**
---

