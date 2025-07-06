POC for authentification cycle

use to open the web browser and authentificate with Google
https://nh-center-zvvu.shuttle.app/login

Redirection after login, will reopen the application

with the following scheme
komee-app://logged?{token}

use the token return by the url to get the tokens

see https://github.com/WarthogVN/nh-center for the authentification API

TODO use reqwest crate after login to retrieve the tokens
