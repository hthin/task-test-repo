pipeline {
   agent any
   stages {
       stage('Hello') {
           steps {
               echo "Hallo die Welt"
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
