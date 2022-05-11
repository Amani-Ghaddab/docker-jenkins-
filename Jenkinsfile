@Library('pipeline_library') _
gitCheckout( 
   scmurl:'https://github.com/Amani-Ghaddab/docker-jenkins-.git'

)
dockerComposeUp(
  dockerComposLocation : '/usr/local/bin/docker-compose'
)

node {
  echo "it works "
//  checkout scm
  //sshDeploy('dev/deploy.yml');
}
