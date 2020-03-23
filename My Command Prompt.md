# This is the copy of my command Prompt with execution used while Installing Apache Superset

``````````
Microsoft Windows [Version 10.0.18362.720]
(c) 2019 Microsoft Corporation. All rights reserved.

C:\WINDOWS\system32>cd C:\

C:\>pip install cryptography
Collecting cryptography
  Downloading https://files.pythonhosted.org/packages/c9/ff/43897d282db0fa5c4a34f5413af39a2d1f22c7d47b52d6b3c2fab5b81352/cryptography-2.8-cp36-cp36m-win_amd64.whl (1.5MB)
    100% |████████████████████████████████| 1.5MB 492kB/s
Collecting cffi!=1.11.3,>=1.8 (from cryptography)
  Downloading https://files.pythonhosted.org/packages/94/49/8df433247344bf992ed319416a3c252f190dbfd7331cf7bb1432ca46980f/cffi-1.14.0-cp36-cp36m-win_amd64.whl (176kB)
    100% |████████████████████████████████| 184kB 2.1MB/s
Collecting six>=1.4.1 (from cryptography)
  Downloading https://files.pythonhosted.org/packages/65/eb/1f97cb97bfc2390a276969c6fae16075da282f5058082d4cb10c6c5c1dba/six-1.14.0-py2.py3-none-any.whl
Collecting pycparser (from cffi!=1.11.3,>=1.8->cryptography)
  Downloading https://files.pythonhosted.org/packages/ae/e7/d9c3a176ca4b02024debf82342dab36efadfc5776f9c8db077e8f6e71821/pycparser-2.20-py2.py3-none-any.whl (112kB)
    100% |████████████████████████████████| 112kB 54kB/s
Installing collected packages: pycparser, cffi, six, cryptography
Successfully installed cffi-1.14.0 cryptography-2.8 pycparser-2.20 six-1.14.0
You are using pip version 9.0.1, however version 20.0.2 is available.
You should consider upgrading via the 'python -m pip install --upgrade pip' command.

C:\python3 -m pip install --upgrade pip
Collecting pip
  Downloading https://files.pythonhosted.org/packages/54/0c/d01aa759fdc501a58f431eb594a17495f15b88da142ce14b5845662c13f3/pip-20.0.2-py2.py3-none-any.whl (1.4MB)
    100% |████████████████████████████████| 1.4MB 442kB/s
Installing collected packages: pip
  Found existing installation: pip 9.0.1
    Uninstalling pip-9.0.1:
      Successfully uninstalled pip-9.0.1
Successfully installed pip-20.0.2

C:\>pip install virtualenv
Collecting virtualenv
  Downloading virtualenv-20.0.10-py2.py3-none-any.whl (4.6 MB)
     |████████████████████████████████| 4.6 MB 1.7 MB/s
Collecting importlib-metadata<2,>=0.12; python_version < "3.8"
  Downloading importlib_metadata-1.5.0-py2.py3-none-any.whl (30 kB)
Collecting appdirs<2,>=1.4.3
  Downloading appdirs-1.4.3-py2.py3-none-any.whl (12 kB)
Collecting filelock<4,>=3.0.0
  Downloading filelock-3.0.12-py3-none-any.whl (7.6 kB)
Requirement already satisfied: six<2,>=1.9.0 in c:\users\corporater\appdata\local\programs\python\python36\lib\site-packages (from virtualenv) (1.14.0)
Collecting importlib-resources<2,>=1.0; python_version < "3.7"
  Downloading importlib_resources-1.3.1-py2.py3-none-any.whl (31 kB)
Collecting distlib<1,>=0.3.0
  Downloading distlib-0.3.0.zip (571 kB)
     |████████████████████████████████| 571 kB 2.2 MB/s
Collecting zipp>=0.5
  Downloading zipp-3.1.0-py3-none-any.whl (4.9 kB)
Installing collected packages: zipp, importlib-metadata, appdirs, filelock, importlib-resources, distlib, virtualenv
    Running setup.py install for distlib ... done
Successfully installed appdirs-1.4.3 distlib-0.3.0 filelock-3.0.12 importlib-metadata-1.5.0 importlib-resources-1.3.1 virtualenv-20.0.10 zipp-3.1.0

C:\>venv\Scripts\activate
(venv) C:\>pip install --upgrade setuptools pip
Collecting setuptools
  Downloading https://files.pythonhosted.org/packages/70/b8/b23170ddda9f07c3444d49accde49f2b92f97bb2f2ebc312618ef12e4bd6/setuptools-46.0.0-py3-none-any.whl (582kB)
    100% |████████████████████████████████| 583kB 144kB/s
Cache entry deserialization failed, entry ignored
Collecting pip
  Using cached https://files.pythonhosted.org/packages/54/0c/d01aa759fdc501a58f431eb594a17495f15b88da142ce14b5845662c13f3/pip-20.0.2-py2.py3-none-any.whl
Installing collected packages: setuptools, pip
  Found existing installation: setuptools 28.8.0
    Uninstalling setuptools-28.8.0:
      Successfully uninstalled setuptools-28.8.0
  Found existing installation: pip 9.0.1
    Uninstalling pip-9.0.1:
      Successfully uninstalled pip-9.0.1
Exception:
Traceback (most recent call last):
  File "C:\Users\Corporater\AppData\Local\Programs\Python\Python36\lib\shutil.py", line 381, in _rmtree_unsafe
    os.unlink(fullname)
PermissionError: [WinError 5] Access is denied: 'C:\\Users\\CORPOR~1\\AppData\\Local\\Temp\\pip-1vh5vuf3-uninstall\\venv\\scripts\\pip.exe'

During handling of the above exception, another exception occurred:

Traceback (most recent call last):
  File "c:\venv\lib\site-packages\pip\basecommand.py", line 215, in main
  File "c:\venv\lib\site-packages\pip\commands\install.py", line 342, in run
  File "c:\venv\lib\site-packages\pip\req\req_set.py", line 795, in install
  File "c:\venv\lib\site-packages\pip\req\req_install.py", line 767, in commit_uninstall
  File "c:\venv\lib\site-packages\pip\req\req_uninstall.py", line 142, in commit
  File "c:\venv\lib\site-packages\pip\_vendor\retrying.py", line 49, in wrapped_f
    return Retrying(*dargs, **dkw).call(f, *args, **kw)
  File "c:\venv\lib\site-packages\pip\_vendor\retrying.py", line 212, in call
    raise attempt.get()
  File "c:\venv\lib\site-packages\pip\_vendor\retrying.py", line 247, in get
    six.reraise(self.value[0], self.value[1], self.value[2])
  File "c:\venv\lib\site-packages\pip\_vendor\six.py", line 686, in reraise
    def assertRegex(self, *args, **kwargs):
  File "c:\venv\lib\site-packages\pip\_vendor\retrying.py", line 200, in call
    attempt = Attempt(fn(*args, **kwargs), attempt_number, False)
  File "c:\venv\lib\site-packages\pip\utils\__init__.py", line 102, in rmtree
  File "C:\Users\Corporater\AppData\Local\Programs\Python\Python36\lib\shutil.py", line 488, in rmtree
    return _rmtree_unsafe(path, onerror)
  File "C:\Users\Corporater\AppData\Local\Programs\Python\Python36\lib\shutil.py", line 378, in _rmtree_unsafe
    _rmtree_unsafe(fullname, onerror)
  File "C:\Users\Corporater\AppData\Local\Programs\Python\Python36\lib\shutil.py", line 378, in _rmtree_unsafe
    _rmtree_unsafe(fullname, onerror)
  File "C:\Users\Corporater\AppData\Local\Programs\Python\Python36\lib\shutil.py", line 383, in _rmtree_unsafe
    onerror(os.unlink, fullname, sys.exc_info())
  File "c:\venv\lib\site-packages\pip\utils\__init__.py", line 114, in rmtree_errorhandler
PermissionError: [WinError 5] Access is denied: 'C:\\Users\\CORPOR~1\\AppData\\Local\\Temp\\pip-1vh5vuf3-uninstall\\venv\\scripts\\pip.exe'

(venv) C:\>pip install apache-superset
Collecting apache-superset
  Using cached apache-superset-0.35.2.tar.gz (27.5 MB)
Collecting backoff>=1.8.0
  Using cached backoff-1.10.0-py2.py3-none-any.whl (31 kB)
Collecting bleach<4.0.0,>=3.0.2
  Using cached bleach-3.1.1-py2.py3-none-any.whl (150 kB)
Collecting celery<5.0.0,>=4.3.0
  Using cached celery-4.4.1-py2.py3-none-any.whl (422 kB)
Collecting click<7.0.0,>=6.0
  Using cached click-6.7-py2.py3-none-any.whl (71 kB)
Collecting colorama
  Using cached colorama-0.4.3-py2.py3-none-any.whl (15 kB)
Collecting contextlib2
  Using cached contextlib2-0.6.0.post1-py2.py3-none-any.whl (9.8 kB)
Collecting croniter>=0.3.28
  Using cached croniter-0.3.31-py2.py3-none-any.whl (16 kB)
Collecting cryptography>=2.4.2
  Using cached cryptography-2.8-cp36-cp36m-win_amd64.whl (1.5 MB)
Collecting flask<2.0.0,>=1.1.0
  Using cached Flask-1.1.1-py2.py3-none-any.whl (94 kB)
Collecting flask-appbuilder<2.3.0,>=2.1.13
  Using cached Flask_AppBuilder-2.2.4-py3-none-any.whl (1.7 MB)
Collecting flask-caching
  Using cached Flask_Caching-1.8.0-py2.py3-none-any.whl (28 kB)
Collecting flask-compress
  Using cached Flask-Compress-1.4.0.tar.gz (6.0 kB)
Collecting flask-talisman
  Using cached flask_talisman-0.7.0-py2.py3-none-any.whl (12 kB)
Collecting flask-migrate
  Using cached Flask_Migrate-2.5.2-py2.py3-none-any.whl (13 kB)
Collecting flask-wtf
  Using cached Flask_WTF-0.14.3-py2.py3-none-any.whl (13 kB)
Collecting geopy
  Using cached geopy-1.21.0-py2.py3-none-any.whl (104 kB)
Collecting gunicorn<19.9.0
  Using cached gunicorn-19.8.1-py2.py3-none-any.whl (112 kB)
Collecting humanize
  Using cached humanize-2.0.0-py3-none-any.whl (52 kB)
Collecting isodate
  Using cached isodate-0.6.0-py2.py3-none-any.whl (45 kB)
Collecting markdown>=3.0
  Using cached Markdown-3.2.1-py2.py3-none-any.whl (88 kB)
Collecting msgpack<0.7.0,>=0.6.1
  Using cached msgpack-0.6.2-cp36-cp36m-win_amd64.whl (68 kB)
Collecting pandas<0.25.0,>=0.24.2
  Using cached pandas-0.24.2-cp36-cp36m-win_amd64.whl (8.8 MB)
Collecting parsedatetime
  Using cached parsedatetime-2.5.tar.gz (58 kB)
Collecting pathlib2
  Using cached pathlib2-2.3.5-py2.py3-none-any.whl (18 kB)
Collecting polyline
  Using cached polyline-1.4.0-py2.py3-none-any.whl (4.4 kB)
Collecting python-dateutil
  Using cached python_dateutil-2.8.1-py2.py3-none-any.whl (227 kB)
Collecting python-dotenv
  Using cached python_dotenv-0.12.0-py2.py3-none-any.whl (17 kB)
Collecting python-geohash
  Using cached python-geohash-0.8.5.tar.gz (17 kB)
Collecting pyarrow<0.16.0,>=0.15.1
  Using cached pyarrow-0.15.1-cp36-cp36m-win_amd64.whl (18.3 MB)
Collecting pyyaml>=5.1
  Using cached PyYAML-5.3-cp36-cp36m-win_amd64.whl (215 kB)
Collecting retry>=0.9.2
  Using cached retry-0.9.2-py2.py3-none-any.whl (8.0 kB)
Collecting selenium>=3.141.0
  Using cached selenium-3.141.0-py2.py3-none-any.whl (904 kB)
Collecting simplejson>=3.15.0
  Using cached simplejson-3.17.0-cp36-cp36m-win_amd64.whl (73 kB)
Processing c:\users\corporater\appdata\local\pip\cache\wheels\4a\1b\3a\c73044d7be48baeb47cbee343334f7803726ca1e9ba7b29095\sqlalchemy-1.3.15-cp36-cp36m-win_amd64.whl
Collecting sqlalchemy-utils>=0.33.2
  Using cached SQLAlchemy-Utils-0.36.1.tar.gz (128 kB)
Collecting sqlparse<0.4,>=0.3.0
  Using cached sqlparse-0.3.1-py2.py3-none-any.whl (40 kB)
Collecting wtforms-json
  Using cached WTForms-JSON-0.3.3.tar.gz (11 kB)
Collecting six>=1.9.0
  Using cached six-1.14.0-py2.py3-none-any.whl (10 kB)
Collecting webencodings
  Using cached webencodings-0.5.1-py2.py3-none-any.whl (11 kB)
Collecting billiard<4.0,>=3.6.3.0
  Using cached billiard-3.6.3.0-py3-none-any.whl (89 kB)
Collecting vine==1.3.0
  Using cached vine-1.3.0-py2.py3-none-any.whl (14 kB)
Collecting kombu<4.7,>=4.6.8
  Using cached kombu-4.6.8-py2.py3-none-any.whl (183 kB)
Collecting pytz>dev
  Using cached pytz-2019.3-py2.py3-none-any.whl (509 kB)
Collecting cffi!=1.11.3,>=1.8
  Using cached cffi-1.14.0-cp36-cp36m-win_amd64.whl (176 kB)
Collecting Jinja2>=2.10.1
  Using cached Jinja2-2.11.1-py2.py3-none-any.whl (126 kB)
Collecting itsdangerous>=0.24
  Using cached itsdangerous-1.1.0-py2.py3-none-any.whl (16 kB)
Collecting Werkzeug>=0.15
  Using cached Werkzeug-1.0.0-py2.py3-none-any.whl (298 kB)
Collecting Flask-SQLAlchemy<3,>=2.4
  Using cached Flask_SQLAlchemy-2.4.1-py2.py3-none-any.whl (17 kB)
Collecting PyJWT>=1.7.1
  Using cached PyJWT-1.7.1-py2.py3-none-any.whl (18 kB)
Collecting marshmallow-sqlalchemy<1,>=0.16.1
  Using cached marshmallow_sqlalchemy-0.22.3-py2.py3-none-any.whl (18 kB)
Collecting apispec[yaml]<2,>=1.1.1
  Using cached apispec-1.3.3-py2.py3-none-any.whl (23 kB)
Collecting marshmallow<2.20,>=2.18.0
  Using cached marshmallow-2.19.5-py2.py3-none-any.whl (50 kB)
Collecting Flask-Babel<2,>=1
  Using cached Flask_Babel-1.0.0-py3-none-any.whl (9.5 kB)
Collecting Flask-OpenID<2,>=1.2.5
  Using cached Flask-OpenID-1.2.5.tar.gz (43 kB)
Collecting prison<1.0.0,>=0.1.2
  Using cached prison-0.1.2-py2.py3-none-any.whl (5.0 kB)
Collecting Flask-Login<0.5,>=0.3
  Using cached Flask-Login-0.4.1.tar.gz (14 kB)
Collecting marshmallow-enum<2,>=1.4.1
  Using cached marshmallow_enum-1.5.1-py2.py3-none-any.whl (4.2 kB)
Collecting Flask-JWT-Extended<4,>=3.18
  Using cached Flask-JWT-Extended-3.24.1.tar.gz (31 kB)
Collecting jsonschema<4,>=3.0.1
  Using cached jsonschema-3.2.0-py2.py3-none-any.whl (56 kB)
Collecting alembic>=0.7
  Using cached alembic-1.4.1.tar.gz (1.1 MB)
Collecting WTForms
  Using cached WTForms-2.2.1-py2.py3-none-any.whl (166 kB)
Collecting geographiclib<2,>=1.49
  Using cached geographiclib-1.50-py3-none-any.whl (38 kB)
Requirement already satisfied: setuptools>=36 in c:\venv\lib\site-packages (from markdown>=3.0->apache-superset) (46.0.0)
Collecting numpy>=1.12.0
  Using cached numpy-1.18.1-cp36-cp36m-win_amd64.whl (12.8 MB)
Collecting decorator>=3.4.2
  Using cached decorator-4.4.2-py2.py3-none-any.whl (9.2 kB)
Collecting py<2.0.0,>=1.4.26
  Using cached py-1.8.1-py2.py3-none-any.whl (83 kB)
Collecting urllib3
  Using cached urllib3-1.25.8-py2.py3-none-any.whl (125 kB)
Collecting importlib-metadata>=0.18; python_version < "3.8"
  Using cached importlib_metadata-1.5.0-py2.py3-none-any.whl (30 kB)
Collecting amqp<2.6,>=2.5.2
  Using cached amqp-2.5.2-py2.py3-none-any.whl (49 kB)
Collecting pycparser
  Using cached pycparser-2.20-py2.py3-none-any.whl (112 kB)
Collecting MarkupSafe>=0.23
  Using cached MarkupSafe-1.1.1-cp36-cp36m-win_amd64.whl (16 kB)
Collecting Babel>=2.3
  Using cached Babel-2.8.0-py2.py3-none-any.whl (8.6 MB)
Collecting python3-openid>=2.0
  Using cached python3_openid-3.1.0-py3-none-any.whl (130 kB)
Collecting pyrsistent>=0.14.0
  Using cached pyrsistent-0.15.7.tar.gz (107 kB)
Collecting attrs>=17.4.0
  Using cached attrs-19.3.0-py2.py3-none-any.whl (39 kB)
Collecting Mako
  Using cached Mako-1.1.2-py2.py3-none-any.whl (75 kB)
Collecting python-editor>=0.3
  Using cached python_editor-1.0.4-py3-none-any.whl (4.9 kB)
Collecting zipp>=0.5
  Using cached zipp-3.1.0-py3-none-any.whl (4.9 kB)
Collecting defusedxml
  Using cached defusedxml-0.6.0-py2.py3-none-any.whl (23 kB)
Installing collected packages: backoff, six, webencodings, bleach, billiard, vine, zipp, importlib-metadata, amqp, kombu, pytz, celery, click, colorama, contextlib2, python-dateutil, croniter, pycparser, cffi, cryptography, MarkupSafe, Jinja2, itsdangerous, Werkzeug, flask, WTForms, flask-wtf, sqlalchemy, Flask-SQLAlchemy, PyJWT, marshmallow, marshmallow-sqlalchemy, sqlalchemy-utils, pyyaml, apispec, Babel, Flask-Babel, defusedxml, python3-openid, Flask-OpenID, prison, Flask-Login, marshmallow-enum, Flask-JWT-Extended, pyrsistent, attrs, jsonschema, flask-appbuilder, flask-caching, flask-compress, flask-talisman, Mako, python-editor, alembic, flask-migrate, geographiclib, geopy, gunicorn, humanize, isodate, markdown, msgpack, numpy, pandas, parsedatetime, pathlib2, polyline, python-dotenv, python-geohash, pyarrow, decorator, py, retry, urllib3, selenium, simplejson, sqlparse, wtforms-json, apache-superset
    Running setup.py install for sqlalchemy-utils ... done
    Running setup.py install for Flask-OpenID ... done
    Running setup.py install for Flask-Login ... done
    Running setup.py install for Flask-JWT-Extended ... done
    Running setup.py install for pyrsistent ... done
    Running setup.py install for flask-compress ... done
    Running setup.py install for alembic ... done
    Running setup.py install for parsedatetime ... done
    Running setup.py install for python-geohash ... done
    Running setup.py install for wtforms-json ... done
    Running setup.py install for apache-superset ... done
Successfully installed Babel-2.8.0 Flask-Babel-1.0.0 Flask-JWT-Extended-3.24.1 Flask-Login-0.4.1 Flask-OpenID-1.2.5 Flask-SQLAlchemy-2.4.1 Jinja2-2.11.1 Mako-1.1.2 MarkupSafe-1.1.1 PyJWT-1.7.1 WTForms-2.2.1 Werkzeug-1.0.0 alembic-1.4.1 amqp-2.5.2 apache-superset-0.35.2 apispec-1.3.3 attrs-19.3.0 backoff-1.10.0 billiard-3.6.3.0 bleach-3.1.1 celery-4.4.1 cffi-1.14.0 click-6.7 colorama-0.4.3 contextlib2-0.6.0.post1 croniter-0.3.31 cryptography-2.8 decorator-4.4.2 defusedxml-0.6.0 flask-1.1.1 flask-appbuilder-2.2.4 flask-caching-1.8.0 flask-compress-1.4.0 flask-migrate-2.5.2 flask-talisman-0.7.0 flask-wtf-0.14.3 geographiclib-1.50 geopy-1.21.0 gunicorn-19.8.1 humanize-2.0.0 importlib-metadata-1.5.0 isodate-0.6.0 itsdangerous-1.1.0 jsonschema-3.2.0 kombu-4.6.8 markdown-3.2.1 marshmallow-2.19.5 marshmallow-enum-1.5.1 marshmallow-sqlalchemy-0.22.3 msgpack-0.6.2 numpy-1.18.1 pandas-0.24.2 parsedatetime-2.5 pathlib2-2.3.5 polyline-1.4.0 prison-0.1.2 py-1.8.1 pyarrow-0.15.1 pycparser-2.20 pyrsistent-0.15.7 python-dateutil-2.8.1 python-dotenv-0.12.0 python-editor-1.0.4 python-geohash-0.8.5 python3-openid-3.1.0 pytz-2019.3 pyyaml-5.3 retry-0.9.2 selenium-3.141.0 simplejson-3.17.0 six-1.14.0 sqlalchemy-1.3.15 sqlalchemy-utils-0.36.1 sqlparse-0.3.1 urllib3-1.25.8 vine-1.3.0 webencodings-0.5.1 wtforms-json-0.3.3 zipp-3.1.0

(venv) C:\>pip install pymssql
Collecting pymssql
  Downloading pymssql-2.1.4-cp36-cp36m-win_amd64.whl (411 kB)
     |████████████████████████████████| 411 kB 234 kB/s
Installing collected packages: pymssql
Successfully installed pymssql-2.1.4


(venv) C:\>cd venv

(venv) C:\venv>python3 Scripts\superset db upgrade
2020-03-13 18:18:59,792:INFO:root:logging was configured successfully
2020-03-13 18:19:00,049:INFO:root:Configured event logger of type <class 'superset.utils.log.DBEventLogger'>
INFO  [alembic.runtime.migration] Context impl SQLiteImpl.
INFO  [alembic.runtime.migration] Will assume transactional DDL.
INFO  [alembic.runtime.migration] Running upgrade  -> 4e6a06bad7a8, Init
INFO  [alembic.runtime.migration] Running upgrade 4e6a06bad7a8 -> 5a7bad26f2a7, empty message
INFO  [alembic.runtime.migration] Running upgrade 5a7bad26f2a7 -> 1e2841a4128, empty message
INFO  [alembic.runtime.migration] Running upgrade 1e2841a4128 -> 2929af7925ed, TZ offsets in data sources
INFO  [alembic.runtime.migration] Running upgrade 2929af7925ed -> 289ce07647b, Add encrypted password field
INFO  [alembic.runtime.migration] Running upgrade 289ce07647b -> 1a48a5411020, adding slug to dash
INFO  [alembic.runtime.migration] Running upgrade 1a48a5411020 -> 315b3f4da9b0, adding log model
INFO  [alembic.runtime.migration] Running upgrade 315b3f4da9b0 -> 55179c7f25c7, sqla_descr
INFO  [alembic.runtime.migration] Running upgrade 55179c7f25c7 -> 12d55656cbca, is_featured
c:\venv\lib\site-packages\alembic\ddl\sqlite.py:41: UserWarning: Skipping unsupported ALTER for creation of implicit constraintPlease refer to the batch mode feature which allows for SQLite migrations using a copy-and-move strategy.
  "Skipping unsupported ALTER for "
INFO  [alembic.runtime.migration] Running upgrade 12d55656cbca -> 2591d77e9831, user_id
INFO  [alembic.runtime.migration] Running upgrade 2591d77e9831 -> 8e80a26a31db, empty message
INFO  [alembic.runtime.migration] Running upgrade 8e80a26a31db -> 7dbf98566af7, empty message
INFO  [alembic.runtime.migration] Running upgrade 7dbf98566af7 -> 43df8de3a5f4, empty message
INFO  [alembic.runtime.migration] Running upgrade 43df8de3a5f4 -> d827694c7555, css templates
INFO  [alembic.runtime.migration] Running upgrade d827694c7555 -> 430039611635, log more
INFO  [alembic.runtime.migration] Running upgrade 430039611635 -> 18e88e1cc004, making audit nullable
INFO  [alembic.runtime.migration] Running upgrade 18e88e1cc004 -> 836c0bf75904, cache_timeouts
INFO  [alembic.runtime.migration] Running upgrade 18e88e1cc004 -> a2d606a761d9, adding favstar model
INFO  [alembic.runtime.migration] Running upgrade a2d606a761d9, 836c0bf75904 -> d2424a248d63, empty message
INFO  [alembic.runtime.migration] Running upgrade d2424a248d63 -> 763d4b211ec9, fixing audit fk
INFO  [alembic.runtime.migration] Running upgrade d2424a248d63 -> 1d2ddd543133, log dt
INFO  [alembic.runtime.migration] Running upgrade 1d2ddd543133, 763d4b211ec9 -> fee7b758c130, empty message
INFO  [alembic.runtime.migration] Running upgrade fee7b758c130 -> 867bf4f117f9, Adding extra field to Database model
INFO  [alembic.runtime.migration] Running upgrade 867bf4f117f9 -> bb51420eaf83, add schema to table model
INFO  [alembic.runtime.migration] Running upgrade bb51420eaf83 -> b4456560d4f3, change_table_unique_constraint
INFO  [alembic.runtime.migration] Running upgrade b4456560d4f3 -> 4fa88fe24e94, owners_many_to_many
INFO  [alembic.runtime.migration] Running upgrade 4fa88fe24e94 -> c3a8f8611885, Materializing permission
INFO  [alembic.runtime.migration] Running upgrade c3a8f8611885 -> f0fbf6129e13, Adding verbose_name to tablecolumn
INFO  [alembic.runtime.migration] Running upgrade f0fbf6129e13 -> 956a063c52b3, adjusting key length
INFO  [alembic.runtime.migration] Running upgrade 956a063c52b3 -> 1226819ee0e3, Fix wrong constraint on table columns
INFO  [alembic.runtime.migration] Running upgrade 1226819ee0e3 -> d8bc074f7aad, Add new field 'is_restricted' to SqlMetric and DruidMetric
INFO  [alembic.runtime.migration] Running upgrade d8bc074f7aad -> 27ae655e4247, Make creator owners
INFO  [alembic.runtime.migration] Running upgrade 27ae655e4247 -> 960c69cb1f5b, add dttm_format related fields in table_columns
INFO  [alembic.runtime.migration] Running upgrade 960c69cb1f5b -> f162a1dea4c4, d3format_by_metric
INFO  [alembic.runtime.migration] Running upgrade f162a1dea4c4 -> ad82a75afd82, Update models to support storing the queries.
INFO  [alembic.runtime.migration] Running upgrade ad82a75afd82 -> 3c3ffe173e4f, add_sql_string_to_table
INFO  [alembic.runtime.migration] Running upgrade 3c3ffe173e4f -> 41f6a59a61f2, database options for sql lab
INFO  [alembic.runtime.migration] Running upgrade 41f6a59a61f2 -> 4500485bde7d, allow_run_sync_async
INFO  [alembic.runtime.migration] Running upgrade 4500485bde7d -> 65903709c321, allow_dml
INFO  [alembic.runtime.migration] Running upgrade 41f6a59a61f2 -> 33d996bcc382, update slice model
INFO  [alembic.runtime.migration] Running upgrade 33d996bcc382, 65903709c321 -> b347b202819b, empty message
INFO  [alembic.runtime.migration] Running upgrade b347b202819b -> 5e4a03ef0bf0, Add access_request table to manage requests to access datastores.
INFO  [alembic.runtime.migration] Running upgrade 5e4a03ef0bf0 -> eca4694defa7, sqllab_setting_defaults
INFO  [alembic.runtime.migration] Running upgrade eca4694defa7 -> ab3d66c4246e, add_cache_timeout_to_druid_cluster
INFO  [alembic.runtime.migration] Running upgrade eca4694defa7 -> 3b626e2a6783, Sync DB with the models.py.
WARNI [root] Constraint must have a name
INFO  [alembic.runtime.migration] Running upgrade 3b626e2a6783, ab3d66c4246e -> ef8843b41dac, empty message
INFO  [alembic.runtime.migration] Running upgrade ef8843b41dac -> b46fa1b0b39e, Add json_metadata to the tables table.
INFO  [alembic.runtime.migration] Running upgrade b46fa1b0b39e -> 7e3ddad2a00b, results_key to query
INFO  [alembic.runtime.migration] Running upgrade 7e3ddad2a00b -> ad4d656d92bc, Add avg() to default metrics
INFO  [alembic.runtime.migration] Running upgrade ad4d656d92bc -> c611f2b591b8, dim_spec
INFO  [alembic.runtime.migration] Running upgrade c611f2b591b8 -> e46f2d27a08e, materialize perms
INFO  [alembic.runtime.migration] Running upgrade e46f2d27a08e -> f1f2d4af5b90, Enable Filter Select
INFO  [alembic.runtime.migration] Running upgrade e46f2d27a08e -> 525c854f0005, log_this_plus
INFO  [alembic.runtime.migration] Running upgrade 525c854f0005, f1f2d4af5b90 -> 6414e83d82b7, empty message
INFO  [alembic.runtime.migration] Running upgrade 6414e83d82b7 -> 1296d28ec131, Adds params to the datasource (druid) table
INFO  [alembic.runtime.migration] Running upgrade 1296d28ec131 -> f18570e03440, Add index on the result key to the query table.
INFO  [alembic.runtime.migration] Running upgrade f18570e03440 -> bcf3126872fc, Add keyvalue table
INFO  [alembic.runtime.migration] Running upgrade f18570e03440 -> db0c65b146bd, update_slice_model_json
INFO  [alembic.runtime.migration] Running upgrade db0c65b146bd -> a99f2f7c195a, rewriting url from shortner with new format
INFO  [alembic.runtime.migration] Running upgrade a99f2f7c195a, bcf3126872fc -> d6db5a5cdb5d, empty message
INFO  [alembic.runtime.migration] Running upgrade d6db5a5cdb5d -> b318dfe5fb6c, adding verbose_name to druid column
INFO  [alembic.runtime.migration] Running upgrade d6db5a5cdb5d -> 732f1c06bcbf, add fetch values predicate
INFO  [alembic.runtime.migration] Running upgrade 732f1c06bcbf, b318dfe5fb6c -> ea033256294a, empty message
INFO  [alembic.runtime.migration] Running upgrade b318dfe5fb6c -> db527d8c4c78, Add verbose name to DruidCluster and Database
INFO  [alembic.runtime.migration] Running upgrade db527d8c4c78, ea033256294a -> 979c03af3341, empty message
INFO  [alembic.runtime.migration] Running upgrade 979c03af3341 -> a6c18f869a4e, query.start_running_time
INFO  [alembic.runtime.migration] Running upgrade a6c18f869a4e -> 2fcdcb35e487, saved_queries
INFO  [alembic.runtime.migration] Running upgrade 2fcdcb35e487 -> a65458420354, add_result_backend_time_logging
INFO  [alembic.runtime.migration] Running upgrade a65458420354 -> ca69c70ec99b, tracking_url
INFO  [alembic.runtime.migration] Running upgrade ca69c70ec99b -> a9c47e2c1547, add impersonate_user to dbs
INFO  [alembic.runtime.migration] Running upgrade ca69c70ec99b -> ddd6ebdd853b, annotations
INFO  [alembic.runtime.migration] Running upgrade a9c47e2c1547, ddd6ebdd853b -> d39b1e37131d, empty message
INFO  [alembic.runtime.migration] Running upgrade ca69c70ec99b -> 19a814813610, Adding metric warning_text
INFO  [alembic.runtime.migration] Running upgrade 19a814813610, a9c47e2c1547 -> 472d2f73dfd4, empty message
INFO  [alembic.runtime.migration] Running upgrade 472d2f73dfd4, d39b1e37131d -> f959a6652acd, empty message
INFO  [alembic.runtime.migration] Running upgrade f959a6652acd -> 4736ec66ce19, empty message
c:\venv\lib\site-packages\sqlalchemy\dialects\sqlite\base.py:1917: SAWarning: WARNING: SQL-parsed foreign key constraint '('datasource_name', 'datasources', 'datasource_name')' could not be located in PRAGMA foreign_keys for table metrics
  "foreign_keys for table %s" % (sig, table_name)
INFO  [alembic.runtime.migration] Running upgrade 4736ec66ce19 -> 67a6ac9b727b, update_spatial_params
INFO  [alembic.runtime.migration] Running upgrade 67a6ac9b727b -> 21e88bc06c02
INFO  [alembic.runtime.migration] Running upgrade 21e88bc06c02 -> e866bd2d4976, smaller_grid
Revision ID: e866bd2d4976
Revises: 21e88bc06c02
Create Date: 2018-02-13 08:07:40.766277
INFO  [alembic.runtime.migration] Running upgrade e866bd2d4976 -> e68c4473c581, allow_multi_schema_metadata_fetch
INFO  [alembic.runtime.migration] Running upgrade e68c4473c581 -> f231d82b9b26, empty message
INFO  [alembic.runtime.migration] Running upgrade f231d82b9b26 -> bf706ae5eb46, cal_heatmap_metric_to_metrics
INFO  [alembic.runtime.migration] Running upgrade f231d82b9b26 -> 30bb17c0dc76, empty message
INFO  [alembic.runtime.migration] Running upgrade 30bb17c0dc76, bf706ae5eb46 -> c9495751e314, empty message
INFO  [alembic.runtime.migration] Running upgrade f231d82b9b26 -> 130915240929, is_sqllab_view
INFO  [alembic.runtime.migration] Running upgrade 130915240929, c9495751e314 -> 5ccf602336a0, empty message
INFO  [alembic.runtime.migration] Running upgrade 5ccf602336a0 -> e502db2af7be, add template_params to tables
INFO  [alembic.runtime.migration] Running upgrade e502db2af7be -> c5756bec8b47, Time grain SQLA
INFO  [alembic.runtime.migration] Running upgrade c5756bec8b47 -> afb7730f6a9c, remove empty filters
INFO  [alembic.runtime.migration] Running upgrade afb7730f6a9c -> 80a67c5192fa, single pie chart metric
INFO  [alembic.runtime.migration] Running upgrade 80a67c5192fa -> bddc498dd179, adhoc filters
INFO  [alembic.runtime.migration] Running upgrade bddc498dd179 -> 3dda56f1c4c6, Migrate num_period_compare and period_ratio_type
INFO  [alembic.runtime.migration] Running upgrade 3dda56f1c4c6 -> 1d9e835a84f9, empty message
INFO  [alembic.runtime.migration] Running upgrade bddc498dd179 -> 4451805bbaa1, remove double percents
INFO  [alembic.runtime.migration] Running upgrade 4451805bbaa1, 1d9e835a84f9 -> 705732c70154, empty message
INFO  [alembic.runtime.migration] Running upgrade 4451805bbaa1, 1d9e835a84f9 -> fc480c87706c, empty message
INFO  [alembic.runtime.migration] Running upgrade fc480c87706c -> bebcf3fed1fe, Migrate dashboard position_json data from V1 to V2
INFO  [alembic.runtime.migration] Running upgrade bebcf3fed1fe, 705732c70154 -> ec1f88a35cc6, empty message
INFO  [alembic.runtime.migration] Running upgrade 4451805bbaa1, 1d9e835a84f9 -> e3970889f38e, empty message
INFO  [alembic.runtime.migration] Running upgrade 705732c70154, e3970889f38e -> 46ba6aaaac97, empty message
INFO  [alembic.runtime.migration] Running upgrade 46ba6aaaac97, ec1f88a35cc6 -> c18bd4186f15, empty message
INFO  [alembic.runtime.migration] Running upgrade c18bd4186f15 -> 7fcdcde0761c, Reduce position_json size by remove extra space and component id prefix
INFO  [alembic.runtime.migration] Running upgrade 7fcdcde0761c -> 0c5070e96b57, add user attributes table
INFO  [alembic.runtime.migration] Running upgrade 0c5070e96b57 -> 1a1d627ebd8e, position_json
INFO  [alembic.runtime.migration] Running upgrade 1a1d627ebd8e -> 55e910a74826, add_metadata_column_to_annotation_model.py
INFO  [alembic.runtime.migration] Running upgrade 55e910a74826 -> 4ce8df208545, empty message
INFO  [alembic.runtime.migration] Running upgrade 4ce8df208545 -> 46f444d8b9b7, remove_coordinator_from_druid_cluster_model.py
INFO  [alembic.runtime.migration] Running upgrade 46f444d8b9b7 -> a61b40f9f57f, remove allow_run_sync
INFO  [alembic.runtime.migration] Running upgrade a61b40f9f57f -> 6c7537a6004a, models for email reports
INFO  [alembic.runtime.migration] Running upgrade 6c7537a6004a -> 3e1b21cd94a4, change_owner_to_m2m_relation_on_datasources.py
INFO  [alembic.runtime.migration] Running upgrade 6c7537a6004a -> cefabc8f7d38, Increase size of name column in ab_view_menu
INFO  [alembic.runtime.migration] Running upgrade 55e910a74826 -> 0b1f1ab473c0, Add extra column to Query
INFO  [alembic.runtime.migration] Running upgrade 0b1f1ab473c0, cefabc8f7d38, 3e1b21cd94a4 -> de021a1ca60d, empty message
INFO  [alembic.runtime.migration] Running upgrade de021a1ca60d -> fb13d49b72f9, better_filters
INFO  [alembic.runtime.migration] Running upgrade fb13d49b72f9 -> a33a03f16c4a, Add extra column to SavedQuery
INFO  [alembic.runtime.migration] Running upgrade 4451805bbaa1, 1d9e835a84f9 -> c829ff0b37d0, empty message
INFO  [alembic.runtime.migration] Running upgrade c829ff0b37d0 -> 7467e77870e4, remove_aggs
INFO  [alembic.runtime.migration] Running upgrade 7467e77870e4, de021a1ca60d -> fbd55e0f83eb, empty message
INFO  [alembic.runtime.migration] Running upgrade fbd55e0f83eb, fb13d49b72f9 -> 8b70aa3d0f87, empty message
INFO  [alembic.runtime.migration] Running upgrade 8b70aa3d0f87, a33a03f16c4a -> 18dc26817ad2, empty message
INFO  [alembic.runtime.migration] Running upgrade 18dc26817ad2 -> c617da68de7d, form nullable
INFO  [alembic.runtime.migration] Running upgrade c617da68de7d -> c82ee8a39623, Add implicit tags
INFO  [alembic.runtime.migration] Running upgrade 18dc26817ad2 -> e553e78e90c5, add_druid_auth_py.py
INFO  [alembic.runtime.migration] Running upgrade e553e78e90c5, c82ee8a39623 -> 45e7da7cfeba, empty message
INFO  [alembic.runtime.migration] Running upgrade 45e7da7cfeba -> 80aa3f04bc82, Add Parent ids in dashboard layout metadata
INFO  [alembic.runtime.migration] Running upgrade 80aa3f04bc82 -> d94d33dbe938, form strip
INFO  [alembic.runtime.migration] Running upgrade d94d33dbe938 -> 937d04c16b64, update datasources
INFO  [alembic.runtime.migration] Running upgrade 937d04c16b64 -> 7f2635b51f5d, update base columns
INFO  [alembic.runtime.migration] Running upgrade 7f2635b51f5d -> e9df189e5c7e, update base metrics
INFO  [alembic.runtime.migration] Running upgrade e9df189e5c7e -> afc69274c25a, update the sql, select_sql, and executed_sql columns in the
   query table in mysql dbs to be long text columns
INFO  [alembic.runtime.migration] Running upgrade afc69274c25a -> d7c1a0d6f2da, Remove limit used from query model
INFO  [alembic.runtime.migration] Running upgrade d7c1a0d6f2da -> ab8c66efdd01, resample
INFO  [alembic.runtime.migration] Running upgrade ab8c66efdd01 -> b4a38aa87893, deprecate database expression
INFO  [alembic.runtime.migration] Running upgrade b4a38aa87893 -> d6ffdf31bdd4, Add published column to dashboards
INFO  [alembic.runtime.migration] Running upgrade d6ffdf31bdd4 -> 190188938582, Remove duplicated entries in dashboard_slices table and add unique constraint
INFO  [alembic.runtime.migration] Running upgrade 190188938582 -> def97f26fdfb, Add index to tagged_object
INFO  [alembic.runtime.migration] Running upgrade def97f26fdfb -> 11c737c17cc6, deprecate_restricted_metrics
INFO  [alembic.runtime.migration] Running upgrade 11c737c17cc6 -> 258b5280a45e, form strip leading and trailing whitespace
INFO  [alembic.runtime.migration] Running upgrade 258b5280a45e -> 1495eb914ad3, time range
INFO  [alembic.runtime.migration] Running upgrade 1495eb914ad3 -> b6fa807eac07, make_names_non_nullable

(venv) C:\venv>cd ..

(venv) C:\>set FLASK_APP=superset

(venv) C:\>flask fab create-admin
Username [admin]: admin
User first name [admin]: user
User last name [user]: one
Email [admin@fab.org]: email@gmail.com
Password:
Repeat for confirmation:
2020-03-13 18:32:43,356:INFO:root:logging was configured successfully
2020-03-13 18:32:43,472:INFO:root:Configured event logger of type <class 'superset.utils.log.DBEventLogger'>
Recognized Database Authentications.
Admin User admin created.

(venv) C:\venv>python3 Scripts\superset load_examples
2020-03-13 18:34:21,041:INFO:root:logging was configured successfully
2020-03-13 18:34:21,190:INFO:root:Configured event logger of type <class 'superset.utils.log.DBEventLogger'>
2020-03-13 18:34:22,458:INFO:root:Creating database reference for examples
Loading examples metadata and related data into examples
Creating default CSS templates
Loading energy related dataset
2020-03-13 18:34:22,526:INFO:root:Database.get_sqla_engine(). Masked URL: sqlite:///C:\Users\Corporater\.superset\superset.db
Creating table [wb_health_population] reference
Loading [World Bank's Health Nutrition and Population Stats]
Creating table [wb_health_population] reference
Creating slices
Creating a World's Health Bank dashboard
Loading [Birth names]
Done loading table!
--------------------------------------------------------------------------------
Creating table [birth_names] reference
Creating some slices
Creating a dashboard
Loading [Unicode test data]
Done loading table!
--------------------------------------------------------------------------------
Creating table [unicode_test] reference
Creating a slice
Creating a dashboard
Loading [Random time series data]
Done loading table!
--------------------------------------------------------------------------------
Creating table [random_time_series] reference
Creating a slice
Loading [Random long/lat data]
Done loading table!
--------------------------------------------------------------------------------
Creating table reference
Creating a slice
Loading [Country Map data]
Done loading table!
--------------------------------------------------------------------------------
Creating table reference
Creating a slice
Loading [Multiformat time series]
Done loading table!
--------------------------------------------------------------------------------
Creating table [multiformat_time_series] reference
Creating Heatmap charts
Loading [Paris GeoJson]
Creating table paris_iris_mapping reference
Loading [San Francisco population polygons]
Creating table sf_population_polygons reference
Loading [Flights data]
Done loading table!
Loading [BART lines]
Creating table bart_lines reference
Loading [Multi Line]
Creating table [wb_health_population] reference
Creating slices
Creating a World's Health Bank dashboard
Creating some slices
Creating a dashboard
Loading [Misc Charts] dashboard
Creating the dashboard
Loading DECK.gl demo
Loading deck.gl dashboard
Creating Scatterplot slice
Creating Screen Grid slice
Creating Hex slice
Creating Grid slice
Creating Polygon slice
Creating Arc slice
Creating Path slice
Creating a dashboard
Loading [Tabbed dashboard]
Creating a dashboard with nested tabs

(venv) C:\venv>python3 Scripts\superset init
2020-03-13 18:36:43,698:INFO:root:logging was configured successfully
2020-03-13 18:36:43,834:INFO:root:Configured event logger of type <class 'superset.utils.log.DBEventLogger'>
2020-03-13 18:37:01,494:INFO:root:Syncing role definition
2020-03-13 18:37:01,650:INFO:root:Syncing Admin perms
2020-03-13 18:37:01,739:INFO:root:Syncing Alpha perms
2020-03-13 18:37:02,149:INFO:root:Syncing Gamma perms
2020-03-13 18:37:02,532:INFO:root:Syncing granter perms
2020-03-13 18:37:02,860:INFO:root:Syncing sql_lab perms
2020-03-13 18:37:03,242:INFO:root:Fetching a set of all perms to lookup which ones are missing
2020-03-13 18:37:03,331:INFO:root:Creating missing datasource permissions.
2020-03-13 18:37:03,337:INFO:root:Creating missing database permissions.
2020-03-13 18:37:03,375:INFO:root:Creating missing metrics permissions
2020-03-13 18:37:03,380:INFO:root:Cleaning faulty perms

(venv) C:\venv>python3 Scripts\superset run -p 8088 --with-threads --reload --debugger
2020-03-13 18:38:55,573:INFO:root:logging was configured successfully
2020-03-13 18:38:55,705:INFO:root:Configured event logger of type <class 'superset.utils.log.DBEventLogger'>
 * Serving Flask app "superset" (lazy loading)
 * Environment: production
   WARNING: This is a development server. Do not use it in a production deployment.
   Use a production WSGI server instead.
 * Debug mode: off
2020-03-13 18:38:57,023:INFO:werkzeug: * Restarting with stat
2020-03-13 18:38:58,900:INFO:root:logging was configured successfully
2020-03-13 18:38:59,048:INFO:root:Configured event logger of type <class 'superset.utils.log.DBEventLogger'>
2020-03-13 18:39:00,340:WARNING:werkzeug: * Debugger is active!
2020-03-13 18:39:00,343:INFO:werkzeug: * Debugger PIN: 483-508-476
2020-03-13 18:39:00,358:INFO:werkzeug: * Running on http://127.0.0.1:8088/ (Press CTRL+C to quit)
2020-03-13 18:39:10,263:INFO:werkzeug:127.0.0.1 - - [13/Mar/2020 18:39:10] "[32mGET / HTTP/1.1[0m" 302 -
2020-03-13 18:39:10,274:INFO:werkzeug:127.0.0.1 - - [13/Mar/2020 18:39:10] "[32mGET /superset/welcome HTTP/1.1[0m" 302 -
2020-03-13 18:39:10,730:INFO:werkzeug:127.0.0.1 - - [13/Mar/2020 18:39:10] "[37mGET /login/ HTTP/1.1[0m" 200 -
2020-03-13 18:39:11,093:INFO:werkzeug:127.0.0.1 - - [13/Mar/2020 18:39:11] "[37mGET /static/appbuilder/css/font-awesome.min.css HTTP/1.1[0m" 200 -
2020-03-13 18:39:11,096:INFO:werkzeug:127.0.0.1 - - [13/Mar/2020 18:39:11] "[37mGET /static/appbuilder/css/bootstrap.min.css HTTP/1.1[0m" 200 -
2020-03-13 18:39:11,346:INFO:werkzeug:127.0.0.1 - - [13/Mar/2020 18:39:11] "[37mGET /static/appbuilder/datepicker/bootstrap-datepicker.css HTTP/1.1[0m" 200 -
2020-03-13 18:39:11,414:INFO:werkzeug:127.0.0.1 - - [13/Mar/2020 18:39:11] "[37mGET /static/appbuilder/select2/select2.css HTTP/1.1[0m" 200 -
2020-03-13 18:39:11,423:INFO:werkzeug:127.0.0.1 - - [13/Mar/2020 18:39:11] "[37mGET /static/appbuilder/css/flags/flags16.css HTTP/1.1[0m" 200 -
2020-03-13 18:39:11,692:INFO:werkzeug:127.0.0.1 - - [13/Mar/2020 18:39:11] "[37mGET /static/appbuilder/css/ab.css HTTP/1.1[0m" 200 -
2020-03-13 18:39:11,762:INFO:werkzeug:127.0.0.1 - - [13/Mar/2020 18:39:11] "[37mGET /static/assets/dist/theme.e0e42a3c95a4349cb372.entry.css HTTP/1.1[0m" 200 -
2020-03-13 18:39:11,832:INFO:werkzeug:127.0.0.1 - - [13/Mar/2020 18:39:11] "[37mGET /static/appbuilder/js/jquery-latest.js HTTP/1.1[0m" 200 -
2020-03-13 18:39:12,020:INFO:werkzeug:127.0.0.1 - - [13/Mar/2020 18:39:12] "[37mGET /static/appbuilder/js/ab_filters.js HTTP/1.1[0m" 200 -
2020-03-13 18:39:12,085:INFO:werkzeug:127.0.0.1 - - [13/Mar/2020 18:39:12] "[37mGET /static/appbuilder/js/ab_actions.js HTTP/1.1[0m" 200 -
2020-03-13 18:39:12,147:INFO:werkzeug:127.0.0.1 - - [13/Mar/2020 18:39:12] "[37mGET /static/assets/dist/theme.e0e42a3c95a4349cb372.entry.js HTTP/1.1[0m" 200 -
2020-03-13 18:39:12,227:INFO:werkzeug:127.0.0.1 - - [13/Mar/2020 18:39:12] "[37mGET /static/assets/images/superset-logo@2x.png HTTP/1.1[0m" 200 -
2020-03-13 18:39:12,406:INFO:werkzeug:127.0.0.1 - - [13/Mar/2020 18:39:12] "[37mGET /static/appbuilder/fonts/fontawesome-webfont.woff2?v=4.7.0 HTTP/1.1[0m" 200 -
2020-03-13 18:39:12,468:INFO:werkzeug:127.0.0.1 - - [13/Mar/2020 18:39:12] "[37mGET /static/appbuilder/img/flags/flags16.png HTTP/1.1[0m" 200 -
2020-03-13 18:39:12,514:INFO:werkzeug:127.0.0.1 - - [13/Mar/2020 18:39:12] "[37mGET /static/appbuilder/datepicker/bootstrap-datepicker.js HTTP/1.1[0m" 200 -
2020-03-13 18:39:12,518:INFO:werkzeug:127.0.0.1 - - [13/Mar/2020 18:39:12] "[37mGET /static/appbuilder/js/bootstrap.min.js HTTP/1.1[0m" 200 -
2020-03-13 18:39:12,547:INFO:werkzeug:127.0.0.1 - - [13/Mar/2020 18:39:12] "[37mGET /static/appbuilder/js/ab.js HTTP/1.1[0m" 200 -
2020-03-13 18:39:12,549:INFO:werkzeug:127.0.0.1 - - [13/Mar/2020 18:39:12] "[37mGET /static/appbuilder/select2/select2.js HTTP/1.1[0m" 200 -
2020-03-13 18:39:12,857:INFO:werkzeug:127.0.0.1 - - [13/Mar/2020 18:39:12] "[37mGET /static/assets/dist/preamble.ae25a392105321c11fde.entry.js HTTP/1.1[0m" 200 -
2020-03-13 18:39:12,981:INFO:werkzeug:127.0.0.1 - - [13/Mar/2020 18:39:12] "[37mGET /static/assets/dist/vendors-addSlice-preamble-profile-welcome.39730f81a95882cce95b.chunk.js HTTP/1.1[0m" 200 -
2020-03-13 18:39:13,234:INFO:werkzeug:127.0.0.1 - - [13/Mar/2020 18:39:13] "[37mGET /static/assets/dist/vendors-major.138ca4bc8051688ec0b9.chunk.js HTTP/1.1[0m" 200 -
2020-03-13 18:39:13,667:INFO:werkzeug:127.0.0.1 - - [13/Mar/2020 18:39:13] "[37mGET /static/assets/images/favicon.png HTTP/1.1[0m" 200 -
2020-03-13 18:39:22,075:INFO:werkzeug:127.0.0.1 - - [13/Mar/2020 18:39:22] "[32mPOST /login/ HTTP/1.1[0m" 302 -
2020-03-13 18:39:22,206:INFO:werkzeug:127.0.0.1 - - [13/Mar/2020 18:39:22] "[32mGET / HTTP/1.1[0m" 302 -
2020-03-13 18:39:22,687:INFO:werkzeug:127.0.0.1 - - [13/Mar/2020 18:39:22] "[37mGET /superset/welcome HTTP/1.1[0m" 200 -
2020-03-13 18:39:22,773:INFO:werkzeug:127.0.0.1 - - [13/Mar/2020 18:39:22] "[37mGET /static/assets/dist/welcome.7b674421f8e5e6150fe0.entry.css HTTP/1.1[0m" 200 -
2020-03-13 18:39:23,027:INFO:werkzeug:127.0.0.1 - - [13/Mar/2020 18:39:23] "[37mGET /static/assets/images/loading.gif HTTP/1.1[0m" 200 -
2020-03-13 18:39:23,285:INFO:werkzeug:127.0.0.1 - - [13/Mar/2020 18:39:23] "[37mGET /static/assets/dist/welcome.7b674421f8e5e6150fe0.entry.js HTTP/1.1[0m" 200 -
2020-03-13 18:39:23,432:INFO:werkzeug:127.0.0.1 - - [13/Mar/2020 18:39:23] "[37mGET /superset/recent_activity/1/?limit=50 HTTP/1.1[0m" 200 -
2020-03-13 18:39:23,737:INFO:werkzeug:127.0.0.1 - - [13/Mar/2020 18:39:23] "[37mGET /superset/fave_slices/1/ HTTP/1.1[0m" 200 -
2020-03-13 18:39:23,743:INFO:werkzeug:127.0.0.1 - - [13/Mar/2020 18:39:23] "[37mGET /superset/fave_dashboards/1/ HTTP/1.1[0m" 200 -
2020-03-13 18:39:23,751:INFO:werkzeug:127.0.0.1 - - [13/Mar/2020 18:39:23] "[37mGET /dashboardasync/api/read?_oc_DashboardModelViewAsync=changed_on&_od_DashboardModelViewAsync=desc HTTP/1.1[0m" 200 -
``````````
