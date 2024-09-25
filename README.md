# Hotel Booking Management System (HBMS)

## Project Overview

The **Hotel Booking Management System (HBMS)** is designed to automate the manual booking and management processes of a hotel using computerized equipment and software. This system enables a seamless, error-free, and secure way to handle hotel reservations, room allocations, additional services, and guest feedback. It enhances the overall performance and improves service quality, leading to better utilization of resources. 

## Entity-Relationship Diagram (ERD)

The following diagram represents the ERD of the Hotel Booking Management System (HBMS):

![Hotel Booking ERD](https://github.com/Epsita-R/Hotel-Booking-Management-System/blob/main/ERD.jpg)


## Features

- Admin and User Management
- Room Booking and Allocation System
- Guest Request and Complaint Tracking
- Additional Services (Airport Transfers, Spa Bookings, Tours)
- Room Category and Facility Management
- Contact Us and Guest Query System
- Invoice Generation
- Guest Feedback Tracking and Management
- Guest Demographics and Preferences Monitoring

## Database Design

| Sno | Attribute   | Description                                                                 |
| --- | ----------- | --------------------------------------------------------------------------- |
| 1   | **Admin**   | `id`, `AdminName`, `username`, `mobile_number`, `email`, `password`, `adminregdate` |
| 2   | **User**    | `id`, `fullname`, `mobile_number`, `email`, `password`, `regdate`            |
| 3   | **Facility**| `id`, `facilitytitle`, `desc`, `image`, `creationdate`                       |
| 4   | **Page**    | `id`, `pagetype`, `pagetitle`, `pagedesc`, `email`, `mobile_number`, `updationdate` |
| 5   | **Booking** | `id`, `roomid`, `bookingno`, `userid`, `gender`, `address`, `checkin`, `checkout`, `bookingdate`, `remark`, `status`, `updation` |
| 6   | **Category**| `id`, `categoryname`, `desc`, `price`, `date`                                |
| 7   | **Contact** | `id`, `name`, `mobile_number`, `email`, `message`, `enquirydate`, `isread`   |
| 8   | **Room**    | `id`, `roomtype`, `roomname`, `maxadult`, `maxchild`, `roomdesc`, `noofbed`, `image` |

## Operations

1. Add and manage user/admin details.
2. Manage room bookings, including check-ins and check-outs.
3. Handle guest requests and complaints.
4. Delete user accounts and bookings.
5. Update user booking details.
6. Allocate rooms based on room availability and type.
7. Manage additional services (transfers, tours, spa).
8. Track guest feedback, demographics, and preferences.

## Control Features

| Sno | Control                  | Description                           |
| --- | ------------------------ | ------------------------------------- |
| 1   | **Book**                 | Book a room for a user.               |
| 2   | **Send (Room booking)**  | Send the booking request to the admin.|
| 3   | **Send (Contact us)**    | Submit guest queries to the admin.    |
| 4   | **Update**               | Update user details.                  |
| 5   | **Change**               | Change user password.                 |
| 6   | **View**                 | View user booking details.            |
| 7   | **Invoice**              | Generate an invoice for bookings.     |

## Technology Stack

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** PHP/Python (depending on choice)
- **Database:** MySQL
- **Additional Tools:** Git, GitHub, Bootstrap


