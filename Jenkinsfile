pipeline {
  agent any
  stages {
    stage('Stage1') {
      steps {
        sh 'git clone https://github.com/abesrour1111/git_devops.git'
      }
    }

    stage('Stage2') {
      steps {
        sh '''if [ -e gestion_groupes ]; then
   echo "le fichier 1 existe"
else
   echo "le fichier 1 n\'existe pas"
fi

if [ -e gestion_utilisateurs ]; then
   echo "le fichier 2 existe"
else
   echo "le fichier 2 n\'existe pas"
fi'''
      }
    }

  }
}