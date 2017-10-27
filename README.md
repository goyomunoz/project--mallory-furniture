# Mallory Furniture

### Description
Mallory Furniture is a local vintage furniture retailer with a constantly changing selection. Their showroom has limited floor space so they initially wanted to build an ecommerce website to show all their inventory, including items in the warehouse.

They have obtained mockups for the site's design, and they have recently built a back-end API that contains their current listings. They now need to implement the front-end functionality. As a forward-looking company, they are interested in building the front-end in React to keep their views orderly and easily modifiable.

### Objectives

#### Learning Objectives
After completing this assignment you should be able to:
- Build a front-end React application from zero using `create-react-app`.
- Declare and style components in React.
- Use React methods to
  - Fetch data from a remote API and pass it as props.
  - Apply event listeners and manage state in a single React component.
  - Manage state across multiple React components.
- Use the React Router to determine what view is rendered and to navigate URLs.
- Query for data from an API in your React application.

### Project Requirements Summary
> **Make a React application that handles routes, fetches data, and renders components for Mallory Furniture's Front End.**

The site map should be structured like this:

```
/
/about
/terms
/all-products
/product/{product-id}
/category/{category-type}
```

The documentation for the API for the project is located here:
https://mallory-furniture-admin.now.sh/docs/

### Features Summary
- For the multi-listing components, there should be a way to  filter for items that are `onSale`.
- Shopping cart component
  - Component should appear/disappear
  - When a User clicks *Add To Cart* button for a single product

### Setup
1. Create React App
2. Download Images


### Mockups

- [Landing Page](mockups/mallory-landing.png)
- [Single Product Page](mockups/mallory-single.png)
- [Terms + Conditions Page](mockups/mallory-terms.png)

### Explorer Mode
- Highlight the current page in the Nav Menu


### Adventure Mode
- For the multi-listing components, a user should be able to filter for multiple parameters:
  - On Sale
  - Quality
  - Max Price
