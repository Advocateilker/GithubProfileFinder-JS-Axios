# GithubProfileFinder-JS-Axios

![GitHub Profile Card Screen](screen.gif)

This project allows you to view GitHub user profiles and displays their top-level information and most popular repositories. It is created using JavaScript, HTML, and CSS, and communicates with the GitHub API using Axios.

## How to Use

1. Clone the project to your computer or download it as a ZIP file.
2. Open the `index.html` file in your web browser.
3. Enter your GitHub username or the username of another user in the "Search Github UserName" field.
4. Click the "Submit" button.
5. View the user's profile card and their top 6 repositories.

## Technologies and Libraries Used

- JavaScript: The project uses JavaScript to fetch user data from GitHub and create the profile card.
- HTML and CSS: HTML and CSS are used to create the user interface.
- Axios: Axios is used to make HTTP requests to the GitHub API.

## How It Works

This project fetches user data from the GitHub API by communicating with it and displays the data in an HTML card. Below is a summary of the main functions within the project:

- `getUser(username)`: Retrieves data of a GitHub user with the entered username and creates a profile card.
- `createUserCard(user)`: Creates a profile card using the user's data.
- `createErrorCard(msg)`: In case of an error, creates an error card and displays an appropriate message to the user.
- `getRepos(username)`: Fetches a user's repositories from the GitHub API and adds links to the top 6 repositories at the bottom of the card.
- `addReposToCard(repos)`: Adds the repositories to the card and displays each as a link.


