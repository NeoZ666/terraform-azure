### make a container registry and login with its credentials

### docker login neodocker.azurecr.io
put down the username and password from access keys

### docker tag getting-started:latest neodocker.azurecr.io/getting-started

### docker push neodocker.azurecr.io/getting-started

### make a container instance, use aforementioned azure container registry in the options and choose a dns name in networks or advanced while building the instance.

### wait for some mins, done.