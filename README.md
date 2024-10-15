<p align="center">
  <img width="300" height="300" src="public/crunchycat-luna.gif" alt="Creatify AI Logo" />
</p>

# Movie App

This template should help get you started developing with Vue 3 in Vite.

## Recommended IDE Setup

- [VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin).

## Customize Configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Compile and Minify for Production

```sh
npm run build
```

## Project Structure

```
movie-app/
├── public/
│   ├── favicon.ico
│   └── index.html
├── src/
│   ├── assets/
│   ├── components/
│   │   ├── MovieCard.vue
│   │   ├── Pagination.vue
│   ├── router/
│   │   └── index.js
│   ├── store/
│   │   └── index.js
│   ├── views/
│   │   ├── Home.vue
│   │   ├── MovieDetail.vue
│   ├── App.vue
│   ├── main.js
├── package.json
└── vite.config.js
```

## Technologies Used

- **Vue 3**: The JavaScript framework used for building user interfaces.
- **Vite**: A build tool that provides a fast development environment.
- **Bootstrap 5**: A CSS framework for styling and responsive design.
- **Axios**: A promise-based HTTP client for making API requests.
- **Vue Router**: For routing and navigation.
- **Vuex**: For state management (if applicable).

## Features

- **Bootstrap 5 Pagination**: Implemented for efficient navigation through movie listings.
- **API Integration**: Fetch, search, and filter movies using API calls.
- **CRUD Operations**:
  - **Create**: Add new movies to the database.
  - **Read**: View movie listings with details.
  - **Update**: Modify existing movie information (add/edit functionality).
  - **Delete**: Remove movies from the database.

## API Endpoints

- `GET /api/movies`: Retrieve a list of movies.
- `GET /api/movies/:id`: Retrieve details of a specific movie.
- `POST /api/movies`: Add a new movie.
- `DELETE /api/movies/:id`: Delete a movie.

## Usage

1. **Start the Development Server**: Run `npm run dev` to start the server and access the application at `http://localhost:3000`.
2. **Add a New Movie**: Navigate to the form and input movie details.
3. **Search and Filter**: Use the search functionality to find movies by title or genre.
4. **Pagination**: Navigate through movie listings using pagination controls.

## Contribution

Contributions are welcome! Please feel free to submit a pull request or open an issue.

## License

This project is licensed under the MIT License.
