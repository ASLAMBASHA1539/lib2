pipeline{
    agent any
    stages{
        stage('fox_build'){
            steps{
                   script {
                    // Clone the repository
                    git 'https://github.com/ASLAMBASHA1539/lib2.git'

                    // Execute the shell script
                    sh 'syntax_check.sh'
                  
                }
            }
        }
    }
}
