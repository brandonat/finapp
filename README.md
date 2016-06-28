## Financial Web Application

This project contains a python application, deployed to the web using the Django framework.

#### Instructions for setting up development environment

For an environment with **Python 3.x** and **pip** already installed, do the following in the working directory.
1. Clone this repository
2. Install **virtualenv**
3. Create and activate virtualenv
4. Load requirements

...using the following commands:

For OSX / Linus
```
git clone https://github.com/brandonat/finapp.git
pip install vitrualenv
virtual venv
source venv/bin/activate
pip install -r requirements.txt
```

For Windows
```
git clone https://github.com/brandonat/finapp.git
pip install vitrualenv
virtual venv
venv\Scripts\activate
pip install -r requirements.txt
```

Once set up, check that the development server is running:  

`python manage.py runserver`
