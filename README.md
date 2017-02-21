# **Analogy server** for IBM Bluemix
Developed by [Craig Carlson][], at [RPI Cognitive Science Department][], a python web server that build analogies between concepts in knowledge bases. The original repository is [https://github.com/carlsc2/analogy][].

The app supports AIMind format and serves as analogy engine in [RelLink Story Narration][].

## Access via Bluemix
[https://rellink-analogy.mybluemix.net][]

## Run the app locally
1. [Install VC++ 2015 Build Tools][] (Windows only)
2. [Install Python][] version 3.5+
+ cd into this project's root directory
+ Run `pip install -r requirements.txt` to install the app's dependencies
+ Run `python webinterface.py`
+ Access the running app in a browser at <http://localhost:5000>

## Deploy to Bluemix
[![Deploy to Bluemix](https://bluemix.net/deploy/button.png)](https://bluemix.net/deploy?repository=https://github.com/rellink/analogy) <- Simply hit the button

## Contributors
+ [Craig Carlson][] - Developer & Creator of the analogy-making algorithm
+ [Dr. Mei Si][] - Supervisor

[Craig Carlson]: https://github.com/carlsc2
[RPI Cognitive Science Department]: http://www.cogsci.rpi.edu/
[https://github.com/carlsc2/analogy]: https://github.com/carlsc2/analogy
[RelLink Story Narration]: https://github.com/rellink/story-narration
[https://rellink-analogy.mybluemix.net]: https://rellink-analogy.mybluemix.net
[Install VC++ 2015 Build Tools]: http://landinghub.visualstudio.com/visual-cpp-build-tools
[Install Python]: https://www.python.org/downloads/

[Dr. Mei Si]: http://si.hass.rpi.edu/
