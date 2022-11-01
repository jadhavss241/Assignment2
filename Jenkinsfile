pipeline {
    
    agent {
        label "built-in"
        CustomWorkspace "/mnt/2022Q1"
    }
    stages {
        stage ("2022Q1") {
            steps {
                sh " docker cp index.html 2022Q1:/usr/local/apache2/htdocs"
            }
        }
    }
}
