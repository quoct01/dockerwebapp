
node {
    checkout scm

<<<<<<< HEAD
    docker.withRegistry('https://registry.hub.docker.com','dockerhub') {
=======
    docker.withRegistry('https://github.com/quoct01/dockerwebapp.git','dockerhub') {
>>>>>>> bfbed772de5d9f1e0cdd340374b5e6be1312db49

        def customImage = docker.build("quoct01/nodejstest")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
