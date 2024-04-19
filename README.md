## Essentials of GitHub Actions learning pathway demo repository

This repository contains the core web application files and configuration you'll need to follow along through the [Essentials of automated application deployment with GitHub Actions & GitHub Pages](https://resources.github.com/learn/pathways/automation/essentials/automated-application-deployment-with-github-actions-and-pages/) module.

To follow along with the step-by-step instructions in the Essentials module, you will need to create a copy of this repository by doing the following:
1. Click **Use this template** above the file list and select **Create a new repository**.
2. Use the **Owner** dropdown menu to select the account you want to own the repository. 
3. Name your repository `actions-learning-pathway` and add a simple description to make it easier to identify later.
4. Set the default visibility for the repo to public, as private repositories use Actions minutes, while public repositories can use GitHub-hosted runners for free.

Click Create repository from template and we’re ready to build our first Actions workflow!



If you have arrived here from the [Intermediate automation strategies with GitHub Actions](https://resources.github.com/learn/pathways/automation/intermediate/workflow-automation-with-github-actions/) module without following the first module, copy the contents of the `/demo-files` folder into the `.github/workflows` folder to follow along.

An Actions workflow is a configurable automated process made up of one or more jobs defined using YAML. Workflows follow a specific structure and are stored in the .github/workflows directory of your repository. There are two ways to create a new workflow—either by creating a new YAML file in the .github/workflows directory, or from the Actions tab of your repository. The first way is simple and straightforward, but the second has some advantages, so let’s do that for now:

Navigate to the “Actions” tab of your repository and click New workflow.

Take a look around and you’ll see that GitHub has suggested a variety of starter workflows based on the languages of the code in your repository. Since the actions-learning-pathway repository has JavaScript and Node.js files, suggestions are primarily for those languages. 
