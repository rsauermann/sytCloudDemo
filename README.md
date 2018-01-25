# Heroku Webapp simple test #
Systemtechnikreferat Demobeispiel

## Requirements ##
* Heroku Account
* Python 3.6
* (git kann mittels Heroku CLI mitinstalliert werden)

## Setup Heroku CLI ##
Heroku CLI herunterladen <https://devcenter.heroku.com/articles/heroku-cli#download-and-install>

`heroku login`

## Testprojekt ##
Testprojekt clonen <https://github.com/rsauermann/sytCloudDemo.git> und `cd sytCloudDemo`

## Heroku App erstellen ##
App erstellen mittels
`heroku create <name>` bzw.
`heroku create`

## App auf Heroku deployen ##
`git push heroku master`

## Web-Prozess Starten ##
`heroku ps : scale web=1`

## App öffnen ##
`heroku open`
