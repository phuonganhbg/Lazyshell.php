# Lazyshell-PHP
A stealthy PHP web shell which supports simple key based authentication.

THIS TOOL SHOULD BE USED FOR AUTHORIZED TESTING PURPOSES ONLY!

* Easily configure key through the $secretkey variable.
* Customizable error page to disguise the web shell when the key is not provided.
* One click to remove web shell.
* Bootstrap theme.

Lazyshell-PHP is similar to other PHP web shells, but requires a secret key to be provided via a GET parameter in order to run. This helps to prevent unauthorized users from finding your web shell during authorized assessment activity!
![Screenshot](https://raw.githubusercontent.com/joeylane/Lazyshell-PHP/master/screenshot.png)

Lazyshell-PHP displays a customizable error page when an incorrect key is provided. You can even specify the HTTP status codes you want to return! Just simply paste in the HTML from an error page on the web server you are testing, and Lazyshell-PHP will be hidden away from anyone who doesn't have your secret key!
![Screenshot](https://raw.githubusercontent.com/joeylane/Lazyshell-PHP/master/screenshot-errorpage.png)
