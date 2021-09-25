# Docker Autoheal With Gotify

This is a fork of https://github.com/willfarrell/docker-autoheal with the added functionality of sending gotify alerts. 

Image can be found at ghcr.io/tchilderhose/autoheal:latest

## ADDED ENV VARS
```
GOTIFY_TITLE=Title of message
GOTIFY_URL=https://gotify.example.com
GOTIFY_TOKEN=GOTIFY_APP_TOKEN
GOTIFY_STARTUP_ALERT_PRIORITY=1 //priority of the "Monitoring containers for unhealthy status in..." message. Default 1 
GOTIFY_ALERT_PRIORITY=5 //priority of the other alerts. Default 5
```
