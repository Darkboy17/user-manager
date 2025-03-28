# Employee Management System

A React application for user management with authentication, built with:
- React.js
- Tailwind CSS
- React Router
- Axios
- React Hot Toast (for important notifications)

## Features

- User authentication (login/logout)
- Paginated user listing
- User search and filtering
- Edit/delete user functionality
- Responsive design

## Screenshots

### Authentication Screen (Level 1)
![auth](https://github.com/user-attachments/assets/5b2a7137-be5f-4da0-839b-76f25ed28111)

### User List Page (Level 2)
![user-list](https://github.com/user-attachments/assets/bf5a6534-0832-4c9b-afa8-70db1cc8f2f5)
![user-list-2](https://github.com/user-attachments/assets/aa62986d-0b8d-4edb-879d-fd6858527532)

### Edit, Delete Page (Level 3)
![edit-modal](https://github.com/user-attachments/assets/bc4308cc-4b91-4f74-9bae-6d3f3e4b537d)


## Prerequisites

- Node.js (v14 or higher)
- npm (v6 or higher) or yarn
- Git

## Installation

1. Clone the repository:
```bash
git clone https://github.com/Darkboy17/user-manager.git
cd user-manager
```

2. Install dependencies:
```bash
npm install
# or
yarn install
```

3. Create a .env file in the project root. Copy and Paste the following in your .env file:
```env
REACT_APP_API_BASE_URL=https://reqres.in/api
```

4. In the project directory, you can run:
```bash
npm start
```

Runs the app in development mode.
Open http://localhost:3000 to view it in your browser.

## Assumptions & Considerations

##### API: Uses the public ReqRes API with provided credentials:

      Email: *****

      Password: *****

##### Authentication:

    Token is stored in localStorage

    No refresh token implementation

    Session persists until logout or token expiration

##### Pagination:

    Server-side pagination for main list

    Client-side filtering during search

##### Environment Variables:

    Only REACT_APP_API_BASE_URL is required


##### Known Limitations

    The mock API doesn't persist changes (edits/deletes)

    No user registration feature (API limitation)

    Basic error handling with toast notifications
