## Non-shared files

### For the last step create a repository but make sure there are no hard coded secrets or files containing secrets. When I download your files and run the application it should error due to missing secrets file (.env). In your repository readme file, you should explain what secret(s) needed to be passed into the application. What is the point of having a "." in front of the file?

When you download my file, the port is not going to work. Since the .env file was not pushed to the repository, it will not have a secret variable enable the functionality of the code. Therefore, you will not be able to go into the browser to request the page for url localhost:3002. The other secrets are basic secrets that would have showed in the console.log. Secret variables such as; USER_ENV, PASS_ENV, HOST, and TEST_ENV.

Dots that are put in front of the file adds to the path and means that executable files in the current directory are considered by the shell.
