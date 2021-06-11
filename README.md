# factorial_fibonacci
![Snyk Vulnerabilities for GitHub Repo](https://img.shields.io/snyk/vulnerabilities/github/kisakyekenneth/factorial_fibonacci?logo=Github&style=flat-square)
![Snyk Vulnerabilities for GitHub Repo](https://img.shields.io/snyk/vulnerabilities/github/TovikMay/Jenk?logo=Github)

pipeline {
    agent any
    stages {
        stage("build"){
            steps{
                echo 'Building the application ...'
            }
        }

        stage("test"){
            steps{
                  echo 'Testing the application ...'
            }
        }

        stage("deploy"){
            steps{
                echo 'Deploying the application ...'
            }
        }
    }
}
