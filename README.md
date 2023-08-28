# password-check

# Express Authentication Example

## Overview
This repository contains a simple Express.js project that demonstrates basic authentication using middleware. Users can access a secret page if they enter the correct password.

## Tech Stack and Frameworks Used
- [Node.js](https://nodejs.org/)
- [Express.js](https://expressjs.com/)
- [body-parser](https://www.npmjs.com/package/body-parser)

## Project Description
This project sets up an Express server that listens on port 3000. Users can access the root route ("/") to see an HTML form where they can enter a password. If the entered password matches the authorized password, the user is granted access to a secret page. Otherwise, they are redirected to the root page.

## Installation
1. Make sure you have [Node.js](https://nodejs.org/) installed on your machine.
2. Clone this repository.
3. Navigate to the project directory in your terminal.
4. Run the following command to install project dependencies:
   ```bash
   npm install