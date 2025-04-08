Requirements

1. The application should run from the command line, accept the GitHub username as an argument, fetch the user’s recent activity using the GitHub API, and display it in the terminal. The user should be able to:

2. Provide the GitHub username as an argument when running the CLI.

   ``` github-activity <username>```

    Fetch the recent activity of the specified GitHub user using the GitHub API. You can use the following endpoint to fetch the user’s activity:

    #### https://api.github.com/users/<username>/events
    #### Example: https://api.github.com/users/paarth-sharma/events

    Sample display of the fetched activity in the terminal.

    Output:
    - Pushed 3 commits to paarth-sharma/developer-roadmap
    - Opened a new issue in paarth-sharma/developer-roadmap
    - Starred paarth-sharma/developer-roadmap
    - ...

3. You can learn more about the [GitHub API](https://docs.github.com/en/rest/activity/events?apiVersion=2022-11-28) here.
4. Handle errors gracefully, such as invalid usernames or API failures.
5. Do not use any external libraries or frameworks to fetch the GitHub activity.
