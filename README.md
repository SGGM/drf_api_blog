# Blog API

![PyPI - Python Version](https://img.shields.io/pypi/pyversions/django)
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

## Installation

```bash
git clone github.com/SGGM/drf_api_blog.git
```

## Usage

In order to start django project .env file should be put in the root folder.

```bash
docker-compose build
docker-compose up
```

## Endpoints

Examples of endpoints usage.

```
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
