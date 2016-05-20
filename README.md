# trumanshow-browser
A virtual Web user that browses a given Python list of Web sites more or less randomly

## Installation ##

The Browser class defined in browser.py requires the third-party Requests library (http://docs.python-requests.org). On Ubuntu 14.04, this library can be installed via APT:

```sudo apt-get install python3-requests```

Otherwise, it is only necessary to copy the two Python scripts to a convenient location on the machine(s) that will serve as platform for the browsers.

## Configuration and Use##

Before running the test_browser.py script, it is necessary to specify a list of URLs to be browsed by the agents. Two possibilities are provided for. The list can be hardcoded at the top of the test_browser.py script. Alternatively, a list of URLs can be specified as a commandline argument at run time:

```python3 test_browser.py 'betaport.26maidenlane.net' 'betabank.26maidenlane.net' 'tncc.26maidenlane.net' 'pots.26maidenlane.net' 'gh.26maidenlane.net' 'pha.26maidenlane.net' 'dantes.26maidenlane.net' 'cfa.26maidenlane.net' 'wbpr.26maidenlane.net'```
