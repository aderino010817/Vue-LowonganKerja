// Import library axios
const axios = require('axios');

// Define endpoint URL
const endpoint = '/pt-job-posts/no-auth';

// Make GET request to endpoint using axios
axios.get(endpoint)
  .then(response => {
    console.log(response.data);
  })
  .catch(error => {
    console.error(error);
  });