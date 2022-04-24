pipeline 
{
    agent any
    
    stages{
        stage(git){
            steps{
            git 'https://github.com/urc1712/java-demo.git'  
            }
        }
        stage(build){
            steps{
                sh 'mvn clean package'
            }
        
        }
        stage(Demo-Stage){
            steps{
                echo "Demo-Stage"
            }
        }
    }
}
