The project aims to allow seamless collaboration between Singapore government agencies in times of emergency. 
Main features of the application:
1) Creation and modification of incidents e.g. haze, car accidents by professionals in government agencies, 
2) Monitor active incidents on a centralised map of Singapore. 
3) Automatically generate and send notifications to affected subscribers via SMS, summarized reports to the president office via email, and broadcast updates to Telegram channel. 

Watch the full vido demo:
[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/BDBIkziQnvc/0.jpg)](https://www.youtube.com/watch?v=BDBIkziQnvc)

Personal Contribution:  
- Second Team Leader and front-end developer in a team of 10 
- Actively involved in the design, documentation, and implementation of the system
- Mainly worked on the display and real-time update of the incident map
- The map content is adjustable through flters, while incident labels can be expanded to show details.
- Video demo on incident map:  

---------------------------------------------------
To host the website locally:
## Pipfile 
We are using pipenv to create a virtual environment for our projects, to manage our python packages easily. 

To use pipenv, 

```bash
pip3 install pipenv
```
or 
```bash
pip install pipenv
```
 
## Clone the repository

```bash
git clone git@github.com:jwngo/CMS3003.git
```

Once it has been cloned, 
```bash 
cd CMS3003
```
Install all dependencies from Pipfile
```bash
pipenv install 
``` 
or 
```bash
pipenv sync
``` 
You will require a python of version >3.7

## Localhost

To run django on localhost, 

```bash
pipenv shell
cd cms
python manage.py runserver
``` 

After commiting, please make a **pull request** instead of 
```bash 
git push origin master
``` 
to prevent merge conflicts! 
