# To run, type: 
flask run at command line. 

Note, this can be integrated into an automatic flask app (deployed using Heroku or Render) 

#App: 
This app is built using Flask, HTML, CSS, SQL and OpenAI GPT3 

### Pre-requisites:

OPENAI_API_KEY can be set with export OPENAI_API_KEY = value (command line) 
or use openai.api_key = key as a local variable straight into the app.py file 

### Name of the project: "

Creating a Flask WebApp for the OpenAI GPT3 engine"

### Idea of the project:

I used Flask, HTML, CSS, SQL and OpenAI GPT3 to create a Web App (an interface) to the OpenAI GPT3 Engine.
This web app has a nice interface beautified with bootstrap and also has login, logout and regitration capabilities. 
There are 3 main directories in the project:
1. static, which holds the styles.css file
2. templates which holds the following html files:
answer.html, apology.html, index.html, layout.html, login.html and register.html. 
The use case of each pf these files should be obvious, especially if you are
familiar with Problem Set 9 of CS50. 
3. the main directory which contains the driver file app.py , the helper file helpers.py as well as the sqlite database database.db. 

This particular APP which I have built here can be extended in a few directions (further work):
 -- allow user to control parameters of the openai.completion.create call such as :
 engine, max_tokens, temperature, top_p or presence_penalty . 
 You can read about the potential effect of each parameter on OPENAI 's site. 
 -- allow user to train a model on a particular topic in order to obtain better results .
 The best way to train a model in my experience is by doing a few shots training, as opposed 
 to fine-tuning. Few shots training means basically to pre-pend the actual query with a few (shots) examples
 of (prompt, completion) which ultimately has the effect of teaching the model how to best answer these 
 particular questions. More details on this matter can be found in the main GPT3 paper: 
"Language Models are Few-Shot Learners " by T. Brown and (many) others. 
-- extend the scope of the project through training or other directions and organize the site accordingly.
-- create more functionality or better esthetic for this site using bootstrap or Javascript as needed.  


Please let me know of your opinion regarding this project. Enjoy! 



