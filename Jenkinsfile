pipeline{
    agent any
    stages{
        stage('Build'){
            when{
                buildTags()
            }
            steps{
                echo 'buildTags() code builded'
            }
        }
    }
}
