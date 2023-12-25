# Airbnb Clone with Next.js 13


## Description

This is a full-stack Airbnb clone built with Next.js 13. It includes features such as user authentication, property listing creation, reservation functionality, and more. The application utilizes React, Tailwind CSS, Prisma, MongoDB, NextAuth for authentication, and Cloudinary for image storage.

## Table of Contents

- [Airbnb Clone with Next.js 13](#airbnb-clone-with-nextjs-13)
  - [Description](#description)
  - [Table of Contents](#table-of-contents)
  - [Demo](#demo)
  - [Installation](#installation)
  - [Features](#features)
  - [Usage](#usage)

## Demo

For a live demo, you can visit [Demo Link](https://project-clone-nine.vercel.app/).

## Installation

1. Clone the repository.
   ```bash
   git clone https://github.com/your-username/airbnb-clone.git


2. Install dependencies.
    ```bash
    cd airbnb-clone
    npm install
    ```


3. Set up the environment variables.
   1. create a **.env** file
   2. copy & paste the following
   ```bash
    DATABASE_URL="DB_URL"
    NEXTAUTH_SECRET="********"

    GITHUB_CLIENT_ID="********"
    GITHUB_CLIENT_SECRET="********"

    GOOGLE_CLIENT_ID="********"
    GOOGLE_CLIENT_SECRET="********"

    NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME="********"
    ```
    3. Update the values in **.env** with your configuration.


4. Run the development server.
    ```bash
    npm run dev
    ```

5. The application will be available at http://localhost:3000.

## Features

- User authentication with NextAuth.
- Property listing creation with multi-step form.
- Social login with **Google** and **Github**.
- Listing reservation functionality.
- Trips, reservations, favorites, and properties screens.
- Integration with **Cloudinary** for image storage.

## Usage
- Register a new account or log in using existing credentials.
- Explore available listings and filter based on preferences.
- Create your own property listing with the step-by-step form.
- Reserve properties you are interested in.
- View and manage your trips, reservations, and favorite properties.





