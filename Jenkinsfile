pipeline{
    agent any
    stages{
        stage(Bedingt){
            when { changeset "**.txt" }
            steps{
                echo "first"
            }
        }
        stage(Bedingt2){
            when{ changeset pattern: "**.txt"}
            steps{
                echo "second"
            }
        }
        stage(NichtBedingt){
            steps{
                echo "Hello"
            }
        }
    }
}
