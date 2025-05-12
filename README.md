# appstake web site

## Project Structure

Currently only /index.html and /assets are used. There is also a Flutter project, but not currently, probably should go away unless works well when compiled to HTML and javascript and not too heavy on initial load

## Deployment

Github actions in .github deploy /index.html and /assets to firebase hosting glevik@gmail.com, appstake_web

## Issues

Github deploy action doesn't work cuz it can't find firebase.json (which should not be checked in in the first place). May be env variables?