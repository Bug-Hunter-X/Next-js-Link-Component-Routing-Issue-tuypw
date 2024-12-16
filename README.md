# Next.js Link Component Routing Issue

This repository demonstrates a common issue encountered when using the Next.js Link component for client-side routing. The issue is that the link to the '/about' page does not work as expected. The About page does not render when navigating from the Home page.

## Bug Description
The Link component in the Home page should navigate to the About page upon clicking the link. However, the About page does not render. The browser URL might change to '/about', but the content remains the same. 

## Bug Reproduction
1. Clone this repository.
2. Run `npm install` to install the dependencies.
3. Run `npm run dev` to start the development server.
4. Navigate to the Home page (http://localhost:3000).
5. Click the link to the About page.
6. Observe that the About page does not render correctly.

## Solution
The solution involves making sure the pages are correctly structured and exported in the `pages` directory.  The issue is usually caused by improper file structure or missing exports.  The provided solution ensures that the pages are correctly defined and exported so that Next.js routing works correctly.  Check the `pages/about.js` and `pages/index.js` files for the fix.