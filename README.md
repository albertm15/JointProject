# Joint Project - Hotel Las Palmeras

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![Closed Issues][closedIssues-shield]][closedIssues-url]

<br />
<div align="center">
  <h3 align="center">Hotel Management System</h3>
  <p align="center">
    A comprehensive web application for managing hotel operations, bookings, and staff.
    <br />
  </p>
</div>

## Description

**Hotel Las Palmeras** is a web-based management system developed using **Django**. It is designed to handle the complex day-to-day operations of a hotel, streamlining communication between different departments such as reception, cleaning staff, and the restaurant.

This project was developed as a joint university project to demonstrate full-stack web development, database management with SQLite, and agile software development methodologies (Scrum).

## Features

* **User Roles & Authentication:** Custom user models for Clients, Receptionists, Cleaning Staff, and Admins.
* **Room Management:**
    * Booking system with Check-in/Check-out functionality.
    * Real-time availability checking.
* **Staff Operations:**
    * **Cleaning:** specialized dashboard for cleaning staff to view dirty rooms and mark them as clean.
* **Restaurant Integration:**
    * Table reservation system.
    * Order management and billing integrated with room expenses.
* **Billing System:** Automated bill generation combining room costs and restaurant services.

## Built With

* **Python** (Backend Logic)
* **Django** (Web Framework)
* **SQLite** (Database)
* **HTML/CSS/JavaScript** (Frontend)

## Project Structure

The project is organized into modular applications:

* **`accounts/`**: Handles user registration, login, and custom user profiles (Client vs. Staff).
* **`JointProject/`**: The core application containing logic for:
    * `models.py`: Database definitions for Rooms, Bookings, Tables, and Orders.
    * `views.py`: Business logic for the management dashboards.
    * `templates/`: HTML interfaces for the user interaction.

---

### Security Configuration Note

> **⚠️ Important:** The `SECRET_KEY` in `djangoProject/settings.py` is intentionally exposed in this repository to facilitate the setup and evaluation of the project in a development environment.
>
> **For Production:** If deploying this application to a production environment, you must:
> 1.  Hide the `SECRET_KEY` using environment variables.
> 2.  Set `DEBUG = False`.
> 3.  Ensure `ALLOWED_HOSTS` is properly configured.

---

## Prerequisites

Before running the application, ensure you have the following installed:

* **Python 3.x**
* **Git**

## How to Run

Follow these steps to set up the project locally:

1.  **Clone the repository**
    ```sh
    git clone [https://github.com/arnaums02/Joint-Project---Grup-B.git](https://github.com/arnaums02/Joint-Project---Grup-B.git)
    ```

2.  **Navigate to the project directory**
    ```sh
    cd Joint-Project---Grup-B
    ```

3.  **Apply Database Migrations**
    Ensure the database structure is created correctly:
    ```sh
    python manage.py makemigrations
    python manage.py migrate
    ```

4.  **Run the Server**
    Start the local development server:
    ```sh
    python manage.py runserver
    ```

5.  **Access the App**
    Open your browser and go to `http://127.0.0.1:8000/`

[contributors-shield]: https://img.shields.io/github/contributors/arnaums02/Joint-Project---Grup-B.svg?style=for-the-badge
[contributors-url]: https://github.com/arnaums02/Joint-Project---Grup-B/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/arnaums02/Joint-Project---Grup-B.svg?style=for-the-badge
[forks-url]: https://github.com/arnaums02/Joint-Project---Grup-B/network/members
[stars-shield]: https://img.shields.io/github/stars/arnaums02/Joint-Project---Grup-B.svg?style=for-the-badge
[stars-url]: https://github.com/arnaums02/Joint-Project---Grup-B/stargazers
[issues-shield]: https://img.shields.io/github/issues/arnaums02/Joint-Project---Grup-B.svg?style=for-the-badge
[issues-url]: https://github.com/arnaums02/Joint-Project---Grup-B/issues
[closedIssues-shield]: https://img.shields.io/badge/Closed%20Issues-85-green?style=for-the-badge
[closedIssues-url]: https://github.com/arnaums02/Joint-Project---Grup-B/issues?q=is%3Aissue+is%3Aclosed

## Testing

To run the automated tests for the booking and management logic:

```sh
python manage.py test

## Team Developer Guide (Git Cheatsheet)

Quick reference for team members managing the repository:

* **Create a branch:**
    `git checkout -b name_of_branch` (or create manually via GitHub)
* **Update repository:**
    `git pull`
* **Switch branch:**
    `git checkout name_of_branch`
* **Check current branch:**
    `git branch` or `git status`
* **Commit changes:**
    ```sh
    git add -A
    git commit -m "Commit Message"
    git push
    ```

