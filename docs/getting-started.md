---
title: Getting started
---

# Getting started

Juxtapoly is a tool for comparing data fast. It supports a variety of formats, including CSV, JSON, and RDBMS.
. If you're familiar with Python, you
can install Juxtapoly with [`pip`][1], the Python package manager.

## Prerequisites

-   Install [git](https://git-scm.com/)
-   Install [Python](https://www.python.org/)

## Installation

### with pip

Juxtapoly can be installed with `pip`:

```
pip install juxtapoly
```

### with git

Juxtapoly can be directly used from [GitHub][3] by cloning the
repository into a subfolder of your project root which might be useful if you
want to use the very latest version:

1. Clone repository to your local

```
    $ git clone https://github.com/nawinto99/juxtapoly.git
```

1. Ensure [poetry](https://python-poetry.org/docs/) is installed, if not follow below.

```
    $ cd juxtapoly
    $ python -m pip install --upgrade pip
    $ pip install poetry
```

1. Install dependencies and start your virtualenv:

```
    $ poetry install
```

[1]: #with-pip-recommended
[3]: https://github.com/nawinto99/juxtapoly
