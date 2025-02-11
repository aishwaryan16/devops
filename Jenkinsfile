pipeline {
    agent any
    stages {
        stage('Test') {
            steps {
                bat '"C:\\Program Files\\Common Files\\Oracle\\Java\\javapath\\java.exe" --version'
                bat '"C:\\Program Files\\Common Files\\Oracle\\Java\\javapath\\javac.exe" p1.java'
                bat '"C:\\Program Files\\Common Files\\Oracle\\Java\\javapath\\java.exe" p1'
            }
        }
    }
}
