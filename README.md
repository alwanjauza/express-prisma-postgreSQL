# Course CRUD

This projec only for making a basic CRUD using express, prisma, and PostgreSQL.

## Prerequisites

Before running this project, ensure you have the following installed:

- Node.js
- Prisma
- PostgreSQL
- npm or yarn

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/alwanjauza/express-prisma-postgreSQL.git
   ```

2. **Navigate to the project directory:**

   ```bash
   cd express-prisma-postgreSQL
   ```

3. **Install dependencies:**

   ```bash
   npm install
   ```

4. **Setup the PostgreSQL database and update the `.env` file with the database URL.**

5. **Run database migrations:**

   ```bash
   npx prisma migrate dev --name init
   ```

6. **Start the server:**

   ```bash
   npm run dev
   ```

## Project Structure

The project follows a layered architecture with the following structure:

- `src/`
  - `controllers/`: Controllers handling request/response logic.
  - `services/`: Business logic layer.
  - `routes/`: Route definitions.
  - `models/`: Prisma schema and generated database models.
  - `app.js`: Express application setup.
  - `server.js`: Server initialization.

## Endpoints

- **GET /users**: Get all users.
- **GET /users/:id**: Get a user by ID.
- **POST /users**: Create a new user.
- **PUT /users/:id**: Update a user.
- **DELETE /users/:id**: Delete a user.

_(Update with other endpoints and descriptions as needed)_

## Testing

You can test the endpoints using tools like Postman or curl. See [Testing the API](#testing-the-api) section in the README for sample requests.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any bugs, feature requests, or suggestions.

## License

This project is licensed under the [MIT License](LICENSE).
