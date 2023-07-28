# Github Profiles Search Application

This is a Github Profiles Search application built with HTML, CSS, JavaScript, and the Axios library. The application allows users to search for a specific GitHub profile and fetches relevant information, such as the user's name, bio, number of followers, number of followings, repositories, and the last 10 repositories. If there is no user available under the name searched, the application will display a message stating "No profile with this username."

![Demo](./asset/Demo.gif)

## How to Use

Follow these steps to use the Github Profiles Search Application:

1. Clone the repository to your local machine or download the source code as a ZIP file.

2. Open the `index.html` file in your preferred web browser.

3. Enter the GitHub username you want to search for in the input field provided on the application's page.

4. Click the "Search" button to initiate the search.

5. The application will fetch the GitHub profile information and display it in a card format.

## Dependencies

The application utilizes the following libraries:

Axios: Axios is used to handle HTTP requests to the GitHub API and fetch the user's profile data.
It simplifies making asynchronous JavaScript calls by providing an easy-to-use interface over XMLHttpRequest, Fetch
It also simplifies error handling by providing an easy-to-use interface with built-in retry
, timeout, and cancel features that can be configured based on specific needs of each request.

## Features

- User-friendly interface for easy navigation.
- Real-time search functionality.
- Display of essential user details in a card format.
  \*Handles cases where the user is not found with a helpful error message.

## How the Application Works

The Github Profiles Search Application uses the GitHub API to fetch user data based on the username entered by the user. When the user submits a search, the application performs an asynchronous HTTP request using Axios to the GitHub API endpoint for user details.

If the user is found, the application populates the card with relevant details, including the user's name, bio, follower count, following count, and repositories (displaying the last 10 repositories).

In case the user is not found, the application displays an error message stating "No profile with this username."

## Contributions

Contributions to the Github Profiles Search Application are welcome! If you find any issues or want to add new features, feel free to create a pull request with your changes.

Thank you for using the Github Profiles Search Application! Happy searching!
