## Configuration of Environment Variables and Repository Secrets

To ensure the proper functioning of the GitHub Actions in this project, it is necessary to configure the following:

1. A secret with the name "TOKEN," and its value should be the token used for making requests to the GitHub API.

2. Four variables with the following values:
   - **Name:** "EMAIL"  
     **Value to be entered:** The user's email to use for performing various pushes.
   - **Name:** "NAME"  
     **Value to be entered:** The user's name to use for performing various pushes.
   - **Name:** "OWNER"  
     **Value to be entered:** The owner's name of the GitHub OSS project to be examined.
   - **Name:** "REPO"  
     **Value to be entered:** The name of the repository of the GitHub OSS project to be examined.

### Configuration of Environment Variables via the GitHub Web Interface:

1. Go to the main page of your repository on GitHub.

2. At the top of the repository, click on the "Settings" tab.

3. In the left sidebar, click on "Secrets and variables" and select "Actions."

4. Proceed to the "Variables" section. Click on "New repository variable" to add a new variable.

5. Here, you can define environment variables that will be available for your GitHub Actions workflows. You can add, modify, or delete them directly from this page.

### Configuration of Repository Secrets via the GitHub Web Interface:

1. Go to the main page of your repository on GitHub.

2. At the top of the repository, click on the "Settings" tab.

3. In the left sidebar, click on "Secrets and variables" and select "Actions."

4. In this section, you can define repository secrets. Click on "New repository secret" to add a new secret.

5. Enter the name of the secret and its value, then click "Add secret" to confirm.

