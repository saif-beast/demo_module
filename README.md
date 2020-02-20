# demo_module
Demo npm package publishing demo

Follow the given steps to publish module to github package

1. Create a an access token [https://help.github.com/en/packages/using-github-packages-with-your-projects-ecosystem/configuring-npm-for-use-with-github-packages]

2. Create a new repo

3. clone the repo and run npm init

4. $ npm login --registry=https://npm.pkg.github.com
> Username: USERNAME
> Password: TOKEN
> Email: PUBLIC-EMAIL-ADDRESS


5. add publishConfig entry in package.json

6. Verify the repository field in your project's package.json. The repository field must match the URL for your GitHub repository. For example, if your repository URL is github.com/my-org/test then the repository field should be git://github.com/my-org/test.git

7. npm publish