# CBS24_PROJECT1
Cyber Base MOOC project 1
Django app with 5 OWASP Top Ten 2021 Web Application security risks

## INSTALLATION
It's assumed that Python 3.10 or later version is already installed. Otherwise see https://www.python.org/downloads/

### 1. Update the project specific Django version (if Django isn't installed, start from 1.3)

### 1.1 Create a virtual environment
Linux / macOS
```python3 -m venv myenv```

### Windows:
myenv\Scripts\activate

### 1.2 Start the environment
Linux / macOS
source env/bin/activate

Windows:
env\Scripts\activate.bat

### 1.3 Install the requirements
Linux / macOS
pip3 install -r requirements.txt

Windows:
pip install -r requirements.txt

### 2. Check your Django version, should print "5.0.4"
Linux / macOs
python3 -m django --version

Windows:
py -m django --version

### 3. Clone this repo 

### 4. Run the server
Linux / macOs
python3 manage.py runserver

Windows:
py manage.py runserver

### 5. Use the following credinteals to log in
How to log in as admin:
username: admin
password: csb

How to log in as regular user:
username: user
password: csbmooc2024

### For troubleshooting see (https://docs.djangoproject.com/en/5.0/intro/tutorial01/)
