# CyberTechWatch
<a href="https://snyk.io/test/github/MehdizadeMilad/cybertechwatch?targetFile=requirements.txt"><img src="https://snyk.io/test/github/MehdizadeMilad/cybertechwatch/badge.svg?targetFile=requirements.txt" alt="Known Vulnerabilities" data-canonical-src="https://snyk.io/test/github/MehdizadeMilad/cybertechwatch?targetFile=requirements.txt" style="max-width:100%;"></a>

A Monitoring tool for Cyber Threats. (Collect Cyber News from different RSS Feeds).

at my job, I needed to check cyber threat news daily from multiple news sources; So I developed this python tool to ease my routine.

## Getting Started
this tool reads multiple cybernews feeds and organizes them into a <i>docx</i> file.


### Prerequisites

- Python
- python pip


### Installing

in ```windows``` run the following in <i>command prompt</i> or just double-click on  ``` setup.bat ``` then ```run.bat```

```
setup.bat

run.bat
```

for ```linux``` environments:

```
sh ./setup.sh

```
then wait for the result to be saved in <b>reports</b> directory.

from now on just ``` ./run.sh ``` to get the news.

## Modules used

* [feedparser](https://pypi.org/project/feedparser/) - Parse Atom and RSS feeds in Python
* [difflib](https://pymotw.com/2/difflib/) - Compare sequences, especially lines of text
* [python-docx](https://python-docx.readthedocs.io/en/latest/) - creating and updating Microsoft Word (.docx) files
* [Pool](https://sebastianraschka.com/Articles/2014_multiprocessing.html) - multiprocessing module
* [traceback](https://docs.python.org/2/library/traceback.html) -  Print stack traces of Python programs
* [python-dateutil](https://pypi.org/project/python-dateutil/) - datetime utilities
