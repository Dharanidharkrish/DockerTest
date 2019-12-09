pipeline{
   agent any
      stages
      {
        stage ('Docker commands')
          {
            steps{ 
                   sh 'ssh -t -i /var/lib/jenkins/.ssh/id_rsa docadmin@172.31.38.18 "sudo docker run -d -p 8080:8080 dharanidharkrish/devopsexample"'                 
                  }
          }
      }


}
