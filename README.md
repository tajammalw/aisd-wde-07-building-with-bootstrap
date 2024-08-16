
# WDE06 Building a Landing Page with Bootstrap

![Screenshot of the project](./assets/complete.png)

## Description
This assignment will guide you in creating a responsive landing page for a code-themed ice cream shop using Bootstrap. You'll learn how to set up your HTML and CSS files, include the necessary Bootstrap components, and build a simple yet professional-looking page step-by-step.

This activity is meant to be done solo. You may ask your instructor or associate for help as needed.

## Prerequisites

- Basic knowledge of HTML and CSS

## Project Structure

```
bootstrap_landing_page_project
│   index.html
│   styles.css
```

## Steps

1. **Create HTML and CSS Files:**

   - Create a new HTML file named `index.html`.
   - Create a new CSS file named `styles.css`.

2. **Add Boilerplate Code to HTML:**

   - Open `index.html` and add the following boilerplate code:

   ```html
   <!DOCTYPE html>
   <html lang="en">
     <head>
       <meta charset="UTF-8" />
       <meta name="viewport" content="width=device-width, initial-scale=1.0" />
       <title>Byte-Scream Ice Cream Shop</title>
       <link rel="stylesheet" href="styles.css" />
     </head>
     <body>
       <!-- Your content goes here -->
     </body>
   </html>
   ```

3. **Include Bootstrap CDN:**

   - In the `<head>` section of your `index.html`, include the Bootstrap CDN to use Bootstrap components and styles:

   ```html
   <link
     href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css"
     rel="stylesheet"
   />
   ```

   Your `<head>` section should now look like this:

   ```html
   <head>
     <meta charset="UTF-8" />
     <meta name="viewport" content="width=device-width, initial-scale=1.0" />
     <title>Byte-Scream Ice Cream Shop</title>
     <link
       href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css"
       rel="stylesheet"
     />
     <link rel="stylesheet" href="styles.css" />
   </head>
   ```

4. **Add a Navbar:**

   - In `index.html`, between the `<body>` tags, add the following Bootstrap navbar code:

   ```html
   <nav class="navbar navbar-expand-lg navbar-light bg-light">
     <div class="container-fluid">
       <a class="navbar-brand" href="#">Byte-Scream</a>
       <button
         class="navbar-toggler"
         type="button"
         data-bs-toggle="collapse"
         data-bs-target="#navbarNav"
         aria-controls="navbarNav"
         aria-expanded="false"
         aria-label="Toggle navigation"
       >
         <span class="navbar-toggler-icon"></span>
       </button>
       <div class="collapse navbar-collapse" id="navbarNav">
         <ul class="navbar-nav">
           <li class="nav-item">
             <a class="nav-link active" aria-current="page" href="#">Home</a>
           </li>
           <li class="nav-item">
             <a class="nav-link" href="#">Flavors</a>
           </li>
           <li class="nav-item">
             <a class="nav-link" href="#">About Us</a>
           </li>
           <li class="nav-item">
             <a class="nav-link" href="#">Contact</a>
           </li>
         </ul>
       </div>
     </div>
   </nav>
   ```

5. **Add a Hero Section:**

   - Below the navbar, add a hero section to introduce the shop:

   ```html
   <div class="container mt-5">
     <div class="jumbotron text-center bg-warning text-dark p-5 rounded">
       <h1>Welcome to Byte-Scream</h1>
       <p>Code Your Way to the Best Ice Cream in Town</p>
       <a class="btn btn-primary btn-lg" href="#" role="button">Order Now</a>
     </div>
   </div>
   ```

6. **Add a Flavors Section:**

   - Add a section to display some of the shop's featured flavors:

   ```html
   <div class="container my-5">
     <h2 class="text-center mb-4">Our Featured Flavors</h2>
     <div class="row">
       <div class="col-md-4">
         <div class="card">
           <img
             src="./assets/vanilla.jpg"
             class="card-img-top"
             alt="Vanilla Byte"
           />
           <div class="card-body">
             <h5 class="card-title">Vanilla Byte</h5>
             <p class="card-text">A classic vanilla flavor with a byte of sweetness.</p>
             <a href="#" class="btn btn-primary">Order Now</a>
           </div>
         </div>
       </div>
       <div class="col-md-4">
         <div class="card">
           <img
             src="./assets/chocolate.jpg"
             class="card-img-top"
             alt="Chocolate Chip Code"
           />
           <div class="card-body">
             <h5 class="card-title">Chocolate Chip Code</h5>
             <p class="card-text">Chocolate chips embedded in rich, creamy goodness.</p>
             <a href="#" class="btn btn-primary">Order Now</a>
           </div>
         </div>
       </div>
       <div class="col-md-4">
         <div class="card">
           <img
             src="https://via.placeholder.com/150"
             class="card-img-top"
             alt="Strawberry Script"
           />
           <div class="card-body">
             <h5 class="card-title">Strawberry Script</h5>
             <p class="card-text">A fruity favorite for code enthusiasts.</p>
             <a href="#" class="btn btn-primary">Order Now</a>
           </div>
         </div>
       </div>
     </div>
   </div>
   ```

7. **Add a Footer:**

   - Finally, add a footer to complete the landing page:

   ```html
   <footer class="bg-light text-center py-4">
     <p>&copy; 2024 Byte-Scream Ice Cream Shop. All rights reserved.</p>
   </footer>
   ```

8. **Customize with Additional CSS:**

   - Open `styles.css` and add custom styles to enhance the appearance:

   ```css
   body {
     font-family: Arial, sans-serif;
   }

   .navbar-brand {
     font-weight: bold;
   }

   .jumbotron {
     background-color: #ffc107;
   }

   .card-title {
     font-weight: bold;
   }

   footer {
     background-color: #f8f9fa;
   }
   ```

9. **Testing Your Page:**

   - Open your `index.html` in a browser to view the landing page.
   - Resize the browser window to see how the page adapts to different screen sizes.

## AI Assistance

If you have any questions or need further explanations, feel free to ask the AI for help. Here are some examples of what you might ask:

- "How do I use Bootstrap components to create a layout?"
- "How can I customize Bootstrap styles?"

Good luck, and enjoy building your Bootstrap landing page!
