Docker

usei: docker build -t meu-nginx .
*como meu dockerfile não tem nome e estou no root da imagem o comando é este.
*local: C:\Users\logonrmlocal\Desktop\docker\web-docker


usei: docker run --name meu-servidor-web -d -p 80:80 meu-nginx
*meu container fica com o nome: meu-servidor-web, utilizara a imagem meu-nginx que foi criada agora pouco.
*cuidado com o uso de ias de LLM elas apenas buscam resolver de qualquer problema, ex: 80:80 é origem/destino
*acesso da página http://localhost/
*host porta: 80 (origem)/ destino: 80(destino)
*o correto deve ser docker run --name some-nginx -d -p 8080:80 some-content-nginx
