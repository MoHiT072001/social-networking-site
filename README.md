# SocialNet - A Social Networking Platform

Welcome to SocialNet, the vibrant social networking site where you can connect, share, and communicate with friends and family.

## Features

- **Login and Registration Page**: Secure access with user authentication.
- **Home Page**: Post status updates, view friends' activities, and interact with posts.
- **Friends**: Send and accept friend requests, manage your friend list.
- **Profile Page**: Customize your profile with your name, age, job, and more.
- **Messaging**: Private messaging feature to stay in touch with friends.
- **Photos**: Upload and share photos with your network.
- **Find Friends**: Search and connect with new friends.

## Prerequisites

Before installing SocialNet, ensure you have XAMPP installed to create a local web server environment.

## Installation

1. **Install XAMPP**: Download and install XAMPP from the official website.
2. **Start Apache and MySQL**: Open the XAMPP Control Panel and start the Apache and MySQL services.
3. **Clone the Repository**:
    ```bash
    git clone https://github.com/yourusername/socialnet.git
    cd socialnet
    ```
4. **Import Database**:
    - Launch `phpMyAdmin` from the XAMPP Control Panel.
    - Create a new database named `socialnet`.
    - Click on the `Import` tab, choose the database file (`socialnet.sql`), and click `Go`.

5. **Configure Database Connection**: Update the database connection settings in your project's configuration file with your local environment's details.

6. **Install Dependencies**: If your project has any dependencies, install them using the package manager.
    ```bash
    npm install
    ```

## Usage

Start the server and explore the functionalities of SocialNet.

```bash
npm start



