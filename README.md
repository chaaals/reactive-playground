# Responsive Product View Component

## Overview

This is a mini project contributed to <strong>Dev-Geeks</strong> repo in Hacktoberfest 2022 🔥. It's a responsive and reusable product view component that can be easily used in your ecommerce projects.

## What's in store for you?

- Responsive Layout

  - Desktop
    <img src='/public/readme-images/desktop-layout.png' alt='desktop-layout'/>
  - Mobile
    <img src='/public/readme-images/mobile-layout.png' alt='mobile-layout'/>
  - Mobile v2
    <img src='/public/readme-images/mobile-layout-v2.png' alt='mobile-layout-v2'/>

- Basic functionalities

  - Selecting a variant of a product
    <img src='/public/readme-images/functionality-1.png' alt='functionality-1'/>
  - Increment/decrement item count
    <img src='/public/readme-images/functionality-2.png' alt='functionality-2'/>

- Easy to use
  - All you need to do is pass an object containing all the properties of your product. Feel free to view and edit the sample schema in the models folder.
  ```
    <Product product={data} />
  ```

## Anatomy of the Product View Component

The component has 4 files: component files, view file, hook file, and index file.

- Component Files (product-view.component.jsx and product-view.css)

  - These files house the product view component its self. From the JSX structure to styling.

- Hook File (product-view.hook.jsx)

  - This file contains all of the logic needed in the product view component. In essence, incrementing/decrementing the product count, selecting a variant and adding to cart or buying the product.

- View File (product-view.view.jsx)

  - This file is contains the UI and renders based on state and responds based on the actions provided.

- Index File (index.jsx)

  - This file is the bridge for both the component and logic.

Developed with 💖 by Charles Ching 😎
