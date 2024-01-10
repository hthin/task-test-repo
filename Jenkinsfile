pipeline {
   agent any
   stages {
       stage('Hello') {
           steps {
               echo "Hallo die Welt"
               echo "Hello wonderful world"
               echo "Hello die schöne Welt"
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
