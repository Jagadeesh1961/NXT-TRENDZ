In this project, let's build a **Nxt Trendz ** by applying the concepts we have learned till now.

### Project Explanation
1. **Correct Credentials Redirection**:
   - Upon successful authentication with the correct email and password combination, users are automatically redirected to the Home Route without any additional steps required from their end.

2. **Unauthenticated User Access Handling**:
   - If a user who hasn't logged in attempts to access protected routes like Home, Products, or Cart directly, the application recognizes the lack of authentication and redirects them to the Login Route.

3. **Authenticated User Access Permissions**:
   - Authenticated users, having successfully logged in, are granted access to navigate freely through the application's routes, including Home, Products, and Cart, without encountering any access restrictions.

4. **Logout Functionality**:
   - Clicking the Logout button triggers the termination of the user's current session, effectively logging them out of the application. Subsequently, users are redirected back to the Login Route, ensuring a secure end to their authenticated session.

5. **Products Section**:
   - Within the Products Section, users are presented with a curated list of available products, meticulously excluding any Prime deals or exclusive offers to maintain transparency in product offerings.

6. **Cart Section**:
   - In the Cart Section, users have the ability to add desired products to their cart and conveniently view the contents of their cart, enabling them to manage their shopping selections efficiently before proceeding to checkout.

<details>
- Prime User credentials

  ```text
   username: rahul
   password: rahul@2021
  ```

- Non-Prime User credentials

  ```text
   username: raja
   password: raja@2021
  ```

</details>

### Set Up Instructions

<details>
<summary>Click to view</summary>

- Download dependencies by running `npm install`
- Start up the app using `npm start`
</details>


