pipeline {
    agent any
    parameters {
        booleanParam(defaultValue: true, description: '', name: 'Check for True')
        string(defaultValue: "MARVEL", description: '', name: 'Enter any Name')
        choice(choices: 'IronMan\nHulk\nSpider-Man\nThor', description: '', name: 'Select a Hero')
    }

  stages {
        stage("foo") {
            steps {
                echo "flag: ${params.userFlagT}"
            }
        }
    }
}
