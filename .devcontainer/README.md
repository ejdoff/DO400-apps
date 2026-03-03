# Using the dev container

The `Dockerfile` expects a `oc` executable that could not be uploaded to github.
So the committed `Dockerfile` misses the copy of the `oc` command,
but does prepare for using this `oc` command.

Download the missing `oc` file from a OpenShift cluster and manually copy that file into
the dev container that is created by your IDE.

