node {
    stage('Clone') {
        git 'https://github.com/azessai/jenk_java.git'
    }
    stage('Build') {
        sh 'javac Main.java'
    }
    stage('Run') {
        sh 'java Main'
    }
}
