# Thread Clone Project

A Thread clone web application built using Next.js, Tailwind CSS, TypeScript, MongoDB, and Clerk for authentication.

## Table of Contents

- [Description](#description)
- [Features](#features)
- [Technologies](#technologies)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Description

The Thread Clone Project is a full-stack web application that aims to replicate all the functionalities and even more and better of the newly launched software by Meta called "Threads". Users can post messages, comment and reply comments, follow other users, create communities and invite others, and engage in discussions even better than Threads itself.

## Features

- User registration and authentication using Clerk.
- Post and read threads.
- Follow and unfollow other users.
- Like and reply to threads.
- comment and reply comment
- Search for threads and users.
- create communities

## Technologies

The project is built using the following technologies:

- Next.js: A React framework for server-side rendering and building web applications.
- Tailwind CSS: A utility-first CSS framework for rapidly styling the application.
- TypeScript: A typed superset of JavaScript, providing better tooling and code consistency.
- MongoDB: A NoSQL database for storing and retrieving thread data.
- Clerk: An authentication service for handling user registration and authentication.

## Getting Started

To run this project locally, follow the steps below:

### Installation

1. Clone the repository:

git clone https://github.com/your-username/thread-clone.git

2. Change into the project directory:

cd thread-clone

3. Install the dependencies:

npm install

### Configuration

Before running the application, you need to set up some configurations:

1. Create a Clerk account and get your API keys.
2. Set up your MongoDB connection and get the connection string.

Create a `.env.local` file in the root directory and add the following environment variables:

CLERK_API_KEY=your_clerk_api_key
MONGODB_URI=your_mongodb_connection_string

### Usage

Start the development server:

npm run dev

Open your browser and navigate to [http://localhost:3000](http://localhost:3000) to access the application.

## Contributing

Contributions are welcome! If you want to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch with a descriptive name: `git checkout -b feature-name`.
3. Make your changes and commit them: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature-name`.
5. Create a pull request with a detailed description of your changes.

## License

This project is licensed under the [MIT License](LICENSE).
