pipeline {
    agent any

    stages {
        stage('Sample job')
         {
            steps 
            {
                build 'JulySampleJob'
            }
         }
        stage('SmokeTest')
         {
            steps 
            {
                build 'SeleniumTestforFreeLanceAppln_MY'
            }
         }
         stage('RegressionTest')
         {
            steps 
            {
                build 'SeleniumTestforFreeLanceAppln_MY with Triggers'
            }
         }
    }
}
