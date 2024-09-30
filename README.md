# Express.js Static File Server

This is a basic Express.js server that serves static files, such as an `index.html`, from a `www` directory. The server listens on port `3030` and serves the homepage when you visit `http://localhost:3030`.

## Features

- Serves static files (HTML, CSS, JavaScript, etc.) from the `www` folder.
- Responds with `index.html` when the root URL is accessed.

## Installation

1. Clone the repository.
2. Navigate to the project directory.
3. Install the necessary dependencies by running:

   ```bash
   npm install
   ```

## Usage

1. Ensure you have Node.js installed.

2. To start the server, run:

```bash
node index.js
```

3. Open your browser and navigate to `http://localhost:3030` to view the index.html page.

## Dependencies

Express: A minimalist web framework for Node.js to handle routing and static file serving.