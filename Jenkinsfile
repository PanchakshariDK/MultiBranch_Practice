pipeline{
    agent{
        label 'java-slave'
    }
    environment{
        name = "Dinesh"
        course = "AWS DEVOPS"

    }
    stages{

        stage(Buildstage){
            environment{
                srename = "Ram Charan"
                application = "Java"
            }
            steps{
                echo "Welcome to Build Stage "
                echo "In this stage we are building the application"
                echo " Hi ${name}, Welcome to the ${course} course!!"
                echo "This build stage is doing by ${srename} and after that approval by ${name}"
            }
        }
        stage(DevStage){
            environment{
                devname = "Arjun"
                cloud = "AWS"
            }
            steps{
                echo "This is Developer Stage"
                echo "In this stage we are deploying the code into Dev Environment by ${devname}"
                echo "This Dev stage is doing by ${devname}"
                echo "This stage is also approved by ${name}"
            }
        }
    }
}
