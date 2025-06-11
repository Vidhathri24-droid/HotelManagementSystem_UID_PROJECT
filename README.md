# HotelManagementSystem_UID_PROJECT

This is a responsive hotel management website user interface built using HTML, CSS (Bootstrap and custom styles), and JavaScript. It includes different dashboards for admins, staff, and customers, along with pages for booking, room management, food ordering, and more.

## 📁 Project Structure

├── index.html # Landing/Home page
├── login.html # Login page (role-based)
├── register.html # User registration
├── admin.html # Admin dashboard
├── staff-dashboard.html # Staff dashboard
├── customer_dashboard.html # Customer dashboard
├── bookings-admin.html # View all bookings (admin)
├── rooms-admin.html # Manage rooms (admin)
├── food_ordering.html # Food ordering system
├── rooms.html # View rooms
├── contact.html # Contact page
├── about-us.html # About the hotel
├── services.html # Hotel services
├── gallery.html # Photo gallery
├── profile.html # User profile
├── users.html # View registered users
├── css/ # All CSS stylesheets
├── js/ # All JavaScript files
├── img/ # Images used across the site
├── fonts/ # Font resources
├── Source/ # Source packages (UI libraries)


## 💡 Features

- **Role-based Login System**: Redirects users to specific dashboards based on their role (admin, staff, customer).
- **Admin Panel**:
  - Manage room details
  - View user bookings
  - Manage registered users
- **Staff Dashboard**:
  - View room booking status
  - View food orders
- **Customer Dashboard**:
  - View and book rooms
  - Place food orders
- **Food Ordering System** with price calculation
- **Gallery**, **About**, and **Services** pages
- **Responsive Design** using Bootstrap and custom styling

## 🛠 Technologies Used

- HTML5 & CSS3
- JavaScript & jQuery
- Bootstrap 4.2.1
- Font Awesome & Linearicons
- Owl Carousel, SlickNav, Nice Select, jQuery UI
- Magnific Popup for modal views

## 📦 Setup Instructions

This project is purely frontend. You can run it locally using any browser:

1. **Download and Extract** the `.zip` file.
2. Open `index.html` or `login.html` in a browser to start.
3. No server or backend setup required for the static UI demo.

## 🧾 Optional: Backend Integration

To make this a fully functional hotel management system:
- Implement backend in PHP, Node.js, or Python Flask/Django.
- Use MySQL or MongoDB for database.
- Store booking, user, room, and food order data.
- Connect login functionality with user sessions.
