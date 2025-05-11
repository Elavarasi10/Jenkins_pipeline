pipeline{
    agent any
    stages {
        stage ("Dev project") {
            steps {
                echo "print my dev project"
            }
        }
        stage ("Test project"){
            agent {
                label 'dev'
            }
            steps {
                echo "print my test project"
            }
        }
        stage ("prod project"){
            steps {
                echo "print my prod project"
            }
            
        }
    }
}
