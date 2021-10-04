
# Creating the Initial React App

This first section is part of the ESIB course, it explains how to create your initial react app with Yarn.

1. Install yarn using globally:

    ```[bash]
    npm install -g yarn
    ```

2. Create your initial react app using yarn:

    ```[bash]
    yarn add create-react-app
    yarn create-react-app conFusion
    ```

    You should commit your ```yarn.lock``` in git, do not add it to [.gitignore](.gitignore)

3. Make sure the HOST variable in the terminal (or command line) is set to ```localhost```.

    ```[bash]
    HOST=localhost
    ```

4. Run the below command to start your application:

    ```[bash]
    yarn start
    ```

    Your react application can now be consulted on [http://localhost:3000/](http://localhost:3000/)

5. Modify [src/App.js](https://github.com/JBakouny/React/commit/6c8c6a9316068be38928b31de1580194f98cf8fd#diff-3d74dddefb6e35fbffe3c76ec0712d5c416352d9449e2fcc8210a9dee57dff67) and [src/index.js](https://github.com/JBakouny/React/commit/6c8c6a9316068be38928b31de1580194f98cf8fd#diff-bfe9874d239014961b1ae4e89875a6155667db834a410aaaa2ebe3cf89820556) in accordance with the [Configure React](https://github.com/JBakouny/React/commit/6c8c6a9316068be38928b31de1580194f98cf8fd) commit.

    View the changes by refreshing [http://localhost:3000/](http://localhost:3000/)


# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).