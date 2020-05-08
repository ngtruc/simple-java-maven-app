node {
    def mvnHome = tool 'Maven'
    stage('Checkout') {
        git 'https://github.com/cloudogu/jenkinsfiles'
    }
    stage('Build') {
        sh "mvn -B package"
    }
}