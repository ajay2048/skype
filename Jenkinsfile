node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'dockerHub_id') {

        def customImage = docker.build("7989461575/ajaytest")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
