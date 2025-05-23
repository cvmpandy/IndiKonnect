# IndiKonnect

**IndiKonnect** is a backend application built to support a marketplace platform. It facilitates seamless interactions between shopkeepers and customers, offering key features such as user authentication, product management, order processing, and file uploads.

## Features

* **User Authentication:** Secure registration and login functionality.
* **Product Management:** Create, read, update, and delete products.
* **Order Processing:** End-to-end order lifecycle handling.
* **File Uploads:** Upload and store images and documents.
* **Middleware Integration:** Custom middleware for streamlined request processing.

## Project Structure

```
IndiKonnect/
├── Controllers/        # Handles business logic
├── MiddleWare/         # Custom middleware functions
├── Models/             # Mongoose schemas
├── Routes/             # API routes
├── uploads/            # Uploaded files
├── sample/             # Sample data/scripts
├── .env.example        # Environment variable example
├── app.js              # Application entry point
├── package.json        # Dependency management
```

## Getting Started

### Prerequisites

* Node.js ([https://nodejs.org](https://nodejs.org))
* MongoDB ([https://mongodb.com](https://mongodb.com))

### Installation

```bash
git clone https://github.com/cvmpandy/IndiKonnect.git
cd IndiKonnect
npm install
```

### Configuration

1. Rename `.env.example` to `.env`:

   ```bash
   mv .env.example .env
   ```
2. Edit `.env` to include your database URI and other environment-specific values.

### Running the App

```bash
npm start
```

Server will start at `http://localhost:3000`.

## Technologies Used

* **Node.js** – Runtime environment
* **Express.js** – Web framework
* **MongoDB** – Database
* **Mongoose** – MongoDB ODM
* **Stripe** – Payment integration (included in `stripe_backup_code.txt`)




