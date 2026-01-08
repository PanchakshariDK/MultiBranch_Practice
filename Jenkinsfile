pipeline{
    agent{
        label'java-slave'
    }

    environment{
        name = "Dinesh"
        course = "Jenkins"
        cloud = "AWS"
    }

    stages{
        stage(firststage){
            steps{
                echo " Welcome to first stage!!!"
                echo " Hii ${name}, Welcome to the course ${course} in the domain ${cloud}. All the BEST!! "
                }
            
        }

        stage(secondstage){
            environment{
                cloud = "GCP"
            }
            steps{
                echo " Welcome to Second stage!!! "
                echo " Welcome to the course ${cloud} and to the course ${course}"
            }
            
        }
    }
}
