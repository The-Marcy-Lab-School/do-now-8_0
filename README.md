# Lesson 8.0 Review

## Essential Questions
**1. What is the virtual DOM?**

**2. What is a component?**

**3. What is JSX?**

## Practice
Answer the following questions using the `index.html` and `app.js` files in this repo.

1. Pull in React, ReactDOM, and Babel from a CDN.

2. Without using JSX, create and render a React element. This element should render the words `Hello, World` as an `h1` HTML element. It should have a class of `"header"`.

3. Create a component `Header` that takes a prop, `title` an renders it as `h1` element.

4. Create a `Card` compenent based on this mock-up. 
   ![card mock-up](./card.png).

5. Create a `NavBar` component. It should display an unordered list of page links. These links should be generated from an array of objects. The objects should have the page title as a key and the page hyperlink as the value.
   ```javascript
   const pageData = [{"About": "/about"}, {"Our Team": "/team"}, {"Pricing": "/pricing"}];
   <NavBar pages={pageData} /`>

## 
<sup>[Review Lecture Video](https://zoom.us/rec/share/2NVVNe3O7UVLcI3UzWveBLUqJaDOX6a8gyYcqfEIyh2HLdlL5K1lVmQh8lTTKH2K)</sup>