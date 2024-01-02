# Auth with NextAuth.js v5

This is a sample project that demonstrates how to implement authentication using NextAuth.js v5.

## Features

- User registration
- User login
- Password reset
- OAuth authentication (Google, Facebook, etc.)
- Email verification

## Prerequisites

Before running this project, make sure you have the following installed:

- Node.js (v14 or higher)
- MongoDB (or any other supported database)

## Getting Started

1. Clone the repository:

```bash
git clone https://github.com/your-username/auth-with-nextauth-v5.git
```

2. Install dependencies:

```bash
cd auth-with-nextauth-v5
npm install
```

3. Configure environment variables:

Create a `.env.local` file in the root directory and add the following variables:

```plaintext
DATABASE_URL=your-mongodb-connection-string
NEXTAUTH_URL=http://localhost:3000
```

4. Run the project:

```bash
npm run dev
```

5. Open your browser and navigate to `http://localhost:3000` to see the application.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
