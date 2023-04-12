# ZihKing Webstore
Beta: https://zihking.netlify.app

## Table of Contents

- [Description](#description)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Scripts](#scripts)
- [Author](#author)
- [License](#license)
- [Backend Dependencies](#backend-dependencies)
- [DevDependencies](#devdependencies)
- [Frontend Dependencies](#frontend-dependencies)
- [Changelog](#changelog)
- [Conclusion](#conclusion)

## Description

The `zihking-webstore-server` is a Node.js backend server for the Zihking Webstore application. It provides RESTful APIs for handling various functionalities, such as authentication, file uploads, email sending, and interacting with external services like AWS S3, AWS CloudFront, and PayPal Checkout.

The `zihking-webstore-client` is a React frontend application for the Zihking Webstore. It allows users to browse and preview products (music instrumentals), add licenses to their cart, and place orders.

## Prerequisites

Before running the `zihking-webstore-server` and `zihking-webstore-client`, you need to have the following installed:

- Node.js (v12 or higher)
- npm (v6 or higher)
- MongoDB (v5 or higher)

## Installation

To install and set up the `zihking-webstore-server` and `zihking-webstore-client`, follow these steps:

1. Clone the repository for `zihking-webstore-server` and `zihking-webstore-client` to your local machine.
2. Navigate to the root directory of each project in your terminal.
3. Run `npm install` to install the dependencies for both projects.
4. Create a `.env` file in the root directory of `zihking-webstore-server` project, and configure the environment variables as per your requirements. You can use the `.env.example` file as a reference.
5. Run `npm run start` to start the server using nodemon for development in the `zihking-webstore-server` project.
6. Run `npm start` to start the React development server for the `zihking-webstore-client` project.

## Scripts

The following scripts are available in the `zihking-webstore-server`:

- `npm test`: Runs the tests for the server (currently not implemented).
- `npm start`: Starts the server using nodemon for development.
- `npm run build`: Installs the project dependencies.

The following scripts are available in the `zihking-webstore-client`:

- `npm test`: Runs the tests for the client (currently not implemented).
- `npm start`: Starts the React development server.

## Author

Sharlmagne Henry

## License

This project is licensed under the ISC License. See the [LICENSE](/LICENSE.md) file for details.

## Backend Dependencies

The following dependencies are used in the `zihking-webstore-server`:

- `@aws-sdk/client-cloudfront`: ^3.282.0
- `@aws-sdk/client-s3`: ^3.282.0
- `@paypal/checkout-server-sdk`: ^1.0.3
- `bcryptjs`: ^2.4.3
- `body-parser`: ^1.20.2
- `cors`: ^2.8.5
- `dotenv`: ^16.0.3
- `ejs`: ^3.1.9
- `express`: ^4.18.2
- `ffmpeg`: ^0.0.4
- `fluent-ffmpeg`: ^2.1.2
- `get-audio-duration`: ^3.1.1
- `image-size`: ^1.0.2
- `jsonwebtoken`: ^9.0.0
- `lamejs`: ^1.2

## DevDependencies

The following devDependencies are used in the `zihking-webstore-server`:

- `nodemon`: ^2.0.20

## Frontend Dependencies

The following dependencies are used in the `zihking-webstore-client`:

- `@mui/material`: ^5.4.0
- `@mui/icons-material`: ^5.4.0
- `@mui/lab`: ^5.4.0
- `@mui/styles`: ^5.4.0
- `@mui/types`: ^5.4.0
- `axios`: ^0.26.0
- `formik`: ^2.2.9
- `lodash`: ^4.17.21
- `react`: ^17.0.2
- `react-dom`: ^17.0.2
- `react-hook-form`: ^7.20.6
- `react-paypal-button-v2`: ^2.8.0
- `react-redux`: ^7.2.6
- `react-router-dom`: ^5.3.0
- `redux`: ^4.1.2
- `redux-thunk`: ^2.4.1
- `yup`: ^0.32.9

## Changelog

##### v1.0.0 (2023-04-12)

- Initial release of the ZihKing Webstore application.
- Added server-side functionalities for authentication, file uploads, email sending, and interacting with external services like AWS S3, AWS CloudFront, and PayPal Checkout.
- Added frontend functionalities for product listing, product details, shopping cart, user authentication, and checkout.
- Implemented server-side and client-side validation for input data.
- Added error handling and logging for robustness and security.
- Integrated with external APIs for payment processing and file storage.
- Added documentation for installation, usage, and contributing to the project.

## Conclusion

I hope the updated documentation provides the complete information you were looking for. If you have any further questions or need additional assistance, please let me know!