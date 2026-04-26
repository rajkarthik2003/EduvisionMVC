# EduVision MVC

Academic management platform built with ASP.NET Core MVC, Entity Framework Core, role-based access control, analytics dashboards, and live deployment on Azure.

## Project Summary

EduVision is a full-stack education platform built to model how a real academic system behaves across multiple user roles. The application combines relational data modeling, authentication, dashboard workflows, analytics, and deployment concerns in one product-style codebase.

## What The Public Repository Demonstrates

- ASP.NET Core MVC application structure
- Entity Framework Core with environment-based database configuration
- role-based authentication and authorization
- dashboard and analytics endpoints
- production-aware deployment and migration handling
- live hosting on Azure App Service

## Main Capabilities

- Admin, Instructor, and Student role flows
- Academic entities such as students, courses, departments, enrollments, and advising relationships
- Chart-driven analytics for academic monitoring
- Development and production database handling
- Deployment-oriented diagnostics and migration support

## Technical Highlights

- `Program.cs` shows environment-based provider selection between SQLite and SQL Server
- production startup includes migration and seed handling
- chart endpoints and dashboard diagnostics are exposed directly in the application
- the project demonstrates backend delivery beyond standard CRUD scaffolding

## Live Demo

[eduvisionmvc.azurewebsites.net](https://eduvisionmvc.azurewebsites.net/)

## Why This Project Matters

This repository is one of my strongest signals for backend engineering breadth because it combines:

- domain modeling
- authentication
- data workflows
- analytics delivery
- cloud deployment

It complements my ML and LLM work by showing I can also build and operate application-facing systems.
