# TRAVEL-AGENCY-DATABASE-MANAGEMENT-SYSTEM
1.2	Problem statement

A travel agency wants to develop a database management system to streamline its operations. The agency offers various travel packages to its customers across different categories and subcategories. Customers can inquire about packages, make bookings, and leave feedback.
1.3	Objective
The objective of developing a Travel Agency Database Management System (DBMS) is to create a comprehensive solution that effectively manages the operations of the travel agency. The main objectives include
•	Efficient Data Management: The DBMS should efficiently store and manage information related to travel packages, inquiries, bookings, customer details, feedback, and other relevant data.
•	Improved Customer Experience: By providing an intuitive user interface for browsing packages, making inquiries, and leaving feedback, the DBMS aims to enhance the overall experience for customers, leading to higher satisfaction and increased loyalty.
•	Streamlined Operations: The system should streamline various operational tasks such as package management, inquiry handling, booking management, and communication with customers.

1.4	Dataset Description

The dataset for the Travel Agency Database Management System (DBMS) typically includes various tables representing different entities and their attributes. Here's a brief description of the dataset based on the provided schema:
 Category:
 
Cat_id: Unique identifier for each category.
Cat_name: Name of the travel category (e.g., Family Tours, Religious Tours).

 Contactus:
 
contactid: Unique identifier for each contact submission.
Name: Name of the person making the contact.
Phno: Phone number of the person making the contact.
Email: Email address of the person making the contact.
Message: Message or inquiry submitted by the person.

Enquiry:

Enquiryid: Unique identifier for each inquiry.
Packageid: Identifier of the package related to the inquiry.
 Name: Name of the person making the inquiry.
Gender: Gender of the person making the inquiry.
Mobileno: Mobile number of the person making the inquiry.
Email: Email address of the person making the inquiry.
NoofDays: Number of days for the travel inquiry.
Child: Number of children included in the inquiry.
Adults: Number of adults included in the inquiry.
Message: Additional message or details provided with the inquiry.
Statusfield: Status of the inquiry (e.g., pending, confirmed).

Package:

Packid: Unique identifier for each package.
Packname: Name of the travel package.
Category: Identifier of the category to which the package belongs.
Subcategory: Identifier of the subcategory to which the package belongs.
Packprice: Price of the travel package.
Pic1, Pic2, Pic3: URLs or file paths of images associated with the package.
Detail: Detailed description or information about the package.

 Subcategory:
 
Subcatid: Unique identifier for each subcategory.
Subcatname: Name of the subcategory.
Catid: Identifier of the category to which the subcategory belongs.
Pic: URL or file path of the image associated with the subcategory.
Detail: Detailed description or information about the subcategory.

Users:

Username: Username of the user.
Pwd: Password of the user.
Typeofuser: Type or role of the user (e.g., admin, customer)

