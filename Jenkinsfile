pipeline 
{
    
    agent any
    

    stages {
        
        stage('build')
        
        {
            steps {
                echo 'Build test'
            }
        }
        
        stage('test')
         
        {
            steps {
                echo 'test de code'
            } 
        }
        
        stage('deploye')
        
        {
            steps {
                echo 'deploye du code'
            }
        }
    }
    
    post
    {
        always
        {
            emailext body: '', subject: 'Pipeline status', to: 'tekamyvan93@gmail.com'
        }
        
        
    }
    
}
