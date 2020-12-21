#!groovy

pipeline 
{
    agent any
    
    options {
          timestamps()
    }

    stages {
        
        stage("Build")
        {
            steps{
                
                     echo "Sunt aici etapa Build"
            }
        }
        
        stage("Testing")
        {
            steps{
                    echo "Sunt aici etapa Test"
                    bat 'eShopOnWeb-master/tests/UnitTests/Web/Extensions/CacheHelpersTests/GenerateTypesCacheKey.cs'
            }
        }
        
        
    }

}
