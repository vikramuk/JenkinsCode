pipeline {
    agent any 
    stages {
        stage('Stage 1') {
            steps {
                echo 'Hello world!' 
            }
        }
        stage('State 2'){
            steps{
                echo "Testing Stage 2"
            }   
        }
        stage('State 3'){
            steps{
                echo "Testing Stage 3"
                //cmd "C:\\ProgApps\\apache-maven-3.6.0\\bin\\mvn -X -Dmaven.test.failure.ignore clean package"  / Error Here
            }   
        }
    }
}
