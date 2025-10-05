# Learn Monolithic Architecture

This project is a demonstration of a **monolithic architecture** using ASP.NET Core.

## Overview

Monolithic architecture is a traditional software design where all components of an application are combined into a single, cohesive unit. In this project, you will find:

- **BL-layer**: Contains the business logic of the application.
- **DAL-layer**: Handles data access and database operations.
- **Learn-Monolithic-Architecture**: The main web API project, including controllers and application configuration.

All layers are part of one deployable application, making it easy to develop, test, and deploy, but scaling individual components independently is limited compared to microservices.

## Features

- Sample Web API with `WeatherForecastController`
- Layered structure for separation of concerns
- Simple setup for learning and experimentation

## Getting Started

1. Clone the repository
2. Open the solution in Visual Studio
3. Build and run the project
4. Access the API endpoints (e.g., `/WeatherForecast`)

## Learning Objectives

- Understand the structure of a monolithic application
- Learn how to separate business logic, data access, and presentation layers
- Explore deployment considerations for monolithic apps
