# appwrite-auth-poc

## Description:

The app serves as a Log In or Sign Up page where users can either log in with their existing credentials or register for a new account. It employs a minimalist and modern user interface design, utilizing Tailwind CSS for styling.

## Features:

- User Authentication: Users can log in using their email and password. If the user doesn't have an account, they can register for a new one.
Error Handling: Error messages are displayed to the user for various scenarios, such as incorrect password, user not found, or duplicate account during registration.

- Loading State: A loading state is implemented to provide visual feedback to the user during actions like logging in or registering. While loading, a watch animation is displayed over the form, and the form is blurred to indicate that it's disabled.

- Responsive Design: The app is designed to be responsive, ensuring a consistent user experience across different devices and screen sizes.
Technologies Used:

- React: A JavaScript library for building user interfaces.
- Tailwind CSS: A utility-first CSS framework used for styling components.
- JavaScript: The primary programming language for implementing app logic and interactions.

## Purpose:
The app serves as a basic authentication system, commonly used in web applications to control access to protected resources. It provides users with a straightforward and visually appealing interface to authenticate and manage their accounts.

## Future Improvements:
Potential improvements could include adding additional authentication methods (e.g., OAuth), implementing more robust error handling, integrating form validation, and enhancing the user experience with animations and transitions. Additionally, security measures such as password hashing and session management could be implemented to improve overall security.

# Third-Party Vendor
At this time, I'm building an app with [AppWrite](https://cloud.appwrite.io/)

Appwrite is an open-source, self-hosted platform for building and managing web and mobile applications. It provides a set of easy-to-use APIs for various backend services commonly required in app development, including user authentication, database management, file storage, and more.

# Run project
You will need to install all the dependencies from the package.json. Please run the following command:

```
npm install ci
```

# Initialize app "LocalHost"
```
npm run dev
```

# Add your local variables within an .env file
```
NEXT_PUBLIC_PROJECT_ID= ["Open AppWrite to find this end-point"]
NEXT_PUBLIC_APPWRITE_ENDPOINT= ["Open AppWrite to find this end-point"]

```
![Screenshot 2024-02-23 at 12 00 19 AM](https://github.com/hvaandres/appwrite-auth-poc/assets/26829975/e90e66f2-4e0b-48cb-aec8-2c7701414d41)
