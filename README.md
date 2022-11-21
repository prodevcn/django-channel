# Live chat app - Django Channels - Redis

Live chat tutor app built with Django and Channels.

## Installation of virtual environment

### 1. Install virtual environment
Move into the root directory

(Windows)
```code
py -m venv <YOUR_VENV_NAME>
```
or (for Mac / Linux)

```code
python3 -m venv <YOUR_VENV_NAME>
```

### 2. Activate virtual env

```code
./venv/<YOUR_VENV_NAME>/Scripts/activate.bat
```

or 

```code
source ./venv/<YOUR_VENV_NAME>/bin/activate
```

### 3. Install required python libraries

```code
pip install -r requirements.txt
```

### Run app

```
py manage.py runserver
```

App will work on 127.0.0.1:8000