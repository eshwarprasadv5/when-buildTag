pipeline{
    agent any
    stages{
        stage('Build'){
            when{
               buildingTag()
            }
            steps{
                echo 'buildingTag() code builded'
            }
        }
    }
}
