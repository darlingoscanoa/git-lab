# First GitHub-lab
## This is to show how issue creation works
### In this git-lab we are going to:

1. Create a New Repository: Log in to your GitHub account. Click on the '+' icon on the top right corner and select 'New repository'. Name the repository 'git-lab' and initialize it with a README file.
2. Create an Issue: Go to the 'Issues' tab in your new repository and click on 'New Issue'. Give it a title (e.g., "Add project description") and a brief description. Click on 'Submit new issue'.
3. Manage the Issue: Go back to the 'Issues' tab. You will see the issue you just created. Click on it, add a comment if needed, and close the issue once it's resolved (i.e., after you add the project description to the README file).
4. Create a GitHub Action: Go to the 'Actions' tab in your repository and click on 'New workflow'. You can set up a workflow yourself or choose a template. For this lab, let's choose the 'Simple workflow' template.
5. Configure the Action: In the 'Edit new file' tab, you will see a YAML file that defines the workflow. This file is divided into three sections: name, on, and jobs. The name is the name of your workflow. The on section defines when your workflow will run (e.g., on every push and pull_request). The jobs section defines what your workflow will do. For this lab, let's keep it simple. Your workflow will just print a "Hello, World!" message. Replace the steps section with the following:
