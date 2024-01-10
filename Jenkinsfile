pipeline {
   agent any
   stages {
       stage('Hello') {
           steps {
               echo "Hallo die Welt"
               echo "Hello wonderful world"
                   }
           }
       }
   post{
       always{
           mail to: "hince1992@gmail.com",
           subject: "Test Email",
           body: "Test"
       }
   }
}
