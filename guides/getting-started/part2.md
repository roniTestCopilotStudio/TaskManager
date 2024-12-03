# Getting Started - Part 2

In this part, we will cover the initial configuration of TaskMaster.

## Environment Variables

Create a `.env` file in the root directory and add the following variables:

```env
DATABASE_URL=your_database_url
JWT_SECRET=your_jwt_secret
```

## Database Setup
Run the following command to initialize the database:
```bash
npm run db:init
```
