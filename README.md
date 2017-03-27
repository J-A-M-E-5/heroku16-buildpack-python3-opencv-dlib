# Heroku (beta stack v16) buildpack with OpenCV & DLib (for Python 3) 

## Info
This buildpack provides a self-contained environment for Python OpenCV/DLib apps.

* Heroku Beta Stack v16 (heroku/heroku:16-build)
* Python version: 3.4.x
* Numpy version: 1.12.1
* OpenCV version: 3.2.0-dev
* DLib version: 19.4.0

This is a stand-alone buildpack which saves compiling time. Use pip / requirements.txt to install additional dependencies for your projects.

## Credits

Based off of numerous old (non-working) examples I found on the internet, this has been heavily tweaked to provide the smallest vendor file possible for quick installation.

Written by James Martin ( https://www.upwork.com/o/profiles/users/_~0187d049a1adf19dda/ ).

I am available to write custom buildpacks for Heroku, Docker, Nixos etc...
