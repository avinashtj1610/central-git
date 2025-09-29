pipeline {                            // 1  // Defines the start of the Jenkins pipeline block
    agent any                         // Specifies the pipeline can run on any available agent
    stages {                          // 2  // Defines the stages block where multiple stages are declared
        stage('Stage 1') {            // 3  // Creates a stage named 'Stage 1'
            steps {                   // 4  // Defines the steps that will be executed in this stage
                sh '''                // Starts a multi-line shell block
                ls                    // Lists the files in the current directory
                date                  // Prints the current date
                cal 2021              // Displays the calendar for the year 2021
                '''                   // Ends the multi-line shell block
            }                         // 4  // Ends the steps block for 'Stage 1'
        }                             // 3  // Ends the 'Stage 1' stage
    }                                 // 2  // Ends the stages block
}                                     // 1  // Ends the pipeline block
