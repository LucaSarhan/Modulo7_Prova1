# Avaliacoes-M7-Inteli
Avaliações do Módulo 7

Para executar o backend:

```bash
python main.py
```

Para executar o frontend:

```bash
node server.js
```

| ***IMPORTANTE:*** Utilizar dentro do contexto do container.

Ambos os Dockerfiles foram criados com sucesso da seguinte maneira: coloquei as linguagens como a primeir instrução, então no do backend coloquei python e no do front coloquei javascript. Depois coloquei o diretório do trabalho que são main e server no backend e no frontend respectivamente. A seguir mandei fazer uma ccopia nos dois diretórios. Depois mandei instalar as dependencias necesarias para fazer rodar. Por ultimo, coloquei os comando para fazer os arquivos rodar. Infelizmente não conseguir fazer o docker compose funcionar. Tambem não conseguir subir no dockerhub porem o certo seria seguir um passo a passo como esse: 

Criação de imagem:

```
docker build .
```

Catalogar imagem no dockerhub:

```
docker tag 'sua-tag' 'nome-do-repositório'
```

Envio para o dockerhub:

```
docker push 'nome-do-repositório'
```

Disponibilidade no dockerhub:

```
docker pull 'nome-do-repositório'
```

Execução:

```
docker-compose up
```


