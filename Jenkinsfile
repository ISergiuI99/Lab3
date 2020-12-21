#!groovy

pipeline 
{
    agent any
    
    options {
          timestamps()
    }
        
        stage("Testing")
        {
            steps{
                    bat 'eShopOnWeb-master/tests/UnitTests/Web/Extensions/CacheHelpersTests/GenerateTypesCacheKey.cs'
            }
        }
        
        
    }

}
