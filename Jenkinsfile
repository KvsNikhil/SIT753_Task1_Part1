pipeline {
  agent any

  stages {

    stage('Build') {
      steps {
        echo 'Building the application...'
        echo 'Tool: Maven (or npm for Node.js apps)'
        // Example: sh 'mvn clean install' or sh 'npm run build'
      }
    }

    stage('Unit and Integration Tests') {
      steps {
        echo 'Running unit and integration tests...'
        echo 'Tool: JUnit, Mocha, or Jest'
        // Example: sh 'npm test' or sh 'mvn test'
      }
    }

    stage('Code Analysis') {
      steps {
        echo 'Running static code analysis...'
        echo 'Tool: SonarCloud or ESLint'
        // Placeholder for code analysis tool command
      }
    }

    stage('Security Scan') {
      steps {
        echo 'Scanning for vulnerabilities...'
        echo 'Tool: npm audit or Snyk'
        // Example: sh 'npm audit'
      }
    }

    stage('Deploy to Staging') {
      steps {
        echo 'Deploying to staging environment...'
        echo 'Tool: AWS CLI, Docker, or SCP'
        // Example: sh 'scp build.zip ec2-user@staging-server:/var/www/app'
      }
    }

    stage('Integration Tests on Staging') {
      steps {
        echo 'Running integration tests on staging...'
        echo 'Tool: Selenium or Postman CLI'
        // Example: sh 'npm run test:staging'
      }
    }

    stage('Deploy to Production') {
      steps {
        echo 'Deploying to production environment...'
        echo 'Tool: AWS CLI or Ansible'
      }
    }

  }
}