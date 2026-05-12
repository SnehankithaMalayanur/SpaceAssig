# SpaceAssig (Flight Search Application)

A modern web application built with the Angular framework designed to search and manage flight or space travel data. This project demonstrates modular architecture, service-based data handling, and component-driven UI.

## Features

* **Flight Search/Listing:** Browse and search through available travel options.
* **Service-Oriented Architecture:** Uses Angular Services (`flights.service.ts`) to manage data and API logic.
* **Routing:** Implements `app-routing.module.ts` for seamless navigation between views.
* **Reactive Design:** A responsive interface built with Angular's component-based CSS and HTML.

## Tech Stack

* **Framework:** [Angular](https://angular.io/)
* **Language:** TypeScript
* **Styling:** CSS3
* **Build Tool:** Angular CLI

## Prerequisites

Before you begin, ensure you have the following installed:
* [Node.js](https://nodejs.org/) (Latest LTS version)
* [Angular CLI](https://angular.io/cli) (`npm install -g @angular/cli`)

## Installation & Local Setup

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/SnehankithaMalayanur/SpaceAssig.git](https://github.com/SnehankithaMalayanur/SpaceAssig.git)
    cd SpaceAssig
    ```

2.  **Install dependencies:**
    ```bash
    npm install
    ```

3.  **Run the development server:**
    ```bash
    ng serve
    ```

4.  **View the app:**
    Open your browser and navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Project Structure

* `src/app/`: Contains the core logic:
    * `flights.service.ts`: Handles data fetching and business logic for flight information.
    * `app-routing.module.ts`: Defines the application's navigation paths.
    * `app.component.*`: The root component of the application.
* `angular.json`: CLI configuration for inheritance and build targets.
* `src/assets/`: Static files like images and icons.

## Running Tests

To execute unit tests via [Karma](https://karma-runner.github.io):
```bash
ng test
