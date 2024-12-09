
pipeline {
    agent any
    stages {
        stage('Write to File') {
            steps {
                script {
                    // Define the file path and content
                    def filePath = "${WORKSPACE}/example.txt"
                    def fileContent = "This is a new file created by the Jenkins pipeline.\nHello, World!"
                    
                    // Write content to the file
                    writeFile file: filePath, text: fileContent

                    // Print a confirmation message
                    echo "File written successfully: ${filePath}"
                }
            }
        }
    }
}
