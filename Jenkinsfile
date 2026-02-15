node {

    stage('Stage 1 - Print Message') {
        echo "This is Scripted Pipeline"
    }

    stage('Stage 2 - Show Date') {
        sh 'date'
    }

    stage('Stage 3 - Read File') {
        sh 'cat app.txt'
    }
stage('Stage 4 - List Files') {
    steps {
        sh 'ls -l'
    echo "Pipeline Finished"
}
