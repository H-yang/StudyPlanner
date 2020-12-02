# StudyPlanner

- Visual studio code with python virtual environment
- (py/python/python3 this depends on your environment variable settings) \
1) Create virtual environment: $ py -m venv .venv 
2) Activate virtual environment: .venv\Scripts\Activate.ps1 or select in visual studio code 
3) You should see (.venv) in the command line 

Packages needed (pip install / py -m pipinstall) \
Install all the necessary packages you see from the console error 

(Windows 10) \
Back-end - run the following commands in the folder where app.py is \
These optional commands allow you the reload flask automatically (without ^C and start again) \ 
- (Optional. copy the $ sign as well) $env:FLASK_APP="app.py"  
- (Optional. copy the $ sign as well) $env:FLASK_ENV="development" 
- $ py -m flask run 

(Linux) \
- (Optional. flask will reload automatically) $ export FLASK_DEBUG=1 
- $ py -m flask run

Front-end \
Go to planner-app folder and open the terminal from here \
If it's first time running, run: $ npm install \
To start service: $ npm start 

Languages used:
- Python 3+
- Node.js

Frameworks:
- Flask
- React.js

DB:
- MongoDB + mongoengine

