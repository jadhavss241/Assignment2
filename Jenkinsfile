pipeline {
    
    agent {
        label "built-in"
        CustomWorkspace "/mnt/2022Q2"
    }
    stages {
        stage ("2022Q2") {
            steps {
                sh " docker cp index.html 2022Q2:/usr/local/apache2/htdocs"
            }
        }
    }
}
