pipeline{
   agent any
      stages
      {
        stage ('Docker commands')
          {
            steps{ 
                   sh 'ssh docadmin@172.31.38.18 "sudo docker run -p 8080:8080 dharanidharkrish/devopsexample"'
                   echo 'started'
                  }
          }
      }


}
