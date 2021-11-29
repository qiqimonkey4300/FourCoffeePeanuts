# StoryBrew by FourCoffeePeanuts

Ryan Wang (PM, SQL) <br />
Eliza Knapp (SQL, Python) <br />
Yaying Liang Li (HTML, SQL) <br />
Jesse Xie (Flask, SQL) <br />

Editors: Shyne Choi & Gavin McGinley <br />

## Description:
StoryBrew is our collaborative storytelling website. After landing on our main page, the user can register or login to collaborate on others' stories or create their own. Once logged in, the user can access their Dashboard - the top header will have buttons where the user can return to the main page, see stories that others made, create a story, or logout (Home, See Stories, Create Story, and Logout, respectively). The body of the Dashboard will contain stories that the user created or previously edited (and can therefore read). Clicking on the title of the story in the Dashboard will bring the user to the story's contents. Use our website to brew up some cool stories to your heart's content!

## Install Instructions
clone repo <br>
`$ git clone https://github.com/rwang2022/FourCoffeePeanuts.git`

cd into it<br>
`$ cd FourCoffeePeanuts/`

if user doesn't already have virtualenv module installed <br>
`$ pip install virtualenv`

create the virtual environment<br>
`$ python3 -m virtualenv venv`

activate the virtual environment<br>
if on Windows: <br>
`$ source venv/Scripts/activate` <br>
if on Mac/Linux: <br>
`$ source venv/bin/activate`

install dependencies<br>
`(venv) $ pip install -r requirements.txt`

## Run Instructions
cd into app <br>
`(venv) $ cd app`

run the python file<br>
`(venv) $ python3 __init__.py`

the link to the site<br>
http://127.0.0.1:5000/
