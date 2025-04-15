# RESTful API Submission

## Features
- CRUD operations for users
- TypeScript + Express
- Jest unit tests

## Setup
1. Clone repo
2. Install dependencies:
   ```bash
   npm install
   ```
3. Compile .ts files:
   ```bash
   npx tsc
   ```
5. Start dev server:
   ```bash
   node app.js
   ```

## Testing
### Automated Tests
```bash
npm test
```

## API Endpoints
| Method | Endpoint       | Description      |
|--------|----------------|------------------|
| GET    | /api/users     | Get all users    |
| POST   | /api/users     | Create new user  |
| GET    | /api/users/ID  | Get user details |
| PUT    | /api/users/ID  | Update a user    |
| DELETE | /api/users/ID  | Delete a user    |
