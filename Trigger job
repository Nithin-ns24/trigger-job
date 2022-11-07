pipeline{
    agent any
    stages {
        stage('Trigger') {
            steps {
                build job: 'build-1', parameters: [string(name: 'ENV', value: "${params.ENV}")]
                build job: 'build-2', parameters: [string(name: 'ENV', value: "${params.ENV}")]
                build job: 'build-3', parameters: [string(name: 'ENV', value: "${params.ENV}")]
            }
        }
    }
}
