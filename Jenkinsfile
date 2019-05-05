node {
    stage('build'){
        echo "building"
    }
}
node {
    stage('test'){
        echo "testing"
    }
}
stage('Get approval'){
    input "Deploy to qa?"
}
node {
    stage('deploy to qa'){
        echo "deploying"
    }
}
node {
    stage('Deploy to preprod'){
    input "Aprroval granted"
    }
}
node {
    stage('Deployed on preprod'){
        echo"Deployed on preprod"
    }
}
