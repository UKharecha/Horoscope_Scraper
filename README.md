# 🔮 Horoscope Scraper

Welcome to the Horoscope Scraper project! This project scrapes horoscope data from Horoscope.com and serves it through a Flask-based API.

## 🌟 Project Setup

### 1. Create a Virtual Environment

First, create a virtual environment to manage the project's dependencies.

```bash
$ python -m venv env
```

### 2. Activate the Virtual Environment
Activate the virtual environment with the following commands:

Windows:
```bash
env\Scripts\activate.bat 
```

Linux and MacOS:
```bash
source env/bin/activate
```

### 3. Install Dependencies
Install the required dependencies:

requests: for sending HTTP requests.

```bash
$ pip install requests
```

bs4 (Beautiful Soup): for parsing HTML and XML files.

```bash
$ pip install bs4
```

Flask: for building the web application.

```bash
$ pip install flask
```

Flask-RESTX: for creating APIs with Swagger Documentation.

```bash
$ pip install flask-restx
```

python-decouple: for handling environment variables.

```bash
$ pip install python-decouple
```
### 4. Project Workflow
The basic workflow of the project will be like this:

Scrape horoscope data from Horoscope.com.
Serve the scraped data through a Flask API that returns JSON responses.


### 📚 Learn More
* Flask Documentation
* Beautiful Soup Documentation
* Requests Documentation
* Flask-RESTX Documentation
