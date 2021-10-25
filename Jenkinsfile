pipeline{
    agent any
    stages {
        stage("Compiler"){
            steps {
                echo "no need to build python code"
            }
        }
        stage("Unit Test"){
            steps {
                sh "python my_file.py"
            }
        }
    }
}