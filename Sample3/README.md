Instructions from the app developer

* this app listens on port 3000
* it should use alpine package manager to install tini: 'apk add --update tini'
* it should create directory /usr/src/app for app files with 'mkdir -p /usr/src/app'
* Node uses a "package manager", so it needs to copy in package.json file
* it needs to run 'npm install' to install dependencies from that file
* it needs to start container with command 'tini -- node ./bin/www'
