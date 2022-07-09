# Sea Level Rising Project
Create a web banner clock that counts the time when 10mm of sea-level increase from January 01, 2020.

### Install prerequisites
Make sure you have git and brew for your system.

### Get the code
```
git clone git@github.com:jiehyunjkim/SLR.git
cd SLR
```
Or you can download as a zip file

### Install the home-brew if you do not have one
```
bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
### Install the server
```
brew install http-server
```
### Test your build on http://localhost:8000/slr.html
```
python3 -m http.server
```
Once built, the clock widget can see the clock on the web
