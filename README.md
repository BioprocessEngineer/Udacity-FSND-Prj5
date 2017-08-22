# Udacity-FSND-Prj5: Linux Server Configuration

SSH conncection to the server can be established at 13.114.190.157:2200

The webapp is acceessible at 13.114.190.157

Software: Apache, mod-WSGI, Python, PostgreSQL, Flask, SQLAlchemy. mod-WSGI.

Configurations:

- Updated packages with apt-get upgrade

- used ufw commands to configure firewall rules

- Created users with finger command

- Modified sudoers list so new user will be able to use sudo commands

- Generated SSH key pair on local machine, and created cooresponding key file on server so that ssh connection is enabled

- Modified sshd_config to allow SSH connection to be established using required ports

- Installed apache2 and mod-WSGI

- Created wsgi file in app folder so the app can be connected with the server

- Created conf file to initiate site

- Cloned git repo of previous catalog app

- Installed all necessary packages so the app will be fully functional, using pip installation

- Adjusted session object to be scoped-session, so database would function properly on the server

Thirdparty - used google oauth2client api. Consulted ask and answers on stackexchange

SSH key for provider user is the file named grader in this repo.
