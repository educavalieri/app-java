peline {
    agent any
    stage('build da imagen docker'){
        steps{
            sh 'docker build -t application/application .'
        }
    }
    stage('subir docker compose app'){
        sh 'docker-compose up -d'
    }
    stage('sleep para subida de containers'){
        sh 'sleep 10'
    }    
}
