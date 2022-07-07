# Docker

### Criar imagem docker

O comando `build` cria a imagem docker, `-t` é uma shotcode de `--tag` que é a flag que nomeia uma imagem e o último parâmetro `path/Dockerfile`, indica o caminho em que o arquivo `Dockerfile` está.
    
    docker build -t image-name path/Dockerfile