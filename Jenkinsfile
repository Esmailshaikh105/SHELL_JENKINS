pipeline {
     agent any
    parameters {
        string(name: 'NAME', defaultValue: 'Esmail', description: 'Plz enter your name')
        string(name: 'AGE', defaultValue: '26', description: 'Plz enter your age')
    }
    stages {
        stage('Build') {
            steps {
                sh 'chmod +X ./esma.sh'
                sh './esma.sh ${params.NAME} ${params.AGE}'
            }
        }


    }
}
