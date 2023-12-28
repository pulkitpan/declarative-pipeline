pipeline
{
    agent any
    stages
    {
        stage('fetch')
        {
            git branch: 'main', url: 'https://github.com/pulkitpan/maven.git'
        }
        
        stage('build')
        {
            build 'maven_job'
        }
        stage('Test')
        {
            echo "Testing..Phase"
        }
        stage('Deploy')
        {
            echo 'Deploying..Phase'
        }
    }
}
