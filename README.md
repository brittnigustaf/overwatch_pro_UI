# Overwatch Pro

A website using ReactJS and Node

## Using the Node Server

```sh
npm install
node server.js
```

Then visit <http://localhost:3000/>.

## Changing the port

You can change the port number by setting the `$PORT` environment variable before invoking any of the scripts above, e.g.,

```sh
PORT=3001 node server.js
```

## Running the unit tests

...sh
cd src/test
jasmine
...

## Running the JSON Builder

...sh
cd src/scripts/JSONBuilder
node builder.js
...

JSON files are put into "src/scripts/JSONBuilder/out"
