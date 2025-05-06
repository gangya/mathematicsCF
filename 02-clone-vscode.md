# Step 2: Clone the Repository and open in VS Code

1. Go to main page of Repository.
2. Copy the Repository URL, clicking on `<> Code` button, select `HTTPS` tab and copy URL.
3. Open your `Terminal/Console` app and execute the following code:

    ```bash
    git clone `YOUR_REPO_URL`
    cd `YOUR_LOCAL_REPO_DIRECTORY`
    ```

4. Create file basiCalculator.js:

    ```bash
    touch basiCalculator.js
    ```

    or 

    ```bash
    vim basiCalculator.js
    ```

5. Add basiCalculator.js file to `git` for tracking and commit changes:

    ```bash
    git add basiCalculator.js
    git commit -m "Creating basiCalculator.js file"
    ```

6. Confirm changes:

    ```bash
    git push origin main
    ```

[Previous step](https://github.com/gangya/mathematicsCF/blob/main/01-create-repository.md)  | [Next step: Create an Issue »](https://github.com/gangya/mathematicsCF/blob/main/03-create-branch-calculator.md)
