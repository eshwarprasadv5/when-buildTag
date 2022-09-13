pipeline{
    agent any
    stages{
        stage('Build'){
            when{
               buildTag()
            }
            steps{
                echo 'buildTags() code builded'
            }
        }
    }
}
