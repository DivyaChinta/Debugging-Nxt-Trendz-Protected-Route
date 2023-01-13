In this project, let's fix the **Nxt Trendz Protected Route** by applying the concepts we have learned till now.

### Refer to the image below:

<br/>
<div style="text-align: center;">
    <img src="https://assets.ccbp.in/frontend/content/react-js/nxt-trendz-protected-route-output.gif" alt="nxt trendz protected route output" style="max-width:70%;box-shadow:0 2.8px 2.2px rgba(0, 0, 0, 0.12)">
</div>
<br/>

### Set Up Instructions

<details>
<summary>Click to view</summary>

- Download dependencies by running `npm install`
- Start up the app using `npm start`
</details>

### Completion Instructions

<details>
<summary>Functionality to be fixed</summary>
<br/>

Fix the given code to have the following functionality

- When an unauthenticated user tries to access the Home Route, Products Route or Cart Route, then the page should be navigated to the Login Route using the protected route
- When an authenticated user tries to access the Home Route, Products Route or Cart Route, then the page should be navigated to the respective route using the protected route
</details>

### Quick Tips

<details>
<summary>Click to view</summary>
<br>

- There are `8` bugs to be fixed to achieve the functionality and the UI that is expected

</details>

### Important Note

<details>
<summary>Click to view</summary>

<br/>

**The following instructions are required for the tests to pass**

- User credentials

  ```text
   username: rahul
   password: rahul@2021
  ```

</details>

> ### _Things to Keep in Mind_
>
> - All components you implement should go in the `src/components` directory.
> - Don't change the component folder names as those are the files being imported into the tests.
> - **Do not remove the pre-filled code**
> - Want to quickly review some of the concepts you’ve been learning? Take a look at the Cheat Sheets.
