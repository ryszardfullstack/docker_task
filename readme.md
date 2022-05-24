The project is just a simple django app and dockerized. added github action and every git pushing going to build docker iamge and automatically pushing to docker image registry.


A few usefull command:

 `sudo docker inspect <containerid/name>` to check all the network info and everything
` sudo docker image ls` list docker iamge

# github action/workflow:
01. Please `.github/workflow` where we added github action to build docker and push github package restiry to docker package registry

