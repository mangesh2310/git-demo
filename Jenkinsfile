node
{
    stage 'checkout1'

    git url: 'https://github.com/bogo-devops/game-of-life.git'


     def mvnHome = tool 'M3'

     stage 'Build'


     sh "${mvnHome}/bin/mvn clean test sonar:sonar")
}
