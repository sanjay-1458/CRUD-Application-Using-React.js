### CRUD App with React.js and Redux Toolkit

This repository contains a CRUD (Create, Read, Update, Delete) application built using React.js and Redux Toolkit. The application interacts with a RESTful API to perform the CRUD operations.

## Features

- Create new records
- Read existing records
- Update existing records
- Delete records
- Search records

## Technologies Used

- React.js
- Redux Toolkit
- RESTful API

## Prerequisites

- Node.js
- npm or yarn package manager

## Getting Started

To get a local copy of this project up and running, follow these steps:

1. Clone the repository to your local machine using the following command:

   ```bash
   git clone https://github.com/sanjay-1458/CRUD-Application-Using-React.js.git
   ```

2. Navigate to the project's directory:

   ```bash
   cd your-repo
   ```

3. Install the dependencies:

   ```bash
   npm install
   # or
   yarn install
   ```

4. Set up the RESTful API:

   - Replace the API endpoint in `src/api/api.js` with the URL of your RESTful API.
   - Make sure your API supports the necessary CRUD operations (create, read, update, delete) for the resource you are working with.

5. Start the development server:

   ```bash
   npm start
   # or
   yarn start
   ```

6. Open your browser and visit [http://localhost:3000](http://localhost:3000) to see the application running.

## Usage

- The application provides a user interface to perform CRUD operations on the specified resource.
- To create a new record, click on the "Add" button and fill in the required fields in the form.
- To read an existing record, click on the "View" button for the corresponding entry.
- To update an existing record, click on the "Edit" button for the corresponding entry and make the necessary changes in the form.
- To delete a record, click on the "Delete" button for the corresponding entry.

## Folder Structure

The project has the following folder structure:

- `src`: Contains the source code of the application.
  - `actions`: Redux actions and action creators.
  - `api`: API configuration and endpoints.
  - `components`: Reusable components used throughout the application.
  - `reducers`: Redux reducers and state slices.
  - `screens`: React components representing different screens/pages of the application.
  - `store`: Redux store configuration.
  - `utils`: Utility functions.
  - `App.js`: The root component of the application.
  - `index.js`: Entry point of the application.
- `public`: Contains the public assets and HTML template.
