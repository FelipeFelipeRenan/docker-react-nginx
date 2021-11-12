# docker-react-nginx 

<img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
<img src="https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white" /> 
<img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white" />


Teste de deploy da aplicação padrão da biblioteca React.js utilizando subsistema linux Ubuntu com WSL 2

Foi utilizado o servidor web **Nginx** para subir tal aplicação 

Utilizou-se, também, o orquestrador de containers **Docker Compose**, na qual faz uso do arquivo docker-compose.yml

Caso queira utilizar a imagem que foi usada no compose, ela é: **felipedev21/teste-react:4.0**

Rodando o comando: **docker run -it -p 8080:80 --name {nome-que-facilite-a-identificação} --rm felipedev21/teste-react:4.0**

Na tag **-p**, pode utilizar a porta do seu desejo, já que a porta exposta pelo o Nginx é a porta 80 (utilizei a porta 8080 por questão de costume)

Pode rodar com a tag **-d** caso queira fazer uso do terminal e deixar o processo em segundo plano

Caso queira utilizar o docker-compose, fazer uso do comando: **docker-compose up -d --build**
