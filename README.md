# Deploying HTML to an MDB GO server

To deply a sample HTML webpage to an MDB GO server follow these steps:

1. Register for an MDB GO account (https://mdbgo.com/):

    ![MDB GO Register](https://raw.githubusercontent.com/codeadamca/mdbgo-deploy-html/main/_readme/screenshot-mdbgo-register.png)

2. Using NPM install the MDB GO CLI (Command Line Interfact):

    ```sh
    npm install -g mdb-cli
    ```

3. Using the Terminal (or Git Bash on a Windows machine) navigate to your project folder:

    ```sh
    cd <FOLDER_NAME>
    li
    ```
  
4. Login to you MDB GO account using the Terinal:

    ```sh
    mdb login
    ``` 

    ![MDB GO Login](https://raw.githubusercontent.com/codeadamca/mdbgo-deploy-html/main/_readme/screenshot-login.png)
  

5. Deploy the project:

      ```sh
      mdb publish
      ```
  
    If you don't have a `package.json` file, This process will walk you through creating one and then deploy the applicationand profide you a working URL. 
  
   You can customize the URL using the Terminal:
  
    ```sh
    mdb config domain <YOUR_SUBDOMAIN>.mdbgo.io
    ```
  
    ![Deployed](https://raw.githubusercontent.com/codeadamca/mdbgo-deploy-html/main/_readme/screenshot-deployed.png)
  
***

** Repository Requirements:

* [MDB GO](https://mdbgo.com/)
* [MDB GO Custom Domain](https://mdbgo.com/docs/custom-domains/mdbgo-subdomains/)

<a href="https://codeadam.ca">
<img src="https://codeadam.ca/images/code-block.png" width="100">
</a>
