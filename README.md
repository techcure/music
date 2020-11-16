# Music
MereGaane
```
git clone https://github.com/techcure/music.git
```
Create virtual environments

```
python -m venv env1
```
Activate virtual environment
```
source env1/bin/activate      # For linux
python env1\Scripts\activate  # For Windows

```
Go the clone project directory

```
(env1)$ cd music
(env1)../music$

```
Run migrations
```
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
```
You will see this on the terminal - 
```
Watching for file changes with StatReloader
Performing system checks...

System check identified no issues (0 silenced).
November 16, 2020 - 09:20:59
Django version 3.1.3, using settings 'website.settings'
Starting development server at http://127.0.0.1:8000/
Quit the server with CONTROL-C.
```
### Boom you did it. Enjoy !
