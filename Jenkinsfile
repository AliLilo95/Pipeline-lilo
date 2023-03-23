/* Requires the Docker Pipeline plugin */
pipeline {
    agent any
    stages {
        stage('Testing Github localy') {
            steps {
                dir('C:\Users\Alili\OneDrive\Skrivbord\Gymgrossisten_Tester'){
                    bat 'python -m unittest'
            }
        }
    }
        stage('Clean Workspace'){
           steps {
               cleanWs()
    }
        }
    }
}
