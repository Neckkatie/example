#Example of Working with Remotes    
---
0. Clone to your local repository.
    * Create an **empty** repository on Github for your code.
    ```
    git clone https://github.com/Neckkatie/example.git
    ```
1. Add a remote to your local repository.
    ```
    git remote add https://github.com/Neckkatie/example.git
    ```
2. Push some work **and** tell git to use this as the *"default"* **upstream** repository.
    ```
    git push -u origin master
    ```