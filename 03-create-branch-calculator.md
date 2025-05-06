# Step 3: Create branch, Adding Code to basicCalculator.js file

1. Creating and moving to new branch:

    ```bash
    # Creates and moves to branch inmmediately
    git checkout -b basic-calculator
    ```

    or

    ```bash
    # Creates new branch
    git branch basic-calculator
    # Moves to new branch
    git checkout basic-calculator
    ```

2. Open, create or modify basicCalculator.js file adding the follwig code:

    ```bash
    // This function adds two numbers
    function addition(a, b) {
    return a + b;
    }

    // This function subtracts two numbers
    function subtraction(a, b) {
    return a - b;
    }
    ```

3. Adding file to `git`, commit and confirm changes:

    ```bash
    git add basicCalculator.js
    git commit -m "Adding operations (addition and substraction) to basicCalculator.js file"
    git push origin main
    ```

[Previous step](https://github.com/gangya/mathematicsCF/blob/main/02-clone-vscode.md)  | [Next step: Basic pull request »]()
