pipeline {
    agent any
    environment { 
        CC = 'clang'
    }
    stages {
        stage('Example') {
            environment { 
                DEBUG_FLAGS = '-g'
            }
            steps {
                print "$CC"
                print "$DEBUG_FLAGS"
            }
        }
    }
}
