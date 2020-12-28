# Heroku deployment steps 

FOR HEROKU DEPLOYMENT: it is a free service for one user and will give something like herokuapp.com at the end of URL
Before deploying the model you need to do prepare configuration files which is “Procfile” now in Heroku you need to tell which file you wan to run first so in Procfile you will have to write web: gunicorn (command)app(name of your application file) :app (flask name) and the other file is requirements.txt so in here you have to maintain all the libraries that has to install in your environment that are been used for deploying into Heroku as suppose if some of the lib is missing you can check it later so you have to upload all this files with your code files  

You can also download the heroku comandline and install it 
the command to chceck the logs is logs --app (name of your app)

Steps for deploying your model on Heroku platform
1.	Train our model
2.	Create web app using Flask
3.	Commit the code in GitHub
4.	Create the account in Heroku (PAAS)
5.	Link the GitHub to Heroku
6.	Deploy the model
7.	Web App is ready

How will you run these files?
Simply follow this step:
1.	Download these files and save it anywhere in your local computer
2.	Open anaconda command prompt and type cd then the file path that you have stored these files into
3.	Then their type “Python app.py” in the last line you will get something like running on http://....
4.	Copy this IP address and paste it in your browser 
5.	Start using it 

