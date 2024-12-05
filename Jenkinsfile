pipeline {
    agent any
    
    stages {
        stage('Clone Repository') {
            steps {
               
                git 'https://github.com/Anuja-Sannak/exam_q1.git'
            }
        }
        
        stage('Run Shell Script') {
            steps {
              
                sh './date_time.sh'
            }
        }
    }
}
