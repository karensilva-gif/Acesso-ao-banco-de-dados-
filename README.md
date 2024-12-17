Projeto de Programação Orientada a Objetos
Desafio: Implementar um banco de dados PostgreSQL no back-end, criar um front-end e conectar ao back-end
Instruções para configurar e executar este projeto no VSCode:

Clone o repositório
Faça o clone do repositório para sua máquina local utilizando o comando git clone <URL_DO_REPOSITÓRIO>.

Instale as dependências do back-end

Acesse a pasta banco.
Execute o comando mvn install para instalar as dependências necessárias.
Configure as propriedades do banco de dados

Acesse o arquivo src/resources/application.properties.
Modifique os campos url, username e password de acordo com as configurações do banco PostgreSQL que você está utilizando.
Ajuste o CORS no back-end

No arquivo src/java/apresentacao/WebConfig.java, localize a configuração de allowedOrigin.
Defina a porta onde o front-end será executado.
Instale as dependências do front-end

Entre na pasta front-end.
Execute o comando yarn install ou npm install para instalar os pacotes necessários.
Execute o front-end

Abra o arquivo principal HTML dentro da pasta front-end.
Use a extensão Live Server do VSCode para rodar o projeto no navegador.
Rode o back-end

Vá até o arquivo src/apresentacao/AcessoADado.java.
Execute o arquivo no VSCode utilizando a opção Run Java.
