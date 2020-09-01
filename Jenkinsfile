node {
    stage('build and run') {
        git 'https://github.com/priximmo/jenkins-helloworld.git'
        sh label: '', script: '''
        javac Main.java
        java Main '''
    }
}
