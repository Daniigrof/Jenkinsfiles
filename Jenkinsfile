pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                  writeFile file: 'MyName.txt', text: 'Working with files the Groovy way is easy.'
            }
        }
    }
}
