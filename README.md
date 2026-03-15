# Software Testing Lab 5 - API Testing

This repository contains the backend code and automated API testing suite for a class roster system supporting CRUD operations for Students and Courses. I used our provided program as a base, but did make a few updates to the student and course controller for better handling of some of my identitified test cases.

## Core Project Links
* **[Postman Collection (JSON)](src/test/resources/postman/StudentRegDemo.postman_collection.json)**
* **[Student Controller](src/main/java/com/baarsch_bytes/studentRegDemo/controller/StudentController.java)**
* **[Course Controller](src/main/java/com/baarsch_bytes/studentRegDemo/controller/CourseController.java)**


## Test Case Documentation
For a complete, line-by-line breakdown of all expected and actual behaviors, please view the attached **[Test Case Documentation](https://docs.google.com/spreadsheets/d/11wOEtRgBFY9yA_Dn1Y2eMzdM2hTBW8VIz0xS0P-McgU/edit?usp=sharing)**.

## Postman Test Results
This automated testing suite utilizes both Black Box & White Box test design to evaluate input equivalence partitions, boundary values, business rules, and missing data fail states

Below is the execution proof showing a 100% pass rate across the collection:
![Postman Tests Passed](final_postman_test_results.png)
