# Lazyshell.php
A stealthy PHP web shell which supports simple key based authentication.

THIS TOOL MAY BE USED FOR AUTHORIZED TESTING PURPOSES ONLY! Users take full responsibility for any actions performed using this tool. The author accepts no liability for damage caused by this tool. If these terms are not acceptable to you, then do not use this tool.

* Easily configure the secret key using the $secretkey variable.
* Customizable error page to disguise the web shell when the secret key is not provided.
* One single button click to remove the web shell when you are done.
* Bootswatch (Bootstrap) Darkly theme.

Lazyshell-PHP is similar to other PHP web shells, but requires a secret key to be provided via a GET parameter in order to run. This helps to prevent unauthorized users from finding your web shell during authorized assessment activity!
![Screenshot](https://raw.githubusercontent.com/joeylane/Lazyshell.php/master/screenshot.png)

Lazyshell-PHP displays a customizable error page when an incorrect key is provided. You can even specify the HTTP status codes you want to return! Just simply paste in the HTML from an error page on the web server you are testing, and Lazyshell-PHP will be hidden away from anyone who doesn't have your secret key!
![Screenshot](https://raw.githubusercontent.com/joeylane/Lazyshell.php/master/screenshot-errorpage.png)

# MIT License

Copyright (c) 2020 Joey Lane

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
