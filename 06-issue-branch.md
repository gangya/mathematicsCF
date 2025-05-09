# Step 6: Solve issue in a new branch

1. Synch your local repository

    ```bash
    # First be sure you are in main branch
    git switch main

    # Pull form origin/remote repository to main 
    git pull origin main
    ```

2. Create a new branch

    ```bash
    git checkout -b add-calculator-operations
    ```

3. Edit basiCalculator.js file adding operations

    ```javascript
    // This function multiplies two numbers
    function multiplication(a, b) {
    return a * b;
    }

    // This function divides two numbers
    function division(a, b) {
    if (b === 0) throw new Error("Zero Division");
    return a / b;
    }
    ```

4. Save basiCalculator.js file, add to stage then commit

    ````bash
    git add basiCalculator.js
    git commit -m "Adding operations (multiplication and division) to basicCalculator.js file"
    ```

5. Create a `Pull request` to main, associate the issue (use closes#issue-number in description)

6. Accept `Pull request`, this closes issue automatically.

[Previous step](https://github.com/gangya/mathematicsCF/blob/main/05-create-issue.md)  | [Next step: Create a detailed Readme »]()
