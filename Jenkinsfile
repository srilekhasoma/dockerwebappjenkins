node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'dockerHub') {

        def customImage = docker.build("docker.io/9492261286/testimage")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}