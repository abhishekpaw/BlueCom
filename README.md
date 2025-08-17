<h1>BlueCom eCommerce Shop With Admin Dashboard in Next.js and Node.js</h1>

<p><b>Bluecom eCommerce shop with admin dashboard in Next.js and Node.js</b> is a <b>free eCommerce store</b> developed using Next.js, Node.js and MySQL. The application is completely built from scratch(custom design) and completely responsive.
BlueCom is a modern online shop that specializes in selling all types of electronic products. The goal of the project is to create a modern web application <b>by following key stages in software engineering</b>. 

<h2>BlueCom – Key features</h2>
<p>BlueCom is Next.js and Node.js full-stack e-commerce website with a <b>free source code</b>. Our application comes with the fully functional <b>admin panel</b> and it is fully open-source. Our <b>free online store website</b> is completely responsive and manually tested. You can use our e-commerce project as a template or boilerplate for you next project. Our ecommerce shop template and Next.js ecommerce theme is fully customized for all your needs. It is available for <b>free download</b> and can be used as an ecommerce example for all your future projects. </p>
<h3>Is Next.js good for eCommerce?</h3>
<p>Next.js is currently one of the best ways for developing custom eCommerce solutions. It’s benefits include improved performance, SEO-friendliness, easy development and deployment, excellent developer experience, and the ability to handle versatile and scalable projects. By leveraging Next.js, developers can create compelling web applications that deliver an exceptional user experience while maintaining optimal performance.</p>


<h2>Step-by-step video instructions for running the app</h2>

<h2>Instructions</h2>

```
DATABASE_URL="mysql://username:password@localhost:3306/BlueCom"
NEXTAUTH_SECRET=12D16C923BA17672F89B18C1DB22A
NEXTAUTH_URL=http://localhost:3000
```

<p>7. After you do it, you need to create another .env file in the server folder and put the same DATABASE_URL you used in the previous .env file:</p>

```
DATABASE_URL="mysql://username:password@localhost:3306/BlueCom"
```

<p>8. Now you need to open your terminal of choice in the root folder of the project and write:</p>


```
npm install
```

<p>9. Now you need to navigate with the terminal in the server folder and install everything:</p>

```
cd server
npm install
```

<p>10. You will need to run the Prisma migration now. Make sure you are in the server folder and write:</p>

```
npx prisma migrate dev
```

<p>11. Next is to insert demo data. To do it you need to go to the server/utills folder and call insertDemoData.js:</p>

```
cd utills
node insertDemoData.js
```

<p>12. Now you can go back to the server folder and run the backend:</p>

```
cd ..
node app.js
```

<p>13. While your backend is running you need to open another terminal(don't stop the backend). In the second terminal, you need to make sure you are in your root project folder and write the following:</p>

```
npm run dev
```

<p>14. Open <a href="http://localhost:3000" target="_blank">http://localhost:3000</a> and see it live!</p>


<h2>Project screenshots</h2>

<h3>Home page</h3>

![BlueCom home page](./public/Hompage.png)
<h3>Shop page</h3>

![BlueCom shop page](./public/Shop%20Page.png)

<h3>Single product page</h3>

![BlueCom single product page](./public/SingleProductPage.png)
<h3>Register page</h3>

![BlueCom register page](./public/RegisterPage.png)

<h3>Login page</h3>

![BlueCom logic page](./public/LoginPage.png)

<h3>Search page</h3>

![BlueCom search page](./public/SearchPage.png)

<h3>Wishlist page</h3>

![BlueCom wishlist page](./public/wishlist.png)

<h3>Cart page</h3>

![BlueCom cart page](./public/CartPage.png)

<h3>Checkout page</h3>

![BlueCom checkout page](./public/CheckoutPage.png)

<h3>Admin dashboard - All orders page</h3>

![BlueCom admin orders page](./public/AdminOrders.png)

<h3>Admin dashboard - All products page</h3>

![BlueCom admin products page](./public/AdminProducts.png)

<h3>Admin dashboard - All categories page<h3>

![BlueCom admin categories page](./public/AdminCategories.png)

<h3>Admin dashboard - All users page</h3>

![BlueCom admin users page](./public/AdminUsers.png)
