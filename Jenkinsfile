Pipeline {
    
    agent {
        label "built-in"
        CustomWorkspace "/mnt/2022Q3"
    }
    stages {
        stage ("2022Q3") {
            steps {
                sh " docker cp index.html 2022Q3:/usr/local/apache2/htdocs"
            }
        }
    }
}
