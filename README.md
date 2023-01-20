
### HOW TO USE THIS PROJECT

> **DO NOT FORK** this is meant to be used from **[Clone this project](https://github.com/franc15/Samantha)** feature.

1. Click on **[Clone this project](https://github.com/franc15/Samantha)**
2. Read the file [CONTRIBUTING.md](CONTRIBUTING.md)
3. Then clone your new project and happy coding!

> **NOTE**: **WAIT** until first CI run on github actions before cloning your new project.

### What is included on this project?

- 🖼️ Templates for starting multiple application types:
  * **Basic low dependency** Python program (default) [use this template](https://github.com/rochacbruno/python-project-template/generate)
  * **Flask** with database, admin interface, restapi and authentication [use this template](https://github.com/rochacbruno/flask-project-template/generate).
  **or Run `make init` after cloning to generate a new project based on a template.**
- 📦 A basic [setup.py](setup.py) file to provide installation, packaging and distribution for your project.  
  Template uses setuptools because it's the de-facto standard for Python packages, you can run `make switch-to-poetry` later if you want.
- 🤖 A [Makefile](Makefile) with the most useful commands to install, test, lint, format and release your project.
- 🧪 Testing structure using [pytest](https://docs.pytest.org/en/latest/)
- ✅ Code linting using [flake8](https://flake8.pycqa.org/en/latest/)
- 📊 Code coverage reports using [codecov](https://about.codecov.io/sign-up/)
 
> If you want to contribute to this project please open an [issue](https://github.com/franc15/Samantha/issues) or fork and send a PULL REQUEST.

[❤️ Sponsor this project](https://github.com/sponsors/franc15/)

<!--  DELETE THE LINES ABOVE THIS AND WRITE YOUR PROJECT README BELOW -->

---
# Samantha Personal Assistant

[![codecov](https://codecov.io/gh/author_name/project_urlname/branch/main/graph/badge.svg?token=project_urlname_token_here)](https://codecov.io/gh/author_name/project_urlname)

Samantha is an intelligent personal assistant that can be used on both Windows and Linux Operating Systems to automate the way we do our tasks on our computers.


## create a virtual environment
```bash
python -m venv env
env\Scripts\activate
```

## Install the dependencies

```bash
pip install -r requirements.txt
```

## run the project

```bash
python app.py
```


## Development

Read the [CONTRIBUTING.md](CONTRIBUTING.md) file.

