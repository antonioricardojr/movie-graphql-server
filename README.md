# Movie GraphQL Server

This is a GraphQL server application that retrieves movies from an external API. It allows users to query for movie information using GraphQL.

## Features

- Fetch movie details by ID
- List all movies
- List featured movies
- Search for movies by genre

## Technologies Used

- Node.js
- Apollo Server
- GraphQL
- node-fetch

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm (v6 or higher)

### Installation

1. Clone the repository:

    ```sh
    git clone https://github.com/your-username/movie-graphql-server.git
    cd movie-graphql-server
    ```

2. Install dependencies:

    ```sh
    npm install
    ```

### Configuration

1. Create a `.env` file in the root directory and add your API URL:

    ```env
    API_URL=https://codeflix-api-sand.vercel.app/
    ```

### Running the Server

To start the GraphQL server, run:

```sh
npm start
