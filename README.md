### [Skripta](https://truepeak78.github.io/ag1)

---

### You can report any issues [**here**](https://github.com/truepeak78/ag1/issues/new)

---

### Notes on reporting

1. Specify where (section number - ex. 4.2) and what the problem is - for example: `4.2 - typo in proof of theorem 4.1`
2. Add any relevant description if needed
3. Create the issue

---

### Running locally to see changes before creating pull request

1. git pull your fork to your machine
2. Create a new branch
3. Make a change
4. Create a python virtual environment and use it to install mkdocs
```bash
python3 -m venv venv # create a python virtual environment
source venv/bin/activate # activate it
pip install mkdocs-material
```
5. Start application
```
cd {your fork folder containing mkdocs.yml file}
mkdocs serve
```
6. Go to your web browser and paste http://127.0.0.1:8000/
7. You do not need to restart mkdocs for changes to be made, those will be refreshed automatically


---

### Creating a Pull request

You can also fix the issue yourself with a pull request

1. Create a fork of the repository
2. Fix the issue in your fork
    - please try to prefix all your commits with `fix: (commit message)` 
4. Request merge to `main` branch of `truepeak78/ag1`
