pipeline {
    agent none 
    stages {
        stage ("This is 1st Stage") {
            agent {
                label "java-agent-slave"
            }
            steps {
                echo "This is java agent"
            }
        }
        stage ("This is 2nd stage") {
            agent {
                label "node-agent-slave"
            }
            steps {
                echo "This is node agent"
            }
        }
    }
}
