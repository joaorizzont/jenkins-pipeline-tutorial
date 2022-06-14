pipeline {
    agent {
        label 'maven'
    }

    parameters {
        booleanParam(name: 'CLEAN_BEFORE_BUILD', description: 'Limpar o workspace antes de rodar o build')
    }

    stages {
        stage('Clean') {
            steps {
                echo 'stage clean'
            }

            when {
                expression {
                    return params.CLEAN_BEFORE_BUILD
                }
            }
        }

        stage('Compile') {
            steps {
                echo 'stage clean'
            }
        }

        stage('Test') {
            steps {
                echo 'stage clean'
            }
        }
    }
}
