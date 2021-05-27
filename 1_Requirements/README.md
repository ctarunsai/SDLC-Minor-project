# Requirements 🎯

## Introduction 💬
* Library Management System helps to maintain records of every issue, return transactions that happens in the libraries in computerized way.
* This helps the librarian in managing the library in a simple and easy manner, also helps to calculate the fines, collect the fines from the end-users.

* There are 2 modules developed, 
  1. Admin Module (Users: Librarian, and other library staff)
  2. Student Module (Users: Students and library users)

* This tool also creates snapshots of the data at hourly frequency, so that we can recover back to previous hour very easily.

## Research 📖
* Initially, people used to maintain account books for these book transactions manually. This conventional way of maintaining records requires a lot of human effort and storage space in order to store the previous data. 
* It used to be difficult for librarians to track each of the books, late fee fines etc.,
* So, we came up with a solution which requires very less human effort, sends timely alerts to the librarians and end users regarding the books.

## Specific Requirements 💼
### *External Interface Requirements*
* The user should be simple and easy to understand and use. Also be an  interactive interface .The system should prompt for the user and administrator to  login to the application and for proper input criteria 

  ### *1. User Interface* 👨‍🦱
  * The software provides good graphical interface for the user any  administrator can operate on the system, performing the required task such as  create,           update, viewing the details of the book. 
  * Allows user to view quick reports like Book Issues/Returned etc in  between particular time. 
  * Stock verification and search facility based on different criteria. 

  ### *2. Hardware interface ⛓️* 
  * Operating system : window 
  * Hard disk :40 GB 
  * RAM : 256 MB 
  * Processor : Pentium(R)Dual-core CPU 
  
  ### *3. Software interface 🖥️*
  * Java language 
  * Net beans IDE 7.0.1 
  * MS SQL server 2005

### *Functional requirements 🗃️*
* Book entry: In this module we can store the details of the  
books. 
* Register student: in this module we can keep the details of the  new student. 
* Book issue: This module is used to keep a track of book issue  details. 
* Book return: This module enables to keep a track of return the  books.  

### *Performance requirements :atom:*
* The capability of the computer depends on the performance of the  software. The software can take any number of inputs provided the database size  is larger enough. This would depend on the available memory space. 
  ### *Design constraints*
  * Each member will be having a identity card which can be used for the library  book issue, fine payment etc. whenever library member wish to take a book, the  book issued by the library authority will be check both the book details as well as  the student details and store it in library database. In case of retrieval of book  much of human intervention can be eliminated.
  ### *System attributes*
  * Maintainability: There will be no maintained requirement for the  software. The database is provided by the end user and therefore is  maintained by this user. 
  * Portability: The system is developed for secured purpose, so it is can’t  be portable. 
  * Availability: This system will available only until the system on which  it is install, is running. 
  * Scalability: Applicable.  
### *Other requirements*
* There are no other requirements.

## Cost and Features :a
### *Cost*
Since the system uses only open source software, it is free of cost..!!

### *Features*
   ### Admin Module Features
   1. Admin Dashboard
   2. Admin can add/update/ delete category
   3. Admin can add/update/ delete author
   4. Admin can add/update/ delete books
   5. Admin can issue a new book to student and also update the details when student return book
   6. Admin can search student by using their student ID
   7. Admin can also view student details
   8. Admin can change own password
   
   ### Student Module Features
   1. Student can register yourself and after registration they will get student_id.
   2. After login student can view own dashboard.
   3. Student can update own profile.
   4. Student can view issued book and book return date-time.
   5. Student can also change own password.
   6. Student can also recover own password.
   
  ### Some other Key Features
  1. Unlimited User Accounts.
  2. End User Access Permissions can be specified by the Admin.
  3. Fetching Books
  4. Alerts to email related to book return date, fines etc.,
  5. Newsletters regarding newly added books are sent periodically.
  6. Book Issue, Return, Fine Calculation.

## Defining the System
![System-Diagram](https://github.com/Sanchana-2k/LTTS_C_MiniProject/blob/bd3f1a159eb0f2032dbd88662892a2142d26b84d/1_Requirements/System%20Diagram.jpg)
    
## SWOT ANALYSIS
![SWOT-Analysis](https://github.com/Sanchana-2k/LTTS_C_MiniProject/blob/6f6972167470b4b186e9995b7a6647f3f8c7cbd5/1_Requirements/swot%20analysis.jpg)

# 4W&#39;s and 1&#39;H

## Who:

This tool is a helping hand for librarians of the libraries across the world, automates the whole book transaction process of library.

## What:

A Library Management System that helps in managing the book transactions like issue, return and also calculates the fines.

## When:

When Librarians or Library Management feels tough to do the library management in old conventional way or when Librarians want to automate the book transactions or scaling up the library.

## Where:

Can be used at places where there are huge number of books in a library, or in libraries where the book transactions are very high.

## How:

The student or library user can pick and add books to the cart and then he can checkout the cart in order to create a issue request. Then after picking the books they can go to librarian, and he can confirm the issue finally. Same flow for the return request as well. Calculated fines are displayed over the user portfolio itself.

# Detail requirements
## High Level Requirements:

|      ID          |Description                          |Status                         |
|----------------|-------------------------------|-----------------------------|
|HR_01|Length |Implemented|
|HR_02|Area |Implemented|
|HR_03|Volume|Implemented|
|HR_04|Mass |Implemented|
|HR_05|Speed |Implemented|
|HR_06|Time|Future|
|HR_07|Temperature|Future|



##  Low level Requirements:
|      ID          |Description                          |  HLR_ID  |Status               |
|----------------|-------------------------------|----------|-----------------------------|
|LR_01|Meter|HR_01|Implemented|
|LR_02|Centimeter|HR_01|Implemented|
|LR_03|Foot|HR_01|Implemented|
|LR_04|Inch|HR_01|Implemented|
|LR_05|Millimeter|HR_01|Implemented|
|LR_06|Square Meter|HR_02|Implemented|
|LR_07|Square Centimeter|HR_02|Implemented|
|LR_08|Square Foot|HR_02|Implemented|
|LR_09|MSquare Inch|HR_02|Implemented|
|LR_10|Square Yard|HR_02|Implemented|
|LR_11|Cubic Meter|HR_03|Implemented|
|LR_12|Cubic Centimeter|HR_03|Implemented|
|LR_13|Litre|HR_03|Implemented|
|LR_14|Millilitre|HR_03|Implemented|
|LR_15|Gallon (imperial)|HR_03|Implemented|
|LR_16|Kilogram|HR_04|Implemented|
|LR_17|Gram|HR_04|Implemented|
|LR_18|Ounce|HR_04|Implemented|
|LR_19|Tonne (metric)|HR_04|Implemented|
|LR_20|Pound|HR_04|Implemented|
|LR_21|Meter per Second|HR_05|Implemented|
|LR_22|Kilometer per Hour|HR_05|Implemented|
|LR_23|Miles per Hour|HR_05|Implemented|
|LR_24|Foot per Second|HR_05|Implemented|
|LR_25|Knot|HR_05|Implemented|
|LR_26|Hour|HR_06|Future|
|LR_27|Minute|HR_06|Future|
|LR_28|Second|HR_06|Future|
|LR_29|Celcius|HR_07|Future|
|LR_30|Farenheit|HR_07|Future|
|LR_31|Kelvin|HR_07|Future|
