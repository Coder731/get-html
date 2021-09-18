# get-html

## To Run / Usage
### Extensions
Ensure have installed:

    Google Developer
        GitPod Browser Extension 

            Visual Studio Code

                Primarily:
                - Live Server
                - Code Runner

                Secondarily:
                - Live Preview
                - Python
                - GitHub Pull Requests and Issues

### To Run
    Live Server
        - Click 
            - Go Live!
                - in bottom right corner of browser

    To run get_html.py
        either use:
            Code Runner
                - Press
                    - Ctrl + Alt N
                - (to stop press: Ctrl + Alt + M)
        or
            Preferred option:
                in terminal (Ctrl + J or Ctrl + ')
                    python3 get_html.py

    
## Development
### Get News (python)
- extract.py [Extracting text from HTML file using Python](https://stackoverflow.com/questions/328356/extracting-text-from-html-file-using-python)
#### beautifulsoup4 (command line interface)
    pip3 install beautifulsoup4 
- [beautifulsoup4 4.10.0](https://pypi.org/project/beautifulsoup4/)
### display command line Output on HTML Page
- [Showing command line output on a html page](https://stackoverflow.com/questions/53860093/showing-command-line-output-on-a-html-page)

#### xterm.js
    npm install xterm
        - index.html code from this site
- [Xterm.js | Build terminals in the browser](https://xtermjs.org/)


### Update dependencies in requirements.txt for Heroku deployment
    pip3 freeze > requirements.txt
check old and new each time

## Bug

Background:
xterm.js running from index.html
running get_html.py

Issue:
    python3 get_html.py
    - prints output to local IDE terminal

Potential Fix:
Run command in xterm.js
    python3 get_html.py

Potential Better Way (Reference): 
- [cs01 / pyxtermjs](https://github.com/cs01/pyxtermjs)

## Bug

Search String:
xterm.js not taking keyboard input

Search Result:
[How to make xterm.js accept input?](https://stackoverflow.com/questions/44447473/how-to-make-xterm-js-accept-input)

Answer given:

xtermjs is a library that expose an api, that allow us to build fully xterm based terminal emulator. But for every of the terminal functionalities you need to implement it through the api. Using the event listeners. And handling them. And combining it with others packages depend on what you want to achieve.

## References
- extract.py [Extracting text from HTML file using Python](https://stackoverflow.com/questions/328356/extracting-text-from-html-file-using-python)
- pip3 install beautifulsoup4 [beautifulsoup4 4.10.0](https://pypi.org/project/beautifulsoup4/)
