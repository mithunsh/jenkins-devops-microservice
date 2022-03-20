pipeline {
		agent { docker{ image 'maven:3.6.3' }}
		stages{
			stage("build"){
				steps{
					script{ 
						sh 'mvn --version'
					}
				
					
				}
			}
			stage("test"){
				steps{
					echo "test"

				}
			}
			stage("intigration-test"){
				steps{
					
					echo "intigration-Test"

				}
			}
		} 
		post{
			always{
				echo"I am awesome,I run always"
			}
			success{
				echo"I run when u are successfull"
			}
			failure{
				echo"I run when u are failure"
			}
		}
	
		
}
