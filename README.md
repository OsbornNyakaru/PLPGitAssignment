 Initialized a new Git repository in your local folder.
 "git init"
 
Linking my local repository to the GitHub repository I created

   ```

git remote add origin <repository-url>

   ```

   Replace `<repository-url>` with the actual URL of your GitHub repository.



Task 3: Making Changes
 Create a File:

  - Inside your local folder, create a new text file (e.g., `hello.txt`).

  - Add a simple text message (e.g., "Hello, Git!").

Committing Changes:

  - Stage the changes.

   ```bash

   git add hello.txt

   ```

  - Commit the changes.

   ```bash

   git commit -m "Add hello.txt with a greeting"

   ```
Pushing to GitHub

  - Push the committed changes to your GitHub repository.

   ```bash

   git push -u origin main
