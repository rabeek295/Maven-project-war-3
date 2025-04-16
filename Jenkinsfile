pipeline {
    agent{
        label'slave_node'
    }
        tools{
            maven'maven'
        }
    stages {
        stage('maven project') {
            steps {
                sh'mvn clean package' 
            }
        }
    }
}
