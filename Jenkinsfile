node {
   stage ('Checkout Repository') {
       // Get our repo cloned and ready for action
       deleteDir()
       checkout scm
   }
   
   stage ('Render Configurations') {
       //Generate configuration
       sh 'ansible-playbook generate_configurations.yaml'
   }

   stage ('Unit Testing') {
       //Do some kind of testing
   }
   
   stage ('Deploy Confoiguration to Dev') {
       //Push Config
   }
   
   stage ('Promotye Configuration to Production') {
       //Push to Production
   }

}