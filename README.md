# FindXSS
FindXSS is a brute forcer for a Cross-Site Scripting

Instagram : https://instagram.com/mr.xploit13

###Requirements:

    Python 2.7

    Wordlist included(list.txt)

    Modules required: Colorama, Mechanize

###Modules Required:

    Colorama: https://pypi.python.org/pypi/colorama/

    Mechanize: https://pypi.python.org/pypi/mechanize/


How to install :

1. apt-get install git
2. apt-get install pip2
3. apt-get install python2
4. git clone https://github.com/Mrxploit13/XssAttack
5. cd FindXSS
6. python2 FindXSS.py

###Usage(GET Method):

COMMAND:  python2 FindXSS.py
METHOD:   g
URL:      http://www.site.com/?parameter=value
WORDLIST: list.txt

###Usage(POST method):

COMMAND:   python2 FindXSS.py
METHOD:    p
URL:       http://www.site.com/file.php
POST DATA: parameter=value&parameter1=value1
WORDLIST:  list.txt

