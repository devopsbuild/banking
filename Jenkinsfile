env.dockerimagename="devopsbasservice/buildonframework:buildon-jenkinsfile"
node {

   stage('Preparation') { //for display purpose
      checkout scm           
   }
   stage('Build') {
      // Run the maven build<appndid>

         sh "mvn clean package -DskipTests=True"
     
   }
}
