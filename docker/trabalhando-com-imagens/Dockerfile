# Criando a primeira imagem com Dockerfile

FROM nginx:latest

RUN apt-get update
RUN apt-get install vi -y

# Comando executado no terminal e sua descrição:
# docker build -t felipenoguez/nginx-com-vi:latest .

# docker build: Comando principal para construir uma imagem Docker.
# -t felipenoguez/nginx-com-vi:latest: Define a tag (-t) da imagem. Neste caso, a tag é felipenoguez/nginx-com-vi:latest. A tag é uma maneira de identificar e nomear uma versão específica da imagem. O latest é uma convenção frequentemente usada para indicar a versão mais recente.
# .: Indica o contexto de build. Neste caso, o ponto (.) representa o diretório atual. Isso significa que o Docker usará todos os arquivos e subdiretórios no diretório atual como o contexto para a construção da imagem.