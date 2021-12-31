node {
    stage('Clone') {
        git 'https://github.com/azessai/jenk_java.git'
    }
    stage('Build') {
        sh 'ls -l'
        sh 'rm -f Main.class'
        sh 'javac Main.java'
    }
    stage('Run') {
        sh 'java Main'
    }
}
