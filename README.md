# Project Readme

## Introduction
This project is a Django web application designed to manage flights and passengers. It provides functionalities to add passengers to flights and display flight details along with passenger information.

## Features
- **Flight Management**: Allows users to view existing flights, including origin, destination, and duration.
- **Passenger Management**: Provides the ability to view passengers associated with each flight and add new passengers to flights.
- **Admin Interface**: Utilizes Django's built-in admin interface for easy manipulation of models, including adding, deleting, and editing flights and passengers.
- **Customizable Admin Settings**: Users can configure the admin interface to display additional information about flights and passengers.
- **Authentication**: Includes a user management system with features for user authentication, login, and logout.

## Usage
1. **Database Setup**: Configure your database settings in `settings.py` and run migrations using `python manage.py migrate`.
2. **Run the Server**: Start the Django development server using `python manage.py runserver`.
3. **Access the Application**: Navigate to `http://localhost:8000` in your web browser to access the application.

## Functionality Details
### Flight Management
- View existing flights with details such as origin, destination, and duration.
- Add, delete, or edit flights using the Django admin interface.

### Passenger Management
- View passengers associated with each flight.
- Add new passengers to flights through the user interface.
- Utilize Django's ORM to handle interactions with the database.

### Admin Interface
- Access the admin interface at `/admin` to manage flights, passengers, and users.
- Customize admin settings to display specific fields and configurations.

### Authentication
- Users can register, log in, and log out using the provided user management system.
- Protected routes ensure that only authenticated users can access certain functionalities.

## File Structure
- **`/flights`**: Main Django application containing flight and passenger models, views, and templates.
- **`/users`**: Additional Django application for user management, including authentication views and templates.
- **`/templates`**: HTML templates for rendering pages.

## License
This project is licensed under the [MIT License](LICENSE).
