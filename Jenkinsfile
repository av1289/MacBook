pipeline {
  agent any
  stages {
    stage('') {
      steps {
        ansibleTowerProjectSync(towerServer: 'AWX', verbose: true, project: 'av', importTowerLogs: true)
      }
    }

  }
}