alias mkstart='minikube start --memory=2048 --cpus=2'
alias lzg='lzg'
alias lzd='lazydocker'

alias reload='source ~/.bashrc'
alias cls='clear'

alias dps='docker ps'
alias dpsa='docker ps -a'
alias di='docker images'


alias mvnrun-dev='set -a && source example.env && set +a && mvn spring-boot:run -Pdev -Dspring-boot.run.profiles=dev'
alias mvninstall-dev='set -a && source example.env && set +a && mvn clean install -Pdev'


Nuxt hater
