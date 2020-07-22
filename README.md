# The-Micro-blog

# How to run - windows powershell
-   `webApp\Scripts\activate`
-   `cd .\Flask_Blog\`
-   `$env:FLASK_APP = "run.py"`
-   `$env:FLASK_ENV = "development"`
-   If username & password from env vars are not working edit the `__init__.py` file
-   `flask run`

## OR
-   `webApp\Scripts\activate`
-   `cd .\Flask_Blog\`
-   `python run.py`

# Update: converting to blueprints
-   Created 3 folders main, users, posts to maintain blueprints.
-   Gave each folder a `__init__.py` to handle each folder as a package.
-   Add a routes file to each of the 3 folders.
-   Create a forms file under posts and users packages
-   Create a `utils.py` file under users package to maintain miscellaneous functions related to users.
