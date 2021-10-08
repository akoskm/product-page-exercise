
Backend API: https://nacapi.com/p/Scrambler-Cyan.

Documentation: https://nacapi.com/p/Scrambler-Cyan#documentation.

<details>
  <summary>What if this is already expired</summary>

  Create a new dummy backend on: https://nacapi.com/ with the following dataset.

  ```json
  {
    "products": [
      {
        "name": "EasyApi",
        "Description": "Easy API Makes it simple for developers to start side projects",
        "Pricing": "Free for early adopters",
        "Price": 10,
        "Discount": 2
      },
      {
        "name": "Email API",
        "Description": "Email API, makes it easy to send emails with a single route",
        "Pricing": "Coming soon",
        "Price": 30,
        "Discount": 10
      },
      {
        "name": "Authenticated API",
        "Description": "Authenticated API Is a way to protect your data while keeping it easy to connect to your api",
        "Pricing": "Coming soon",
        "Price": 15,
        "Discount": 5
      }
    ]
  }
  ```
</details>


## Goal
Create the Admin Panel of an Online Store.

## Expectations
Using the provided API to create a prototype of an admin panel where the store owner can manage digital subscriptions.
The prototype should contain pages for:

 - listing all products
 - editing products (Price, Discount, Price label, etc)

Identify two features that would be useful to have in the admin panel and implement them.
Explain why they would be useful.

## Deliverable
 - a source code in a GitHub repository.
 - the application hosted on Heroku (free tier).

### Use:
 - https://blueprintjs.com/ for the UI
 - create-react-app to initialize the project

### Not use:
  - state management libraries, Redux, Flow, etc

### Would be cool to use:
  - React Hooks