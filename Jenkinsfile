pipeline{
    agent any
    environment{
    PATH="/opt/maven3/bin:$PATH"
    }
        stages{
            stage("Git"){
                steps{
                    git 'https://github.com/wickedrishav/hello-world.git'    
            }
        }
            stage(Mvn){
                steps{
                    sh "mvn clean package"  
                }
            }
    }
}
