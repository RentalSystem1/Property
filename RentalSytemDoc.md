
Property Rental Management System

INTRODUCTION

The property rental industry is constantly evolving, demanding efficient and user-friendly solutions for managing properties and bookings. Enter the Property Rental Management System (PRMS), a comprehensive software solution that streamlines operations and enhances the overall rental experience. A PRMS acts as a central hub for managing all aspects of property rental, from listing creation and marketing to booking management and tenant communication. This system automates tasks like scheduling viewings, collecting rent, and handling maintenance requests, freeing up landlords and property managers to focus on other critical aspects of their business. By providing a centralized platform for managing multiple properties, a PRMS fosters transparency and accountability. Landlords and tenants can access real-time information on bookings, payments, and property status, leading to improved communication and reduced disputes. In today's competitive rental market, a PRMS is an essential tool for maximizing efficiency, enhancing tenant satisfaction, and achieving sustainable growth.
 


Project Features and Characteristics

The proposed project Rental Management System Web Based consists of the following features:


•	Admin Booking Management:
Admins manage all booking activities, ensuring availability and accurate scheduling.
•	Profit Monitoring:
The system allows admins to track and analyze profit margins, aiding financial decision-making.
•	Payment Processing:
Facilitates secure payment collection and transaction tracking for room bookings.
•	Room Management:
Admins can add, delete, and update room details to maintain an accurate listing.
•	User-Friendly Booking:
Users can easily browse rooms and services, then book based on their specific needs




Project Scope

•	The Property Rental Management System is designed to streamline the management of property rentals by providing dedicated functionalities for both admin and users. On the admin side, the system enables comprehensive management of bookings, tracking of profit, processing of payments, and the ability to add or remove property listings. Admins play a crucial role in maintaining the efficiency of the system, ensuring that all data is up-to-date and accurate.
•	For users, the system offers a seamless experience through a well-organized interface. Users can navigate the homepage, explore services, view available properties, and access contact information. The booking process is simplified, allowing users to reserve properties based on their specific needs. This project aims to provide a convenient and efficient solution for property rentals, making it easier for users to book properties and for property managers to oversee their operations effectively.



Functional Requirements

User Requirements

Project Features
Apartment Search by Location
Users can input a location (city, neighborhood, etc.) and see available listings based on their criteria, including filters for price, size, and amenities.

 View Detailed House Information and Images
Each property listing includes detailed descriptions, amenities, high-resolution images, and floor plans to give users a comprehensive view of the house.

Real-Time Rental Availability
Each apartment listing features an integrated calendar showing available rental dates, allowing users to plan their rental period easily.

Listing Navigation
A user-friendly interface that lets users smoothly navigate between listings, view different properties, and save favorites for later reference.

Booking and Payment Integration
Once a user finds a property, they can book it directly through the platform with payment options (credit card, bank transfer, etc.) integrated for smooth transaction processing.


Work breakdown Structure

![12](https://github.com/user-attachments/assets/d5e9b9c0-af05-4727-9197-763276dae5e3)



Functional Requirements

Project Features
 Apartment Search by Location
Users can input a location (city, neighborhood, etc.) and see available listings based on their criteria, including filters for price, size, and amenities.

 View Detailed House Information and Images
Each property listing includes detailed descriptions, amenities, high-resolution images, and floor plans to give users a comprehensive view of the house.

 Real-Time Rental Availability
Each apartment listing features an integrated calendar showing available rental dates, allowing users to plan their rental period easily.

Listing Navigation
A user-friendly interface that lets users smoothly navigate between listings, view different properties, and save favorites for later reference.

Booking and Payment Integration
Once a user finds a property, they can book it directly through the platform with payment options (credit card, bank transfer, etc.) integrated for smooth transaction processing.


Use Cases 


![1241](https://github.com/user-attachments/assets/1fd563b7-b14e-4a51-9dda-ab625b61cfdc)



| FIELD NAME | DESCRIPTION      | DATA TYPE     | LENGTH | SAMPLE              |
|------------|------------------|---------------|--------|---------------------|
| id         | Primary key      | int unsigned  | 10     | 1                   |
| fullname   | Full name        | varchar       | 100    | JohnRuzzel          |
| phone      | Phone number     | int           | 10     | 09052755830         |
| email      | Email address    | text          | N/A    | Natojoshua22@gmail.com |
| date       | Contact date     | date          | N/A    | 2024-08-26          |
| approval   | Approval status  | varchar       | 12     | Approved            |


| FIELD NAME | DESCRIPTION | DATA TYPE | LENGTH | SAMPLE |
|------------|-------------|-----------|--------|--------|
| id         | Unique identifier | int       | 10     | 1      |
| name       | Username    | varchar   | 30     | admin  |
| pass       | Password    | varchar   | 30     | 1234   |



| FIELD NAME | DESCRIPTION               | DATA TYPE | LENGTH | SAMPLE      |
|------------|---------------------------|-----------|--------|-------------|
| id         | Unique identifier         | int       | 11     | 1           |
| title      | Title of the payment      | varchar   | 5      | Mr          |
| fname      | First name of the guest   | varchar   | 30     | John        |
| lname      | Last name of the guest    | varchar   | 30     | Bacia       |
| troom      | Type of room booked       | varchar   | 30     | Simple      |
| tbed       | Type of bed booked        | varchar   | 30     | Simple      |
| nroom      | Number of rooms booked    | int       | 11     | 2           |
| cin        | Check-in date             | date      | -      | 2024-08-25  |
| cout       | Check-out date            | date      | -      | 2024-08-30  |
| ttot       | Total amount              | double    | 8.2    | 900         |
| fintot     | Final total amount        | double    | 8.2    | 550.00      |
| mepr       | Meal price                | double    | 8.2    | 1050.00     |
| meal       | Meal type                 | varchar   | 30     | Breakfast   |
| btot       | Total booking amount      | double    | 8.2    | 1050.00     |
| noofdays   | Number of days            | int       | 11     | 5           |


| FIELD NAME | DESCRIPTION          | DATA TYPE | LENGTH | SAMPLE          |
|------------|----------------------|-----------|--------|------------------|
| id         | Unique identifier    | int       | 10     | 1                |
| type       | Room type            | varchar   | 15     | Suite            |
| bedding    | Bedding type         | varchar   | 10     | Double           |
| place      | Room location/area   | varchar   | 10     | North Caloocan   |
| cusid      | Customer ID          | int       | 11     | 500123           |



| FIELD NAME | DESCRIPTION         | DATA TYPE | LENGTH | SAMPLE                  |
|------------|---------------------|-----------|--------|--------------------------|
| id         | Unique identifier   | int       | 10     | 1001                     |
| Title      | Booking title       | varchar   | 5      | Mr.                      |
| FName      | First name of the guest | text      | -      | John                     |
| LName      | Last name of the guest  | text      | -      | Bacia                    |
| Email      | Email address       | varchar   | 50     | Natojoshua22@gmail.com   |
| National   | Nationality         | varchar   | 30     | Philippines              |
| Phone      | Phone number        | text      | -      | 09052755830              |
| TRoom      | Type of room booked | varchar   | 20     | Simple                   |
| NRoom      | Number of rooms booked | varchar   | 2      | 2                        |
| Meal       | Meal preferences    | varchar   | 15     | None                     |
| cin        | Check-in date       | date      | -      | 2024-08-25               |
| cout       | Check-out date      | date      | -      | 2024-08-26               |
| stat       | Booking status      | varchar   | 15     | Confirmed                |
| nodays     | Number of days booked | int       | 11     | 4                        |





Entity Relationship Diagrams
![14](https://github.com/user-attachments/assets/363b0b05-82b2-4ab7-8e66-b21990404b23)
 









