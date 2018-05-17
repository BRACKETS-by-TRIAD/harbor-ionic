# Adding Harbor Ionic #

In order to initialize harbor ionic to the existing project or when starting a new project (in empty folder) use
`harbor add ionic` 

# Starting a ionic harbor (docker) #

To start the docker environment with ionic use:
`harbor ionic`

This will start the docker container and start also ionic serve for development.

# Daily usage #

In this section you can find all commands supported by harbor ionic.

`harbor rebuild`

Stops and destroy all containers also with volumes, delete testing database path, rebuild docker images and then starts again all containers.

`harbor ionic`

Run ionic serve command on node container.

`harbor npm`

Run npm command on node container and pass all additional arguments to npm.

`harbor yarn`

Run yarn command on node container and pass all additional arguments to yarn.

`harbor gulp`

Run gulp command on node container from node modules and pass all additional arguments to gulp.








