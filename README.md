# Movie-Recommender

Movie Recommender, as the name suggests is a Web Application, built using Flask which allows the user to find similar movies based on the name of the movie the user entered. The system takes into cosideration various factors and taps into the large number of movie ratings and various genres with respect to the movie name entered by the user.

Flask
-----

Flask is a lightweight `WSGI`_ web application framework. It is designed to make getting started quick and easy, with the ability to scale up to complex applications. It began as 
a simple wrapper around `Werkzeug`_ and `Jinja`_ and has become one of the most popular Python web application frameworks.

Flask offers suggestions, but doesn't enforce any dependencies or project layout. It is up to the developer to choose the tools and libraries they want to use. There are many 
extensions provided by the community that make adding new functionality easy.

Important Resources / Links
-----

* Website: https://palletsprojects.com/p/flask/
* Documentation: https://flask.palletsprojects.com/
* Releases: https://pypi.org/project/Flask/
* Code: https://github.com/pallets/flask
* Issue tracker: https://github.com/pallets/flask/issues
* Test status: https://dev.azure.com/pallets/flask/_build
* Official chat: https://discord.gg/pallets
--------------------------------------------------------------------------------------
* WSGI: https://wsgi.readthedocs.io
* Werkzeug: https://www.palletsprojects.com/p/werkzeug/
* Jinja: https://www.palletsprojects.com/p/jinja/
* pip: https://pip.pypa.io/en/stable/quickstart/

# Installing

1. Download the entire folder in .zip format or git clone the entire folder : https://github.com/Selium98/Movie-Recommender.git
2. Once done extracting the contents, run the requirements.txt file from CLI or Powershell : 
```
pip install -r requirements.txt
```
3. The above command will install all the dependancies required, along with Flask, Jinja, Numpy, Pandas and all other required parameters to get the project going.
4. Once all the requirements are installed, open Powershell in the folder where all the files are present or browse into the folder via CLI.
5. Run the command : 
```
python3 application.py
```
6. This will start the services. 
7. Enter http://127.0.0.1:5000/ in the browser and you should be able to see the project.
