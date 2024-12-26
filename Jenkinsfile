node {
    stage('Build') {
        echo 'Building the project...'
    }
    stage('Test') {
        echo 'Running tests...'
    }
    stage('Deploy') {
        echo 'Deploying the application...'
    }
    if (currentBuild.result == 'SUCCESS') {
        echo 'Build succeeded!'
    } else {
        echo 'Build failed.'
    }
}
