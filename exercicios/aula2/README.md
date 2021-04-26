# Lista de Exercícios

Faça os seguintes exercícios. Sinta-se à vontade para usar a [documentação
oficial do docker](https://docs.docker.com/), ou `docker <command> --help` ou
até mesmo o Google para encontrar soluções. No entanto, evite copiar e colar
soluções - queremos que você aprenda como fazer essas operações fluentemente e
digitar os comandos ajudará.


### Cleanup

Remover todas images e contêineres que estejam em execução


### Executando contêineres


1. Criar contêineres utilizando a imagem do Ubuntu para (um por item):
  1. Mostrar a data atual;
  1. Utilizar o comando `curl` para baixar o seguinte [arquivo](https://www.gutenberg.org/files/11/11-0.txt). A imagem do ubuntu possui o comando `curl`? Como resolver isso?
1. Executar contêiner do python para imprimir a mensagem: "Hello World"

### Trabalhando com arquivos Dockerfile

1. Criar Dockerfiles:
  1. Imagem do ubuntu com o software `curl` instalado;
  1. Fazer download de um livro no [Projeto Gutenberg](https://www.gutenberg.org/files/11/11-0.txt) e copiá-lo para o diretório /data;


