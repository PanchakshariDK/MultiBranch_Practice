pipeline{
    agent{
        label'java-slave'
    }

    environment{
        // key = value
        course = "Kubernetes"
        name = "Dinesh"
        cloud = "AWS"
    }

    stages{
        stage('First Stage'){
            environment{
                Cloud = "GCP"
            }
            steps{
                echo"*** This is a building stage *****"
                echo"***** Welcome to ${name}"
                echo"***** Welcome to ${course}, All the Best ${name}"
                echo"**** Thanks for chosing ${Cloud}******"
            }
        stage('Second Stage'){
            steps{
                echo"*** This is a building stage *****"
                echo"***** Welcome to ${name}"
                echo"***** Welcome to ${course}, All the Best ${name}"
            }
            
        }
    }
}


    
