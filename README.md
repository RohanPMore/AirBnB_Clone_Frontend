# AirBnB Clone Frontend

This project is a frontend clone of Airbnb, built using Django, Django Rest Framework, and Next.js. This project was developed following step-by-step tutorials from [Code with Stein](https://codewithstein.com) and his YouTube channel **Code with Stein**.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Features

- User authentication and authorization
- Property listings with detailed information
- Search functionality for properties
- Booking system for users
- Responsive design for various devices

## Technologies Used

- **Frontend**: Next.js, React, Tailwind CSS
- **Backend**: Django, Django Rest Framework
- **Database**: [Specify your database, e.g., PostgreSQL, MySQL]
- **Authentication**: [Specify your authentication method, e.g., JWT, OAuth]

## Getting Started

To get a local copy of the project up and running, follow these steps:

### Prerequisites

- Node.js and npm installed
- Python and pip installed
- [Specify any other prerequisites]

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/RohanPMore/AirBnB_Clone_Frontend.git
   cd AirBnB_Clone_Frontend
   ```

2. **Install frontend dependencies:**

   ```bash
   npm install
   ```

3. **Set up environment variables:**

   Create a `.env.local` file in the root directory and add the following variables:

   ```env
   NEXT_PUBLIC_API_URL=http://localhost:8000/api
   ```

   Adjust the `NEXT_PUBLIC_API_URL` to point to your backend API.

4. **Start the development server:**

   ```bash
   npm run dev
   ```

   The application will be available at `http://localhost:3000`.

## Project Structure

```
AirBnB_Clone_Frontend/
├── app/                # Main application components
├── public/             # Public assets
├── .env.prod           # Environment variables for production
├── .gitignore          # Git ignore file
├── README.md           # Project README
├── next.config.mjs     # Next.js configuration
├── package-lock.json   # Package lock file
├── package.json        # Package configuration
├── postcss.config.js   # PostCSS configuration
├── tailwind.config.ts  # Tailwind CSS configuration
└── tsconfig.json       # TypeScript configuration
```

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add YourFeature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
