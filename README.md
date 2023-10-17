# Crypto Asset Search Tool 🪙

Create an easy and useful tool to quickly find detailed information about any crypto asset.

![Mobula Logo](https://i.imgur.com/YI8M066.png)

---

## Table of Contents 📖

- [Features](#features-)
- [Usage](#usage-)
- [Quick Guide](#quick-guide-)
- [API Reference](#api-reference-)

---

## Features ✨

- **Fast Search:** Look up any crypto asset in Mobula's database quickly.
- **Detailed Asset Info:** Get important details and history about the assets you find.
- **User-friendly:** Easy to use, even if you're new to crypto.

---

## Usage 💡

Perfect for both newbies and pros in the crypto world. Use the tool to search for a crypto asset's name or details, and get all the info you need in return.

---

## Quick Guide 🚀

### Building with Node.js:

1. **Start a Node.js Project:**
   - Get Node.js and npm.
   - Begin a new project:
     ```
     npm init -y
     ```

2. **Make the Search Work:**
   - Get data from the Mobula API based on what users look for.
   - Think about using tools like Express.js for the backend and maybe React or Vue for showing things on the screen.

3. **Show the Search Results:**
   - Make a results page that gives users all the asset info they want.
   - If there are lots of search results, maybe add pages or filters to make it easier to see.

4. **Make it Nice for Users:**
   - Remember what users search for most and show them results faster next time.
   - Add a dropdown with suggestions for popular or recent searches.

---

## API Reference 🌐

This tool mainly uses the Mobula API's search endpoint:

- **Search Asset:** 
  - **Method:** GET
  - **Endpoint:** `https://api.app-mobula.com/api/1/search`
  - **Details:** Use this to find a specific asset in Mobula's big database.

More about this can be found in the [Mobula API guide](https://developer.mobula.fi/reference/searchcryptodata).

---

Built to make crypto searching simple, using the [Mobula API](https://developer.mobula.fi/).
