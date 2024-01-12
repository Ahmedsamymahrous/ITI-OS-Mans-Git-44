# ✨ Git Practice Table for ITI Mansoura OS Track 
Welcome to the Git Practice Table!\
This table has been created to provide the ITI students with a hands-on environment for practicing Git commands and collaborating with their coworkers.\
This README.md file will guide you through the setup, usage, and contribution process.

## 🛠️ Usage
The Git Practice Table is a simple HTML table.\
It includes various table elements that can be modified, added, or deleted\
So, follow the below steps to contribute in this repository:
- Clone the Git Repository:
    ```bash
    git clone https://github.com/Ahmedsamymahrous/ITI-OS-Mans-Git-44.git
    ```
- Navigate to the Repository:
    ```bash
    cd ITI-OS-Mans-Git-44
    ```
- Add your name alongside your email in the HTML table, by copying the below code:
    ```html
    <!-- copy from here -->
        <tr scope="row">
            <td>1</td>
            <td><a href="#">Ahmed Samy</a></td>
            <td>example@example.com</td>
        </tr>
    <!-- to here -->
    ```

- Commit your changes:
    ```bash
    git add index.html
    git commit -m "Add <your-name> in the table"
    ```
- Push to the Github repository:
    ```bash
    git push
    ```

## 🤝 Handling Conflicts
When collaborating on a shared repository, conflicts may arise when multiple contributors make changes to the same part of the code simultaneously.\
So, if Git detects conflicts during the rebase, you'll need to resolve them manually. Open the conflicted files in your text editor and look for sections marked with conflict markers ```<<<<<<<, =======, >>>>>>>```.

```html
    <<<<<<< HEAD
    // Your changes
    =======
    // Incoming changes from main
    >>>>>>> origin/main
```
Edit the conflicted sections to combine both sets of changes appropriately.
