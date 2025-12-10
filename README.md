Book Movie Tickets – Database Project

This project is a complete Database System for booking movie tickets. It demonstrates strong understanding of database design, SQL queries, ERD modeling, triggers, views, and complex database operations.
The system simulates how a cinema manages users, customers, employees, movies, seats, tickets, showtimes, and snack orders.


Project Overview

This project was developed as part of a Database Systems course.
The objective is to design a fully functional relational database for a Movie Ticket Booking System.

The project includes:
	•	ER model
	•	Database schema
	•	Populated tables with sample records
	•	Simple SQL queries
	•	Complex SQL queries
	•	Triggers
	•	Views
	•	Nested queries


Key Features

ERD (Entity–Relationship Diagram)

A complete ER model representing all major entities and their relationships, including User, Customer, Employee, Movie, Theater, Seat, ShowTime, Ticket, and Snacks.

Database Schema

Each table includes:
	•	Field names
	•	Data types
	•	Primary keys
	•	Foreign keys
	•	Table constraints

Sample Data

All tables are populated with ten sample records, simulating a real movie ticket booking environment.

SQL Queries

The project includes a variety of SQL operations.

Simple Queries:
	•	INSERT
	•	UPDATE
	•	DELETE
	•	LIKE
	•	IN
	•	BETWEEN
	•	ORDER BY

Complex Queries:
	•	JOIN
	•	INNER JOIN
	•	UNION
	•	EXCEPT
	•	EXISTS
	•	Aggregation functions
	•	Grouping with HAVING
	•	Nested queries

Advanced Features:
	•	Trigger that updates snack categories
	•	View for listing theaters with specific capacity conditions


System Entities Overview

User

Stores general user information, linked to customers or employees.

Customer

Tracks customer status and is connected to ticket purchases.

Employee

Contains employee details such as role, hire date, years of experience, and assigned theater.

Movie

Includes movie title, category, rating, release date, and duration.

Ticket

Stores purchase details including seat, customer ID, and pricing.

Seat

Stores seat number, type, and availability.

Theater

Defines theater capacity, name, and location.

ShowTime

Links movies with seats and theaters and schedules viewing times.

Snacks

Stores snack items and their categories with customer associations.


Technologies Used
	•	SQL
	•	Database Modeling
	•	ERD Design
	•	Relational Schema Design
	•	Triggers and Views
	•	Query Optimization and Testing


How to Use This Repository
	1.	Download the PDF file containing the full project documentation.
	2.	Review the ERD, table schema, and SQL query outputs.
	3.	Recreate the structure in a SQL environment (MySQL, MariaDB, or PostgreSQL) if needed.


Skills Demonstrated

This project demonstrates proficiency in:
	•	Relational database design
	•	Query writing and data retrieval
	•	Advanced SQL operations
	•	Logical data modeling
	•	Use of triggers and views
	•	Handling relationships between multiple tables

Project Files
	•	Book_Movie_Tickets_Database_Project.pdf (full documentation)
