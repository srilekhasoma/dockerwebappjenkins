node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'Lekha@1998') {

        def customImage = docker.build("9492261286/testimage")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}