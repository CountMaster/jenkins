pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                echo 'Compilando el proyecto...'
            }
        }
        
        stage('Test') {
            steps {
                echo 'Ejecutando pruebas...'
            }
        }
        
        stage('Deploy') {
            steps {
                echo 'Desplegando la aplicación...'
            }
        }
    }
    
    post {
        success {
            echo 'Pipeline ejecutado con éxito!'
        }
        failure {
            echo 'Error en el pipeline!'
        }
    }
}
