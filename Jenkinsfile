pipeline {
    agent any 
    stages {
        stage('Stage 1') {
            steps {
                echo 'Hello world!' 
                sonar-scanner \
  -Dsonar.projectKey=Hareesh6666 \
  -Dsonar.organization=hareesh6666 \
  -Dsonar.host.url=https://sonarcloud.io \
  -Dsonar.login=d6d6b073917e10fc333aac1ccdca14d659ac3085
            }
        }
    }
}
