def buildImage = docker.build("ubuntu", "${WORKSPACE}/.jenkins")
buildImage.inside {
    dir("${WORKSPACE}src/Linux") {
        sh 'touch myfile'
    }
}