# O Dockerfile sempre deve ser começado importando a imagem de base.
# É utilizado a palavra 'FROM'.
# Neste caso aqui, irei importar a imagem do python.
# Assim, a gente escreve 'python' para o nome da imagem e 'latest' para a versão.
# Link para acessar outros tipos de imagens: https://hub.docker.com/

FROM python:latest

# Importado a imagem, agora para lançar nosso código em Python, será necessário importá-lo em nossa imagem.
# Usamos pra isto a palavra chave 'COPY'
# O primeiro parâmetro 'main.py' é o nome do arquivo no host.
# O segundo parâmetro '/' é o caminho onde colocar o arquivo na imagem.
# Neste caso, colocaremos o arquivo na pasta raiz da imagem.

COPY main.py /

# Agora é necessário definir o comando para lançar quando rodar a imagem.
# Utilizamos a palavra 'CMD' para isto.
# O comando executará "python ./main.py".

CMD [ "python", "./main.py"]