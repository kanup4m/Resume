# Resume
A simple portfolio made with HTML,CSS & Javascript.

# Portfolio Website (Link)
Managing the portfolio site was always a pain if just frontend was used. Even for minute changes to be made, whole website code was to be formatted. I have used django for CMS (Content Management Service) to ease the pain of editing whole code for any changes.

I am basically working on making this project an opensource Portfolio Management System and will soon be releasing a multi functional and generic PMS (Portfolio Management System).

Any contributions from you guys are welcome. Just fork this repository, make changes in the code and create a pull request, I will merge the changes if it seems interesting. :)

Do star the repo if you think it worth it.

# Requirements (that shall be installed in your system)
1.Git
2.virtualenv
3.Python

# How to run in your local machine?
1.Firstly, clone the repository using the git shell
$ git clone https://github.com/rajujha373/portfolio.git
2.Goto the base directory of the project
cd portfolio
3.Create a virtual environment and activate it.
$ virtualenv venv
$ venv\Scripts\activate on Windows or $ source venv/bin/activate on Posix system
4.Install the requirements for the project
$ pip install -r requirements.txt
5.Now start the localhost server
$ python manage.py runserver
