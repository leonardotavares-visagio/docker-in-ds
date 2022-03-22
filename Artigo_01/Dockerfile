# Seleciona a imagem base
FROM python:3.10-slim

# Seleciona o diretório que estamos utilizando para os comandos
WORKDIR "/app"

# Copia o arquivo de requisitos para dentro do container
COPY ./requirements.txt ./

# Instala as dependências
RUN pip install -r requirements.txt

# Copia todos os arquivos para dentro do container
COPY . .

# Configura o comando padrão para o container
CMD python main.py