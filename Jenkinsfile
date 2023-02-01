node(){
    cleanWs()
    try{
        stage('firsjob')
        {
            sh "echo hello word"
        }

        stage('twojob')
        {
            sh "echo tout marche"
        }
    }
    finally{
        cleanWs()
    }

}