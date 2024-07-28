# Auth Credential Application

This is an authentication application built with Next.js, Mongoose, MongoDB, NextAuth, and Tailwind CSS. The application includes login and registration pages, allowing only registered users to log in. Upon successful login, the user's data is displayed on a dashboard in a card format.

## Tech Stack

- Next.js: React framework for server-side rendering and generating static websites.
- Mongoose: ODM (Object Data Modeling) library for MongoDB and Node.js.
- MongoDB: NoSQL database for storing user data.
- NextAuth: Authentication library for Next.js applications.
- Tailwind CSS: Utility-first CSS framework for styling.

## Features

- User Registration
- User Login
- Protected Routes
- User Dashboard displaying user data in a card

## Setup Process

Follow these steps to set up and run the application locally:

1. Clone the repository:
    ```bash
    git clone https://github.com/ranjangupta4590/Auth-credential.git
    cd auth-credential-app
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Create environment variables:

    Create a `.env.local` file in the root of your project and add the following environment variables:

    ```plaintext
    MONGODB_URI=your_mongodb_connection_string
    NEXTAUTH_URL=http://localhost:3000
    NEXTAUTH_SECRET=your_nextauth_secret
    ```

4. Set up MongoDB:

    Ensure you have a MongoDB instance running. You can use MongoDB Atlas or a local MongoDB server. Replace `your_mongodb_connection_string` in the `.env.local` file with your MongoDB connection string.

5. Run the development server:
    ```bash
    npm run dev
    ```

    The application should now be running on [http://localhost:3000](http://localhost:3000).

## Deployment

For deploying your application, you can use platforms like Vercel, which is the recommended platform for Next.js applications. Follow the instructions on the [Vercel documentation](https://vercel.com/docs) to deploy your application.

## Contributing

Feel free to open issues or submit pull requests for any improvements or bug fixes. Contributions are welcome!

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Happy coding!
