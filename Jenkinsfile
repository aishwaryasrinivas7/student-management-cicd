
stage('Install Dependencies') {
    steps {
        sh '''
            python3 -m venv .venv
            .venv/bin/python -m pip install --upgrade pip --timeout 60 --retries 5
            .venv/bin/python -m pip install -r requirements.txt --timeout 60 --retries 5
        '''
    }
}
