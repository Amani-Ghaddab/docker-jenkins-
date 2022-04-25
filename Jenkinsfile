@Library('pipeline_library') _
gitCheckout( 
   scmurl:'https://github.com/Amani-Ghaddab/docker-jenkins-.git'

)
dockerBuild(
  dockerfileLocation: './mvc/dockerfile'
)
dockerComposeUp(
  dockerComposLocation : '/user/local/bin/docker-compose'
)