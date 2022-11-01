pipeline {
    
    agent {
        label {
        label 'built-in'
        customWorkspace '/mnt/2022Q1'
        }
    }
    stages {
        stage ('2022Q1') {
            steps {
                sh 'docker cp index.html 2022Q1:/usr/local/apache2/htdocs'
            }
        }
    }
}
