# Heroku Deploy for ubykuo Wiki powered by Wiki.js

This repo is an Heroku app definition for Wiki.js.  
For information about Wiki.js, including detailed installation steps, read the following links:

- [Official Website](https://wiki.js.org/)
- [Installation Guide](https://wiki.js.org/get-started.html)
- [GitHub Repository](https://github.com/Requarks/wiki)

To modify the configuration beyond what's available through environment variables, then:
* Modify this repo
* Commit the changes
* Add heroku remote with `heroku git:remote -a ubykuo-wiki`
* `git push heroku`, or if you are on a branch, `git push heroku mybranch:master`
