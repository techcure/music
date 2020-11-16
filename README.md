

### Features
Here You can:
 - Add new albums
 - Add songs to Albums

 - Search for songs and Albums

### Installing App

Windows users must have python or python3 installed before use. Now create virtual environment by following command:
```
python3 -m venv myenv
```
Activate virtual environments:
```
myvenv\Scripts\activate #Windows
source myenv/bin/activate #linux
```
Either install from packages by typing these commands in your terminal
```
sudo apt-get update
sudo apt-get install python-django

#For Windows os:

py -m pip install Django

```

You can confirm whether its installed or not by typing 
```
django-admin --version
```

Other way is installing by using pip 
```
sudo apt-get update
```
Install pip if you dont have by 
```
sudo apt-get install python-pip

#For Windows os:

/> python get-pip.py
/> pip --version
/> python -m pip install
```
Then install django by 
```
sudo pip install django
```

### Running the code 
Just go into the code directory and type 
```
python manage.py runserver
```
"MereGaane" app will start on 127.0.0.1:8000 (Local Address).
 
### Applying Migrations on the Project 

```
python manage.py makemigrations
python manage.py migrate 
python manage.py runserver
```
You can use *showmigration*  to list projects migration.
### Have Fun ! 

   
