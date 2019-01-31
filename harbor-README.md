# Harbor #

This harbor provides docker configuration for your ionic project. It consist of node container.

## Starting a harbor ionic serve (in docker) ##

To start the docker environment with ionic use:

`harbor ionic-serve`

This will start the docker container and start also ionic serve for development.

## Daily usage ##

In this section you can find all commands supported by harbor ionic.

`harbor rebuild` will stop and destroy all containers then starts again all containers, build them if changes has been made.

`harbor ionic` will run ionic serve command on node container.

`harbor npm` will run npm command on node container and pass all additional arguments to npm.

`harbor yarn` will run yarn command on node container and pass all additional arguments to yarn.

`harbor gulp` will run gulp command on node container from node modules and pass all additional arguments to gulp.