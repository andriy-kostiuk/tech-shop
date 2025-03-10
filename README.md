# TechShop

[TechShop (Link)](https://andriy-kostiuk.github.io/tech-shop/)

This is a fully functional e-commerce application built with React and TypeScript. It includes features such as product catalog, product details page, shopping cart, favorites, and more.

## Features

- **Product Catalog**: Browse products by category (Phones, Tablets, Accessories).
- **Product Details Page**: View detailed information for each product.
- **Shopping Cart**: Add/remove products to/from the cart, modify quantities, and see the total price.
- **Favorites**: Add products to your favorites and view them on the favorites page.
- **Search**: Search for products by name.
- **Sort & Pagination**: Sort products by various criteria (Newest, Alphabetically, Cheapest) and paginate the product list.
- **Responsive Design**: The app is responsive and works well on various screen sizes.
- **Sticky Header and Footer**: The app features a sticky header with a logo, navigation links, and cart/favorites icons, along with a footer containing links to the GitHub repository.

## Code Style

- **TypeScript**: All code is written in TypeScript for type safety and maintainability.
- **React**: The app follows the latest React patterns, using functional components with hooks (e.g., `useState`, `useEffect`, `useContext`).
- **CSS Modules**: Styles for each component are written using CSS Modules (`ComponentName.module.scss`), providing scoped styling to avoid conflicts.
- **Responsive Design**: The layout is fully responsive using CSS Flexbox and Grid. Media queries are used to adjust styles for various screen sizes.
- **Folder Structure**: The project follows a modular folder structure, with components grouped by feature (e.g., HomePage, CartPage). Shared components and utilities are placed in the `shared` folder.
- **Code Quality**: The project follows best practices for clean and readable code. Functions are kept small and focused on a single responsibility.

## Features Implementation

### 1. Home Page

- **Product Catalog**: Displays a list of products from the API, sorted by category and price.
- **Picture Slider**: Automatically switches between product images every 5 seconds and allows users to manually navigate.
- **Categories**: Links to different product categories (Phones, Tablets, Accessories).

### 2. Product Pages

- **Phones, Tablets, Accessories**: Each category page fetches and displays products based on the selected category.
- **Sorting and Pagination**: Products can be sorted by age, title, or price. Pagination controls allow users to navigate through large product lists.
- **Search**: Implements a search bar to filter products based on the query. The search value is saved in the URL.

### 3. Product Details Page

- **Product Information**: Shows detailed information about a product, including available colors, capacities, and technical specifications.
- **Suggested Products**: Displays related products based on the current product.

### 4. Shopping Cart

- **Add to Cart**: Users can add products to their cart and view them on the Cart page.
- **Remove Items**: Items can be removed from the cart.
- **Quantity Control**: The quantity of each product in the cart can be updated.
- **Local Storage**: Cart items are saved to localStorage and loaded on page load.

### 5. Favorites

- **Add to Favorites**: Users can add products to their favorites and view them on the Favorites page.
- **Heart Icon**: The heart icon changes color when the product is added to favorites.
- **Local Storage**: Favorite items are saved to localStorage and loaded on page load.

### 6. NotFoundPage

- **Page Not Found**: Displays a message for unknown URLs with a link back to the HomePage.

### 7. Footer and Header

- **Sticky Header**: Includes the logo, navigation links, and cart/favorites icons.
- **Footer**: Includes a link to the GitHub repository and a "Back to top" button.

### 8. Advanced Features

- **Color Theme Switching**: Allows the user to switch between different themes.

## Getting Started

### 1. To run this project locally, ensure you have the following installed:

The project has been tested with **Node.js v16.x** and **npm v7.x or higher**.  
 Run the following commands to verify your versions:

```bash
 # Check Node.js version
 node -v

 # Check npm version
 npm -v
```

### 2. Clone the repository

```bash
 git clone https://github.com/andriy-kostiuk/phone_catalog.git
```

### 3. Navigate to the project directory

```bash
 cd phone_catalog
```

### 4. Install dependencies

```bash
 npm install
```

### 5. Start the development server

```bash
  npm start
```

## Additional Scripts

- #### Format Code

  ```bash
  npm run format
  ```

- #### Lint Code

  ```bash
  npm run lint
  ```

- #### Build Production Version

  ```bash
  npm run build
  ```
