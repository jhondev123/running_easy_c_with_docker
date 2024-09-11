## Rodando C com Docker
1° Criando um container e copiando o código nele
docker run -it --rm -v "$(pwd)/src":/usr/src -w /usr/src gcc:4.9 bash

2° Executando o código
gcc -o main main.c && ./main
