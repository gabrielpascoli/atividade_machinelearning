# Use uma imagem base do Python
FROM python:3.9-slim

# Defina o diretório de trabalho no contêiner
WORKDIR /api_ML 

# Copie todos os arquivos necessários para o diretório de trabalho
COPY . .

# Instale as dependências do Python
RUN pip install -r requirements.txt 

# Exponha a porta em que a sua API estará em execução
EXPOSE 8000

# Comando para iniciar a sua API quando o contêiner for executado
CMD ["uvicorn", "app:app", "--host", "0.0.0.0", "--port", "8000"]
