
node {
    checkout scm

    docker.withRegistry('https://github.com/quoct01/dockerwebapp.git','dockerhub') {

        def customImage = docker.build("quoct01/nodejstest")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
