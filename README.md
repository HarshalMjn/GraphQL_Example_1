# GraphQL Server Example

This project demonstrates a simple GraphQL server using Apollo Server and Express. The server provides an API to query book information including title, author, publication year, genres, description, and cover image.

## Table of Contents

- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [GraphQL Schema](#graphql-schema)
- [License](#license)

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- Node.js 
- npm 

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/graphql-server-example.git
    ```
2. Change to the project directory:
    ```sh
    cd graphql-server-example
    ```
3. Install the dependencies:
    ```sh
    npm install
    ```

### Usage

1. Start the server:
    ```sh
    node index.mjs
    ```
2. The server will be running at:
    ```
    http://localhost:4000
    ```

### GraphQL Schema

The GraphQL schema defines the structure of the API. The schema for this project includes a `Book` type and a `Query` type.

#### Book Type

```graphql
type Book {
  id: Int
  title: String
  author: String
  publication_year: Int
  genre: [String]
  description: String
  cover_image: String
}







