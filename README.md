# playgrounddevfile

Copied from ExpressJS Sample Application

## Important to know

- secret file with credentials for the image registry must be created in the admin-che namespace
- theia must be started with hostaname="0.0.0.0" so that it listens also to external processes
- in the che-editor:yaml, add the attribute type: main to the endpoint to be used to add the workspace
- url to open/create the workspace: https://192.168.49.2.nip.io/#https://github.com/MichelSc/playgrounddevfile

## Issues still to be solved

- provide credentials to github for cloning the workspace
- start theia in the che workspace

## Contents of original ReadMe

# Developer Workspace
[![Contribute](http://beta.codenvy.com/factory/resources/codenvy-contribute.svg)](http://beta.codenvy.com/f?id=r8et9w6vohmqvro8)

# Stack to use

FROM [codenvy/node](https://hub.docker.com/r/codenvy/node/)

# How to run

| #       | Description           | Command  |
| :------------- |:-------------| :-----|
| 1      | Run | `cd ${current.project.path}/app && node app.js` |
