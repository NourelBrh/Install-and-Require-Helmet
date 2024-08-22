# Install-and-Require-Helmet
const express = require('express');
const helmet = require('helmet');
const app = express();

// Ajoutez votre code ici
app.use(helmet());

// Code existant ou fourni
app.get('/', (req, res) => {
  res.send('Hello, world!');
});

module.exports = app;
