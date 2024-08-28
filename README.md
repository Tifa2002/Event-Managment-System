# Event Management System
# Overview
This project is an event management system website built using ASP.NET Core MVC. It is designed to provide a seamless experience for users, organizers, and admins. The application follows best practices in software design, including the Unit of Work pattern and modular architecture using areas.

# Features
Role-Based Authorization: The system supports two roles—Admin and Organizer. By default, users register as regular users. Admins can upgrade any account to the Organizer role, allowing them to create and manage events.
Event Management: Organizers can create, edit, and manage events through a dedicated interface.
Ticket Booking: Users can browse events and book tickets directly from the website.
Payment Integration: Secure payment processing is handled via Stripe, ensuring a safe transaction experience for users.
Responsive Design: The website is fully responsive, providing an optimal viewing experience across a wide range of devices.
# Technologies Used
ASP.NET Core MVC: For building the web application using the MVC architectural pattern.
Unit of Work Design Pattern: To ensure a clean and maintainable codebase, separating business logic from data access.
Stripe API: Integrated for secure online payment processing.
Bootstrap/CSS: To create a responsive and user-friendly interface.
# Installation
Clone the repository:
git clone https://github.com/Tifa2002/event-management-system.git
Navigate to the project directory:
cd event-management-system
Restore dependencies:
dotnet restore
Update the database connection string in appsettings.json.
Apply migrations:
dotnet ef database update
Run the application:
dotnet run
# Usage
Admin Role: Admins can manage user roles, including promoting users to organizers.
Organizer Role: Organizers have the ability to create and manage events.
User Role: Registered users can book tickets for available events.
Payments: All transactions are handled through Stripe for secure payment processing.

# Demo
https://github.com/user-attachments/assets/d47d4d27-751c-421e-808f-4a12c38adcbf

# License
This project is licensed under the MIT License. See the LICENSE file for details.

# Contributing
Contributions are welcome! Please submit a pull request or open an issue to discuss your ideas or report bugs.
