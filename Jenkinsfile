node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', '9492261286') {

        def customImage = docker.build("9492261286/testimage")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}