pipeline {
	agent any 
	
	stages {
		stage('Checkout') {
			steps {
				echo "Clonage du repo ..."
				checkout scm
			}
		}
		
		stage('Build') {
			steps {
				echo "Compilation en cours ..."
			}
		}
		
		stage('Test') {
			steps {
				echo "Exécution des tests ..."
			}
		}
	
		stage('Deploy') {
			steps {
				echo "Déploiement terminé "
			}
		}
	}
}