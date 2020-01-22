pipeline{
    agent none
    stages{
        stage(CreateAndDeploy){
            agent{
                docker{
                    image 'maven:latest'
                    args '--network=documentation_sonarnet'
                }
            }
            steps{
		sh 'ls'
            }
        }
    }
}
