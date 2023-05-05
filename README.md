# Container Apps Example Repository

This is an example codebase we can use to deploy to [container apps](https://github.com/arschles/containerscaler)

Thanks to [Tierney Cyren](https://github.com/bnb) for the code for this app. You can see it at https://github.com/bnb/step-by-step-express

# Deploy

There's a VSCode task in here that will do the deploy for you. Hit ctrl+shift+b to run it, and it should build and install everything to your container apps installation.

You'll need the container apps CLI installed before this will work.

>The task is hard-coded to work with my Docker repository, so you'll need to go change [.vscode/tasks.json](./vscode/tasks.json) to match your repository name
