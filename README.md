# Just Another Text Editor (JATE)

JATE (Just Another Text Editor) is a versatile and powerful text editor that runs in your browser. This application allows you to create and store notes or code snippets with or without an internet connection, ensuring reliability and accessibility for your content.

## Table of Contents
- [User Story](#user-story)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Deployment](#deployment)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## User Story

```md
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use

## Features

- **Offline Functionality:** Create and edit notes or code snippets even when you're offline, and the changes will be saved locally.
- **IndexedDB Storage:** Utilizes IndexedDB to store data, providing redundancy and ensuring your content is accessible even if the browser doesn't support certain options.
- **Progressive Web App (PWA):** The application meets the PWA criteria, allowing for installation and reliable performance.
- **Service Worker:** A registered service worker enables offline access and pre-caching of static assets.
- **Webpack Build:** The application uses Webpack for bundling JavaScript files and generating HTML, service worker, and manifest files.

## Getting Started

### Prerequisites

Ensure you have the following installed before running the application:

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/)

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/jate.git
    ```

2. Navigate to the project directory:

    ```bash
    cd jate
    ```

3. Install dependencies:

    ```bash
    npm install
    ```

## Usage

1. Run the application:

    ```bash
    npm run start
    ```

2. Open your browser and visit [http://localhost:3001](http://localhost:3001) to access the text editor.

3. Create, edit, and save your content. The application will utilize IndexedDB for data persistence.

4. Enjoy the offline functionality and the ability to install the application as a Progressive Web App.

## Deployment

Follow the [Render Deployment Guide](https://coding-boot-camp.github.io/full-stack/render/render-deployment-guide) to deploy the application to Render.

## Technologies Used

- [Express.js](https://expressjs.com/) - Web application framework for Node.js.
- [Webpack](https://webpack.js.org/) - Module bundler for JavaScript applications.
- [IndexedDB](https://developer.mozilla.org/en-US/docs/Web/API/IndexedDB_API) - Web browser storage solution for larger amounts of structured data.
- [Workbox](https://developers.google.com/web/tools/workbox) - JavaScript library for adding offline support to web apps.
- [idb](https://www.npmjs.com/package/idb) - Lightweight wrapper around the IndexedDB API.

## Contributing

Contributions are welcome! Feel free to submit issues or pull requests.

## License

This project is licensed under the [ISC License](LICENSE).

## Acknowledgements

- Special thanks to the contributors of the packages used in this project.
- Inspired by the needs of developers for a reliable offline text editor.
