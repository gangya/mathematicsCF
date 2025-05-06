# Step 2: Clone the Repository and open in VS Code

1. Go to main page of Repository.
2. Copy the Repository URL, clicking on `<> Code` button, select `HTTPS` tab and copy URL.
3. Open your `Terminal/Console` app and execute the following code:

    ```bash
    git clone `YOUR_REPO_URL`
    cd `YOUR_LOCAL_REPO_DIRECTORY`
    ```

4. Open Vs Code typing:

    ```bash
    code .
    ```

5. Create the basicCalculator.js file directly editor or your orefeddre editor:

    ```bash
    touch basicCalculator.js
    ```

    or 

    ```bash
    vim basicCalculator.js
    ```

6. Adding file to `git` for tracking and commit changes:

    ```bash

    git add basicCalculator.js
    git commit -m "Adding basicCalculator.js file initial uploading" 
    ```

7. Upload files to `gitHub` repository:

    ```bash
    git push origin main
    ```

[Previous step](https://github.com/gangya/mathematicsCF/blob/main/01-create-repository.md)  | [Next step: Create branch, Adding code to basicCalculator.js file »]()
