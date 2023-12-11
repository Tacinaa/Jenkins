node {
    stage('Clone') {
        git branch: 'main', url: 'https://github.com/Tacinaa/Jenkins.git'
    }
    stage("Build") {
        bat 'javac Main.java'
    }
    stage("Run") {
        bat 'java Main'
    }
}