pipeline {                            // 1  // Defines the start of the Jenkins pipeline block
    agent any                         // Specifies the pipeline can run on any available agent

    stages {                          // 2  // Defines the stages block where multiple stages are declared
        stage('Build') {              // 3  // Creates a stage named 'Build'
            steps {                   // 4  // Defines the steps that will be executed in this stage
                sh 'date'             // Executes the shell command to print the current date
                sh 'pwd'              // Executes the shell command to print the current working directory
            }                         // 4  // Ends the steps block for 'Build' stage
        }                             // 3  // Ends the 'Build' stage

        stage('Test') {               // 5  // Creates a stage named 'Test'
            steps {                   // 6  // Defines the steps that will be executed in this stage
                echo 'Testing..'      // Prints 'Testing..' in the console output
            }                         // 6  // Ends the steps block for 'Test' stage
        }                             // 5  // Ends the 'Test' stage

        stage('Deploy') {             // 7  // Creates a stage named 'Deploy'
            steps {                   // 8  // Defines the steps that will be executed in this stage
                echo 'Deploying....'  // Prints 'Deploying....' in the console output
            }                         // 8  // Ends the steps block for 'Deploy' stage
        }                             // 7  // Ends the 'Deploy' stage
    }                                 // 2  // Ends the stages block
}                                     // 1  // Ends the pipeline block
