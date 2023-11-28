# Blog API

![PyPI - Python Version](https://img.shields.io/pypi/pyversions/django)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Last Commit](https://img.shields.io/github/last-commit/SGGM/drf_api_blog.svg)](https://github.com/SGGM/drf_api_blog/commits/master)


## Description

Simple Blog API made with DRF

## Table of Contents

- [Blog API](#blog-api)
  - [Description](#description)
  - [Table of Contents](#table-of-contents)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Endpoints](#endpoints)
  - [License](#license)
  - [Author](#author)


## Installation

```bash
git clone github.com/SGGM/drf_api_blog.git
```

## Usage

In order to start django project .env file should be put in the root folder.
It should contain:
```bash
DJANGO_SECRET_KEY = "django-insecure-ag4krm^-0)3o&=g&oa^@l4x&0c6$s-q6&*hgs&&auf^-5%i!mz"

DB_NAME = 'drf_blog_api_db'
DB_USER = 'db_admin'
DB_PASSWORD = 'db_password'
```

In order to create and start containers.

```bash
docker-compose build
docker-compose up
```

There is an admin user, you can use.

```bash
Login: admin2
Password: admin2
```

## Endpoints

Examples of endpoints usage.

```bash
api/v1/ - shows list of all blogs, if method == GET
api/v1/ - creates new blog, if method == POST
api/v1/<int> - shows blog by id, if method == GET
api/v1/<int> - changes blog by id, if method == PUT
```

Full set of endpoints could be seen in documentation.
```bash
swagger/
redoc/
```

## License

This project is under license from MIT. For more details, see the LICENSE file.

## Author

* GitHub: https://github.com/SGGM
* Email: gleb_somov@mail.ru
* LeetCode: https://leetcode.com/Arctic__Fox/
* CodeWars: https://www.codewars.com/users/SGGM