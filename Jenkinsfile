node('master') 
{
    stage('ContinuousDownload_loans') 
    {
         git 'https://github.com/intelliqittrainings/maven.git'
    }
     stage('ContinuousBuild_loans') 
    {
        sh label: '', script: 'mvn package'
    }
    
    
    
    
}
