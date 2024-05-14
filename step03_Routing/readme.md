# Routing

The skeleton of every application is routing.

## How to create Next.js Route.

There are two main ways to create routes in Next.js, depending on your project structure and preferences:

### Src Directory and app folder:

This is the most common approach and leverages Next.js's file-system based routing. Here's how it works:

- Create a folder: Inside your project's pages directory, create a new folder for each route you want to define.
- Add a page.js (or .jsx, .tsx) file: Within the newly created folder, add a file named page.js (or .jsx or .tsx). This file acts as the React component for that specific route.
- File Name Convention: The name of the folder reflects the URL segment. For example, a folder named about creates a route accessible at /about.
- Nested Routes: To create nested routes, simply create nested folders within the pages directory. The URL path reflects this hierarchy (e.g., /products/electronics).

```ts
pages / index.js; // Home page
about / about.js; // About page
contact / contact.js; // Contact page
```
[Routing & Nexted Routes](https://youtu.be/Hi2yZcXWTpw?si=4JgLh6C-Bjsvut7O)
[Route Groups](https://youtu.be/wa19jz-OTcE?si=U3P2qlLY9_t56yUX)
