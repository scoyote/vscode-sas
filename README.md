# vscode-sas
demonstration module for running vs code with SAS in a linux container

docker run -it -p 38080:38080 \
 -v '/Users/samuelcroker/OneDrive - SAS':/SASOneDrive \
 -v './SASRemote/:/sasremote/
registry.unx.sas.com/sacrok/sas94_2021:latest /bin/bash
