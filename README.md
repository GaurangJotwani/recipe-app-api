<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for build-url, contributors-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Build Status][build-shield]][build-url]
[![Contributors][contributors-shield]][contributors-url]

<!-- PROJECT LOGO -->
<br />
<p align="center">
  <h3 align="center">Django Recipe API</h3>

  <p align="center">
    A Django REST API with TDD.
  </p>
</p>



<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [Usage](#usage)
* [Roadmap](#roadmap)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)
* [Acknowledgements](#acknowledgements)



<!-- ABOUT THE PROJECT -->
## About The Project

This is a learning project.  

I wanted to learn how to build a REST API with Django and test-driven development.

### Built With
- [Django](https://www.djangoproject.com/)
- [Docker](https://www.docker.com/)
- [Travis CI](https://travis-ci.org/)


<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple example steps:

### Prerequisites

You need [Docker](https://www.docker.com/get-started) and [Docker Compose](https://docs.docker.com/compose/).

### Installation

Git clone this repository

<!-- USAGE EXAMPLES -->
## Usage

1. To run the app:

```sh
docker-compose up -d
```

The API is available at `localhost:8000`.

Available endpoints:

- `admin/`
- `api/user`
- `api/recipe`

2. Create admin:

```sh
docker-compose run --rm app sh -c "python manage.py createsuperuser"
```

3. Run tests:

```sh
docker-compose run --rm app sh -c "python manage.py test"
```

<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/sophiabrandt/django-recipe-api/issues) for a list of proposed features (and known issues).



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

**Please be aware that this is a learning project and not a real world app.**


<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
- [Build a Backend REST API with Python & Django - Advanced][udemy]
- [Best-README-Template](https://github.com/othneildrew/Best-README-Template/blob/master/README.md)
- [Django REST Framework](https://www.django-rest-framework.org/)


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[build-shield]: https://travis-ci.org/sophiabrandt/django-recipe-api.svg?branch=master
[build-url]: https://travis-ci.org/sophiabrandt/django-recipe-api
[contributors-shield]: https://img.shields.io/badge/contributors-1-orange.svg?style=flat-square
[contributors-url]: https://github.com/sophiabrandt/django-recipe-api/graphs/contributors
[license-url]: https://choosealicense.com/licenses/mit
[product-screenshot]: https://raw.githubusercontent.com/sophiabrandt/django-recipe-api/master/screenshot.png
[udemy]: https://www.udemy.com/course/django-python-advanced/
