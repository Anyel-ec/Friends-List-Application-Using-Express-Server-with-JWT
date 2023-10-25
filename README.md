# Friends Management Project

This is an example project that demonstrates how to create a simple friend management application using Node.js, Express, and JSON Web Tokens (JWT) for user authentication. The app allows users to register, log in, and manage a friends list.

## Requirements

Make sure you have Node.js installed on your system before running the application.

## Facility

1. Clone this repository to your local machine:

```bash
git clone https://github.com/Anyel-ec/Friends-List-Application-Using-Express-Server-with-JWT
```

2. Navigate to the project directory:

```bash
cd Friends-List-Application-Using-Express-Server-with-JWT
```

3. Install the dependencies using npm:

```bash
npm install
```

## Setting

Before running the application, you must configure some environment variables in a `.env` file. Create a `.env` file in the project root and define the following variables:

```
SECRET_KEY=your_secret_key
PORT=5000
```

- `SECRET_KEY`: This is the secret key used to sign and verify JWT tokens.
- `PORT`: Port on which the Express server will run.

## Use

1. Run the application:

```bash
npm start
```

2. The application will be available at `http://localhost:5000`.

3. To use the friends API, you must first register and log in to the application using the `/register` and `/login` paths.

4. Once authenticated, you can use the following routes:

- `GET /friends`: Gets the list of friends.
- `GET /friends/:email`: Gets a friend's email details.
- `POST /friends`: Add a new friend.
- `PUT /friends/:email`: Update a friend's information.
- `DELETE /friends/:email`: Delete a friend.

## Contribute

If you would like to contribute to this project, please follow these steps:

1. Create a branch for your contribution:

```bash
git checkout -b your-branch
```

2. Make your changes and make sure everything works correctly.

3. Make a commit of your changes:

```bash
git commit -m "Description of your changes"
```

4. Upload your changes to your repository:

```bash
git push origin your-branch
```

5. Create a pull request on GitHub and describe your changes in detail.

## License

This project is licensed under the MIT License. You can find more information in the LICENSE file.

Enjoy managing your friends!
