pipeline {
    agent any
    options {
        skipStagesAfterUnstable()
    }
    tools {
        maven 'Maven'
    }

    stages {
        stage('Build') {
            steps {
                echo '------ Building ------'
              //  sh 'mvn -B -DskipTests clean compile'
            }
        }
        stage('Test') {
            steps {
                echo '------ Testing ------'
               // sh 'mvn test'
                 snDevOpsChange(changeRequestDetails: """
                {
                    "setCloseCode": false,
                    "pollingInterval":"10",
                    "abortOnChangeCreationFailure": true,
                    "attributes": {
                        "requested_by": {
                        "name": "DevOps System"
                        },
                        "category": "DevOps",
                        "priority": "2",
                        "comments": "This is a sample pipeline script to be added in your change step",
                        "work_notes": "Update this to work_notes",
                        "start_date": "2022-01-05 11:59:59",
                        "end_date": "2022-01-08 11:59:59"
                     }
                }""")
            }
//             post {
//                 always {
//                     junit 'target/surefire-reports/*.xml'
//                 }
                
//             }
        }
        stage('Deploy') { 
            steps {
                echo '------ Deploying ------'
                //sh './jenkins/scripts/deliver.sh' 
//                 snDevOpsChange(changeRequestDetails: """
//                 {
//                     "setCloseCode": false,
//                     "pollingInterval":"10",
//                     "attributes": {
//                         "requested_by": {
//                         "name": "DevOps System"
//                         },
//                         "category": "DevOps",
//                         "priority": "2",
//                         "comments": "This is a sample pipeline script to be added in your change step",
//                         "work_notes": "Update this to work_notes",
//                         "start_date": "2022-01-05 11:59:59",
//                         "end_date": "2022-01-08 11:59:59"
//                      }
//                 }""")
            }
        }
    }
}
