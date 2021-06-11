# factorial_fibonacci
![Snyk Vulnerabilities for GitHub Repo](https://img.shields.io/snyk/vulnerabilities/github/kisakyekenneth/factorial_fibonacci?logo=Github&style=flat-square)
![Snyk Vulnerabilities for GitHub Repo](https://img.shields.io/snyk/vulnerabilities/github/TovikMay/Jenk?logo=Github)
![GitHub top language](https://img.shields.io/github/languages/top/TovikMay/Jenk?style=for-the-badge)

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
