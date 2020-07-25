## Initialization
Project initialization.
### `yarn add .`

## API KEY
Edit with your own API KEY, you can register [HERE!](https://www.themoviedb.org/)<br>
file path: `src-> scripts -> globals -> config.js` 
```
const CONFIG = {
    KEY: 'YOUR_OWN_TMDB_API_KEY',
    BASE_URL: 'https://api.themoviedb.org/3/',
    BASE_IMAGE_URL: 'https://image.tmdb.org/t/p/w500/',
    DEFAULT_LANGUAGE: 'en-us',
    CACHE_NAME: new Date().toISOString(),
};

export default CONFIG;
```

## Available Scripts

In the project directory, you can run:

### `yarn run start-dev`

Runs the app in the development mode.<br />
Open [http://localhost:8080](http://localhost:8080) to view it in the browser.

The page will reload if you make edits and dont forget to clear cache first if you develop PWA before use this script in this project.<br />

### `yarn run build`

Builds the app for production to the `dist` folder.<br />
It correctly bundles the app in production mode and optimizes the build for the best performance.

