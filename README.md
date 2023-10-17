# Crypto Asset Search Tool 🪙

Find and learn about any crypto asset, just like you'd use Google to search the web.

![Mobula Logo](https://i.imgur.com/YI8M066.png)

---

## Table of Contents 📖

- [Features](#features-)
- [Usage](#usage-)
- [Quick Guide](#quick-guide-)
- [API Reference](#api-reference-)

---

## Features ✨

- **Fast Search:** Efficiently query Mobula's database.
- **Detailed Asset Info:** Access a wealth of information about the assets.
- **User-friendly Interface:** Designed for ease of use, irrespective of your crypto expertise.

---

## Usage 💡

Ideal for both crypto novices and veterans. Use this tool to search for a crypto asset's name or details and receive comprehensive data in return.

---

## Quick Guide 🚀

### Building with [Node.js](https://nodejs.org/):

1. **Initiate a Node.js Project:**
   - Download and install [Node.js](https://nodejs.org/) and npm.
   - Start a new project:
     ```bash
     npm init -y
     ```

2. **Set Up the Search Functionality:**
   - Fetch data from the Mobula API based on user queries.
   - Consider using frameworks like [Express.js](https://expressjs.com/) for the backend and options like [React](https://reactjs.org/) or [Vue.js](https://vuejs.org/) for the frontend.

3. **Display the Search Outcomes:**
   - Design a results page presenting the comprehensive asset information.
   - For extensive search results, incorporate pagination or filtering options for better user experience.

4. **Enhance User Interactivity:**
   - Cache frequent user searches to facilitate faster subsequent lookups.
   - Integrate a dropdown for popular or recent search suggestions.

---

## API Reference 🌐

Primarily, this tool utilizes the Search endpoint of the Mobula API:

- **Search Asset:** 
  - **Method:** GET
  - **Endpoint:** `https://api.app-mobula.com/api/1/search`
  - **Details:** This endpoint facilitates the search for specific assets within Mobula's database.

For further details, delve into the [Mobula API documentation](https://developer.mobula.fi/reference/searchcryptodata).

---

Designed with ❤️ making the world of crypto assets more accessible, powered by [Mobula API](https://developer.mobula.fi/)
