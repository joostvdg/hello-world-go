node {
    def goHome = tool name: 'Go Latest', type: 'org.jenkinsci.plugins.golang.GolangInstallation'
    env.PATH = "${goHome}/bin:${env.PATH}"
    env.GOROOT = "${goHome}"

    stage('SCM') {
        checkout scm
    }

    stage('Build') {
        sh 'go build src/main.go'
    }

    stage('Run'){
        sh 'go run src/main.go'
    }
}