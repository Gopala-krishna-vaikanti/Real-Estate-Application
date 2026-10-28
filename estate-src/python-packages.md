Package                  Version
------------------------ ---------
appdirs                  1.4.4
asgiref                  3.12.1
black                    21.6b0
click                    8.5.0
Django                   3.2.7
django-autoslug          1.9.8
django-countries         7.2.1
django-environ           0.7.0
django-filter            21.1
django-phonenumber-field 5.2.0
djangorestframework      3.12.4
flake8                   3.9.2
isort                    5.9.3
mccabe                   0.6.1
mypy_extensions          1.1.0
pathspec                 0.12.1
phonenumbers             8.12.33
Pillow                   8.3.2
pip                      23.0.1
psycopg2-binary          2.9.1
pycodestyle              2.7.0
pyflakes                 2.3.1
pytz                     2026.5
regex                    2026.9.29
setuptools               65.5.0
sqlparse                 0.6.0
toml                     0.10.2
typing_extensions        4.16.0


# Web frameworks and API
+ Django, Django REST framework, asgiref, sqlparse :: build websites, backend logic, REST APIs & Asynchronous web features

| Package | Usage |
|---|---|
| Django 3.2.7 | The main web framework. Provides models, views, URL routing, an ORM, authentication, admin pages, and database migrations. |
| djangorestframework 3.12.4 | Builds REST APIs so frontend applications, mobile apps, or other services can communicate with your backend using HTTP and JSON. |
| asgiref 3.12.1 | Provides ASGI-related utilities and tools for asynchronous programming and compatibility between synchronous and asynchronous code. |
| sqlparse 0.6.0 | Parses and formats SQL statements. Django uses it for certain SQL-related operations, including displaying formatted SQL. |

# Database and data management
+ psycopg2-binary, django-filter, django-autoslug, django-countries :: connect to PostgreSQL, filter records, manage slugs and country information
| Package | Usage |
|---|---|
| psycopg2-binary 2.9.1 | PostgreSQL database adapter for Python. Allows Django to communicate with a PostgreSQL database. |
| django-filter 21.1 | Adds filtering functionality to Django querysets and REST API endpoints, such as filtering products by category or price. |
| django-autoslug 1.9.8 | Automatically creates URL-friendly slugs from model fields, often for blog posts, products, or categories. |
| django-countries 7.2.1 | Provides country choices and country-related fields for Django models and forms. |

# Validation and image handling
+ django-phonenumber-field, phonenumbers, pillow :: validate phone numbers and work with image files
| Package | Usage |
|---|---|
| django-phonenumber-field 5.2.0 | Adds phone-number fields to Django models and forms. |
| phonenumbers 8.12.33 | Parses, validates, and formats phone numbers using international numbering rules. It is a dependency commonly used by the package above. |
| Pillow 8.3.2 | Opens, resizes, crops, converts, and processes images. It is commonly used with Django's ImageField. |

# Code formatting and quality
+ black, flake8, isort, pycodestyle, pyflakes, mccabe :: keep python code formatted, organized and easier to maintain

| Package | Usage |
|---|---|
| django-environ 0.7.0 | Reads environment variables and `.env` files to configure Django settings. Useful for database credentials, secret keys, and debug settings. |
| appdirs 1.4.4 | Helps determine suitable operating-system-specific directories for application data, configuration, or cache files. |
| pytz 2026.5 | Provides time-zone definitions and conversion utilities. Older Django applications often use it for time-zone handling. |

# configuration and supporting tools
+ django-environ, appdirs, click, pip, setuptools :: manage settings, command-line operations, dependencies & python compatibility

| Package | Usage |
|---|---|
| black 21.6b0 | Automatically formats Python code according to a consistent style. |
| flake8 3.9.2 | Checks Python code for style violations, common errors, and some complexity issues. |
| isort 5.9.3 | Automatically sorts and organizes Python import statements. |
| pycodestyle 2.7.0 | Checks Python code against PEP 8 style conventions. |
| pyflakes 2.3.1 | Detects potential errors such as unused imports and undefined names. |
| mccabe 0.6.1 | Measures code complexity, helping identify functions that may be too complicated. |
| mypy_extensions 1.1.0 | Provides additional typing-related features used by some Python type-checking tools and libraries. |
| pathspec 0.12.1 | Matches file paths against patterns, such as Git-ignore-style patterns. Used by tools including Black. |
| toml 0.10.2 | Reads and writes TOML configuration files. |


# command-line and python installation tools
| Package | Usage |
|---|---|
| click 8.5.0 | Makes it easier to create command-line applications with commands, options, and arguments. |
| pip 23.0.1 | Installs, upgrades, and removes Python packages. |
| setuptools 65.5.0 | Supports building and packaging Python projects and installing certain distributions. |
| typing_extensions 4.16.0 | Provides typing features that may not exist in the Python version a library supports. |
| regex 2026.9.29 | Provides advanced regular-expression matching, with features beyond Python's built-in `re` module. |
| toml 0.10.2 | Also serves as a configuration-file parser for tools that use TOML files. |

# Remaining packages 
| Package | Usage |
|---|---|
| pycodestyle 2.7.0 | Checks Python style; often used by Flake8. |
| mccabe 0.6.1 | Checks cyclomatic complexity; often used by Flake8. |
| pyflakes 2.3.1 | Detects likely programming mistakes; often used by Flake8. |
| pathspec 0.12.1 | Helps tools identify files based on path patterns. |
| mypy_extensions 1.1.0 | Provides supplementary Python typing constructs. |
| typing_extensions 4.16.0 | Supplies additional type hints and typing APIs. |
| regex 2026.9.29 | Supports advanced text matching and replacement. |
| pytz 2026.5 | Supports time zones; its role may overlap with newer Python and Django time-zone features. |

