# Sending Emails with AWS SES and Nodemailer in Node.js

This project demonstrates how to send an email using **AWS SES** (Simple Email Service) and **Node.js** with the help of the **Nodemailer**.

## Prerequisites

Before running the project, make sure you have the following:

- **AWS Account**: Set up and configured with SES.
- **Verified Email Addresses**: In AWS SES, ensure that both the sender and recipient email addresses are verified (if you're using SES in the sandbox environment).
- **AWS Access Keys**: You need to have an **AWS Access Key** and **Secret Access Key** to interact with AWS SES.

## Installation

Follow these steps to set up and run the project:

### 1. Install Dependencies

First, you need to install dependencies. In your project directory, run the following command to install the required dependencies:

```bash
npm install
```

### 2. Environment variables

Configure your environment variables using the `.env.example` file.

1. Copy the contents from `.env.example` to a new `.env` file.
2. Update the `.env` file with the appropriate values.


### 3. Run the `index.js` File
```bash
node index.js
```

## You can experiment with configurations based on the specific use case. For more details, refer to the documentation of Nodemon and AWS SES.
