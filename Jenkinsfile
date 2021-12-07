pipeline{
    agent any
    stages {
        stage("git")
        {
            steps{
                git branch: 'main', url: 'https://github.com/agarwalyash02/jenkins_test.git'
            }
        }
        stage("copy")
        {
            steps{
                sh "cp index.html /var/www/html/"
            }
        }
    }
}
