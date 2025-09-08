pipeline{
  agent any 
    
      environment{
                 REGISTRY = "docker.io"
                 IMAGE_NAME = "image1"
                 IMAGE_TAG = "latest"
                 SERVER_PORT = "8081"
                }
     stages{
            stage('Checkout'){
                    steps{
                         git branch: 'master', url:'https://github.com/Curiousgoal202/azure11111.git'
                         }
                  }
           stage('Build'){
                    steps{
                         echo 'Building'
                          }
                        }
                       }
                    }

    
