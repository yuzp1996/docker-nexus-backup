library "alauda-cicd-enable-get-multi-arch-image"
def language = "golang"
AlaudaPipeline {
    config = [
        agent: 'golang-1.12',
        folder: '.',
        sonar: [
            binding: "sonarqube",
            enabled: false
        ],
    ]
    yaml = "alauda.yaml"
}
