
## 1.0 Auto-grader comments


Logs
×
Cloning into 'grader'...
Warning: Permanently added 'github.com,140.82.112.4' (ECDSA) to the list of known hosts.
Collecting selenium
Downloading selenium-4.27.1-py3-none-any.whl (9.7 MB)
Collecting certifi>=2021.10.8
Downloading certifi-2026.7.22-py3-none-any.whl (136 kB)
Collecting websocket-client~=1.8
Downloading websocket_client-1.8.0-py3-none-any.whl (58 kB)
Collecting urllib3[socks]<3,>=1.26
Downloading urllib3-2.2.3-py3-none-any.whl (126 kB)
Collecting trio~=0.17
Downloading trio-0.27.0-py3-none-any.whl (481 kB)
Collecting typing_extensions~=4.9
Downloading typing_extensions-4.13.2-py3-none-any.whl (45 kB)
Collecting trio-websocket~=0.9
Downloading trio_websocket-0.12.2-py3-none-any.whl (21 kB)
Collecting pysocks!=1.5.7,<2.0,>=1.5.6; extra == "socks"
Downloading PySocks-1.7.1-py3-none-any.whl (16 kB)
Collecting sortedcontainers
Downloading sortedcontainers-2.4.0-py2.py3-none-any.whl (29 kB)
Collecting outcome
Downloading outcome-1.3.0.post0-py2.py3-none-any.whl (10 kB)
Collecting idna
Downloading idna-3.15-py3-none-any.whl (72 kB)
Collecting attrs>=23.2.0
Downloading attrs-25.3.0-py3-none-any.whl (63 kB)
Collecting exceptiongroup; python_version < "3.11"
Downloading exceptiongroup-1.3.1-py3-none-any.whl (16 kB)
Collecting sniffio>=1.3.0
Downloading sniffio-1.3.1-py3-none-any.whl (10 kB)
Collecting wsproto>=0.14
Downloading wsproto-1.2.0-py3-none-any.whl (24 kB)
Collecting h11<1,>=0.9.0
Downloading h11-0.16.0-py3-none-any.whl (37 kB)
Installing collected packages: certifi, websocket-client, pysocks, urllib3, sortedcontainers, attrs, outcome, idna, typing-extensions, exceptiongroup, sniffio, trio, h11, wsproto, trio-websocket, selenium
Successfully installed attrs-25.3.0 certifi-2026.7.22 exceptiongroup-1.3.1 h11-0.16.0 idna-3.15 outcome-1.3.0.post0 pysocks-1.7.1 selenium-4.27.1 sniffio-1.3.1 sortedcontainers-2.4.0 trio-0.27.0 trio-websocket-0.12.2 typing-extensions-4.13.2 urllib3-2.2.3 websocket-client-1.8.0 wsproto-1.2.0
WARNING: You are using pip version 20.1.1; however, version 25.0.1 is available.
You should consider upgrading via the '/usr/local/bin/python -m pip install --upgrade pip' command.
/usr/local/lib/python3.8/site-packages/selenium/webdriver/remote/remote_connection.py:418: UserWarning: Embedding username and password in URL could be insecure, use ClientConfig instead
headers = self.get_remote_connection_headers(parsed_url, self._client_config.keep_alive)
----------------------------------------------------------------
----------------------------------------------------------------
----------------------------------------------------------------
****_________________BEGIN AUTOGRADER MESSAGES________________ ****
----------------------------------------------------------------
----------------------------------------------------------------
URL received for Autograder:
https://bonni-b-02.github.io/hw2-f26/
----------------
##### Running submission through validators ...
We are no longer able to check your code automatically with the validators.
However, we will check manually after submission and there will be 5 point
deduction for any w3, Wave, aXe, or csslint errors. (With the exception of
aXe color contrast errors.
Make sure to check aXe on your own!!
#########################################
---------- Safari checks start ----------
#########################################
***************************** Starting Autograder ****************************
***************************** ****************************
***************************** ****************************
***************************** ****************************
Initial check: [PASS]
Current: 100
I am Checking source file for the style tag......
Checking body
Checking h1
Checking footer
Checking h2
Checking p
Checking img
[Checking new CSS......]
Checking for proper style sheets
-5: html5reset.css stylesheet linked: FAILED


-5: style.css stylesheet linked: FAILED


Checking introduction ...
Checking h2 ...
Checking p element ...
-5: all p elements font size [FAILED]


Checking body element ...
-5: body has correct margin [FAILED]


Checking for reset value
Checking h1 format ...
-5: h1 element text align [FAILED]


Checking img format ...
Checking img margin ...
Checking img display property ...
-5: image have correct display to center correctly [FAILED]


Checking img width property ...
Checking red div format ...
-5: red div padding [FAILED]


Checking blue div format ...
-5: blue div padding [FAILED]


Checking blue h2..
-5: all blue h2 elements color [FAILED]


Checking yellow div format ...
-5: yellow div padding [FAILED]


Checking h2..
Checking green div format ...
-5: green div padding [FAILED]


-5: green div left margin [FAILED]


-5: the green div border [FAILED]


-5: footer border [FAILED]


-5: footer paragraph padding [FAILED]


#############################################
---------- Safari checks COMPLETED ----------
#############################################
--------------- Homework Two Autograder Result ---------------
Total Score: 25 / 100
sending Grade