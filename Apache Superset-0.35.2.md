# Installation-Guide-for-Windows-10---Apache-Superset-0.35.2
# System Requirements
1. Apache Superset requires Python evironment. Install [Python 3.6](https://www.python.org/downloads/release/python-360/).
2. Install [Microsoft Visual C++ 14.0 with Build Tools for Visual Studio 2019](https://visualstudio.microsoft.com/thank-you-downloading-visual-studio/?sku=BuildTools&rel=16). Make sure the following tools are selected.
    - MSVC v142 - VS 2019 C++ x64/x86 build tools (v14.24)
    - Windows 10 SDK (10.0.18362.0)
# Requirements and Environment Set-Up
1.	Open Command Prompt in Administrator Mode move to C:\
2.	Check whether your python installation contains pip package and It should be above version 20.0.2. Check version by using following cmd 
    ```
    pip -V
    ``` 
    If pip version is not 20.0.2, then download [get-pip.py](https://bootstrap.pypa.io/get-pip.py), and run 
        ```
        python get-pip.py
        ```
3.	Superset stores database connection information in its metadata database. For that purpose, we use Cryptography Library which is a Python library to encrypt connection passwords. This library has OS level dependencies, so to install this admin previleges is neccesary. Run this command.
    ```
    pip install cryptography
    ```
4.	It is recommended to install Superset inside a virtualenv. Python 3 already ships virtualenv. But if it’s not installed in your environment for some reason, you can install it from pip. Run this command.
    ```
    pip install virtualenv
    ```
5.	You can create and activate a virtualenv by:
    ```
    python3 -m venv venv
    venv\Scripts\activate
    ```
    Once you activated your virtualenv everything you are doing is confined inside the virtualenv.If you wish to deactivate virtual environment, run this command.
    ```
    venv\Scripts\deactivate
    ```
6.  Put all the chances on your side by getting the very latest pip and setuptools libraries.
    ```
    pip install --upgrade setuptools pip
    ```
    Make sure the setuptools and pip are present.
    -setuptools in c:\venv\lib\site-packages (46.0.0)
    -pip in c:\venv\lib\site-packages (20.0.2)

# Superset installation and initialization. 
Please type the following commands inside the virtual environment.
Follow these few simple steps to install Superset:
1.  Install superset
    ```
    pip install apache-superset
    ```
2.  Initialize the database
     ```
    cd venv
    py Scripts\superset db upgrade
    ```
3.  Create an admin user (you will be prompted to set a username, first and last name before setting a password)
    ```
    cd ..
    set FLASK_APP=superset
    flask fab create-admin
    cd venv
    ```
4.  Load some data to play with
    ```
    py Scripts\superset load_examples
    ```
5.  Create default roles and permissions
    ```
    py Scripts\superset init
    ```
6.  To start a development web server on port 8088, use -p to bind to another port
    ```
    py Scripts\superset run -p 8088 --with-threads --reload –debugger
    ```

After installation, you should be able to point your browser to the right hostname:port http://localhost:8088, login using the credential you entered while creating the admin account, and navigate to Menu -> Admin -> Refresh Metadata. This action should bring in all of your datasources for Superset to be aware of, and they should show up in Menu -> Datasources, from where you can start playing with your data!
# To INSTALL DATABASE DEPENDENCIES
1)	Stop server “ctrl+C”
2)	I am using MS SQL Server and based on your database select the pypi package from here https://superset.apache.org/installation.html#database-dependencies
(venv) C:\venv>cd ..
(venv) C:\>pip install pymssql
3)	(venv) C:\>cd venv
4)	(venv) C:\venv>py Scripts\superset run -p 8088 --with-threads --reload –debugger
# References:
https://visualstudio.microsoft.com/visual-cpp-build-tools/
https://visualstudio.microsoft.com/downloads/#build-tools-for-visual-studio-2017
https://www.itechtics.com/microsoft-visual-c-redistributable-versions-direct-download-links/
https://github.com/apache/incubator-superset/issues/7707
https://github.com/apache/incubator-superset/issues/4479
https://github.com/apache/incubator-superset/issues/7763
https://stackoverflow.com/questions/50295010/is-there-a-way-to-create-read-only-dashboard-in-apache-superset
https://answers.microsoft.com/en-us/windows/forum/all/microsoft-visual-c-140/6f0726e2-6c32-4719-9fe5-aa68b5ad8e6d
https://gist.github.com/mark05e/d9cccae129dd11a21d7219eddd7d9923




