# 🇮🇹 Italian Recipe

This is a simple web application that allows users to **search for Italian recipes** using a public API. It is built using **HTML**, **CSS (with Bootstrap)**, and **JavaScript**. The project demonstrates how to fetch data from an external API and dynamically display it on a webpage.

---

## Features

*  Search Recipes: Type any keyword like "pizza", "pasta", or "salad" to fetch matching Italian recipes.
*  Search History: Stores the last 5 search terms in local storage and displays them for quick access.
*  LocalStorage Support: Remembers your last search and shows results even if you reload the page.
*  Clear Button: Instantly clear the search box and local storage with one click.
*  Responsive Design: Works on mobile and desktop screens using Bootstrap.

---

## Technologies Used

* HTML5 with Bootstrap
* CSS
* JavaScript 
* [Forkify API](https://forkify-api.herokuapp.com/) – for fetching real recipe data

---

## Example API Call

```js
fetch("https://forkify-api.herokuapp.com/api/search?q=pizza")
```
## Tasks Completed

*  Integrated external API using `fetch()`
*  Handled API errors (e.g. no results, bad query)
*  Displayed dynamic content based on search
*  Stored and retrieved data from localStorage
*  Built a responsive media with Bootstrap
*  Used linear gradient for Italian flag effect in navbar branding
