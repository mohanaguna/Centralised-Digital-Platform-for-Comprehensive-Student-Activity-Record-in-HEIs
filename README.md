# Centralised-Digital-Platform-for-Comprehensive-Student-Activity-Record-in-HEIs


## **Project Overview**

The **Centralised Digital Platform for Comprehensive Student Activity Record in HEIs** is designed to maintain and manage all student activity records in a single digital system. The platform will store academic, co-curricular, and extracurricular achievements of students in an organized manner. It will help students, faculty members, and administrators access records easily and efficiently. The system aims to reduce paperwork, improve data accuracy, and provide a centralized solution for tracking student performance and achievements. This platform will enhance transparency, accessibility, and overall record management in Higher Education Institutions.



## **Problem Statement**

Many Higher Education Institutions maintain student activity records using separate systems, spreadsheets, or manual documentation. This makes it difficult to track and manage academic, co-curricular, and extracurricular achievements efficiently. The lack of a centralized system can lead to data duplication, loss of records, and limited accessibility. Therefore, there is a need for a centralized digital platform that securely stores, manages, and provides easy access to comprehensive student activity records for students, faculty members, and administrators.



## **Project Objectives**

- Store all student activity records in one platform.
- Maintain academic and extracurricular achievements.
- Reduce manual paperwork and record management.
- Provide easy access to student records.
- Improve data accuracy and security.



## **Module List**

- Student Registration Module
- Student Activity Management Module
- Faculty Verification Module
- Report Generation Module
- Admin Dashboard Module


## **Use Case Diagram**

The Use Case Diagram illustrates the interaction between users and the system. It shows the major functionalities available for Students, Faculty, and Admin in the Centralised Student Activity Record Platform.

![Use Case Diagram](file_0000000038dc720b9a6e467279bda56c.png)

## **Table List**

| S.No | Table Name  | Description |
|-------|------------|-------------|
| 1 | Student | Stores student details |
| 2 | Faculty | Stores faculty information |
| 3 | Admin | Stores administrator details |
| 4 | Activity | Stores student activity records |
| 5 | Achievement | Stores achievements and certificates |
| 6 | Report | Stores generated reports |

## **ER Diagram**

The ER Diagram represents the relationship between the entities in the system database. It helps in understanding how student activity records are stored and managed.

![ER Diagram](file_0000000078d87209a4e117b473585aaf.png)

## **SQL Schema**

```sql
CREATE TABLE Student (
    Student_ID INT PRIMARY KEY,
    Name VARCHAR(100),
    Email VARCHAR(100),
    Department VARCHAR(50),
    Year INT
);

CREATE TABLE Activity (
    Activity_ID INT PRIMARY KEY,
    Activity_Name VARCHAR(100),
    Activity_Type VARCHAR(50),
    Student_ID INT,
    FOREIGN KEY (Student_ID) REFERENCES Student(Student_ID)
);
```

## **Page Layouts**

The page layouts were designed to provide a simple and user-friendly interface for managing student activity records. The layouts include Login, Registration, Dashboard, Activity Management, and Report pages.

## **UI Screens**

The UI screens were designed to provide a simple and interactive interface for users. The screens include Login, Registration, Dashboard, Activity Management, and Report pages for efficient record management.

## **UI Prototype**

The UI Prototype was created to visualize the overall design and functionality of the system. It includes screens such as Login, Registration, Dashboard, Activity Management, and Report Generation for a better user experience.

## **Design Approval**

The proposed system design was reviewed and approved. The UI layouts, database structure, and overall system workflow were verified to ensure they meet the project requirements and objectives.

## **React Project Setup**

The React project was initialized and configured for frontend development. The required dependencies were installed, and the basic project structure was created to support the development of the student activity record management system.

## **Login Module**

The Login Module was developed to provide secure access to the system. Users can log in using their credentials and access features based on their roles and permissions.

## **Registration Module**

The Registration Module was developed to allow new users to create an account in the system. It collects user details and stores them securely for future access and authentication.

## **Dashboard UI**

The Dashboard UI was designed to provide a clear overview of student activities and records. It enables users to access key features, view updates, and navigate through the system efficiently.

## **Forms Completed**

The required forms for the system were successfully designed and completed. The forms include user registration, login, activity entry, and record management forms to support efficient data collection and management.

## **Data Listing**

The Data Listing module was completed to display student activity records in a structured format. It allows users to view, search, and manage stored data efficiently.

## **Frontend Review**

The frontend development was reviewed to ensure that all user interface components function correctly and meet the project requirements. The design, navigation, and responsiveness were evaluated and finalized.






