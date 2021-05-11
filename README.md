# Authentication application

This project uses the following technologies: 

- React for frontend
- Express and Node for the backend
- MongoDB for the database
- Redux for state management between React components



## Configuration

Make sure to add your own `MONGOURI` in `config/keys.js`.

```javascript
module.exports = {
  mongoURI: "YOUR_MONGO_URI_HERE",
  secretOrKey: "secret"
};
```

## Quick Start

```
npm install

// Run client & server with concurrently
npm run dev

// Server runs on http://localhost:5000 and client on http://localhost:3000
```
