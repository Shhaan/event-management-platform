# 🎟️ Event Booking & Registration Platform

## Overview

This is a full-stack event management application built with Django
(backend) and Next.js (frontend).\
The platform allows users to create events and register attendees with
proper email validation.

Backend functionality is tested using pytest to ensure reliability and
correctness.

------------------------------------------------------------------------

## Features

-   Create and manage events
-   Attendee registration system
-   Email validation during registration
-   REST API communication between backend and frontend
-   Backend unit testing using pytest
-   Structured and scalable project architecture

------------------------------------------------------------------------

## Architecture

### Backend

-   Django
-   Django ORM
-   REST APIs
-   Pytest for automated testing

### Frontend

-   Next.js
-   React

### Database

-   PostgreSQL / SQLite (based on environment)

------------------------------------------------------------------------

## Application Flow

1.  Event is created through the system
2.  Attendees register using their email
3.  Email validation ensures correct format and integrity
4.  Event and attendee data stored in database
5.  Backend tests validate core logic and API behavior

------------------------------------------------------------------------

## Testing

The backend is tested using pytest, covering: - Event creation logic -
Attendee registration - Email validation - API responses

------------------------------------------------------------------------

## Purpose

This project was built to: - Practice full-stack development with Django
and Next.js - Implement clean API architecture - Apply backend testing
using pytest - Design a scalable event registration system

------------------------------------------------------------------------

## Future Improvements

-   Email confirmation system
-   Event capacity management
-   Role-based access control
-   Admin dashboard
-   Payment integration for paid events

------------------------------------------------------------------------

## Status

Core event creation and attendee registration functionality completed.
Testing implemented for backend services.
