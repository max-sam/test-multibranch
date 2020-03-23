pipeline {
   agent any

   stages {
      stage('Hello') {
         steps {
			ws('Frontend') {
				sh 'pwd'
			}
            echo 'Hello World'
         }
      }
   }
}