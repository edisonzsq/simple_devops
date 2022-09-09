# Skills Union Event - The Why, What and How of DevOps

## Brief

This repository is used in a free workshop conducted by [Skills Union](www.skillsunion.com) to help the general public who are interested in career transition to become DevOps Engineer to gain hands on experience with DevOps CICD Pipeline.

## Platforms & Tools

- [Node](https://nodejs.org/en/)
- [GitHub](https://www.github.com)
- [Circle CI](https://www.circleci.com)
- [Heroku](https://www.heroku.com)

## Step by step guide

### Step 1 - Installation & Account Creations

1. Install [GIT](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
1. Create a [GitHub](https://github.com/) account
1. Create a [Circle CI](https://circleci.com/) account via GitHub skillsunion
1. Create a [Heroku](https://heroku.com/) account

### Step 2 - Fork repository

Fork [this](https://github.com/edisonzsq/simple_devops) repository. To verify fork successful, you should see the following URL:

- `https://github.com/<your username>/simple_devops`

### Step 3 - Configure Circle CI

Upon signing in with GitHub account, Circle CI will show a list of repositories belonged to you. Choose the `simple_devops` repository.

### Step 4 - Setup Heroku App

You are to create an App so that Circle CI can deploy the application to. You should name the App based on your preference (recommendation: `simple_devops_<your name>`). The App name is globally unique.

### Step 5 - Add Environmental Variables to Circle CI

There are two environment variables to be added in Circle CI. Namely, 

- HEROKU_API_KEY
- HEROKU_APP_NAME

The HEROKU_API_KEY can be found in your Heroku account settings.

The HEROKU_APP_NAME is the name of the App in Heroku that you created. Recommended: `simple_devops_<your name>`.

### Step 6 - Inspect the Pipeline Script

The pipeline script has been provided by the instructor and you can view the file [here](./.circleci/config.yml). This script resides in the GitHub repository that you have forked.

The instructor would explain what the script do in the session.