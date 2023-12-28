pipeline
{
    agent any
    stages
    {
        stage('fetch')
        {
            steps{
            git branch: 'main', url: 'https://github.com/pulkitpan/maven.git'
            }
        }
        
        stage('build')
        {
            steps{
            build 'https://github.com/pulkitpan/maven.git'
            }
        }
        stage('Test')
        {
            steps{
            echo "Testing..Phase"
            }
        }
        stage('Deploy')
        {
            steps{
            echo 'Deploying..Phase'
            }
        }
    }
}
