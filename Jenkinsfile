pipeline {
    agent any

    stages {
        stage('Preparation') {
            steps {
                echo 'Підготовка середовища...'
                sh 'date'
            }
        }

        stage('Build') {
            steps {
                echo 'Виконую білд...'
                sh 'echo "Компільований код..."'
            }
        }

        stage('Test') {
            steps {
                echo 'Запуск тестів...'
                sh 'echo "Усі тести пройдені успішно!"'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Деплой додатку...'
                sh 'echo "Деплой завершено."'
            }
        }
    }
}

