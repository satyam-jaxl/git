## If you want to contribute in existing project, you can follow these steps:

1. Clone the project
    ```bash
    git clone <repo-ssh-url>
    ```

2. Create a new branch
    ```bash
    git checkout -b <branch-name>
    ```

3. Make changes

4. Add changes to staging
    ```bash
    git add .
    ```

5. Commit your changes
    ```bash
    git commit -m "<commit-message>"
    ```

6. If typescript project, then patch the version
    ```bash
    npm version patch
    ```

7. If your local main is outdated, you can pull the changes from remote main

    * 7a. Checkout to your local main
        ```bash
        git checkout main
        ```
        
    * 7b. Pull the changes from remote main
        ```bash
        git pull origin main
        ```
    * 7c. Checkout to your branch
        ```bash
        git checkout <branch-name>
        ```
    * 7d. Merge main to your branch
        ```bash
        git merge main
        ```

    * 7e. If there are any conflicts, resolve them

    * 7f. If typescript project, then patch the version
        ```bash
        npm version patch
        ```


8. Push your changes
    ```bash
    git push origin <branch-name>
    ```

9. Create a pull request

10. Link the pull request to the issue

11. Request for review

12. Wait for the review

13. If there are any changes requested, make the changes and push them to the same branch again (follow steps 3-8)

14. If there are no changes requested and workflow pass, your pull request will be merged
