# Deploying HTML to a MDB GO server

To deply a sample HTML webpage to an MDB GO server follow these steps:

1. Register for an MDB GO account:

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

5. Deploy the project:

  ```sh
  mdb publish
  ```
  
  If yo don't have a `package.json` file, This process will walk you through creating one and then deploy the applicationand profide you a working URL. 
  
  You can customiz the URL using:
  
  ```sh
  mdb config domain <YOUR_SUBDOMAIN>.mdbgo.io
  ```
  
***

