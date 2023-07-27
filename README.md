# mydiary
[![PYVER](https://img.shields.io/badge/Python-3.9-blue)](https://www.python.org/) [![JINJA2](https://img.shields.io/badge/Jinja-2-brown)](https://palletsprojects.com/p/jinja/) [![HTMLVER](https://img.shields.io/badge/CSS-3-blue)](https://en.wikipedia.org/wiki/CSS) [![GitHub release](https://img.shields.io/badge/HTML-5-important)](https://en.wikipedia.org/wiki/HTML)
<p align=”left”>
  
<!--   ![](https://raw.githubusercontent.com/Perminev/mydiary/main/screenshots/screen1.png)-->
<!--   ![](https://raw.githubusercontent.com/Perminev/mydiary/main/screenshots/screen2.png)-->
#  ![](https://raw.githubusercontent.com/Perminev/mydiary/main/screenshots/screen3.png)
<!--   ![](https://raw.githubusercontent.com/Perminev/mydiary/main/screenshots/screen4.png)-->

</p>

### How to use it?
### Windows:
`First you need to download zip or write one command in the terminal:`
```
git clone https://github.com/Perminev/mydiary
```
`Second you need to install requirements`
```
cd YOUR_PROJECT_FOLDER
pip install -r requirements.txt
```
`Next you need to run it`
```
python main.py
```
### Linux:
`Preparing for install (You can skip this if all packages are installed and updated):`
```
pkg install git
pkg install pip
pkg upgrade
pkg update
```
`First you need write one command in the terminal:`
```
git clone https://github.com/Perminev/mydiary
```
`Second you need to install requirements`
```
cd mydiary-main
pip install -r requirements.txt
```
`Next you need to run it`
```
python main.py
```

### Termux:
`Preparing for install (You can skip this if all packages are installed and updated):`
```
pkg install git
pkg install pip
pkg upgrade
pkg update
```
`First you need write one command in the terminal:`
```
git clone https://github.com/Perminev/mydiary
```
`Second you need to install requirements`
```
cd mydiary
pip install -r requirements.txt
```
`Next you need to run it`
```
python main.py
```

###### p.s. On the python 3.10 and newer stable working not garanted and if you open diary.db do this five commands in terminal:

```
cd YOUR_PROJECT_FOLDER
python
from main import app, db
app.app_context().push()
db.create_all()
```
