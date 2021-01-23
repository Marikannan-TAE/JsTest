pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                bat 'echo "Hello World"'
            }
        }
        stage('BuildMore')
        {
           steps {
                    bat '''
                    echo "Multiline shell steps works too"
                   attrib
                '''
            }
        }
    }
}

