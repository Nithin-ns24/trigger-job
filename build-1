pipeline {
    agent any
    parameters {
        string(name: 'ENV', description: 'enter env value')
    }
    stages {
        stage('Example') {
            steps {
                script{
                    echo "${params.ENV}"
                }
            }
        }
    }
}
