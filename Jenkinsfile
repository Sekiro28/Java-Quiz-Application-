pipeline {
         	agent any
         	stages {
                     	stage ("build") {
                                 	steps {
                                        echo"1st build"
                                 	}
                     	}
         	}
         post{
                  always{
                           emailext body: 'abc', subject: 'Java app', to: 'harshitpoojari2801@gmail.com'
                  } 
         }
 }
