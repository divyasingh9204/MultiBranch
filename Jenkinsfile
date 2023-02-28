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
                sh 'mvn -B -DskipTests clean compile'
            }
        }
        stage('Test') {
            steps {
                echo '------ Testing ------'
               // sh 'mvn test'
               // snDevOpsChange changeCreationTimeOut: 30, changeRequestDetails: '{ "attributes": { "short_description": "Test description", "priority": "1", "start_date": "2021-02-05 08:00:00", "end_date": "2022-04-05 08:00:00", "justification": "test justification", "description": "test description", "cab_required": true, "comments": "This update for work notes is from jenkins file", "work_notes": "test work notes", "assignment_group": "a715cd759f2002002920bde8132e7018" }, "setCloseCode": false }', changeStepTimeOut: 20, pollingInterval: 10
               //  snDevOpsChange abortOnChangeStepTimeOut: false, changeCreationTimeOut: 30, changeRequestDetails: '{ "attributes": { "short_description": "Test description", "priority": "1", "start_date": "2021-02-05 08:00:00", "end_date": "2022-04-05 08:00:00", "justification": "test justification", "description": "test description", "cab_required": true, "comments": "This update for work notes is from jenkins file", "work_notes": "test work notes", "assignment_group": "a715cd759f2002002920bde8132e7018" }, "setCloseCode": false }', changeStepTimeOut: 20, pollingInterval: 10
               // snDevOpsChange changeCreationTimeOut: 30, changeRequestDetails: '{ "attributes": { "short_description": "Test description", "priority": "1", "start_date": "2021-02-05 08:00:00", "end_date": "2022-04-05 08:00:00", "justification": "test justification", "description": "test description", "cab_required": true, "comments": "This update for work notes is from jenkins file", "work_notes": "test work notes", "assignment_group": "a715cd759f2002002920bde8132e7018" }, "setCloseCode": false }', changeStepTimeOut: 60, pollingInterval: 10
              //  snDevOpsChange abortOnChangeStepTimeOut: false, changeCreationTimeOut: 30, changeRequestDetails: '{ "attributes": { "short_description": "Test description", "priority": "1", "start_date": "2021-02-05 08:00:00", "end_date": "2022-04-05 08:00:00", "justification": "test justification", "description": "test description", "cab_required": true, "comments": "This update for work notes is from jenkins file", "work_notes": "test work notes", "assignment_group": "a715cd759f2002002920bde8132e7018" }, "setCloseCode": false }', changeStepTimeOut: 60, pollingInterval: 10
               // snDevOpsChange changeCreationTimeOut: 50, changeRequestDetails: '{ "attributes": { "short_description": "Test description", "priority": "1", "start_date": "2021-02-05 08:00:00", "end_date": "2022-04-05 08:00:00", "justification": "test justification", "description": "test description", "cab_required": true, "comments": "This update for work notes is from jenkins file", "work_notes": "test work notes", "assignment_group": "a715cd759f2002002920bde8132e7018" }, "setCloseCode": false }', changeStepTimeOut: 60, pollingInterval: 10
               // snDevOpsChange abortOnChangeCreationFailure: false, changeCreationTimeOut: 50, changeRequestDetails: '{ "attributes": { "short_description": "Test description", "priority": "1", "start_date": "2021-02-05 08:00:00", "end_date": "2022-04-05 08:00:00", "justification": "test justification", "description": "test description", "cab_required": true, "comments": "This update for work notes is from jenkins file", "work_notes": "test work notes", "assignment_group": "a715cd759f2002002920bde8132e7018" }, "setCloseCode": false }', changeStepTimeOut: 60//, pollingInterval: 10
            snDevOpsChange changeCreationTimeOut: 50, changeRequestDetails: '{ "attributes": { "short_description": "Test description", "priority": "1", "start_date": "2021-02-05 08:00:00", "end_date": "2022-04-05 08:00:00", "justification": "test justification", "description": "test description", "cab_required": true, "comments": "This update for work notes is from jenkins file", "work_notes": "test work notes", "assignment_group": "a715cd759f2002002920bde8132e7018" }, "setCloseCode": false }', changeStepTimeOut: 70, pollingInterval: 10
            }
           // post {
           //     always {
           //         junit 'target/surefire-reports/*.xml'
                    
           //         snDevOpsChange()
           //    }
                
           // }
        }
        stage('Deploy') { 
            steps {
                echo '------ Deploying ------'
                //sh './jenkins/scripts/deliver.sh' 
//snDevOpsChange changeCreationTimeOut: 30, changeRequestDetails: '{ "attributes": { "short_description": "Test description", "priority": "1", "start_date": "2021-02-05 08:00:00", "end_date": "2022-04-05 08:00:00", "justification": "test justification", "description": "test description", "cab_required": true, "comments": "This update for work notes is from jenkins file", "work_notes": "test work notes", "assignment_group": "a715cd759f2002002920bde8132e7018" }, "setCloseCode": false }', changeStepTimeOut: 20, pollingInterval: 10
            }
        }
    }
}
