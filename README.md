
This repository contains material to build a docker container for the headphones application.

Build
=====

'''docker build --tag headphones:latest .'''

Run
===

'''docker run --name headphones --publish 8181:8181 --detach headphones'''

Then navigate to http://localhost:8181/
