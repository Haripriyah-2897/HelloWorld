pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                git 'https://github.com/your-username/hello-world.git'
            }
        }

        stage('Build') {
            steps {
                // Example: running a shell script (hello_world.sh)
                sh 'chmod +x hello_world.sh && ./hello_world.sh'
            }
        }

        stage('Deploy') {
            steps {
                // Add your deployment script or commands here (e.g., copy files, trigger a container)
                echo 'Deploying Hello World Application'
            }
        }
    }
}

