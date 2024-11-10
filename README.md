# Kanban Board Auth with JWT

## Description

When you build an app that requires authentication to access its resources, you must take steps to protect sensitive user information. For example, you should not store user passwords in your database. A solution for this problem is to set up logic to protect the user information by storing an encrypted version of the password. In this app, authentication using JSON Web Tokens is demonstrated. A user would be able to login to the app without storing their password to the app's database. Instead, a token will be dynamically created and stored in local storage to grant access to the app's resources.

## Installation

After cloning the repository, do the following to test the functionality of the app locally. 

1) Install dependencies: run npm install.
2) Start the database: login to postgress.
3) Run seeds: run npm run seed.
4) Start the app: npm run start.

## Usage

The JWT authentication will prevent unauthorized users from accessing the app's resources if their username and password information is incorrect. The screenshots below illustrate the result of using correct login credentials.

![Landing Page](/assets/kanban-board-jwt-landing-page.png)

![Login Page](/assets/kanban-board-jwt-login-page.png)

![Krazy Kanban Board Main Page](/assets/kanban-board-jwt-krazy-kanban-board-page.png)

## Credits

This app utilized some start code to which the authentication logic were added.

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## How to Contribute

- Direct Request on GitHub [https://github.com/Theon87/kanban-board-jwt].

[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg)](code_of_conduct.md)