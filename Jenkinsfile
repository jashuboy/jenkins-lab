pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Pulling code from GitHub'
            }
        }

        stage('Build') {
            steps {
                echo 'Simulating build process'
                bat 'echo Build successful'
            }
        }

        stage('Test') {
            steps {
                echo 'Running basic tests'
                bat 'echo Tests passed'
            }
        }
    }

    post {
        success {
            echo 'Pipeline completed successfully'
        }
        failure {
            echo 'Pipeline failed'
        }
    }
}





// pipeline{
//     agent any
//     stages{
//         stage('Build'){
//             steps{
//                 echo 'Building Application'
//             }
//         }
//         stage('Test'){
//             steps{
//                 echo 'Testing Application'
//             }
//         }
//         stage('Deploy'){
//             steps{
//                 echo 'Deploying Application'
//             }
//         }
//     }
// }

     
