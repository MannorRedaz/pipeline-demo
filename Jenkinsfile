pipeline {
    agent {
        docker{
            images 'node:10'
            args '-p 20000:8080'
        }
    } 
    stages {
        stage('Build') { 
            steps {
                sh 'node -v'
                sh 'echo "hello world !!"'
            }
        }
        // stage('Test') { 
        //     steps {
        //         // 
        //     }
        // }
        // stage('Deploy') { 
        //     steps {
        //         // 
        //     }
        // }
    }
<<<<<<< HEAD
}
=======
}
>>>>>>> 8988ede2a0760d4a4265994f45eac69b996846a7
