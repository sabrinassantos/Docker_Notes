# dockerNotes
Anotações, sobre estudo do docker

###### Comandos:
`docker version`  
`docker run nome_da_imagem`, cria um container com a imagem passada por parâmetro  
`docker ps`lista todos os containers ativos no momento
`docker ps -a` lista todos os containers  
`docker run -it nome_do_container` atrela o nome do container com o terminal cmd, shell ou Docker Quick Start Terminal  
`docker stop id_container`para a execução do container  
`dcoker stop -t 0 id_container` por padrão o demora 10 seg para parar a execução, passando o -t dizemos quanto tempo queremos esperar  
`docker start id_container`para executar um container  
`docker start -a -i`-a para integrar os terminais, -i para interagir com o terminal dentro do container  
`docker rm id_container`remove o container  
`docker container prune`remove todos os containers  
`docker images`lista todas as imagens  
`docker rmi` remover imagens  
`docker run -d` roda a imagem sem atrelar ao terminal terminal  

