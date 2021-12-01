pipeline
{
    agent any
    stages
    {
        stage ('execute commands')
        {
            steps
            {
                sh 'touch abc.txt'
                sh 'echo $JENKINSFILE'
            }
        }
    }
}
