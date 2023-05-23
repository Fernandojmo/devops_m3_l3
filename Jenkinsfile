    pipeline {
        agent any
    
        stages {
            stage('Hello') {
                steps {
                    echo 'Hello World'
                    git branch: 'main', credentialsId: '2ea4d506-8e73-4248-ae69-c438976f5715', url: 'https://github.com/Fernandojmo/devops_m3_l3.git'
                }
            }
        }
    }
