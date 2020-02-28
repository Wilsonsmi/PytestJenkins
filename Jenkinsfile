#!groovy
/*
 * Copyright 2016 Testbirds GmbH
 *
 * Licensed under the Apache License, Version 2.0 (the "License");
 * you may not use this file except in compliance with the License.
 * You may obtain a copy of the License at
 *
 * http://www.apache.org/licenses/LICENSE-2.0
 *
 * Unless required by applicable law or agreed to in writing, software
 * distributed under the License is distributed on an "AS IS" BASIS,
 * WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 * See the License for the specific language governing permissions and
 * limitations under the License.
 */


pipeline {
    agent { }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
    }
}

// pipeline {
//     agent { docker { image 'python:3.5.1' } }
// 	stage('Python pytest Tests') {
// 		dir('pytest') {
// 			sh 'virtualenv -p /home/wison/venv/bin/python3 venv'
// 			sh 'source /home/wison/venv/bin/activate && pip install -r requirements.txt'
// 			sh 'source /home/wison/venv/bin/activate && pytest --junit-xml=test_results.xml test || true'
// 			junit keepLongStdio: true, allowEmptyResults: true, testResults: 'test_results.xml'
// 		}
// 	}
// }