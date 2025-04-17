# Music API  

A simple API that provides JSON data of songs, artists, and albums for testing and building music-related projects.

## Overview
The Music API is a RESTful service designed to help developers manage and retrieve information about songs, artists, and albums. It is lightweight, fast, and scalable, making it ideal for prototyping and testing music-related applications.

## Features
- Retrieve detailed information about songs, artists, and albums.
- Perform CRUD (Create, Read, Update, Delete) operations on songs, artists, and albums.
- Search functionality for songs by title, artist, or album.
- Supports pagination and filtering for efficient data retrieval.

## Installation
To set up the Music API locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/Swadesh-c0de/music-api.git
    ```
2. Navigate to the project directory:
    ```bash
    cd music-api
    ```
3. Install the required dependencies:
    ```bash
    npm install
    ```

## Usage
1. Start the server:
    ```bash
    npm start
    ```
2. Access the API at:
    ```
    http://localhost:3000
    ```

## API Endpoints

### Songs
- `GET /songs`  
  Retrieve a list of all songs.
- `POST /songs`  
  Add a new song to the database.
- `GET /songs/:id`  
  Retrieve details of a specific song by its ID.
- `PUT /songs/:id`  
  Update information for a specific song by its ID.
- `DELETE /songs/:id`  
  Remove a specific song by its ID.

### Artists
- `GET /artists`  
  Retrieve a list of all artists.
- `POST /artists`  
  Add a new artist to the database.
- `GET /artists/:id`  
  Retrieve details of a specific artist by their ID.
- `PUT /artists/:id`  
  Update information for a specific artist by their ID.
- `DELETE /artists/:id`  
  Remove a specific artist by their ID.

### Albums
- `GET /albums`  
  Retrieve a list of all albums.
- `POST /albums`  
  Add a new album to the database.
- `GET /albums/:id`  
  Retrieve details of a specific album by its ID.
- `PUT /albums/:id`  
  Update information for a specific album by its ID.
- `DELETE /albums/:id`  
  Remove a specific album by its ID.