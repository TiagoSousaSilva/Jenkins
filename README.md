# Jenkins

The Jenkins project utilized GitHub integration to create a series of pipelines for various tasks. The pipelines were designed to automate different processes and tasks. Blue Ocean, a powerful Jenkins plugin, played a central role in enhancing the user experience and simplifying the creation of Continuous Integration/Continuous Deployment (CI/CD) pipelines.

The first pipeline involved accessing a Java code from a public GitHub repository to print "Hello." Similarly, the second pipeline used a Java code to execute the "ls -l" command in GitHub.

For the third pipeline, a GitHub token was generated to grant Jenkins full access to the GitHub account. This allowed Jenkins to commit and push code to the repository. Using the Blue Ocean plugin, Jenkins could then retrieve and execute the code, printing "Hello" and performing other actions.

The fourth and final pipeline, also using the Blue Ocean plugin, interacted with the localhost. It sent shell commands to the localhost, enabling tasks like folder deletion, folder creation, and user creation.

Throughout the project, Blue Ocean significantly improved the user interface, providing a more modern and intuitive experience for visualizing and managing pipelines. It simplified the creation of complex build and deployment workflows, allowing for streamlined automation and efficient management of Jenkins projects.
