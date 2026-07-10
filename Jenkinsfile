pipeline {

    agent any

    stages {

        stage('Compile') {

            steps {

                bat 'javac prg.java'

            }

        }

        stage('Run') {

            steps {

                bat 'prg Hello'

            }

        }

    }
}
