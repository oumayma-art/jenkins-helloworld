node {
    stage('Clone') {
        git 'https://github.com/oumayma-art/jenkins-helloworld.git'
    }
    stage('build') {
        sh label: '', script: 'javac Main.java'
    }
    stage('Run') {
        sh label: '', script: 'java Main'
    }
}
