# School Management API

Node.js APIs for managing school data, built with Express.js and MySQL.

## Setup
1. Install Node.js and MySQL.
2. Clone the repository: `git clone https://github.com/Ronyghosh27/school-management-api.git`
3. Install dependencies: `npm install`
4. Update MySQL credentials in `server.js`.
5. Run the application: `npm start`

## APIs
- **POST /addSchool**: Add a new school.
  - Payload: `{ "name": "School Name", "address": "Address", "latitude": 39.7817, "longitude": -89.6501 }`
- **GET /listSchools?latitude=X&longitude=Y**: List schools sorted by proximity.

## Testing
- Import the Postman collection (`School_Management_APIs.postman_collection.json`) to test the APIs.