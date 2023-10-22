

# Secret Website

Whisper is a web application built on the Express.js framework and powered by the Axios library for making API requests. It aims to provide users with a platform to share and discover secrets anonymously. The application fetches random secrets from an external API and displays them to users, maintaining the privacy of the secret sharers. Users can enjoy the excitement of reading secrets without knowing the identity of the secret holders.


## Tech Stack

Express.js: A fast and minimalist web framework for Node.js used for building the     server-side of the application.

Axios: A popular JavaScript library for making HTTP requests.

EJS: A templating engine used to dynamically render HTML pages with data (secrets and usernames) fetched from the API.

CSS: The project includes custom CSS styles to create an appealing and interactive user interface.

Google Fonts API: Utilized to load custom fonts, "Gloria Hallelujah" and "Titan One," to enhance the visual appearance of the application.
## Features

Anonymously Share Secrets: The Whisper application fetches random secrets from an external API, ensuring complete anonymity for secret holders. Users can safely share their secrets without revealing their identity.

Random Secret Display: Upon accessing the application, users are greeted with a random secret each time they refresh the page. The secrets are fetched from the external API and displayed in an attractive card layout.

User-Friendly Interface: The application features a minimalist and user-friendly interface. The custom CSS styles, background image, and animated card design enhance the overall user experience.

Secret and User Information: Each displayed secret is accompanied by the username of the person who shared it. Users can enjoy reading secrets and discovering the variety of experiences and thoughts people have shared.

Server-Side Rendering: The application uses server-side rendering with the EJS templating engine. The secrets and usernames fetched from the API are dynamically rendered into the HTML, creating a seamless user experience.

