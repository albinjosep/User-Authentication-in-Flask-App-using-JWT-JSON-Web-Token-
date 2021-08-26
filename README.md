User-Authentication-in-Flask-App-using-JWT-JSON-Web-Token-, 

To create an app which is a login and a password from that requests a JWT from the server, and verify it in JWT website(jwt.io).


how to get a secret key, 
In your command line >>> access Python >>> then type:

OS Approach 

import os

os.urandom(14)

OR

UUID Approach

import uuid

uuid.uuid4().hex


Secrets [ only for Python 3.6 + ]

import secrets

secrets.token_urlsafe(14)

