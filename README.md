# Gaming Product Manager

This is a full-stack gaming product management application designed for indie game developers, publishers, and digital storefronts. The application consists of a Flutter frontend and a Node.js backend, providing a seamless experience for managing a curated list of video games.

## Features

- **Home Screen**: Displays a list of games with options to view details, edit, or delete.
- **Add Game Screen**: A form to add new games to the database.
- **Game Detail Screen**: Shows detailed information about a selected game.
- **Edit Game Screen**: Allows users to edit existing game details.

## Tech Stack

- **Frontend**: Flutter, Dart, Provider for state management
- **Backend**: Node.js, Express, MongoDB

## Installation

### Frontend

1. Navigate to the `frontend` directory.
2. Run `flutter pub get` to install dependencies.
3. Use `flutter run` to start the application.

### Backend

1. Navigate to the `backend` directory.
2. Run `npm install` to install dependencies.
3. Start the server with `node src/app.js`.

### Environment Variables

Create a `.env` file in the `backend` directory and add the following:

```
MONGODB_URI=mongodb://localhost:27017/gaming_db
PORT=5000
```

## API Endpoints

- `GET /api/games`: Retrieve all games
- `GET /api/games/:id`: Retrieve a game by ID
- `POST /api/games`: Add a new game
- `PUT /api/games/:id`: Update an existing game
- `DELETE /api/games/:id`: Delete a game

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any enhancements or bug fixes.

## License

This project is licensed under the MIT License. See the LICENSE file for details.