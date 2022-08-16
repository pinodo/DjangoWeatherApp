<div id="top"></div>

<div align="center">
<h3 align="center">Django Weather Detector API App</h3>

  <p align="center">
    Django Login Implementation<br />
    Reference - https://www.youtube.com/watch?v=jBzwzrDvZ18
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisite">Prerequisite</a></li>
        <li><a href="#installation">Installation</a></li>
        <li><a href="#usage">Usage</a></li>
      </ul>
    </li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## About The Project

This project aims to know the usage of public weather API built with Django and python.

### Built With

- [Python](https://www.python.org/)
- [Django](https://www.djangoproject.com/)

<!-- GETTING STARTED -->

## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisite

1. Install the latest version of python and django

### Installation

1. Make a virtual environment in cmd
   ```sh
   i) py -3 -m venv {envname}
   ```
   ```sh
   ii) cd {envname}/Scripts
   ```
   ```sh
   iii) activate
   ```
   Then now you can see your virtual environment as a bracket as
   ```sh
   ({appname})Users\...
   ```
2. Install django
   ```
   pip install django
   ```
3. Create a new django project in a root file
   ```sh
   django-admin startproject {projectname}
   ```
4. Create an app in the project file
   ```sh
   cd {projectname}
   ```
   ```sh
   python manage.py startapp {appname}
   ```
5. Go to project file and work on
   ```sh
   cd {projectname}
   ```
   Total File Structure<br />

```hash
.
└── {filename}
    ├── {envname}
    └── {projectname} (work on in here)
        └── {appname}
            └── ...
        └── {projectname}
            └── ...
```

### Usage

1. Go to http://api.openweathermap.org and get API key
2. Paste your API key to APP_ID to views.py in weather folder

<!-- └── -->
<p align="right">(<a href="#top">back to top</a>)</p>
