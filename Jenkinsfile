pipeline {
    agent{
        label'Slave_Node'
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
