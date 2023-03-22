def gv

pipeline {
    agent any
    parameters {
        choice(name: 'VERSION', choices: ['1.1.0', '1.2.0', '1.3.0'], description: '')
        booleanParam(name: 'executeTests', defaultValue: true, description: '')
    }
    stages {
        stage("init") {
            steps {
                echo 'Doing some init ...'
            }
        }
        stage("build") {
            steps {
                echo 'Doing build ...'
            }
        }
        stage("deploy") {
            steps {
                echo 'Doing deploy ...'
            }
        }
    }   
}
