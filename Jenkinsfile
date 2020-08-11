node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'dockerrams') {

        def customImage = docker.build("rameshpv09/game-image")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
